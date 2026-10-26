---
title: LookupNamespace()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die Namespace-URI für das angegebene Präfix zurück.
type: docs
weight: 404
url: /de/system.xml.xpath/xpathnavigator/lookupnamespace/
---
## XPathNavigator::LookupNamespace(const String\&) Methode


Gibt die Namespace-URI für das angegebene Präfix zurück.

```cpp
String System::Xml::XPath::XPathNavigator::LookupNamespace(const String &prefix) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Das Präfix, dessen Namespace-URI Sie auflösen möchten. Um den Standardsnamespace zu matchen, übergeben Sie [String::Empty](../../../system/string/empty/). |

### Rückgabewert

Ein [String](../../../system/string/), das die dem angegebenen Namespace-Präfix zugewiesene Namespace-URI enthält; **nullptr**, wenn dem angegebenen Präfix keine Namespace-URI zugewiesen ist. Das zurückgegebene [String](../../../system/string/) ist atomisiert.

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XPathNavigator](../)
* Namensraum [System::Xml::XPath](../../)
* Bibliothek [Aspose.Slides](../../../)