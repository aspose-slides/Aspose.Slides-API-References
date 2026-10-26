---
title: Transform()
second_title: مرجع API برای Aspose.Slides به زبان C++
description: داده‌های XML موجود در XPathNavigator را با استفاده از args مشخص‌شده تبدیل می‌کند و نتیجه را به یک XmlReader خروجی می‌دهد.
type: docs
weight: 40
url: /fa/system.xml.xsl/xsltransform/transform/
---
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

داده‌های XML را در XPathNavigator با استفاده از **args** مشخص‌شده تبدیل می‌کند و نتیجه را به یک [XmlReader](../../../system.xml/xmlreader/) خروجی می‌دهد.

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | یک XPathNavigator که شامل داده‌های قابل تبدیل است. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | یک [XsltArgumentList](../../xsltargumentlist/) که شامل آرگومان‌های دارای فضای‌نامی مورد استفاده به عنوان ورودی برای تبدیل است. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) مورد استفاده برای حل تابع XSLT **document()**. اگر این مقدار **nullptr** باشد، تابع **document()** حل نمی‌شود. [XmlResolver](../../../system.xml/xmlresolver/) پس از پایان اجرای این متد ذخیره‌سازی (کش) نمی‌شود. |

### مقدار بازگشت

یک [XmlReader](../../../system.xml/xmlreader/) که شامل نتایج تبدیل است.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&) method

داده‌های XML را در XPathNavigator با استفاده از **args** مشخص‌شده تبدیل می‌کند و نتیجه را به یک [XmlReader](../../../system.xml/xmlreader/) خروجی می‌دهد.

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | یک XPathNavigator که شامل داده‌های قابل تبدیل است. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | یک [XsltArgumentList](../../xsltargumentlist/) که شامل آرگومان‌های دارای فضای‌نامی مورد استفاده به عنوان ورودی برای تبدیل است. |

### مقدار بازگشت

یک [XmlReader](../../../system.xml/xmlreader/) که شامل نتایج تبدیل است.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

داده‌های XML را در XPathNavigator با استفاده از **args** مشخص‌شده تبدیل می‌کند و نتیجه را به یک [XmlWriter](../../../system.xml/xmlwriter/) خروجی می‌دهد.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | یک XPathNavigator که شامل داده‌های قابل تبدیل است. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | یک [XsltArgumentList](../../xsltargumentlist/) که شامل آرگومان‌های دارای فضای‌نامی مورد استفاده به عنوان ورودی برای تبدیل است. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) که می‌خواهید خروجی به آن داده شود. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) مورد استفاده برای حل تابع XSLT **document()**. اگر این مقدار **nullptr** باشد، تابع **document()** حل نمی‌شود. [XmlResolver](../../../system.xml/xmlresolver/) پس از پایان اجرای این متد ذخیره‌سازی (کش) نمی‌شود. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method

داده‌های XML را در XPathNavigator با استفاده از **args** مشخص‌شده تبدیل می‌کند و نتیجه را به یک [XmlWriter](../../../system.xml/xmlwriter/) خروجی می‌دهد.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | یک XPathNavigator که شامل داده‌های قابل تبدیل است. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | یک [XsltArgumentList](../../xsltargumentlist/) که شامل آرگومان‌های دارای فضای‌نامی مورد استفاده به عنوان ورودی برای تبدیل است. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) که می‌خواهید خروجی به آن داده شود. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

داده‌های XML را در XPathNavigator با استفاده از **args** مشخص‌شده تبدیل می‌کند و نتیجه را به یک Stream خروجی می‌دهد.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | یک XPathNavigator که شامل داده‌های قابل تبدیل است. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | یک [XsltArgumentList](../../xsltargumentlist/) که شامل آرگومان‌های دارای فضای‌نامی مورد استفاده به عنوان ورودی برای تبدیل است. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Stream که می‌خواهید خروجی به آن داده شود. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) مورد استفاده برای حل تابع XSLT **document()**. اگر این مقدار **nullptr** باشد، تابع **document()** حل نمی‌شود. [XmlResolver](../../../system.xml/xmlresolver/) پس از پایان اجرای این متد ذخیره‌سازی (کش) نمی‌شود. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method

داده‌های XML را در XPathNavigator با استفاده از **args** مشخص‌شده تبدیل می‌کند و نتیجه را به یک Stream خروجی می‌دهد.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | یک XPathNavigator که شامل داده‌های قابل تبدیل است. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | یک [XsltArgumentList](../../xsltargumentlist/) که شامل آرگومان‌های دارای فضای‌نامی مورد استفاده به عنوان ورودی برای تبدیل است. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Stream که می‌خواهید خروجی به آن داده شود. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

داده‌های XML را در XPathNavigator با استفاده از **args** مشخص‌شده تبدیل می‌کند و نتیجه را به یک TextWriter خروجی می‌دهد.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | یک XPathNavigator که شامل داده‌های قابل تبدیل است. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | یک [XsltArgumentList](../../xsltargumentlist/) که شامل آرگومان‌های دارای فضای‌نامی مورد استفاده به عنوان ورودی برای تبدیل است. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter که می‌خواهید خروجی به آن داده شود. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) مورد استفاده برای حل تابع XSLT **document()**. اگر این مقدار **nullptr** باشد، تابع **document()** حل نمی‌شود. [XmlResolver](../../../system.xml/xmlresolver/) پس از پایان اجرای این متد ذخیره‌سازی (کش) نمی‌شود. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method

داده‌های XML را در XPathNavigator با استفاده از **args** مشخص‌شده تبدیل می‌کند و نتیجه را به یک TextWriter خروجی می‌دهد.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | یک XPathNavigator که شامل داده‌های قابل تبدیل است. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | یک [XsltArgumentList](../../xsltargumentlist/) که شامل آرگومان‌های دارای فضای‌نامی مورد استفاده به عنوان ورودی برای تبدیل است. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter که می‌خواهید خروجی به آن داده شود. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

داده‌های XML را در IXPathNavigable با استفاده از **args** مشخص‌شده تبدیل می‌کند و نتیجه را به یک [XmlReader](../../../system.xml/xmlreader/) خروجی می‌دهد.

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | شیئی که رابط IXPathNavigable را پیاده‌سازی می‌کند. می‌تواند یک [XmlNode](../../../system.xml/xmlnode/) (معمولاً یک [XmlDocument](../../../system.xml/xmldocument/)) یا یک XPathDocument باشد که شامل داده‌های قابل تبدیل است. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | یک [XsltArgumentList](../../xsltargumentlist/) که شامل آرگومان‌های دارای فضای‌نامی مورد استفاده به عنوان ورودی برای تبدیل است. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) مورد استفاده برای حل تابع XSLT **document()**. اگر این مقدار **nullptr** باشد، تابع **document()** حل نمی‌شود. [XmlResolver](../../../system.xml/xmlresolver/) پس از پایان اجرای این متد ذخیره‌سازی (کش) نمی‌شود. |

### مقدار بازگشت

یک [XmlReader](../../../system.xml/xmlreader/) که شامل نتایج تبدیل است.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&) method

داده‌های XML را در IXPathNavigable با استفاده از **args** مشخص‌شده تبدیل می‌کند و نتیجه را به یک [XmlReader](../../../system.xml/xmlreader/) خروجی می‌دهد.

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | شیئی که رابط IXPathNavigable را پیاده‌سازی می‌کند. می‌تواند یک [XmlNode](../../../system.xml/xmlnode/) (معمولاً یک [XmlDocument](../../../system.xml/xmldocument/)) یا یک XPathDocument باشد که شامل داده‌های قابل تبدیل است. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | یک [XsltArgumentList](../../xsltargumentlist/) که شامل آرگومان‌های دارای فضای‌نامی مورد استفاده به عنوان ورودی برای تبدیل است. |

### مقدار بازگشت

یک [XmlReader](../../../system.xml/xmlreader/) که شامل نتایج تبدیل است.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

داده‌های XML را در IXPathNavigable با استفاده از **args** مشخص‌شده تبدیل می‌کند و نتیجه را به یک TextWriter خروجی می‌دهد.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | شیئی که رابط IXPathNavigable را پیاده‌سازی می‌کند. می‌تواند یک [XmlNode](../../../system.xml/xmlnode/) (معمولاً یک [XmlDocument](../../../system.xml/xmldocument/)) یا یک XPathDocument باشد که شامل داده‌های قابل تبدیل است. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | یک [XsltArgumentList](../../xsltargumentlist/) که شامل آرگومان‌های دارای فضای‌نامی مورد استفاده به عنوان ورودی برای تبدیل است. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter که می‌خواهید خروجی به آن داده شود. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) مورد استفاده برای حل تابع XSLT **document()**. اگر این مقدار **nullptr** باشد، تابع **document()** حل نمی‌شود. [XmlResolver](../../../system.xml/xmlresolver/) پس از پایان اجرای این متد ذخیره‌سازی (کش) نمی‌شود. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method

داده‌های XML را در IXPathNavigable با استفاده از **args** مشخص‌شده تبدیل می‌کند و نتیجه را به یک TextWriter خروجی می‌دهد.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | شیئی که رابط IXPathNavigable را پیاده‌سازی می‌کند. می‌تواند یک [XmlNode](../../../system.xml/xmlnode/) (معمولاً یک [XmlDocument](../../../system.xml/xmldocument/)) یا یک XPathDocument باشد که شامل داده‌های قابل تبدیل است. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | یک [XsltArgumentList](../../xsltargumentlist/) که شامل آرگومان‌های دارای فضای‌نامی مورد استفاده به عنوان ورودی برای تبدیل است. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter که می‌خواهید خروجی به آن داده شود. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

داده‌های XML را در IXPathNavigable با استفاده از **args** مشخص‌شده تبدیل می‌کند و نتیجه را به یک Stream خروجی می‌دهد.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | شیئی که رابط IXPathNavigable را پیاده‌سازی می‌کند. می‌تواند یک [XmlNode](../../../system.xml/xmlnode/) (معمولاً یک [XmlDocument](../../../system.xml/xmldocument/)) یا یک XPathDocument باشد که شامل داده‌های قابل تبدیل است. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | یک [XsltArgumentList](../../xsltargumentlist/) که شامل آرگومان‌های دارای فضای‌نامی مورد استفاده به عنوان ورودی برای تبدیل است. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Stream که می‌خواهید خروجی به آن داده شود. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) مورد استفاده برای حل تابع XSLT **document()**. اگر این مقدار **nullptr** باشد، تابع **document()** حل نمی‌شود. [XmlResolver](../../../system.xml/xmlresolver/) پس از پایان اجرای [XslTransform::Transform](./) متد ذخیره‌سازی (کش) نمی‌شود. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method

داده‌های XML را در IXPathNavigable با استفاده از **args** مشخص‌شده تبدیل می‌کند و نتیجه را به یک Stream خروجی می‌دهد.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | شیئی که رابط IXPathNavigable را پیاده‌سازی می‌کند. می‌تواند یک [XmlNode](../../../system.xml/xmlnode/) (معمولاً یک [XmlDocument](../../../system.xml/xmldocument/)) یا یک XPathDocument باشد که شامل داده‌های قابل تبدیل است. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | یک [XsltArgumentList](../../xsltargumentlist/) که شامل آرگومان‌های دارای فضای‌نامی مورد استفاده به عنوان ورودی برای تبدیل است. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Stream که می‌خواهید خروجی به آن داده شود. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

داده‌های XML را در IXPathNavigable با استفاده از **args** مشخص‌شده تبدیل می‌کند و نتیجه را به یک [XmlWriter](../../../system.xml/xmlwriter/) خروجی می‌دهد.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | شیئی که رابط IXPathNavigable را پیاده‌سازی می‌کند. می‌تواند یک [XmlNode](../../../system.xml/xmlnode/) (معمولاً یک [XmlDocument](../../../system.xml/xmldocument/)) یا یک XPathDocument باشد که شامل داده‌های قابل تبدیل است. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | یک [XsltArgumentList](../../xsltargumentlist/) که شامل آرگومان‌های دارای فضای‌نامی مورد استفاده به عنوان ورودی برای تبدیل است. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) که می‌خواهید خروجی به آن داده شود. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) مورد استفاده برای حل تابع XSLT **document()**. اگر این مقدار **nullptr** باشد، تابع **document()** حل نمی‌شود. [XmlResolver](../../../system.xml/xmlresolver/) پس از پایان اجرای این متد ذخیره‌سازی (کش) نمی‌شود. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method

داده‌های XML را در IXPathNavigable با استفاده از **args** مشخص‌شده تبدیل می‌کند و نتیجه را به یک [XmlWriter](../../../system.xml/xmlwriter/) خروجی می‌دهد.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | شیئی که رابط IXPathNavigable را پیاده‌سازی می‌کند. می‌تواند یک [XmlNode](../../../system.xml/xmlnode/) (معمولاً یک [XmlDocument](../../../system.xml/xmldocument/)) یا یک XPathDocument باشد که شامل داده‌های قابل تبدیل است. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | یک [XsltArgumentList](../../xsltargumentlist/) که شامل آرگومان‌های دارای فضای‌نامی مورد استفاده به عنوان ورودی برای تبدیل است. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) که می‌خواهید خروجی به آن داده شود. |

## XslTransform::Transform(const String\&, const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

داده‌های XML را در فایل ورودی تبدیل می‌کند و نتیجه را به یک فایل خروجی می‌نویسد.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const String &inputfile, const String &outputfile, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| inputfile | const [String](../../../system/string/)\& | URL سند منبع برای تبدیل. |
| outputfile | const [String](../../../system/string/)\& | URL فایل خروجی. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) مورد استفاده برای حل تابع XSLT **document()**. اگر این مقدار **nullptr** باشد، تابع **document()** حل نمی‌شود. [XmlResolver](../../../system.xml/xmlresolver/) پس از پایان اجرای [XslTransform::Transform](./) متد ذخیره‌سازی (کش) نمی‌شود. |

## XslTransform::Transform(const String\&, const String\&) method

داده‌های XML را در فایل ورودی تبدیل می‌کند و نتیجه را به یک فایل خروجی می‌نویسد.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const String &inputfile, const String &outputfile)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| inputfile | const [String](../../../system/string/)\& | URL سند منبع برای تبدیل. |
| outputfile | const [String](../../../system/string/)\& | URL فایل خروجی. |

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [Stream](../../../system.io/stream/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [String](../../../system/string/)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)