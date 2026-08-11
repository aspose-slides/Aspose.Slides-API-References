---
title: SupportsType()
second_title: Aspose.Slides برای C++ مرجع API
description: تعیین می‌کند که آیا رزولوور از انواع دیگری علاوه بر Stream پشتیبانی می‌کند.
type: docs
weight: 66
url: /fa/system.xml.resolvers/xmlpreloadedresolver/supportstype/
---
## XmlPreloadedResolver::SupportsType(SharedPtr\<Uri\>, const TypeInfo\&) متد

تعیین می‌کند که آیا رزولوور از انواع دیگر علاوه بر Stream پشتیبانی می‌کند یا خیر.

```cpp
bool System::Xml::Resolvers::XmlPreloadedResolver::SupportsType(SharedPtr<Uri> absoluteUri, const TypeInfo &type) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI مطلق برای بررسی. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | Type برای بازگشت. |

### مقدار بازگشتی

**true** اگر Type پشتیبانی شود؛ در غیر این صورت **false**.

## همچنین ببینید

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [Uri](../../../system/uri/)
* کلاس [TypeInfo](../../../system/typeinfo/)
* کلاس [XmlPreloadedResolver](../)
* فضای‌نام [System::Xml::Resolvers](../../)
* کتابخانه [Aspose.Slides](../../../)