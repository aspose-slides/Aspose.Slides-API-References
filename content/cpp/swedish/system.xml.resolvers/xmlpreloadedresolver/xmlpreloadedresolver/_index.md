---
title: XmlPreloadedResolver()
second_title: Aspose.Slides för C++ API-referens
description: Initierar en ny instans av XmlPreloadedResolver-klassen.
type: docs
weight: 27
url: /sv/system.xml.resolvers/xmlpreloadedresolver/xmlpreloadedresolver/
---
## XmlPreloadedResolver::XmlPreloadedResolver() konstruktor


Initialiserar en ny instans av klassen [XmlPreloadedResolver](../).

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver()
```

## XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds) konstruktor


Initialiserar en ny instans av klassen [XmlPreloadedResolver](../) med de specificerade förinlästa välkända DTD:erna.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds preloadedDtds)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | De välkända DTD:erna som ska föras in i cachen. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&) konstruktor


Initialiserar en ny instans av klassen [XmlPreloadedResolver](../) med den specificerade reservlösaren.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | Den [XmlResolver](../../../system.xml/xmlresolver/) eller din egen resolver. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds) konstruktor


Initialiserar en ny instans av klassen [XmlPreloadedResolver](../) med den specificerade reservlösaren och förinlästa välkända DTD:er.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | Den [XmlResolver](../../../system.xml/xmlresolver/) eller din egen resolver. |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | De välkända DTD:erna som ska föras in i cachen. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds, const SharedPtr\<Collections::Generic::IEqualityComparer\<SharedPtr\<Uri\>\>\>\&) konstruktor


Initialiserar en ny instans av klassen [XmlPreloadedResolver](../) med den specificerade reservlösaren, förinlästa välkända DTD:er och URI-jämförare.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds, const SharedPtr<Collections::Generic::IEqualityComparer<SharedPtr<Uri>>> &uriComparer)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | Den [XmlResolver](../../../system.xml/xmlresolver/) eller din egen resolver. |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | De välkända DTD:erna som ska föras in i cachen. |
| uriComparer | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\>\>\& | Implementeringen av IEqualityComparer-gränssnittet som ska användas när du jämför URI:er. |

## Se också

* Enum [XmlKnownDtds](../../xmlknowndtds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlPreloadedResolver](../)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)
* Class [Uri](../../../system/uri/)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)