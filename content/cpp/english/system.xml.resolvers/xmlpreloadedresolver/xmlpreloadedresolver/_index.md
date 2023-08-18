---
title: XmlPreloadedResolver()
second_title: Aspose.Slides for C++ API Reference
description: Initializes a new instance of the XmlPreloadedResolver class.
type: docs
weight: 27
url: /system.xml.resolvers/xmlpreloadedresolver/xmlpreloadedresolver/
---
## XmlPreloadedResolver::XmlPreloadedResolver() constructor


Initializes a new instance of the [XmlPreloadedResolver](../) class.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver()
```

## XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds) constructor


Initializes a new instance of the [XmlPreloadedResolver](../) class with the specified preloaded well-known DTDs.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds preloadedDtds)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | The well-known DTDs that should be prepopulated into the cache. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&) constructor


Initializes a new instance of the [XmlPreloadedResolver](../) class with the specified fallback resolver.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | The [XmlResolver](../../../system.xml/xmlresolver/) or your own resolver. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds) constructor


Initializes a new instance of the [XmlPreloadedResolver](../) class with the specified fallback resolver and preloaded well-known DTDs.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | The [XmlResolver](../../../system.xml/xmlresolver/) or your own resolver. |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | The well-known DTDs that should be prepopulated into the cache. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds, const SharedPtr\<Collections::Generic::IEqualityComparer\<SharedPtr\<Uri\>\>\>\&) constructor


Initializes a new instance of the [XmlPreloadedResolver](../) class with the specified fallback resolver, preloaded well-known DTDs, and URI equality comparer.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds, const SharedPtr<Collections::Generic::IEqualityComparer<SharedPtr<Uri>>> &uriComparer)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | The [XmlResolver](../../../system.xml/xmlresolver/) or your own resolver. |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | The well-known DTDs that should be prepopulated into cache. |
| uriComparer | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\>\>\& | The implementation of the IEqualityComparer interface to use when you compare URIs. |

## See Also

* Enum [XmlKnownDtds](../../xmlknowndtds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlPreloadedResolver](../)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)
* Class [Uri](../../../system/uri/)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)