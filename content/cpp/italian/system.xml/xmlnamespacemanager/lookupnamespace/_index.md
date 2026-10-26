---
title: LookupNamespace()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce l'URI dello spazio dei nomi per il prefisso specificato.
type: docs
weight: 118
url: /it/system.xml/xmlnamespacemanager/lookupnamespace/
---
## XmlNamespaceManager::LookupNamespace(const String\&) metodo

Restituisce l'URI dello spazio dei nomi per il prefisso specificato.

```cpp
String System::Xml::XmlNamespaceManager::LookupNamespace(const String &prefix) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Il prefisso il cui URI dello spazio dei nomi si desidera risolvere. Per corrispondere allo spazio dei nomi predefinito, passare [String::Empty](../../../system/string/empty/). |

### Valore di ritorno

L'URI dello spazio dei nomi per **prefix** o **nullptr** se non esiste uno spazio dei nomi mappato. La stringa restituita è atomizzata. Per ulteriori informazioni sulle stringhe atomizzate, vedere la classe [XmlNameTable](../../xmlnametable/).

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XmlNamespaceManager](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)