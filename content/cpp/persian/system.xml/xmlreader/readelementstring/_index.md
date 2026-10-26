---
title: ReadElementString()
second_title: "مرجع API Aspose.Slides برای C++"
description: "یک عنصر فقط متنی را می‌خواند. با این حال، توصیه می‌شود به‌جای آن از متد XmlReader::ReadElementContentAsString استفاده شود، زیرا راه‌حل ساده‌تری برای انجام این عملیات فراهم می‌کند."
type: docs
weight: 859
url: /fa/system.xml/xmlreader/readelementstring/
---
## XmlReader::ReadElementString() متد

یک عنصر فقط متنی را می‌خواند. با این حال، توصیه می‌شود به جای آن از متد [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) استفاده کنید، زیرا راه‌حل ساده‌تری برای انجام این عملیات فراهم می‌کند.

```cpp
virtual String System::Xml::XmlReader::ReadElementString()
```

### مقدار بازگشت

متنی که در عنصر خوانده شده قرار داشته است. اگر عنصر خالی باشد، رشتهٔ خالی برگردانده می‌شود.

## XmlReader::ReadElementString(String) متد

بررسی می‌کند که مقدار [XmlReader::get_Name](../get_name/) عنصر پیدا شده با رشتهٔ داده‌شده مطابقت داشته باشد قبل از خواندن عنصر فقط متنی. با این حال، توصیه می‌شود به جای آن از متد [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) استفاده کنید، زیرا راه‌حل ساده‌تری برای انجام این عملیات فراهم می‌کند.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String name)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | [String](../../../system/string/) | نام برای بررسی. |

### مقدار بازگشت

متنی که در عنصر خوانده شده قرار داشته است. اگر عنصر خالی باشد، رشتهٔ خالی برگردانده می‌شود.

## XmlReader::ReadElementString(String, String) متد

بررسی می‌کند که مقادیر [XmlReader::get_LocalName](../get_localname/) و [XmlReader::get_NamespaceURI](../get_namespaceuri/) عنصر پیدا شده با رشته‌های داده‌شده مطابقت داشته باشند قبل از خواندن عنصر فقط متنی. با این حال، توصیه می‌شود به جای آن از متد [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) استفاده کنید، زیرا راه‌حل ساده‌تری برای انجام این عملیات فراهم می‌کند.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String localname, String ns)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| localname | [String](../../../system/string/) | نام محلی برای بررسی. |
| ns | [String](../../../system/string/) | URI فضای‌نام برای بررسی. |

### مقدار بازگشت

متنی که در عنصر خوانده شده قرار داشته است. اگر عنصر خالی باشد، رشتهٔ خالی برگردانده می‌شود.

## مراجع

* کلاس [String](../../../system/string/)
* کلاس [XmlReader](../)
* فضای‌نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)