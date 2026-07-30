---
title: get_Name()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce il nome qualificato del nodo corrente.
type: docs
weight: 14
url: /it/system.xml/xmlvalidatingreader/get_name/
---
## XmlValidatingReader::get_Name() method


Restituisce il nome qualificato del nodo corrente.

```cpp
String System::Xml::XmlValidatingReader::get_Name() override
```


### Valore di ritorno

Il nome qualificato del nodo corrente. Per esempio, **Name** è **bk:book** per l'elemento **<bk:book>**.
## Osservazioni



Il nome restituito dipende dal XmlValidatingReader::NodeType del nodo. I seguenti tipi di nodo restituiscono i valori elencati. Tutti gli altri tipi di nodo restituiscono una stringa vuota. 

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
* Classe [XmlValidatingReader](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)