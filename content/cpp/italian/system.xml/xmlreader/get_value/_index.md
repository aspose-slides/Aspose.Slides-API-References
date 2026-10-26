---
title: get_Value()
second_title: Riferimento API di Aspose.Slides per C++
description: Quando sovrascritto in una classe derivata, ottiene il valore di testo del nodo corrente.
type: docs
weight: 92
url: /it/system.xml/xmlreader/get_value/
---
## XmlReader::get_Value() metodo

Quando viene sovrascritto in una classe derivata, ottiene il valore di testo del nodo corrente.

```cpp
virtual String System::Xml::XmlReader::get_Value()=0
```

### Valore restituito

Il valore restituito dipende dal valore [XmlReader::get_NodeType](../get_nodetype/) del nodo.

## Osservazioni

La tabella seguente elenca i tipi di nodo che hanno un valore da restituire. Tutti gli altri tipi di nodo restituiscono [String::Empty](../../../system/string/empty/). 

| Tipo di nodo | Valore |
| --- | --- |
| `[Attribute](../../../system/attribute/)`| Il valore dell'attributo. |
| `CDATA`| Il contenuto della sezione CDATA. |
| `Comment`| Il contenuto del commento. |
| `DocumentType`| Il sottoinsieme interno. |
| `ProcessingInstruction`| L'intero contenuto, escluso il target. |
| `SignificantWhitespace`| Lo spazio bianco tra i markup in un modello di contenuto misto. |
| `[Text](../../../system.text/)`| Il contenuto del nodo di testo. |
| `Whitespace`| Lo spazio bianco tra i markup. |
| [XmlDeclaration](../../xmldeclaration/)| Il contenuto della dichiarazione. |

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XmlReader](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)