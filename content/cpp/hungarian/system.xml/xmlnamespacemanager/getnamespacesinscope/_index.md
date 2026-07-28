---
title: GetNamespacesInScope()
second_title: Aspose.Slides C++ API referenciája
description: Visszaad egy gyűjteményt a névtérnevekről, amelyek előtag alapján kulcsként vannak indexelve, és felhasználhatók az aktuálisan hatókörben lévő névterek felsorolására.
type: docs
weight: 105
url: /hu/system.xml/xmlnamespacemanager/getnamespacesinscope/
---
## XmlNamespaceManager::GetNamespacesInScope(XmlNamespaceScope) metódus


Egy gyűjteményt ad vissza a névtérnevekről, amelyeket előtag alapján kulcsként használnak, és felhasználhatók az aktuálisan hatókörben lévő névterek felsorolására.

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlNamespaceManager::GetNamespacesInScope(XmlNamespaceScope scope) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | Egy felsorolásérték, amely meghatározza a visszaadandó névtércsomópontok típusát. |

### Visszatérési érték

Egy gyűjtemény a névtér- és előtag-párokhoz, amelyek jelenleg hatókörben vannak.

## Lásd még

* Enum [XmlNamespaceScope](../../xmlnamespacescope/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IDictionary](../../../system.collections.generic/idictionary/)
* Osztály [String](../../../system/string/)
* Osztály [XmlNamespaceManager](../)
* Névtere [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)