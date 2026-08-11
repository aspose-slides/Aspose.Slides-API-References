---
title: Transform()
second_title: مرجع API Aspose.Slides برای C++
description: تبدیل را با استفاده از سند ورودی که توسط شیء IXPathNavigable مشخص شده اجرا می‌کند و نتایج را به یک XmlWriter خروجی می‌دهد.
type: docs
weight: 40
url: /fa/system.xml.xsl/xslcompiledtransform/transform/
---
## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XmlWriter\>\&) متد


تبدیل را با استفاده از سند ورودی که توسط شیء IXPathNavigable مشخص می‌شود اجرا می‌کند و نتایج را به یک [XmlWriter](../../../system.xml/xmlwriter/) خروجی می‌دهد.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XmlWriter> &results)
```


### پارامترها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | یک شیء که رابط IXPathNavigable را پیاده‌سازی می‌کند. می‌تواند یک [XmlNode](../../../system.xml/xmlnode/) (معمولاً یک [XmlDocument](../../../system.xml/xmldocument/)) یا یک XPathDocument حاوی داده‌های قابل تبدیل باشد. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) که می‌خواهید خروجی را به آن بنویسید. اگر شیوه‌نامه شامل عنصر **xsl:output** باشد، باید [XmlWriter](../../../system.xml/xmlwriter/) را با استفاده از شیء [XmlWriterSettings](../../../system.xml/xmlwritersettings/) که از مقدار [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) برگردانده می‌شود، ایجاد کنید. این کار اطمینان می‌دهد [XmlWriter](../../../system.xml/xmlwriter/) تنظیمات خروجی صحیح دارد. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) متد


تبدیل را با استفاده از سند ورودی که توسط شیء IXPathNavigable مشخص می‌شود اجرا می‌کند و نتایج را به یک [XmlWriter](../../../system.xml/xmlwriter/) خروجی می‌دهد. [XsltArgumentList](../../xsltargumentlist/) آرگومان‌های زمان اجرا اضافی را فراهم می‌کند.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```


### پارامترها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | یک شیء که رابط IXPathNavigable را پیاده‌سازی می‌کند. می‌تواند یک [XmlNode](../../../system.xml/xmlnode/) (معمولاً یک [XmlDocument](../../../system.xml/xmldocument/)) یا یک XPathDocument حاوی داده‌های قابل تبدیل باشد. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | یک [XsltArgumentList](../../xsltargumentlist/) حاوی آرگومان‌های نام‌فضایی-qualified که به عنوان ورودی به تبدیل استفاده می‌شود. این مقدار می‌تواند **nullptr** باشد. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) که می‌خواهید خروجی را به آن بنویسید. اگر شیوه‌نامه شامل عنصر **xsl:output** باشد، باید [XmlWriter](../../../system.xml/xmlwriter/) را با استفاده از شیء [XmlWriterSettings](../../../system.xml/xmlwritersettings/) که از مقدار [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) برگردانده می‌شود، ایجاد کنید. این کار اطمینان می‌دهد [XmlWriter](../../../system.xml/xmlwriter/) تنظیمات خروجی صحیح دارد. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) متد


تبدیل را با استفاده از سند ورودی که توسط شیء IXPathNavigable مشخص می‌شود اجرا می‌کند و نتایج را به یک TextWriter خروجی می‌دهد. [XsltArgumentList](../../xsltargumentlist/) آرگومان‌های زمان اجرا اضافی را فراهم می‌کند.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```


### پارامترها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | یک شیء که رابط IXPathNavigable را پیاده‌سازی می‌کند. می‌تواند یک [XmlNode](../../../system.xml/xmlnode/) (معمولاً یک [XmlDocument](../../../system.xml/xmldocument/)) یا یک XPathDocument حاوی داده‌های قابل تبدیل باشد. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | یک [XsltArgumentList](../../xsltargumentlist/) حاوی آرگومان‌های نام‌فضایی-qualified که به عنوان ورودی به تبدیل استفاده می‌شود. این مقدار می‌تواند **nullptr** باشد. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter که می‌خواهید خروجی را به آن بنویسید. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) متد


تبدیل را با استفاده از سند ورودی که توسط شیء IXPathNavigable مشخص می‌شود اجرا می‌کند و نتایج را به یک جریان خروجی می‌دهد. [XsltArgumentList](../../xsltargumentlist/) آرگومان‌های زمان اجرا اضافی را فراهم می‌کند.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```


### پارامترها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | یک شیء که رابط IXPathNavigable را پیاده‌سازی می‌کند. می‌تواند یک [XmlNode](../../../system.xml/xmlnode/) (معمولاً یک [XmlDocument](../../../system.xml/xmldocument/)) یا یک XPathDocument حاوی داده‌های قابل تبدیل باشد. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | یک [XsltArgumentList](../../xsltargumentlist/) حاوی آرگومان‌های نام‌فضایی-qualified که به عنوان ورودی به تبدیل استفاده می‌شود. این مقدار می‌تواند **nullptr** باشد. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | جریانی که می‌خواهید خروجی را به آن بنویسید. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XmlWriter\>\&) متد


تبدیل را با استفاده از سند ورودی که توسط شیء [XmlReader](../../../system.xml/xmlreader/) مشخص می‌شود اجرا می‌کند و نتایج را به یک [XmlWriter](../../../system.xml/xmlwriter/) خروجی می‌دهد.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XmlWriter> &results)
```


### پارامترها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) حاوی سند ورودی. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) که می‌خواهید خروجی را به آن بنویسید. اگر شیوه‌نامه شامل عنصر **xsl:output** باشد، باید [XmlWriter](../../../system.xml/xmlwriter/) را با استفاده از شیء [XmlWriterSettings](../../../system.xml/xmlwritersettings/) که از مقدار [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) برگردانده می‌شود، ایجاد کنید. این کار اطمینان می‌دهد [XmlWriter](../../../system.xml/xmlwriter/) تنظیمات خروجی صحیح دارد. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) متد


تبدیل را با استفاده از سند ورودی که توسط شیء [XmlReader](../../../system.xml/xmlreader/) مشخص می‌شود اجرا می‌کند و نتایج را به یک [XmlWriter](../../../system.xml/xmlwriter/) خروجی می‌دهد. [XsltArgumentList](../../xsltargumentlist/) آرگومان‌های زمان اجرا اضافی را فراهم می‌کند.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```


### پارامترها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) حاوی سند ورودی. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | یک [XsltArgumentList](../../xsltargumentlist/) حاوی آرگومان‌های نام‌فضایی-qualified که به عنوان ورودی به تبدیل استفاده می‌شود. این مقدار می‌تواند **nullptr** باشد. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) که می‌خواهید خروجی را به آن بنویسید. اگر شیوه‌نامه شامل عنصر **xsl:output** باشد، باید [XmlWriter](../../../system.xml/xmlwriter/) را با استفاده از شیء [XmlWriterSettings](../../../system.xml/xmlwritersettings/) که از مقدار [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) برگردانده می‌شود، ایجاد کنید. این کار اطمینان می‌دهد [XmlWriter](../../../system.xml/xmlwriter/) تنظیمات خروجی صحیح دارد. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) متد


تبدیل را با استفاده از سند ورودی که توسط شیء [XmlReader](../../../system.xml/xmlreader/) مشخص می‌شود اجرا می‌کند و نتایج را به یک TextWriter خروجی می‌دهد. [XsltArgumentList](../../xsltargumentlist/) آرگومان‌های زمان اجرا اضافی را فراهم می‌کند.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```


### پارامترها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) حاوی سند ورودی. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | یک [XsltArgumentList](../../xsltargumentlist/) حاوی آرگومان‌های نام‌فضایی-qualified که به عنوان ورودی به تبدیل استفاده می‌شود. این مقدار می‌تواند **nullptr** باشد. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter که می‌خواهید خروجی را به آن بنویسید. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) متد


تبدیل را با استفاده از سند ورودی که توسط شیء [XmlReader](../../../system.xml/xmlreader/) مشخص می‌شود اجرا می‌کند و نتایج را به یک جریان خروجی می‌دهد. [XsltArgumentList](../../xsltargumentlist/) آرگومان‌های زمان اجرا اضافی را فراهم می‌کند.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```


### پارامترها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | یک [XmlReader](../../../system.xml/xmlreader/) حاوی سند ورودی. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | یک [XsltArgumentList](../../xsltargumentlist/) حاوی آرگومان‌های نام‌فضایی-qualified که به عنوان ورودی به تبدیل استفاده می‌شود. این مقدار می‌تواند **nullptr** باشد. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | جریانی که می‌خواهید خروجی را به آن بنویسید. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XmlWriter\>\&) متد


تبدیل را با استفاده از سند ورودی که توسط URI مشخص می‌شود اجرا می‌کند و نتایج را به یک [XmlWriter](../../../system.xml/xmlwriter/) خروجی می‌دهد.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XmlWriter> &results)
```


### پارامترها

| پارامتر | نوع | توضیحیات |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI سند ورودی. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) که می‌خواهید خروجی را به آن بنویسید. اگر شیوه‌نامه شامل عنصر **xsl:output** باشد، باید [XmlWriter](../../../system.xml/xmlwriter/) را با استفاده از شیء [XmlWriterSettings](../../../system.xml/xmlwritersettings/) که از مقدار [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) برگردانده می‌شود، ایجاد کنید. این کار اطمینان می‌دهد [XmlWriter](../../../system.xml/xmlwriter/) تنظیمات خروجی صحیح دارد. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) متد


تبدیل را با استفاده از سند ورودی که توسط URI مشخص می‌شود اجرا می‌کند و نتایج را به یک [XmlWriter](../../../system.xml/xmlwriter/) خروجی می‌دهد. [XsltArgumentList](../../xsltargumentlist/) آرگومان‌های زمان اجرا اضافی را فراهم می‌کند.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```


### پارامترها

| پارامتر | نوع | توضیحیات |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI سند ورودی. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | یک [XsltArgumentList](../../xsltargumentlist/) حاوی آرگومان‌های نام‌فضایی-qualified که به عنوان ورودی به تبدیل استفاده می‌شود. این مقدار می‌تواند **nullptr** باشد. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) که می‌خواهید خروجی را به آن بنویسید. اگر شیوه‌نامه شامل عنصر **xsl:output** باشد، باید [XmlWriter](../../../system.xml/xmlwriter/) را با استفاده از شیء [XmlWriterSettings](../../../system.xml/xmlwritersettings/) که از مقدار [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) برگردانده می‌شود، ایجاد کنید. این کار اطمینان می‌دهد [XmlWriter](../../../system.xml/xmlwriter/) تنظیمات خروجی صحیح دارد. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) متد


تبدیل را با استفاده از سند ورودی که توسط URI مشخص می‌شود اجرا می‌کند و نتایج را به یک TextWriter خروجی می‌دهد.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```


### پارامترها

| پارامتر | نوع | توضیحیات |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI سند ورودی. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | یک [XsltArgumentList](../../xsltargumentlist/) حاوی آرگومان‌های نام‌فضایی-qualified که به عنوان ورودی به تبدیل استفاده می‌شود. این مقدار می‌تواند **nullptr** باشد. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter که می‌خواهید خروجی را به آن بنویسید. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) متد


تبدیل را با استفاده از سند ورودی که توسط URI مشخص می‌شود اجرا می‌کند و نتایج را به یک جریان خروجی می‌دهد. [XsltArgumentList](../../xsltargumentlist/) آرگومان‌های زمان اجرا اضافی را فراهم می‌کند.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```


### پارامترها

| پارامتر | نوع | توضیحیات |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI سند ورودی. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | یک [XsltArgumentList](../../xsltargumentlist/) حاوی آرگومان‌های نام‌فضایی-qualified که به عنوان ورودی به تبدیل استفاده می‌شود. این مقدار می‌تواند **nullptr** باشد. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | جریانی که می‌خواهید خروجی را به آن بنویسید. |

## XslCompiledTransform::Transform(const String\&, const String\&) متد


تبدیل را با استفاده از سند ورودی که توسط URI مشخص می‌شود اجرا می‌کند و نتایج را به یک فایل خروجی می‌دهد.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const String &resultsFile)
```


### پارامترها

| پارامتر | نوع | توضیحیات |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI سند ورودی. |
| resultsFile | const [String](../../../system/string/)\& | URI فایل خروجی. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) متد


تبدیل را با استفاده از سند ورودی که توسط شیء [XmlReader](../../../system.xml/xmlreader/) مشخص می‌شود اجرا می‌کند و نتایج را به یک [XmlWriter](../../../system.xml/xmlwriter/) خروجی می‌دهد. [XsltArgumentList](../../xsltargumentlist/) آرگومان‌های زمان اجرا اضافی را فراهم می‌کند و [XmlResolver](../../../system.xml/xmlresolver/) تابع XSLT **document()** را حل می‌کند.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```


### پارامترها

| پارامتر | نوع | توضیحیات |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) حاوی سند ورودی. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | یک [XsltArgumentList](../../xsltargumentlist/) حاوی آرگومان‌های نام‌فضایی-qualified که به عنوان ورودی به تبدیل استفاده می‌شود. این مقدار می‌تواند **nullptr** باشد. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) که می‌خواهید خروجی را به آن بنویسید. اگر شیوه‌نامه شامل عنصر **xsl:output** باشد، باید [XmlWriter](../../../system.xml/xmlwriter/) را با استفاده از شیء [XmlWriterSettings](../../../system.xml/xmlwritersettings/) که از مقدار [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) برگردانده می‌شود، ایجاد کنید. این کار اطمینان می‌دهد [XmlWriter](../../../system.xml/xmlwriter/) تنظیمات خروجی صحیح دارد. |
| documentResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) مورد استفاده برای حل تابع XSLT **document()**. اگر این مقدار **nullptr** باشد، تابع **document()** حل نمی‌شود. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) متد


تبدیل را با استفاده از سند ورودی که توسط شیء IXPathNavigable مشخص می‌شود اجرا می‌کند و نتایج را به یک [XmlWriter](../../../system.xml/xmlwriter/) خروجی می‌دهد. [XsltArgumentList](../../xsltargumentlist/) آرگومان‌های زمان اجرا اضافی را فراهم می‌کند و [XmlResolver](../../../system.xml/xmlresolver/) تابع XSLT **document()** را حل می‌کند.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```


### پارامترها

| پارامتر | نوع | توضیحیات |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | سندی که توسط شیء IXPathNavigable مشخص می‌شود و باید تبدیل شود. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | فهرست آرگومان‌ها به عنوان [XsltArgumentList](../../xsltargumentlist/). |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) که می‌خواهید خروجی را به آن بنویسید. اگر شیوه‌نامه شامل عنصر **xsl:output** باشد، باید [XmlWriter](../../../system.xml/xmlwriter/) را با استفاده از شیء [XmlWriterSettings](../../../system.xml/xmlwritersettings/) که از مقدار [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) برگردانده می‌شود، ایجاد کنید. این کار اطمینان می‌دهد [XmlWriter](../../../system.xml/xmlwriter/) تنظیمات خروجی صحیح دارد. |
| documentResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) مورد استفاده برای حل تابع XSLT **document()**. اگر این مقدار **nullptr** باشد، تابع **document()** حل نمی‌شود. |

## مراجع

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* کلاس [XmlWriter](../../../system.xml/xmlwriter/)
* کلاس [XslCompiledTransform](../)
* کلاس [XsltArgumentList](../../xsltargumentlist/)
* کلاس [TextWriter](../../../system.io/textwriter/)
* کلاس [Stream](../../../system.io/stream/)
* کلاس [XmlReader](../../../system.xml/xmlreader/)
* کلاس [String](../../../system/string/)
* کلاس [XmlResolver](../../../system.xml/xmlresolver/)
* فضای‌نام [System::Xml::Xsl](../../)
* کتابخانه [Aspose.Slides](../../../)