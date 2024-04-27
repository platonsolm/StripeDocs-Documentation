<style>
    .divider{
      height: 1px;
      background-color: #ccc;
      margin-top: 5px;
    }
    .callout-container {
      display: flex;
      flex-direction: column;
    }

    .callout-row {
      display: flex;
      justify-content: space-between;
      margin-bottom: 20px;
    }

    .callout {
        width: 48%;
        border: 1px solid #E3E8EE;
        border-radius: 5px;
        padding-top: 15px;
        padding-left: 15px;
        box-sizing: border-box;
    }

    .callout-text {
      color: #5D6479;
      font-size: 14px;
    }

    .callout-header {
      font-size: 16px;
      font-weight: bold;
    }

    .callout:hover {
      box-shadow: 0 0 5px rgba(0, 0, 0, 0.3);
    }
    .callout:active {
      box-shadow: 0 0 10px rgba(74, 95, 191, 0.5);
    }
</style>
<script>
    function redirectPaymentLink() {
      window.location.href = "payments/create-a-payment-link";
    }
    function redirectShareLink() {
      window.location.href = "payments/share-a-payment-link";
    }
    function redirectTrackLink() {
      window.location.href = "payments/track-a-payment-link";
    }
    function redirectBuyButtonLink() {
      window.location.href = "payments/create-an-embeddable-buy-button";
    }
</script>

<a href="#">Home</a>
<h1>Payment Links</h1>
<h3>Sell online without building a digital storefront.</h3>
<p>Accept a payment or sell subscriptions without building additional standalone websites or applications with Payment Links. Share the link as many times as you want on social media, in emails, or on your website.</p>

<p>Payment Links supports <a>20+ payment methods</a> — including credit and debit cards, Apple Pay, and Google Pay. The Payment Link automatically matches your customer’s preferred browser language for <a href="">30+ languages</a>. If you don’t have a Stripe account, <a>sign up now.</a></p>

<h3><b>Get Started</b></h3>
<div class="callout-container">
  <div class="callout-row">
    <div class="callout" onclick="redirectPaymentLink()">
      <a class="callout-header" href="payments/create-a-payment-link">Create a payment link</a>
      <div class="callout-body">
        <p class="callout-text">Create a payment link without using code.</p>
      </div>
    </div>
    <div class="callout" onclick="redirectShareLink()">
      <a class="callout-header" href="payments/share-a-payment-link">Share a payment link</a>
      <div class="callout-body">
        <p class="callout-text">Share a payment link with your customers.</p>
      </div>
    </div>
  </div>
  <div class="callout-row">
    <div class="callout" onclick="redirectTrackLink()">
      <a class="callout-header" href="payments/track-a-payment-link">Track a payment link</a>
      <div class="callout-body">
        <p class="callout-text">Track a payment link and related campaigns.</p>
      </div>
    </div>
    <div class="callout" onclick="redirectBuyButtonLink()">
      <a class="callout-header" href="payments/create-an-embeddable-buy-button">Create an embeddable buy button</a>
      <div class="callout-body">
        <p class="callout-text">Create an embeddable buy button to sell a product, subscription, or accept a payment on your website.</p>
      </div>
    </div>
  </div>
</div>
<h3><b>Explore advanced options</b></h3>
<div class="callout-container">
  <div class="callout-row">
    <div class="callout">
      <a class="callout-header">Create and manage a payment link with the API</a>
      <div class="callout-body">
        <p class="callout-text">Create and manage a payment link with the API.</p>
      </div>
    </div>
    <div class="callout">
      <a class="callout-header">Customize your checkout experience</a>
      <div class="callout-body">
        <p class="callout-text">Choose the information you collect from customers at checkout.</p>
      </div>
    </div>
  </div>
</div>
