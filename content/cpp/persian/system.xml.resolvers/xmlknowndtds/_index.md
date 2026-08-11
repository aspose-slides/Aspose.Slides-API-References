---
title: XmlKnownDtds
second_title: مرجع API Aspose.Slides برای C++
description: "شمارش Resolvers::XmlKnownDtds توسط Resolvers::XmlPreloadedResolver استفاده می‌شود و تعیین می‌کند که چه DTDهای شناخته‌شده‌ای توسط Resolvers::XmlPreloadedResolver تشخیص داده می‌شوند."
type: docs
weight: 14
url: /fa/system.xml.resolvers/xmlknowndtds/
---
## XmlKnownDtds enum

این شمارش [Resolvers::XmlKnownDtds](./) توسط [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) استفاده می‌شود و تعیین می‌کند که چه DTDهای شناخته‌شده‌ای توسط [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) تشخیص داده می‌شوند.

```cpp
enum class XmlKnownDtds
```

### مقادیر

| نام | مقدار | توضیح |
| --- | --- | --- |
| None | 0 | مشخص می‌کند که [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) هیچ یک از DTDهای پیش‌تعریف‌شده را تشخیص نمی‌دهد. |
| Xhtml10 | 1 | مشخص می‌کند که [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) DTDها و موجودیت‌هایی را که در XHTML 1.0 تعریف شده‌اند تشخیص می‌دهد. |
| Rss091 | 2 | مشخص می‌کند که [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) DTDها و موجودیت‌هایی را که در RSS 0.91 تعریف شده‌اند تشخیص می‌دهد. |
| All | 65535 | مشخص می‌کند که [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) تمام DTDهای هم‌اکنون پشتیبانی‌شده را تشخیص می‌دهد. این رفتار پیش‌فرض است. |

## مراجع دیگر

* فضای‌نام [System::Xml::Resolvers](../)
* کتابخانه [Aspose.Slides](../../)