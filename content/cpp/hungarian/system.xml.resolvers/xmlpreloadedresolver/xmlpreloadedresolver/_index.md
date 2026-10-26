---
title: XmlPreloadedResolver()
second_title: Aspose.Slides C++ API Referenciája
description: Új példányt hoz létre az XmlPreloadedResolver osztályból.
type: docs
weight: 27
url: /hu/system.xml.resolvers/xmlpreloadedresolver/xmlpreloadedresolver/
---
## XmlPreloadedResolver::XmlPreloadedResolver() konstruktor

Új példányt hoz létre a [XmlPreloadedResolver](../) osztályból.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver()
```

## XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds) konstruktor

Új példányt hoz létre a [XmlPreloadedResolver](../) osztályból a megadott előre betöltött jól ismert DTD-kkel.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds preloadedDtds)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | A jól ismert DTD-k, amelyeket előre be kell tölteni a gyorsítótárba. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&) konstruktor

Új példányt hoz létre a [XmlPreloadedResolver](../) osztályból a megadott visszaeső feloldóval.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | A [XmlResolver](../../../system.xml/xmlresolver/) vagy a saját feloldód. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds) konstruktor

Új példányt hoz létre a [XmlPreloadedResolver](../) osztályból a megadott visszaeső feloldóval és előre betöltött jól ismert DTD-kkel.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | A [XmlResolver](../../../system.xml/xmlresolver/) vagy a saját feloldód. |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | A jól ismert DTD-k, amelyeket előre be kell tölteni a gyorsítótárba. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds, const SharedPtr\<Collections::Generic::IEqualityComparer\<SharedPtr\<Uri\>\>\>\&) konstruktor

Új példányt hoz létre a [XmlPreloadedResolver](../) osztályból a megadott visszaeső feloldóval, előre betöltött jól ismert DTD-kkel és URI egyenlőség-összehasonlítóval.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds, const SharedPtr<Collections::Generic::IEqualityComparer<SharedPtr<Uri>>> &uriComparer)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | A [XmlResolver](../../../system.xml/xmlresolver/) vagy a saját feloldód. |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | A jól ismert DTD-k, amelyeket előre be kell tölteni a gyorsítótárba. |
| uriComparer | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\>\>\& | Az IEqualityComparer interfész megvalósítása, amelyet URI-k összehasonlításakor használ. |

## Lásd még

* Enum [XmlKnownDtds](../../xmlknowndtds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlPreloadedResolver](../)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)
* Class [Uri](../../../system/uri/)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)