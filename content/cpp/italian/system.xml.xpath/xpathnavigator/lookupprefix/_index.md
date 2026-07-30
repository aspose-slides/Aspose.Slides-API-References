---
title: LookupPrefix()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce il prefisso dichiarato per l'URI dello spazio dei nomi specificato.
type: docs
weight: 417
url: /it/system.xml.xpath/xpathnavigator/lookupprefix/
---
## XPathNavigator::LookupPrefix(const String\&) metodo

Restituisce il prefisso dichiarato per l'URI dello spazio dei nomi specificato.

```cpp
String System::Xml::XPath::XPathNavigator::LookupPrefix(const String &namespaceURI) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| namespaceURI | const [String](../../../system/string/)\& | L'URI dello spazio dei nomi da risolvere per il prefisso. |

### Valore di ritorno

Un [String](../../../system/string/) che contiene il prefisso dello spazio dei nomi assegnato all'URI dello spazio dei nomi specificato; in caso contrario, [String::Empty](../../../system/string/empty/) se nessun prefisso è assegnato all'URI dello spazio dei nomi specificato. Il [String](../../../system/string/) restituito è atomizzato.

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XPathNavigator](../)
* Spazio dei nomi [System::Xml::XPath](../../)
* Libreria [Aspose.Slides](../../../)