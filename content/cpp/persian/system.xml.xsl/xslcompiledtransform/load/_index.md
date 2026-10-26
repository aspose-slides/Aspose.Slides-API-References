---
title: Load()
second_title: مرجع API Aspose.Slides برای C++
description: برگهٔ استایل موجود در XmlReader را کامپایل می‌کند.
type: docs
weight: 27
url: /fa/system.xml.xsl/xslcompiledtransform/load/
---
## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&) متد

برگهٔ استایل موجود در [XmlReader](../../../system.xml/xmlreader/) را کامپایل می‌کند.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | یک [XmlReader](../../../system.xml/xmlreader/) حاوی برگهٔ استایل. |

## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) متد

برگهٔ XSLT موجود در [XmlReader](../../../system.xml/xmlreader/) را کامپایل می‌کند. [XmlResolver](../../../system.xml/xmlresolver/) هر عنصر **import** یا **include** XSLT را برطرف می‌کند و تنظیمات XSLT مجوزهای برگهٔ استایل را تعیین می‌کند.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) حاوی برگهٔ استایل. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\>\& | [XsltSettings](../../xsltsettings/) برای اعمال بر روی برگهٔ استایل. اگر این مقدار **nullptr** باشد، تنظیم [XsltSettings::get_Default](../../xsltsettings/get_default/) اعمال می‌شود. |
| stylesheetResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) مورد استفاده برای برطرف کردن هر برگهٔ استایلی که در عناصر **import** و **include** XSLT ارجاع شده است. اگر این مقدار **nullptr** باشد، منابع خارجی برطرف نمی‌شوند. |

## XslCompiledTransform::Load(const String\&) متد

برگهٔ استایلی را که در URI مشخص شده قرار دارد بارگذاری و کامپایل می‌کند.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stylesheetUri | const [String](../../../system/string/)\& | URI برگهٔ استایل. |

## XslCompiledTransform::Load(const String\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) متد

برگهٔ XSLT را که توسط URI مشخص شده است بارگذاری و کامپایل می‌کند. [XmlResolver](../../../system.xml/xmlresolver/) هر عنصر **import** یا **include** XSLT را برطرف می‌کند و تنظیمات XSLT مجوزهای برگهٔ استایل را تعیین می‌کند.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stylesheetUri | const [String](../../../system/string/)\& | URI برگهٔ استایل. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\>\& | [XsltSettings](../../xsltsettings/) برای اعمال بر روی برگهٔ استایل. اگر این مقدار **nullptr** باشد، تنظیم [XsltSettings::get_Default](../../xsltsettings/get_default/) اعمال می‌شود. |
| stylesheetResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) مورد استفاده برای برطرف کردن URI برگهٔ استایل و هر برگهٔ استایلی که در عناصر **import** و **include** XSLT ارجاع شده است. |

## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) متد

برگهٔ استایل موجود در شیء IXPathNavigable را کامپایل می‌کند.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | شیئی که رابط IXPathNavigable را پیاده‌سازی می‌کند. می‌تواند یک [XmlNode](../../../system.xml/xmlnode/) (معمولاً یک [XmlDocument](../../../system.xml/xmldocument/)) یا یک XPathDocument حاوی برگهٔ استایل باشد. |

## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, SharedPtr\<XsltSettings\>, SharedPtr\<XmlResolver\>) متد

برگهٔ XSLT موجود در IXPathNavigable را کامپایل می‌کند. [XmlResolver](../../../system.xml/xmlresolver/) هر عنصر **import** یا **include** XSLT را برطرف می‌کند و تنظیمات XSLT مجوزهای برگهٔ استایل را تعیین می‌کند.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, SharedPtr<XsltSettings> settings, SharedPtr<XmlResolver> stylesheetResolver)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | شی‌ای که رابط IXPathNavigable را پیاده‌سازی می‌کند. می‌تواند یک [XmlNode](../../../system.xml/xmlnode/) (معمولاً یک [XmlDocument](../../../system.xml/xmldocument/)) یا یک XPathDocument حاوی برگهٔ استایل باشد. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\> | [XsltSettings](../../xsltsettings/) برای اعمال بر روی برگهٔ استایل. اگر این مقدار **nullptr** باشد، تنظیم [XsltSettings::get_Default](../../xsltsettings/get_default/) اعمال می‌شود. |
| stylesheetResolver | [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\> | [XmlResolver](../../../system.xml/xmlresolver/) مورد استفاده برای برطرف کردن هر برگهٔ استایلی که در عناصر **import** و **include** XSLT ارجاع شده است. اگر این مقدار **nullptr** باشد، منابع خارجی برطرف نمی‌شوند. |

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [XmlReader](../../../system.xml/xmlreader/)
* کلاس [XslCompiledTransform](../)
* کلاس [XsltSettings](../../xsltsettings/)
* کلاس [XmlResolver](../../../system.xml/xmlresolver/)
* کلاس [String](../../../system/string/)
* کلاس [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* فضای‌نام [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)