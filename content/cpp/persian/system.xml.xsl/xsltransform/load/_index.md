---
title: Load()
second_title: مرجع API Aspose.Slides برای C++
description: برگه سبک XSLT موجود در XmlReader را بارگذاری می‌کند.
type: docs
weight: 27
url: /fa/system.xml.xsl/xsltransform/load/
---
## XslTransform::Load(const SharedPtr\<XmlReader\>\&) متد

بارگذاری شیت استایل XSLT موجود در [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | یک شیء [XmlReader](../../../system.xml/xmlreader/) که شیت استایل XSLT را شامل می‌شود. |

## XslTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) متد

بارگذاری شیت استایل XSLT موجود در [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | یک شیء [XmlReader](../../../system.xml/xmlreader/) که شیت استایل XSLT را شامل می‌شود. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) مورد استفاده برای بارگذاری هر شیت استایلی که در عناصر **xsl:import** و **xsl:include** ارجاع داده شده است. اگر مقدار **nullptr** باشد، منابع خارجی حل نمی‌شوند. [XmlResolver](../../../system.xml/xmlresolver/) پس از تکمیل این متد کش نمی‌شود. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) متد

بارگذاری شیت استایل XSLT موجود در IXPathNavigable.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | شیئی که رابط IXPathNavigable را پیاده‌سازی می‌کند. می‌تواند یا یک [XmlNode](../../../system.xml/xmlnode/) (معمولاً یک [XmlDocument](../../../system.xml/xmldocument/)) باشد، یا یک XPathDocument که شیت استایل XSLT را شامل می‌شود. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) متد

بارگذاری شیت استایل XSLT موجود در IXPathNavigable.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | شیئی که رابط IXPathNavigable را پیاده‌سازی می‌کند. می‌تواند یا یک [XmlNode](../../../system.xml/xmlnode/) (معمولاً یک [XmlDocument](../../../system.xml/xmldocument/)) باشد، یا یک XPathDocument که شیت استایل XSLT را شامل می‌شود. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) مورد استفاده برای بارگذاری هر شیت استایلی که در عناصر **xsl:import** و **xsl:include** ارجاع داده شده است. اگر مقدار **nullptr** باشد، منابع خارجی حل نمی‌شوند. [XmlResolver](../../../system.xml/xmlresolver/) پس از تکمیل این متد کش نمی‌شود. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&) متد

بارگذاری شیت استایل XSLT موجود در XPathNavigator.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | شیء XPathNavigator که شیت استایل XSLT را شامل می‌شود. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) متد

بارگذاری شیت استایل XSLT موجود در XPathNavigator.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | شیء XPathNavigator که شیت استایل XSLT را شامل می‌شود. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) مورد استفاده برای بارگذاری هر شیت استایلی که در عناصر **xsl:import** و **xsl:include** ارجاع داده شده است. اگر مقدار **nullptr** باشد، منابع خارجی حل نمی‌شوند. [XmlResolver](../../../system.xml/xmlresolver/) پس از تکمیل این متد کش نمی‌شود. |

## XslTransform::Load(const String\&) متد

بارگذاری شیت استایل XSLT مشخص‌شده توسط یک URL.

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL که شیت استایل XSLT را برای بارگذاری مشخص می‌کند. |

## XslTransform::Load(const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) متد

بارگذاری شیت استایل XSLT مشخص‌شده توسط یک URL.

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL که شیت استایل XSLT را برای بارگذاری مشخص می‌کند. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) برای بارگذاری شیت استایل و هر شیت(ها) ارجاع داده‌شده در عناصر **xsl:import** و **xsl:include**. اگر مقدار **nullptr** باشد، یک [XmlUrlResolver](../../../system.xml/xmlurlresolver/) پیش‌فرض بدون اعتبارسند کاربری برای باز کردن شیت استایل استفاده می‌شود. [XmlUrlResolver](../../../system.xml/xmlurlresolver/) پیش‌فرض برای حل منابع خارجی در شیت استایل استفاده نمی‌شود، بنابراین عناصر **xsl:import** و **xsl:include** حل نمی‌شوند. [XmlResolver](../../../system.xml/xmlresolver/) پس از تکمیل این متد کش نمی‌شود. |

## مراجع

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [XmlReader](../../../system.xml/xmlreader/)
* کلاس [XslTransform](../)
* کلاس [XmlResolver](../../../system.xml/xmlresolver/)
* کلاس [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* کلاس [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* کلاس [String](../../../system/string/)
* فضای‌نام [System::Xml::Xsl](../../)
* کتابخانه [Aspose.Slides](../../../)