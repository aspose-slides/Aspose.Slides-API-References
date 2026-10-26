---
title: ResolveUri()
second_title: مرجع API Aspose.Slides برای C++
description: آدرس مطلق را از URIهای پایه و نسبی با فراخوانی ResolveUri بر روی XmlResolver زیرین حل می‌کند.
type: docs
weight: 40
url: /fa/system.xml/xmlsecureresolver/resolveuri/
---
## XmlSecureResolver::ResolveUri(SharedPtr\<Uri\>, String) متد

آدرس مطلق را از URIهای پایه و نسبی با فراخوانی **ResolveUri** روی [XmlResolver](../../xmlresolver/) زیرین حل می‌کند.

```cpp
SharedPtr<Uri> System::Xml::XmlSecureResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI پایه‌ای که برای حل URI نسبی استفاده می‌شود. |
| relativeUri | [String](../../../system/string/) | URI که باید حل شود. این URI می‌تواند مطلق یا نسبی باشد. اگر مطلق باشد، این مقدار عملاً مقدار **baseUri** را جایگزین می‌کند. اگر نسبی باشد، با **baseUri** ترکیب می‌شود تا یک URI مطلق ساخته شود. |

### مقدار بازگشتی

URI مطلق یا **nullptr** اگر URI نسبی قابل حل نباشد (بازگشت یافته توسط فراخوانی **ResolveUri** روی [XmlResolver](../../xmlresolver/) زیرین).

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [Uri](../../../system/uri/)
* کلاس [String](../../../system/string/)
* کلاس [XmlSecureResolver](../)
* فضای‌نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)