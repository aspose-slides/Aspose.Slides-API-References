---
title: get_Name()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce il nome qualificato del nodo corrente.
type: docs
weight: 14
url: /it/system.xml/xmltextreader/get_name/
---
## XmlTextReader::get_Name() metodo

Restituisce il nome qualificato del nodo corrente.

```cpp
String System::Xml::XmlTextReader::get_Name() override
```

### Valore restituito

Il nome qualificato del nodo corrente. Per esempio, **Name** è **bk:book** per l'elemento **<bk:book>**.

## Osservazioni

Il nome restituito dipende dal valore [XmlTextReader::get_NodeType](../get_nodetype/) del nodo. I seguenti tipi di nodo restituiscono i valori elencati. Tutti gli altri tipi di nodo restituiscono una stringa vuota. 

| Tipo di nodo | Nome |
| --- | --- |
| [Attribute](../../../system/attribute/)| Il nome dell'attributo. |
| DocumentType| Il nome del tipo di documento. |
| Element| Il nome del tag. |
| EntityReference| Il nome dell'entità referenziata. |
| ProcessingInstruction| Il target dell'istruzione di elaborazione. |
| [XmlDeclaration](../../xmldeclaration/)| La stringa letterale `xml`. |

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XmlTextReader](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)