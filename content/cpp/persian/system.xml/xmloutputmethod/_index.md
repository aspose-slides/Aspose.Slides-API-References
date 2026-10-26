---
title: XmlOutputMethod
second_title: Aspose.Slides برای مرجع API C++
description: روشی را که برای سریال‌سازی خروجی XmlWriter استفاده می‌شود، مشخص می‌کند.
type: docs
weight: 846
url: /fa/system.xml/xmloutputmethod/
---
## XmlOutputMethod enum

روش مورد استفاده برای سریال‌سازی خروجی [XmlWriter](../xmlwriter/) را مشخص می‌کند.

```cpp
enum class XmlOutputMethod
```

### مقادیر

| نام | مقدار | توضیح |
| --- | --- | --- |
| Xml | 0 | سریال‌سازی بر اساس قوانین XML 1.0. |
| Html | 1 | سریال‌سازی بر اساس قوانین HTML که توسط XSLT مشخص شده است. |
| Text | 2 | فقط بلوک‌های متن را سریال‌سازی می کند. |
| AutoDetect | 3 | از قوانین XSLT برای انتخاب بین روش‌های خروجی [XmlOutputMethod::Xml](./) و [XmlOutputMethod::Html](./) در زمان اجرا استفاده می‌شود. |

## موارد مرتبط

* Namespace [System::Xml](../)
* Library [Aspose.Slides](../../)