---
title: XPathNodeType
second_title: مرجع API Aspose.Slides برای C++
description: انواع گره‌های XPath را که می‌توان از کلاس XPathNavigator دریافت کرد، تعریف می‌کند.
type: docs
weight: 157
url: /fa/system.xml.xpath/xpathnodetype/
---
## XPathNodeType enum

انواع گره [XPath](../) را که می‌توان از کلاس [XPathNavigator](../xpathnavigator/) دریافت کرد، تعریف می‌کند.

```cpp
enum class XPathNodeType
```

### مقادیر

| نام | مقدار | توضیح |
| --- | --- | --- |
| Root | 0 | گره ریشهٔ سند XML یا درخت گره‌ها. |
| Element | 1 | یک عنصر، مانند **<element>**. |
| Attribute | 2 | یک ویژگی، مانند **id='123'**. |
| Namespace | 3 | یک فضای نام، مانند **xmlns=\"namespace\"**. |
| Text | 4 | محتوای متنی یک گره. معادل مدل سند [Object](../../system/object/) (DOM) [Text](../../system.text/) و انواع گره CDATA. حداقل شامل یک کاراکتر است. |
| SignificantWhitespace | 5 | یک گره با کاراکترهای فاصله‌دار و **xml:space** تنظیم شده به **preserve**. |
| Whitespace | 6 | یک گره که فقط شامل کاراکترهای فاصله‌دار است و فضای سفید معناداری ندارد. کاراکترهای فاصله‌دار عبارتند از **'\x20'**, **'\x0d'**, **'\x0a'**, **'\x09'**. |
| ProcessingInstruction | 7 | یک دستور پردازش، مانند **<?pi test?>**. این شامل اعلان‌های XML نمی‌شود، که برای کلاس [XPathNavigator](../xpathnavigator/) قابل مشاهده نیستند. |
| Comment | 8 | یک نظر، مانند ****. |
| All | 9 | هر یک از انواع گره XPathNodeType. |

## موارد مرتبط

* فضای نام [System::Xml::XPath](../)
* کتابخانه [Aspose.Slides](../../)