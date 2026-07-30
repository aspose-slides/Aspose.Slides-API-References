---
title: get_Value()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce il valore di testo del nodo corrente.
type: docs
weight: 79
url: /it/system.xml/xmlnodereader/get_value/
---
## XmlNodeReader::get_Value() metodo


Restituisce il valore di testo del nodo corrente.

```cpp
String System::Xml::XmlNodeReader::get_Value() override
```


### Valore di ritorno

Il valore restituito dipende dal [XmlNodeReader::get_NodeType](../get_nodetype/) del nodo.
## Osservazioni



La tabella seguente elenca i tipi di nodo che hanno un valore da restituire. Tutti gli altri tipi di nodo restituiscono [String::Empty](../../../system/string/empty/). 

| Tipo di nodo | Valore |
| --- | --- |
| [Attribute](../../../system/attribute/)| Il valore dell'attributo. |
| CDATA| Il contenuto della sezione CDATA. |
| Comment| Il contenuto del commento. |
| DocumentType| Il sottoinsieme interno. |
| ProcessingInstruction| L'intero contenuto, escluso il target. |
| SignificantWhitespace| Lo spazio bianco tra markup in un modello di contenuto misto. |
| [Text](../../../system.text/)| Il contenuto del nodo di testo. |
| Whitespace| Lo spazio bianco tra markup. |
| [XmlDeclaration](../../xmldeclaration/)| Il contenuto della dichiarazione. |


## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XmlNodeReader](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)