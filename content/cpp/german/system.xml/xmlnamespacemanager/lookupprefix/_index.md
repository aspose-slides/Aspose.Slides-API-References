---
title: LookupPrefix()
second_title: Aspose.Slides für C++ API-Referenz
description: Findet das für die angegebene Namespace-URI deklarierte Präfix.
type: docs
weight: 131
url: /de/system.xml/xmlnamespacemanager/lookupprefix/
---
## XmlNamespaceManager::LookupPrefix(const String\&) Methode

Findet das für die angegebene Namespace-URI deklarierte Präfix.

```cpp
String System::Xml::XmlNamespaceManager::LookupPrefix(const String &uri) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | Der Namespace, für den das Präfix aufgelöst werden soll. |

### Rückgabewert

Das passende Präfix. Gibt es kein zugeordnetes Präfix, liefert die Methode [String::Empty](../../../system/string/empty/). Wird ein Nullwert übergeben, wird **nullptr** zurückgegeben.

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XmlNamespaceManager](../)
* Namespace [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)