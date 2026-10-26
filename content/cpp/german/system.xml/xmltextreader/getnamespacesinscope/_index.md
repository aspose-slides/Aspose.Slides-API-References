---
title: GetNamespacesInScope()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt eine Sammlung zurück, die alle derzeit im Gültigkeitsbereich befindlichen Namensräume enthält.
type: docs
weight: 716
url: /de/system.xml/xmltextreader/getnamespacesinscope/
---
## XmlTextReader::GetNamespacesInScope(XmlNamespaceScope) Methode

Gibt eine Sammlung zurück, die alle derzeit im Gültigkeitsbereich befindlichen Namensräume enthält.

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlTextReader::GetNamespacesInScope(XmlNamespaceScope scope) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | Ein XmlNamespaceScope-Wert, der den Typ der zurückzugebenden Namespace-Knoten angibt. |

### Rückgabewert

Ein IDictionary-Objekt, das alle aktuellen im Gültigkeitsbereich befindlichen Namensräume enthält. Wenn der Reader nicht auf einem Element positioniert ist, wird ein leeres Wörterbuch (keine Namensräume) zurückgegeben.

## Siehe auch

* Enum [XmlNamespaceScope](../../xmlnamespacescope/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IDictionary](../../../system.collections.generic/idictionary/)
* Klasse [String](../../../system/string/)
* Klasse [XmlTextReader](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)