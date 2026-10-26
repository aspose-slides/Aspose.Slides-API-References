---
title: XmlPreloadedResolver()
second_title: مرجع API Aspose.Slides برای C++
description: یک نمونه جدید از کلاس XmlPreloadedResolver را مقداردهی اولیه می‌کند.
type: docs
weight: 27
url: /fa/system.xml.resolvers/xmlpreloadedresolver/xmlpreloadedresolver/
---
## XmlPreloadedResolver::XmlPreloadedResolver() سازنده

یک نمونه جدید از کلاس [XmlPreloadedResolver](../) را مقداردهی اولیه می‌کند.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver()
```

## XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds) سازنده

یک نمونه جدید از کلاس [XmlPreloadedResolver](../) را با DTDهای مشهور پیش‌بارگذاری‌شدهٔ مشخص شده مقداردهی اولیه می‌کند.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds preloadedDtds)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | DTDهای مشهور که باید در کش پیش‌پر شوند. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&) سازنده

یک نمونه جدید از کلاس [XmlPreloadedResolver](../) را با حل‌کنندهٔ جایگزین مشخص شده مقداردهی اولیه می‌کند.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) یا حل‌کنندهٔ خودتان. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds) سازنده

یک نمونه جدید از کلاس [XmlPreloadedResolver](../) را با حل‌کنندهٔ جایگزین مشخص شده و DTDهای مشهور پیش‌بارگذاری‌شده مقداردهی اولیه می‌کند.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) یا حل‌کنندهٔ خودتان. |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | DTDهای مشهور که باید در کش پیش‌پر شوند. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds, const SharedPtr\<Collections::Generic::IEqualityComparer\<SharedPtr\<Uri\>\>\>\&) سازنده

یک نمونه جدید از کلاس [XmlPreloadedResolver](../) را با حل‌کنندهٔ جایگزین، DTDهای مشهور پیش‌بارگذاری‌شده، و مقایسه‌گر مساوی‌سازی URI مقداردهی اولیه می‌کند.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds, const SharedPtr<Collections::Generic::IEqualityComparer<SharedPtr<Uri>>> &uriComparer)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) یا حل‌کنندهٔ خودتان. |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | DTDهای مشهور که باید در کش پیش‌پر شوند. |
| uriComparer | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\>\>\& | پیاده‌سازی رابط IEqualityComparer که هنگام مقایسهٔ URIها استفاده می‌شود. |

## مراجع دیگر

* Enum [XmlKnownDtds](../../xmlknowndtds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlPreloadedResolver](../)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)
* Class [Uri](../../../system/uri/)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)