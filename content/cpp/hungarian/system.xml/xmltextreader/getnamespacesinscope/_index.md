---
title: GetNamespacesInScope()
second_title: Aspose.Slides for C++ API-referencia
description: Visszaad egy gyűjteményt, amely tartalmazza az összes jelenleg hatókörben lévő névteret.
type: docs
weight: 716
url: /hu/system.xml/xmltextreader/getnamespacesinscope/
---
## XmlTextReader::GetNamespacesInScope(XmlNamespaceScope) metódus


Visszaad egy gyűjteményt, amely tartalmazza az összes jelenleg hatókörben lévő névteret.

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlTextReader::GetNamespacesInScope(XmlNamespaceScope scope) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | Egy XmlNamespaceScope érték, amely meghatározza a visszaadandó névtércsomópontok típusát. |

### Visszatérési érték

Egy IDictionary objektum, amely tartalmazza az összes jelenlegi hatókörben lévő névteret. Ha a olvasó nem egy elemre van pozícionálva, egy üres szótár (nincs névtér) kerül visszaadásra.

## Lásd még

* Enum [XmlNamespaceScope](../../xmlnamespacescope/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* osztály [IDictionary](../../../system.collections.generic/idictionary/)
* osztály [String](../../../system/string/)
* osztály [XmlTextReader](../)
* névtér [System::Xml](../../)
* könyvtár [Aspose.Slides](../../../)