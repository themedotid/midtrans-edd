=== Midtrans-Easy-Digital-Downloads ===
Contributors: yocki, rizdaprasetya
Tags: comments, spam
Tags: midtrans, snap, payment, payment-gateway, credit-card, commerce, e-commerce, edd, easy-digital-downloads
Requires at least: 3.9.1
Tested up to: 5.2.0
Stable tag: 2.2.2s
Requires PHP: 5.2.4
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Midtrans-Easy-Digital-Downloads is plugin for Midtrans, Indonesian Payment Gateway. Brings safety and highly dedicated to customer experience (UX) to Easy Digital Downloads

== Description ==

Midtrans-Easy-DIgital-Downloads is official plugin from [Midtrans](https://midtrans.com), Indonesian Payment Gateway. Brings safety and highly dedicated to customer experience (UX) to Easy Digital Downloads. Support various online payment channel.

Payment Method Feature:

* Credit card fullpayment and other payment methods.
* Bank transfer.
* Credit card Online & offline installment payment.
* Custom expiry.
* Two-click & One-click feature.
* Midtrans Snap all payment method fullpayment.
 
== Installation ==

1. Upload the plugin files to the `wp-content/plugins/midtrans-edd` directory, or install the plugin through the WordPress plugins screen directly.
2. Activate the plugin through the `Plugins` screen in WordPress
3. Go to **Downloads - Settings - Payment Gateways - Midtrans** menu, fill the configuration fields.

### Midtrans MAP Configuration

1. Login to Midtrans MAP Dashboard.
2. Select the environment (sandbox or production).
3. Go to **settings - configuration**

    - Insert `http://[yourweb]/?edd-listener=midtrans` as your Payment Notification URL
    - Insert `http://[yourweb]` as your Finish, Pending and Error Redirect URL

== Frequently Asked Questions ==

= Where can find my access key (client & server key)? How to get Started? =

Register first to [Midtrans](https://account.midtrans.com/register), you will get the access key on Midtrans Dashboard.
Also please refere to this official [documentation](http://docs.midtrans.com/en/snap/integration_woocommerce.html).

= Where can I report bugs? =

The best way please email to support@midtrans.com, but bugs can be reported in our [repo](https://github.com/Midtrans/midtrans-edd/issues), or you can also use WordPress plugins support for reporting bugs and error. 

== Screenshots ==

1. Payment displayed as popup, your customer no need to leave your store!

2. Various payment channel

3. Configuration page

== Changelog ==

= 1.0.0 =
* First release.
* SNAP redirection feature.

= 2.0.0 =
* Add SNAP popup feature.
* Update README.md.

= 2.1.0 =
* Add mixpanel.

= 2.1.1 =
* Add payment instruction (pdf url) on success page.
* Update php lib.

= 2.1.2 =
* Add payment notes for every status changes.

= 2.2.0 =
* Enhancement code.

= 2.2.1 =
* Add additional fee to item details.
* Add discount code field.

= 2.3.0 =
* Bump version to match WordPress official plugin repo version.
* Change all function to unique names.
* Add wp_create_nonce() function.
* Make midtrans mixpanel disable by default (optional).
* Change plugin name to edd-midtrans-gateway.

= 2.3.1 =
* Add mixpanel.

= 2.4.0 =
* Update veritrans lib to midtrans lib.
* Update the snap redirection.

== Get Help ==

*	[Midtrans registration](https://account.midtrans.com/register)
*	[Midtrans Documentation](https://docs.midtrans.com)
*	[Midtrans Snap API Documentation](https://snap-docs.midtrans.com)