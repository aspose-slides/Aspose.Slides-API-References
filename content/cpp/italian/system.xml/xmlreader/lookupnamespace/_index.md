---
title: LookupNamespace()
second_title: Riferimento API di Aspose.Slides per C++
description: Quando viene sovrascritto in una classe derivata, risolve un prefisso di namespace nell'ambito dell'elemento corrente.
type: docs
weight: 729
url: /it/system.xml/xmlreader/lookupnamespace/
---
## XmlReader::LookupNamespace(const String\&) metodo


When overridden in a derived class, resolves a namespace prefix in the current element's scope.

```cpp
virtual String System::Xml::XmlReader::LookupNamespace(const String &prefix)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Il prefisso il cui URI di namespace si desidera risolvere. Per corrispondere allo spazio dei nomi predefinito, passare una stringa vuota. |

### Valore di ritorno

L'URI del namespace a cui il prefisso è associato o **nullptr** se non viene trovato alcun prefisso corrispondente.

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XmlReader](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)