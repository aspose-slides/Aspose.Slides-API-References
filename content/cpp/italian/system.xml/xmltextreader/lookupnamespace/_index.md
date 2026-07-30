---
title: LookupNamespace()
second_title: Riferimento API Aspose.Slides per C++
description: Risolve un prefisso di spazio dei nomi nell'ambito dell'elemento corrente.
type: docs
weight: 612
url: /it/system.xml/xmltextreader/lookupnamespace/
---
## XmlTextReader::LookupNamespace(const String\&) metodo

Risolvi un prefisso di spazio dei nomi nell'ambito dell'elemento corrente.

```cpp
String System::Xml::XmlTextReader::LookupNamespace(const String &prefix) override
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Il prefisso il cui URI di spazio dei nomi si desidera risolvere. Per corrispondere allo spazio dei nomi predefinito, passare una stringa vuota. Questa stringa non deve essere atomizzata. |

### Valore di ritorno

L'URI di spazio dei nomi a cui il prefisso corrisponde oppure **nullptr** se non viene trovato alcun prefisso corrispondente.

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)