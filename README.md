<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>WriteMate - Privacy Policy & Terms</title>
  <style>
    body {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Arial;
      margin: 0;
      background: #f7f7f7;
      color: #222;
      line-height: 1.6;
    }
    .container {
      max-width: 900px;
      margin: 0 auto;
      background: #fff;
      padding: 24px;
    }
    h1 { font-size: 22px; margin-bottom: 8px; }
    h2 { font-size: 16px; margin-top: 22px; }
    p, li { font-size: 14px; }
    .tabs {
      display: flex;
      border-bottom: 1px solid #eee;
      margin-bottom: 16px;
    }
    .tab {
      flex: 1;
      text-align: center;
      padding: 12px;
      cursor: pointer;
      font-weight: 600;
    }
    .tab.active {
      color: #007aff;
      border-bottom: 2px solid #007aff;
    }
    .section { display: none; }
    .section.active { display: block; }
    .updated { font-size: 12px; color: #888; }
  </style>
</head>

<body>
<div class="container">

<h1>WriteMate Legal Documents</h1>
<p class="updated">Last updated: June 23, 2026</p>

<div class="tabs">
  <div class="tab active" onclick="show('privacy', this)">Privacy Policy</div>
  <div class="tab" onclick="show('terms', this)">Terms of Service</div>
</div>

<!-- Privacy Policy -->
<div id="privacy" class="section active">

<h2>1. Information We Collect</h2>
<p>When you use WriteMate, we may collect:</p>
<ul>
  <li>Device information (model, OS version)</li>
  <li>Usage data (feature interactions, crash logs)</li>
  <li>User content (text entered for AI writing and editing)</li>
</ul>

<h2>2. How We Use Information</h2>
<p>We use data to:</p>
<ul>
  <li>Provide and improve WriteMate services</li>
  <li>Enhance AI text generation quality</li>
  <li>Improve user experience</li>
  <li>Ensure security and prevent abuse</li>
</ul>

<h2>3. Third-Party Services</h2>
<ul>
  <li>Apple In-App Purchase (subscriptions)</li>
  <li>Cloud AI processing providers</li>
  <li>Analytics tools</li>
</ul>

<h2>4. Data Security</h2>
<p>We apply reasonable security measures, but no system is 100% secure.</p>

<h2>5. Data Sharing</h2>
<p>We do not sell user data. Data may only be shared when required by law or necessary for service operation.</p>

<h2>6. Data Retention</h2>
<p>Data is retained only as long as needed for service functionality.</p>

<h2>7. Children’s Privacy</h2>
<p>WriteMate is not intended for users under 13 years old.</p>

<h2>8. Contact</h2>
<p>Email: 1596078700@qq.com</p>

</div>

<!-- Terms -->
<div id="terms" class="section">

<h2>1. Acceptance of Terms</h2>
<p>By using WriteMate, you agree to these Terms of Service.</p>

<h2>2. Service Description</h2>
<p>WriteMate provides AI-powered text writing, rewriting, and optimization tools.</p>

<h2>3. User Responsibilities</h2>
<p>You agree not to use WriteMate for illegal, harmful, or abusive activities.</p>

<h2>4. Subscription & Purchases</h2>
<p>Some features may require subscription or in-app purchases. Payments are processed by Apple.</p>

<h2>5. AI Content Disclaimer</h2>
<p>AI-generated content may be inaccurate. Users are responsible for reviewing outputs.</p>

<h2>6. Service Changes</h2>
<p>We may modify or discontinue features at any time.</p>

<h2>7. Limitation of Liability</h2>
<p>We are not responsible for damages caused by use of the application.</p>

<h2>8. Contact</h2>
<p>Email: 1596078700@qq.com</p>

</div>

</div>

<script>
function show(type, el){
  document.querySelectorAll('.section').forEach(s => s.classList.remove('active'));
  document.getElementById(type).classList.add('active');

  document.querySelectorAll('.tab').forEach(t => t.classList.remove('active'));
  el.classList.add('active');
}
</script>

</body>
</html>
