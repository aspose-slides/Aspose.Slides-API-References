---
title: XmlPreloadedResolver()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Inicjalizuje nową instancję klasy XmlPreloadedResolver.
type: docs
weight: 27
url: /pl/system.xml.resolvers/xmlpreloadedresolver/xmlpreloadedresolver/
---
## XmlPreloadedResolver::XmlPreloadedResolver() konstruktor


Inicjalizuje nową instancję klasy [XmlPreloadedResolver](../).

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver()
```

## XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds) konstruktor


Inicjalizuje nową instancję klasy [XmlPreloadedResolver](../) z podanymi wstępnie załadowanymi, dobrze znanymi DTD.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds preloadedDtds)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | DTD, które powinny być wstępnie umieszczone w pamięci podręcznej. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&) konstruktor


Inicjalizuje nową instancję klasy [XmlPreloadedResolver](../) z podanym resolverem awaryjnym.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) lub własny resolver. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds) konstruktor


Inicjalizuje nową instancję klasy [XmlPreloadedResolver](../) z podanym resolverem awaryjnym i wstępnie załadowanymi, dobrze znanymi DTD.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) lub własny resolver. |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | DTD, które powinny być wstępnie umieszczone w pamięci podręcznej. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds, const SharedPtr\<Collections::Generic::IEqualityComparer\<SharedPtr\<Uri\>\>\>\&) konstruktor


Inicjalizuje nową instancję klasy [XmlPreloadedResolver](../) z podanym resolverem awaryjnym, wstępnie załadowanymi DTD oraz porównywaczem równości URI.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds, const SharedPtr<Collections::Generic::IEqualityComparer<SharedPtr<Uri>>> &uriComparer)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) lub własny resolver. |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | DTD, które powinny być wstępnie umieszczone w pamięci podręcznej. |
| uriComparer | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\>\>\& | Implementacja interfejsu IEqualityComparer używana przy porównywaniu URI. |

## Zobacz także

* Wyliczenie [XmlKnownDtds](../../xmlknowndtds/)
* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlPreloadedResolver](../)
* Klasa [XmlResolver](../../../system.xml/xmlresolver/)
* Klasa [IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)
* Klasa [Uri](../../../system/uri/)
* Przestrzeń nazw [System::Xml::Resolvers](../../)
* Biblioteka [Aspose.Slides](../../../)