---
title: XmlPreloadedResolver()
second_title: مرجع API Aspose.Slides for C++
description: ينشئ مثالا جديداً من فئة XmlPreloadedResolver.
type: docs
weight: 27
url: /ar/system.xml.resolvers/xmlpreloadedresolver/xmlpreloadedresolver/
---
## منشئ XmlPreloadedResolver::XmlPreloadedResolver()

ينشئ مثالا جديدا من الفئة [XmlPreloadedResolver](../).

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver()
```

## منشئ XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds)

ينشئ مثالا جديدا من الفئة [XmlPreloadedResolver](../) باستخدام DTDs المعروفة المحملة مسبقًا المحددة.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds preloadedDtds)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | DTDs المعروفة التي يجب تعبئتها مسبقًا في الذاكرة المؤقتة. |

## منشئ XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&)

ينشئ مثالا جديدا من الفئة [XmlPreloadedResolver](../) باستخدام محلل الرجوع المحدد.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | الـ [XmlResolver](../../../system.xml/xmlresolver/) أو محلل (resolver) الخاص بك. |

## منشئ XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds)

ينشئ مثالا جديدا من الفئة [XmlPreloadedResolver](../) باستخدام محلل الرجوع المحدد وDTDs المعروفة المحملة مسبقًا.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | الـ [XmlResolver](../../../system.xml/xmlresolver/) أو محلل (resolver) الخاص بك. |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | DTDs المعروفة التي يجب تعبئتها مسبقًا في الذاكرة المؤقتة. |

## منشئ XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds, const SharedPtr\<Collections::Generic::IEqualityComparer\<SharedPtr\<Uri\>\>\>\&)

ينشئ مثالا جديدا من الفئة [XmlPreloadedResolver](../) باستخدام محلل الرجوع المحدد، DTDs المعروفة المحملة مسبقًا، ومقارن مساواة URI.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds, const SharedPtr<Collections::Generic::IEqualityComparer<SharedPtr<Uri>>> &uriComparer)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | الـ [XmlResolver](../../../system.xml/xmlresolver/) أو محلل (resolver) الخاص بك. |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | DTDs المعروفة التي يجب تعبئتها مسبقًا في الذاكرة المؤقتة. |
| uriComparer | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\>\>\& | تنفيذ واجهة IEqualityComparer لاستخدامه عند مقارنة عناوين URI. |

## راجع أيضًا

* تعداد [XmlKnownDtds](../../xmlknowndtds/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [XmlPreloadedResolver](../)
* فئة [XmlResolver](../../../system.xml/xmlresolver/)
* فئة [IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)
* فئة [Uri](../../../system/uri/)
* نطاق [System::Xml::Resolvers](../../)
* مكتبة [Aspose.Slides](../../../)