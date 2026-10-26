---
title: ResolveUri()
second_title: مرجع API Aspose.Slides برای C++
description: آدرس مطلق URI را از URIهای پایه و نسبی حل می‌کند.
type: docs
weight: 66
url: /fa/system.xml/xmlurlresolver/resolveuri/
---
## XmlUrlResolver::ResolveUri(SharedPtr\<Uri\>, String) متد

آدرس مطلق URI را از URI پایه و نسبی حل می‌کند.

```cpp
SharedPtr<Uri> System::Xml::XmlUrlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### پارامترها
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI پایه‌ای که برای حل URI نسبی استفاده می‌شود. |
| relativeUri | [String](../../../system/string/) | URIی که باید حل شود. این URI می‌تواند مطلق یا نسبی باشد. اگر مطلق باشد، این مقدار عملاً مقدار **baseUri** را جایگزین می‌کند. اگر نسبی باشد، با **baseUri** ترکیب می‌شود تا یک URI مطلق تشکیل دهد. |

### مقدار برگشتی
آدرس مطلق URI، یا **nullptr** اگر URI نسبی قابل حل نباشد.

## همچنین ببینید

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [Uri](../../../system/uri/)
* کلاس [String](../../../system/string/)
* کلاس [XmlUrlResolver](../)
* فضای‌نام [System::Xml](../../)
* Library [Aspose.Slides](../../../)