---
title: GetNamespacesInScope()
second_title: Aspose.Slides for C++ API referenciája
description: Visszaad egy gyűjteményt a jelenleg hatókörben lévő definiált előtag-névtér leképezésekről.
type: docs
weight: 1
url: /hu/system.xml/ixmlnamespaceresolver/getnamespacesinscope/
---
## IXmlNamespaceResolver::GetNamespacesInScope(XmlNamespaceScope) metódus

Visszaad egy gyűjteményt a jelenleg hatókörben lévő definiált előtag-névtér leképezésekről.

```cpp
virtual SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::IXmlNamespaceResolver::GetNamespacesInScope(XmlNamespaceScope scope)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | Egy XmlNamespaceScope érték, amely meghatározza a visszaadandó névtér-csomópontok típusát. |

### Visszatérési érték

Egy IDictionary gyűjtemény, amely tartalmazza a jelenleg hatókörben lévő névtereket.

## Lásd még

* enum [XmlNamespaceScope](../../xmlnamespacescope/)
* typedef [SharedPtr](../../../system/sharedptr/)
* osztály [IDictionary](../../../system.collections.generic/idictionary/)
* osztály [String](../../../system/string/)
* osztály [IXmlNamespaceResolver](../)
* névtér [System::Xml](../../)
* könyvtár [Aspose.Slides](../../../)