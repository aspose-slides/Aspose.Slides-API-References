---
title: ResolveUri()
second_title: مرجع API Aspose.Slides برای C++
description: زمانى که در یک کلاس مشتق شده بازنویسی می‌شود، URI مطلق را از URIهای پایه و نسبی حل می‌کند.
type: docs
weight: 27
url: /fa/system.xml/xmlresolver/resolveuri/
---
## XmlResolver::ResolveUri(SharedPtr\<Uri\>, String) متد

زمانی که در یک کلاس مشتق شده بازنویسی می‌شود، URI مطلق را از URIهای پایه و نسبی حل می‌کند.

```cpp
virtual SharedPtr<Uri> System::Xml::XmlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri)
```

### استدلال‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI پایه‌ای که برای حل URI نسبی استفاده می‌شود. |
| relativeUri | [String](../../../system/string/) | URI برای حل. این URI می‌تواند مطلق یا نسبی باشد. اگر مطلق باشد، این مقدار عملاً مقدار **baseUri** را جایگزین می‌کند. اگر نسبی باشد، با **baseUri** ترکیب می‌شود تا یک URI مطلق ساخته شود. |

### مقدار بازگشتی

URI مطلق یا **nullptr** اگر URI نسبی قابل حل نباشد.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [Uri](../../../system/uri/)
* کلاس [String](../../../system/string/)
* کلاس [XmlResolver](../)
* فضای نام [System::Xml](../../)
* Library [Aspose.Slides](../../../)