---
title: GetEntity()
second_title: Aspose.Slides برای C++ مرجع API
description: یک URI را به شیئی که منبع واقعی را شامل می‌شود، نگاشت می‌کند.
type: docs
weight: 53
url: /fa/system.xml.resolvers/xmlpreloadedresolver/getentity/
---
## XmlPreloadedResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) متد

یک URI را به شیئی که منبع واقعی را شامل می‌شود، نگاشت می‌کند.

```cpp
SharedPtr<Object> System::Xml::Resolvers::XmlPreloadedResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI‌ای که از فراخوانی [XmlResolver::ResolveUri(SharedPtr<Uri>,String)](../../../system.xml/xmlresolver/resolveuri/) برگردانده شده است. |
| role | [String](../../../system/string/) | در حال حاضر استفاده نمی‌شود. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | نوع شیئی که باید بازگردانده شود. [XmlPreloadedResolver](../) اشیاء Stream و اشیاء TextReader را برای URIهایی که به عنوان [String](../../../system/string/) اضافه شده‌اند، پشتیبانی می‌کند. اگر نوع درخواستی توسط resolver پشتیبانی نشود، یک استثنا پرتاب می‌شود. برای تعیین اینکه آیا یک **Type** خاص توسط این resolver پشتیبانی می‌شود، از متد XmlPreloadedResolver::SupportsType(SharedPtr<Uri>,TypeInfo) استفاده کنید. |

### مقدار بازگشت

شیء Stream یا TextReader که متناظر با منبع واقعی است.

## همچنین ببینید

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)