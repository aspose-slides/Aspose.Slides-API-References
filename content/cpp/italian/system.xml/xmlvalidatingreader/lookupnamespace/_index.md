---
title: LookupNamespace()
second_title: Riferimento API di Aspose.Slides per C++
description: Risolvi un prefisso di spazio dei nomi nell'ambito dell'elemento corrente.
type: docs
weight: 547
url: /it/system.xml/xmlvalidatingreader/lookupnamespace/
---
## XmlValidatingReader::LookupNamespace(const String\&) method

Risolvi un prefisso di spazio dei nomi nell'ambito dell'elemento corrente.

```cpp
String System::Xml::XmlValidatingReader::LookupNamespace(const String &prefix) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Il prefisso il cui Uniform Resource Identifier (URI) di spazio dei nomi si desidera risolvere. Per corrispondere allo spazio dei nomi predefinito, passare una stringa vuota. |

### Valore di ritorno

L'URI dello spazio dei nomi a cui il prefisso corrisponde oppure **nullptr** se non viene trovato alcun prefisso corrispondente.

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XmlValidatingReader](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)