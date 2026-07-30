---
title: get_Name()
second_title: Riferimento API di Aspose.Slides per C++
description: Quando sovrascritto in una classe derivata, ottiene il nome qualificato del nodo corrente.
type: docs
weight: 27
url: /it/system.xml/xmlreader/get_name/
---
## XmlReader::get_Name() metodo


Quando sovrascritto in una classe derivata, ottiene il nome qualificato del nodo corrente.

```cpp
virtual String System::Xml::XmlReader::get_Name()
```


### Valore di ritorno

Il nome qualificato del nodo corrente. Per esempio, **Name** è **bk:book** per l'elemento **<bk:book>**.

## Osservazioni

Il nome restituito dipende dal valore [XmlReader::get_NodeType](../get_nodetype/) del nodo. I seguenti tipi di nodo restituiscono i valori elencati. Tutti gli altri tipi di nodo restituiscono una stringa vuota. 

| Tipo di nodo | Nome |
| --- | --- |
| `[Attribute](../../../system/attribute/)`| Il nome dell'attributo. |
| `DocumentType`| Il nome del tipo di documento. |
| `Element`| Il nome del tag. |
| `EntityReference`| Il nome dell'entità referenziata. |
| `ProcessingInstruction`| La destinazione dell'istruzione di elaborazione. |
| [XmlDeclaration](../../xmldeclaration/)| La stringa letterale `xml`. |


## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XmlReader](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)