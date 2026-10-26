---
title: XmlPreloadedResolver()
second_title: Aspose.Slides pro C++ API referenční příručka
description: Inicializuje novou instanci třídy XmlPreloadedResolver.
type: docs
weight: 27
url: /cs/system.xml.resolvers/xmlpreloadedresolver/xmlpreloadedresolver/
---
## XmlPreloadedResolver::XmlPreloadedResolver() konstruktor


Inicializuje novou instanci třídy [XmlPreloadedResolver](../).

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver()
```

## XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds) konstruktor


Inicializuje novou instanci třídy [XmlPreloadedResolver](../) s určenými přednačtenými známými DTD.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds preloadedDtds)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | Známé DTD, které by měly být přednačteny do mezipaměti. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&) konstruktor


Inicializuje novou instanci třídy [XmlPreloadedResolver](../) s určeným náhradním resolverem.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) nebo váš vlastní resolver. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds) konstruktor


Inicializuje novou instanci třídy [XmlPreloadedResolver](../) s určeným náhradním resolverem a přednačtenými známými DTD.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) nebo váš vlastní resolver. |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | Známé DTD, které by měly být přednačteny do mezipaměti. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds, const SharedPtr\<Collections::Generic::IEqualityComparer\<SharedPtr\<Uri\>\>\>\&) konstruktor


Inicializuje novou instanci třídy [XmlPreloadedResolver](../) s určeným náhradním resolverem, přednačtenými známými DTD a porovnávačem URI.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds, const SharedPtr<Collections::Generic::IEqualityComparer<SharedPtr<Uri>>> &uriComparer)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) nebo váš vlastní resolver. |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | Známé DTD, které by měly být přednačteny do mezipaměti. |
| uriComparer | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\>\>\& | Implementace rozhraní IEqualityComparer, která se použije při porovnávání URI. |

## Viz také

* Výčet [XmlKnownDtds](../../xmlknowndtds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlPreloadedResolver](../)
* Třída [XmlResolver](../../../system.xml/xmlresolver/)
* Třída [IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)
* Třída [Uri](../../../system/uri/)
* Jmenný prostor [System::Xml::Resolvers](../../)
* Knihovna [Aspose.Slides](../../../)