---
title: LookupNamespace()
second_title: Riferimento API di Aspose.Slides per C++
description: Risolve un prefisso di namespace nell'ambito dell'elemento corrente.
type: docs
weight: 404
url: /it/system.xml/xmlnodereader/lookupnamespace/
---
## XmlNodeReader::LookupNamespace(const String\&) metodo


Risolvi un prefisso di spazio dei nomi nell'ambito dell'elemento corrente.

```cpp
String System::Xml::XmlNodeReader::LookupNamespace(const String &prefix) override
```


### Arguments

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Il prefisso il cui URI di namespace si desidera risolvere. Per corrispondere al namespace predefinito, passare una stringa vuota. Questa stringa non deve essere atomizzata. |

### Return Value

L'URI del namespace a cui il prefisso corrisponde o **nullptr** se non viene trovato alcun prefisso corrispondente.

## See Also

* Classe [String](../../../system/string/)
* Classe [XmlNodeReader](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)