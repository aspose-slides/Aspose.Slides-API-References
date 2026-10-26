---
title: ResolveUri()
second_title: مرجع API Aspose.Slides برای C++
description: آدرس URI مطلق را از URIهای پایه و نسبی حل می‌کند.
type: docs
weight: 40
url: /fa/system.xml.resolvers/xmlpreloadedresolver/resolveuri/
---
## XmlPreloadedResolver::ResolveUri(SharedPtr\<Uri\>, String) متد

آدرس URI مطلق را از URIهای پایه و نسبی حل می‌کند.

```cpp
SharedPtr<Uri> System::Xml::Resolvers::XmlPreloadedResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### Arguments

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI پایه‌ای که برای حل URI نسبی استفاده می‌شود. |
| relativeUri | [String](../../../system/string/) | URI که باید حل شود. URI می‌تواند مطلق یا نسبی باشد. اگر مطلق باشد، این مقدار بطور مؤثر مقدار **baseUri** را جایگزین می‌کند. اگر نسبی باشد، با **baseUri** ترکیب می‌شود تا یک URI مطلق ایجاد کند. |

### مقدار برگشتی

[Uri](../../../system/uri/) که نمایانگر URI مطلق است یا **nullptr** اگر URI نسبی قابل حل نباشد.

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [Uri](../../../system/uri/)
* کلاس [String](../../../system/string/)
* کلاس [XmlPreloadedResolver](../)
* فضای نام [System::Xml::Resolvers](../../)
* کتابخانه [Aspose.Slides](../../../)