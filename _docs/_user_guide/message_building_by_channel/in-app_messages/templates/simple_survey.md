---
nav_title: Simple Survey
platform: Message_Building_and_Personalization
subplatform: In-App Messages
page_order: 9
description: "Collect custom user attributes and power retargeting campaigns using an In-App Message Survey Template."
---

# Simple Survey In-App Message

Collect custom user attributes and power retargeting campaigns using an In-App Message Survey Template.

{% alert important %}
This feature is in *Early Access*. Ask your Braze account team to request access!
{% endalert %}

## Examples {#examples}

{% gallery %}
{{site.baseurl}}/assets/img/iam-survey.png  <br> <h2>Collect User Preferences as Custom Attributes</h2>
{{site.baseurl}}/assets/img/iam-survey.png  <br> <h2>Gather Customers Satisfaction and Feedback</h2>
{{site.baseurl}}/assets/img/iam-survey.png  <br> <h2>Promote New Features and Trigger Promotions</h2>
{% endgallery %}

## SDK Requirements {#supported-sdk-versions}

This template requires upgrading to the following Braze SDK versions:

* Web SDK v2.5+ [Changelog]({{site.baseurl}}/developer_guide/platform_integration_guides/web/changelog/#250)
* iOS SDK - v3.23.0+ [Changelog]({{site.baseurl}}/developer_guide/platform_integration_guides/ios/changelog/#3230)
* Android SDK - v8.0.0+ [Changelog]({{site.baseurl}}/developer_guide/platform_integration_guides/android/changelog/#800)

{% alert warning %}
Because this message type can only be received by certain newer SDK versions, users that are on unsupported SDK versions will not receive the message. 

Consider adopting this new message type once a significant portion of your user base is reachable, or target only those users whose app version is _above_ the requirements. [Learn More]({{ site.baseurl }}/user_guide/engagement_tools/campaigns/ideas_and_strategies/new_features/#filtering-by-most-recent-app-versions)
{% endalert %}

## Creating A New Survey Message {#create}

Create a new Survey message by selecting the Simple Survey option in your message's Template Type option.

![Simple Survey Message Type]({{site.baseurl}}/assets/img/survey-message-type.png)

This Survey template is supported on mobile, web, or both mobile + web. Remember to be sure that your SDKs are on the [minimum versions](#supported-sdk-versions) required for this feature.

### Options {#options}

#### Single vs. Multiple Choice {#single-multiple-choice}

Use the Single vs. Multiple Choice option to control the number of choices a user can select; one, or multiple.

When Custom Attribute collection is enabled, the Multiple Choice option will set each choice's designated custom attribute. Be sure to use a unique Custom Attribute name for each choice to prevent choices from overwriting each other.

![Single Multiple Choice]({{site.baseurl}}/assets/img/single-multiple-choice.png)

### Collecting Custom Attributes

![Color Theme Picker]({{site.baseurl}}/assets/img/collect-attributes.png)

### Showing A Confirmation Page

![Confirmation Option]({{site.baseurl}}/assets/img/confirmation-option.png)

![Confirmation Page]({{site.baseurl}}/assets/img/confirmation-page.png)

### Styling Your Message

![Color Theme Picker]({{site.baseurl}}/assets/img/color-theme-picker.png)

## Analyzing Results

![Analytics]({{site.baseurl}}/assets/img/analytics.png)

## Retargeting Using Custom Attributes
