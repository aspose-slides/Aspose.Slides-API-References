---
title: GetEntity()
second_title: Aspose.Slides برای C++ مرجع API
description: یک URI را به شیئی که حاوی منبع واقعی است، نگاشت می‌کند.
type: docs
weight: 53
url: /fa/system.xml/xmlurlresolver/getentity/
---
## XmlUrlResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) متد

یک URI را به شیئی که حاوی منبع واقعی است، نگاشت می‌کند.

```cpp
SharedPtr<Object> System::Xml::XmlUrlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI که از فراخوانی [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../../xmlresolver/resolveuri/) بازگردانده می‌شود. |
| role | [String](../../../system/string/) | در حال حاضر استفاده نمی‌شود. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | نوع شیء برای بازگرداندن. پیاده‌سازی فعلی فقط اشیاء Stream را برمی‌گرداند. |

### مقدار بازگشتی

یک شیء Stream یا **nullptr** اگر نوعی غیر از Stream مشخص شده باشد.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [Object](../../../system/object/)
* کلاس [Uri](../../../system/uri/)
* کلاس [String](../../../system/string/)
* کلاس [TypeInfo](../../../system/typeinfo/)
* کلاس [XmlUrlResolver](../)
* فضای‌نام [System::Xml](../../)
* Library [Aspose.Slides](../../../)