---
title: LookupPrefix()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt das für den angegebenen Namespace-URI deklarierte Präfix zurück.
type: docs
weight: 417
url: /de/system.xml.xpath/xpathnavigator/lookupprefix/
---
## XPathNavigator::LookupPrefix(const String\&) Methode

Gibt das für den angegebenen Namespace-URI deklarierte Präfix zurück.

```cpp
String System::Xml::XPath::XPathNavigator::LookupPrefix(const String &namespaceURI) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| namespaceURI | const [String](../../../system/string/)\& | Der Namespace-URI, der für das Präfix aufgelöst werden soll. |

### Rückgabewert

Ein [String](../../../system/string/), der das dem angegebenen Namespace-URI zugewiesene Präfix enthält; andernfalls [String::Empty](../../../system/string/empty/), wenn dem angegebenen Namespace-URI kein Präfix zugewiesen ist. Das zurückgegebene [String](../../../system/string/) ist atomisiert.

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XPathNavigator](../)
* Namensraum [System::Xml::XPath](../../)
* Bibliothek [Aspose.Slides](../../../)