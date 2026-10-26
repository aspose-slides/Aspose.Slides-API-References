---
title: LookupPrefix()
second_title: Riferimento API di Aspose.Slides per C++
description: Trova il prefisso dichiarato per l'URI dello spazio dei nomi specificato.
type: docs
weight: 131
url: /it/system.xml/xmlnamespacemanager/lookupprefix/
---
## XmlNamespaceManager::LookupPrefix(const String\&) metodo

Trova il prefisso dichiarato per l'URI dello spazio dei nomi specificato.

```cpp
String System::Xml::XmlNamespaceManager::LookupPrefix(const String &uri) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | Lo spazio dei nomi da risolvere per il prefisso. |

### Valore restituito

Il prefisso corrispondente. Se non esiste alcun prefisso mappato, il metodo restituisce [String::Empty](../../../system/string/empty/). Se viene fornito un valore nullo, viene restituito **nullptr**.

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XmlNamespaceManager](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)