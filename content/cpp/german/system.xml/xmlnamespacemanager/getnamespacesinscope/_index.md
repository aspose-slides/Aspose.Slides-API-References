---
title: GetNamespacesInScope()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt eine Sammlung von Namespace-Namen zurück, die nach Präfix indiziert sind und zur Aufzählung der aktuell im Gültigkeitsbereich befindlichen Namespaces verwendet werden können.
type: docs
weight: 105
url: /de/system.xml/xmlnamespacemanager/getnamespacesinscope/
---
## XmlNamespaceManager::GetNamespacesInScope(XmlNamespaceScope) Methode

Gibt eine Sammlung von Namespace-Namen zurück, die nach Präfix indiziert sind und zur Aufzählung der aktuell im Gültigkeitsbereich befindlichen Namespaces verwendet werden können.

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlNamespaceManager::GetNamespacesInScope(XmlNamespaceScope scope) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | Ein Aufzählungswert, der den Typ der zurückzugebenden Namespace-Knoten angibt. |

### Rückgabewert

Eine Sammlung von Namespace- und Präfix-Paaren, die derzeit im Gültigkeitsbereich sind.

## Siehe auch

* Aufzählung [XmlNamespaceScope](../../xmlnamespacescope/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IDictionary](../../../system.collections.generic/idictionary/)
* Klasse [String](../../../system/string/)
* Klasse [XmlNamespaceManager](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)