---
title: LookupNamespace()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die Namespace-URI für das angegebene Präfix zurück.
type: docs
weight: 118
url: /de/system.xml/xmlnamespacemanager/lookupnamespace/
---
## XmlNamespaceManager::LookupNamespace(const String\&) Methode

Gibt die Namespace-URI für das angegebene Präfix zurück.

```cpp
String System::Xml::XmlNamespaceManager::LookupNamespace(const String &prefix) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Das Präfix, dessen Namespace-URI Sie auflösen möchten. Um den Standard-Namespace zu übernehmen, übergeben Sie [String::Empty](../../../system/string/empty/). |

### Rückgabewert

Die Namespace-URI für **prefix** oder **nullptr**, wenn kein zugeordneter Namespace vorhanden ist. Der zurückgegebene String ist atomisiert. Weitere Informationen zu atomisierten Strings finden Sie in der [XmlNameTable](../../xmlnametable/)-Klasse.

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XmlNamespaceManager](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)