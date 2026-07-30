---
title: XmlPreloadedResolver()
second_title: Riferimento API di Aspose.Slides per C++
description: Inizializza una nuova istanza della classe XmlPreloadedResolver.
type: docs
weight: 27
url: /it/system.xml.resolvers/xmlpreloadedresolver/xmlpreloadedresolver/
---
## XmlPreloadedResolver::XmlPreloadedResolver() costruttore


Inizializza una nuova istanza della classe [XmlPreloadedResolver](../).

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver()
```

## XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds) costruttore


Inizializza una nuova istanza della classe [XmlPreloadedResolver](../) con i DTD noti pre-caricati specificati.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds preloadedDtds)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | I DTD noti che devono essere pre-popolati nella cache. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&) costruttore


Inizializza una nuova istanza della classe [XmlPreloadedResolver](../) con il resolver di fallback specificato.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | Il [XmlResolver](../../../system.xml/xmlresolver/) o il tuo resolver. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds) costruttore


Inizializza una nuova istanza della classe [XmlPreloadedResolver](../) con il resolver di fallback specificato e i DTD noti pre-caricati.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | Il [XmlResolver](../../../system.xml/xmlresolver/) o il tuo resolver. |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | I DTD noti che devono essere pre-popolati nella cache. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds, const SharedPtr\<Collections::Generic::IEqualityComparer\<SharedPtr\<Uri\>\>\>\&) costruttore


Inizializza una nuova istanza della classe [XmlPreloadedResolver](../) con il resolver di fallback specificato, i DTD noti pre-caricati e il comparatore di uguaglianza URI.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds, const SharedPtr<Collections::Generic::IEqualityComparer<SharedPtr<Uri>>> &uriComparer)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | Il [XmlResolver](../../../system.xml/xmlresolver/) o il tuo resolver. |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | I DTD noti che devono essere pre-popolati nella cache. |
| uriComparer | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\>\>\& | L'implementazione dell'interfaccia IEqualityComparer da utilizzare quando confronti gli URI. |

## Vedi anche

* Enum [XmlKnownDtds](../../xmlknowndtds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlPreloadedResolver](../)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)
* Class [Uri](../../../system/uri/)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)