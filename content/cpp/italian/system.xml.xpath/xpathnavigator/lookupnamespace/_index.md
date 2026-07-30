---
title: LookupNamespace()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce l'URI dello spazio dei nomi per il prefisso specificato.
type: docs
weight: 404
url: /it/system.xml.xpath/xpathnavigator/lookupnamespace/
---
## XPathNavigator::LookupNamespace(const String\&) metodo

Restituisce l'URI dello spazio dei nomi per il prefisso specificato.

```cpp
String System::Xml::XPath::XPathNavigator::LookupNamespace(const String &prefix) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Il prefisso il cui URI dello spazio dei nomi si desidera risolvere. Per corrispondere allo spazio dei nomi predefinito, passare [String::Empty](../../../system/string/empty/). |

### Valore restituito

Un [String](../../../system/string/) che contiene l'URI dello spazio dei nomi assegnato al prefisso dello spazio dei nomi specificato; **nullptr** se nessun URI dello spazio dei nomi è assegnato al prefisso specificato. Il [String](../../../system/string/) restituito è atomizzato.

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XPathNavigator](../)
* Spazio dei nomi [System::Xml::XPath](../../)
* Libreria [Aspose.Slides](../../../)