---
title: XmlPreloadedResolver()
second_title: Aspose.Slides voor C++ API-referentie
description: Initialiseert een nieuw exemplaar van de XmlPreloadedResolver klasse.
type: docs
weight: 27
url: /nl/system.xml.resolvers/xmlpreloadedresolver/xmlpreloadedresolver/
---
## XmlPreloadedResolver::XmlPreloadedResolver() constructor

Initialiseert een nieuw exemplaar van de [XmlPreloadedResolver](../) klasse.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver()
```

## XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds) constructor

Initialiseert een nieuw exemplaar van de [XmlPreloadedResolver](../) klasse met de opgegeven vooraf geladen bekende DTD's.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds preloadedDtds)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | De bekende DTD's die in de cache moeten worden voorbevolkt. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&) constructor

Initialiseert een nieuw exemplaar van de [XmlPreloadedResolver](../) klasse met de opgegeven fallback resolver.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | De [XmlResolver](../../../system.xml/xmlresolver/) of uw eigen resolver. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds) constructor

Initialiseert een nieuw exemplaar van de [XmlPreloadedResolver](../) klasse met de opgegeven fallback resolver en vooraf geladen bekende DTD's.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | De [XmlResolver](../../../system.xml/xmlresolver/) of uw eigen resolver. |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | De bekende DTD's die in de cache moeten worden voorbevolkt. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds, const SharedPtr\<Collections::Generic::IEqualityComparer\<SharedPtr\<Uri\>\>\>\&) constructor

Initialiseert een nieuw exemplaar van de [XmlPreloadedResolver](../) klasse met de opgegeven fallback resolver, vooraf geladen bekende DTD's en URI-vergelijkingsoperator.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds, const SharedPtr<Collections::Generic::IEqualityComparer<SharedPtr<Uri>>> &uriComparer)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | De [XmlResolver](../../../system.xml/xmlresolver/) of uw eigen resolver. |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | De bekende DTD's die in de cache moeten worden voorbevolkt. |
| uriComparer | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\>\>\& | De implementatie van de IEqualityComparer-interface die wordt gebruikt bij het vergelijken van URI's. |

## Zie ook

* Enum [XmlKnownDtds](../../xmlknowndtds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlPreloadedResolver](../)
* Klasse [XmlResolver](../../../system.xml/xmlresolver/)
* Klasse [IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)
* Klasse [Uri](../../../system/uri/)
* Naamruimte [System::Xml::Resolvers](../../)
* Bibliotheek [Aspose.Slides](../../../)