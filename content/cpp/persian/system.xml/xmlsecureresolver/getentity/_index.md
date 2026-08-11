---
title: GetEntity()
second_title: Aspose.Slides برای مرجع API C++
description: یک URI را به شیئی که شامل منبع واقعی است، نگاشت می‌کند.
type: docs
weight: 27
url: /fa/system.xml/xmlsecureresolver/getentity/
---
## XmlSecureResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) method

یک URI را به شیئی که شامل منبع واقعی است، نگاشت می‌کند.

```cpp
SharedPtr<Object> System::Xml::XmlSecureResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI که از فراخوانی [XmlSecureResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/) برگردانده می‌شود. |
| role | [String](../../../system/string/) | در حال حاضر استفاده نمی‌شود. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | نوع شیئی که باید برگردانده شود. نسخهٔ فعلی فقط اشیای Stream را برمی‌گرداند. |

### مقدار بازگشت

جریانی که با فراخوانی **GetEntity** بر روی [XmlResolver](../../xmlresolver/) زیرین بازگردانده می‌شود. اگر نوعی غیر از Stream مشخص شود، متد **nullptr** را برمی‌گرداند.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [Object](../../../system/object/)
* کلاس [Uri](../../../system/uri/)
* کلاس [String](../../../system/string/)
* کلاس [TypeInfo](../../../system/typeinfo/)
* کلاس [XmlSecureResolver](../)
* فضای‌نام [System::Xml](../../)
* Library [Aspose.Slides](../../../)