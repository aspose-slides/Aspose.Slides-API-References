---
title: GetEntity()
second_title: مرجع API Aspose.Slides برای C++
description: زمانی که در یک کلاس مشتق شده بازنویسی می‌شود، یک URI را به شیئی که منبع واقعی را شامل می‌شود نگاشت می‌کند.
type: docs
weight: 14
url: /fa/system.xml/xmlresolver/getentity/
---
## XmlResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) روش

هنگامی که در یک کلاس مشتق شده بازنویسی می‌شود، یک URI را به شیئی که منبع واقعی را در بر دارد نگاشت می‌کند.

```cpp
virtual SharedPtr<Object> System::Xml::XmlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI برگشت‌داده‌شده از فراخوانی [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/). |
| role | [String](../../../system/string/) | در حال حاضر استفاده نمی‌شود. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | نوع شیئی که باید برگردانده شود. نسخهٔ فعلی فقط اشیای Stream را برمی‌گرداند. |

### مقدار بازگشت

یک شیء stream یا **nullptr** اگر نوعی غیر از stream مشخص شده باشد.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [Object](../../../system/object/)
* کلاس [Uri](../../../system/uri/)
* کلاس [String](../../../system/string/)
* کلاس [TypeInfo](../../../system/typeinfo/)
* کلاس [XmlResolver](../)
* فضای‌نام [System::Xml](../../)
* Library [Aspose.Slides](../../../)