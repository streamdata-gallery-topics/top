---
name: AWS Simple Notification Service
x-slug: aws-simple-notification-service
description: Amazon Simple Notification Service (Amazon SNS) is a fast, flexible,
  fully managed push notification service that lets you send individual messages or
  to fan-out messages to large numbers of recipients. Amazon SNS makes it simple and
  cost effective to send push notifications to mobile device users, email recipients
  or even send messages to other distributed services.With Amazon SNS, you can send
  notifications to Apple, Google, Fire OS, and Windows devices, as well as to Android
  devices in China with Baidu Cloud Push. You can use SNS to send SMS messages to
  mobile device users worldwide.Beyond these endpoints, Amazon SNS can also deliver
  messages toAmazon Simple Queue Service(SQS),AWS Lambda functions, or to any HTTP
  endpoint.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AmazonSNS.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Top
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/top/master/_listings/aws-simple-notification-service/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Simple Notification Service API - Create Topic
  x-api-slug: actioncreatetopic-get
  description: Creates a topic to which notifications can be published.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AmazonSNS.png
  humanURL: https://aws.amazon.com/sns/
  baseURL: :///
  tags: Amazon Web Services, Notifications, SMS, Stack Network, API Service Provider,
    API Service Provider, API Provider, Messages, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/top/master/_listings/aws-simple-notification-service/actioncreatetopic-get-openapi.md
- name: AWS Simple Notification Service API - Delete Topic
  x-api-slug: actiondeletetopic-get
  description: Deletes a topic and all its subscriptions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AmazonSNS.png
  humanURL: https://aws.amazon.com/sns/
  baseURL: :///
  tags: Amazon Web Services, Notifications, SMS, Stack Network, API Service Provider,
    API Service Provider, API Provider, Messages, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/top/master/_listings/aws-simple-notification-service/actiondeletetopic-get-openapi.md
- name: AWS Simple Notification Service API - Get Topic Attributes
  x-api-slug: actiongettopicattributes-get
  description: Returns all of the properties of a topic.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AmazonSNS.png
  humanURL: https://aws.amazon.com/sns/
  baseURL: :///
  tags: Amazon Web Services, Notifications, SMS, Stack Network, API Service Provider,
    API Service Provider, API Provider, Messages, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/top/master/_listings/aws-simple-notification-service/actiongettopicattributes-get-openapi.md
- name: AWS Simple Notification Service API - List Subscriptions By Topic
  x-api-slug: actionlistsubscriptionsbytopic-get
  description: Returns a list of the subscriptions to a specific topic.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AmazonSNS.png
  humanURL: https://aws.amazon.com/sns/
  baseURL: :///
  tags: Amazon Web Services, Notifications, SMS, Stack Network, API Service Provider,
    API Service Provider, API Provider, Messages, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/top/master/_listings/aws-simple-notification-service/actionlistsubscriptionsbytopic-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/top/master/_listings/aws-simple-notification-service/actionlistsubscriptionsbytopic-get-openapi.md
- name: AWS Simple Notification Service API - List Topics
  x-api-slug: actionlisttopics-get
  description: Returns a list of the requester's topics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AmazonSNS.png
  humanURL: https://aws.amazon.com/sns/
  baseURL: :///
  tags: Amazon Web Services, Notifications, SMS, Stack Network, API Service Provider,
    API Service Provider, API Provider, Messages, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/top/master/_listings/aws-simple-notification-service/actionlisttopics-get-openapi.md
- name: AWS Simple Notification Service API - Set Topic Attributes
  x-api-slug: actionsettopicattributes-get
  description: Allows a topic owner to set an attribute of the topic to a new value.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AmazonSNS.png
  humanURL: https://aws.amazon.com/sns/
  baseURL: :///
  tags: Amazon Web Services, Notifications, SMS, Stack Network, API Service Provider,
    API Service Provider, API Provider, Messages, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/top/master/_listings/aws-simple-notification-service/actionsettopicattributes-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.simple.email.service.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.simple.notification.service.stack.network
- type: x-change-log
  url: http://aws.amazon.com/releasenotes/Amazon-SN
- type: x-console
  url: https://console.aws.amazon.com/sns
- type: x-documentation
  url: http://docs.aws.amazon.com/sns/latest/api/
- type: x-faq
  url: https://aws.amazon.com/sns/faqs/
- type: x-forum
  url: https://forums.aws.amazon.com/forum.jspa?forumID=72
- type: x-getting-started
  url: https://aws.amazon.com/sns/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/sns/pricing/
- type: x-website
  url: https://aws.amazon.com/sns/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---