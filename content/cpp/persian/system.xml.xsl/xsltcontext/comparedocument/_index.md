---
title: CompareDocument()
second_title: Aspose.Slides برای C++ مرجع API
description: هنگامی که در یک کلاس مشتق بازنویسی می‌شود، شناسه‌های Uniform Resource Identifiers (URIs) پایه دو سند را بر اساس ترتیب بارگذاری آن‌ها توسط پردازشگر XSLT (یعنی کلاس XslTransform) مقایسه می‌کند.
type: docs
weight: 53
url: /fa/system.xml.xsl/xsltcontext/comparedocument/
---
## XsltContext::CompareDocument(String, String) متد

هنگام بازنویسی در یک کلاس مشتق، شناسه‌های یونیفورم منبع (URIs) پایه دو سند را بر اساس ترتیب بارگذاری آن‌ها توسط پردازنده XSLT (که همان کلاس [XslTransform](../../xsltransform/) است) مقایسه می‌کند.

```cpp
virtual int32_t System::Xml::Xsl::XsltContext::CompareDocument(String baseUri, String nextbaseUri)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| baseUri | [String](../../../system/string/) | URI پایه سند اول برای مقایسه. |
| nextbaseUri | [String](../../../system/string/) | URI پایه سند دوم برای مقایسه. |

### مقدار بازگشت

یک مقدار صحیح که ترتیب نسبی دو URI پایه را توصیف می‌کند: -1 اگر **baseUri** پیش از **nextbaseUri** باشد؛ 0 اگر دو URI پایه یکسان باشند؛ و 1 اگر **baseUri** پس از **nextbaseUri** باشد.

## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [XsltContext](../)
* فضای‌نام [System::Xml::Xsl](../../)
* کتابخانه [Aspose.Slides](../../../)