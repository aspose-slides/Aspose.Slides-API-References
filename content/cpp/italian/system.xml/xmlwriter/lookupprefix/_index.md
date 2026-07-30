---
title: LookupPrefix()
second_title: Riferimento API di Aspose.Slides per C++
description: Quando sovrascritto in una classe derivata, restituisce il prefisso più vicino definito nell'ambito dello spazio dei nomi corrente per l'URI dello spazio dei nomi.
type: docs
weight: 352
url: /it/system.xml/xmlwriter/lookupprefix/
---
## XmlWriter::LookupPrefix(String) metodo


Quando sovrascritto in una classe derivata, restituisce il prefisso più vicino definito nell'ambito dello spazio dei nomi corrente per l'URI dello spazio dei nomi.

```cpp
virtual String System::Xml::XmlWriter::LookupPrefix(String ns)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ns | [String](../../../system/string/) | L'URI dello spazio dei nomi il cui prefisso si desidera trovare. |

### Valore di ritorno

Il prefisso corrispondente o **nullptr** se non viene trovato alcun URI di spazio dei nomi corrispondente nell'ambito corrente.

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XmlWriter](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)