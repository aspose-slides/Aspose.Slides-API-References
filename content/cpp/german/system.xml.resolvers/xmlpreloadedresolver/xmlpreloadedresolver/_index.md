---
title: XmlPreloadedResolver()
second_title: Aspose.Slides für C++ API-Referenz
description: Initialisiert eine neue Instanz der XmlPreloadedResolver-Klasse.
type: docs
weight: 27
url: /de/system.xml.resolvers/xmlpreloadedresolver/xmlpreloadedresolver/
---
## XmlPreloadedResolver::XmlPreloadedResolver() Konstruktor


Initialisiert eine neue Instanz der [XmlPreloadedResolver](../) Klasse.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver()
```

## XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds) Konstruktor


Initialisiert eine neue Instanz der [XmlPreloadedResolver](../) Klasse mit den angegebenen vorab geladenen bekannten DTDs.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds preloadedDtds)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | Die bekannten DTDs, die in den Cache vorab geladen werden sollen. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&) Konstruktor


Initialisiert eine neue Instanz der [XmlPreloadedResolver](../) Klasse mit dem angegebenen Fallback-Resolver.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | Der [XmlResolver](../../../system.xml/xmlresolver/) oder Ihr eigener Resolver. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds) Konstruktor


Initialisiert eine neue Instanz der [XmlPreloadedResolver](../) Klasse mit dem angegebenen Fallback-Resolver und vorab geladenen bekannten DTDs.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | Der [XmlResolver](../../../system.xml/xmlresolver/) oder Ihr eigener Resolver. |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | Die bekannten DTDs, die in den Cache vorab geladen werden sollen. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds, const SharedPtr\<Collections::Generic::IEqualityComparer\<SharedPtr\<Uri\>\>\>\&) Konstruktor


Initialisiert eine neue Instanz der [XmlPreloadedResolver](../) Klasse mit dem angegebenen Fallback-Resolver, vorab geladenen bekannten DTDs und einem URI-Gleichheitsvergleich.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds, const SharedPtr<Collections::Generic::IEqualityComparer<SharedPtr<Uri>>> &uriComparer)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | Der [XmlResolver](../../../system.xml/xmlresolver/) oder Ihr eigener Resolver. |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | Die bekannten DTDs, die in den Cache vorab geladen werden sollen. |
| uriComparer | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\>\>\& | Die Implementierung des IEqualityComparer-Interfaces, das beim Vergleich von URIs verwendet wird. |

## Siehe auch

* Enum [XmlKnownDtds](../../xmlknowndtds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlPreloadedResolver](../)
* Klasse [XmlResolver](../../../system.xml/xmlresolver/)
* Klasse [IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)
* Klasse [Uri](../../../system/uri/)
* Namensraum [System::Xml::Resolvers](../../)
* Bibliothek [Aspose.Slides](../../../)