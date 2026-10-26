---
title: get_Value()
second_title: Aspose.Slides C++ API Referencia
description: Visszaadja az aktuális csomópont szöveges értékét.
type: docs
weight: 79
url: /hu/system.xml/xmlnodereader/get_value/
---
## XmlNodeReader::get_Value() metódus


Visszaadja az aktuális csomópont szöveges értékét.

```cpp
String System::Xml::XmlNodeReader::get_Value() override
```


### Visszatérési érték

A visszaadott érték a csomópont [XmlNodeReader::get_NodeType](../get_nodetype/)-jától függ.

## Megjegyzések

Az alábbi táblázat felsorolja azokat a csomóponttípusokat, amelyeknek van visszaadható értékük. Minden más csomóponttípus [String::Empty](../../../system/string/empty/) értéket ad vissza. 

| Csomópont típusa | Érték |
| --- | --- |
| [Attribute](../../../system/attribute/)| Az attribútum értéke. |
| CDATA| A CDATA szakasz tartalma. |
| Comment| A megjegyzés tartalma. |
| DocumentType| A belső részhalmaz. |
| ProcessingInstruction| A teljes tartalom, a cél nélkül. |
| SignificantWhitespace| A markup között lévő üres karakterek egy vegyes tartalommodellben. |
| [Text](../../../system.text/)| A szövegcsomópont tartalma. |
| Whitespace| A markup között lévő üres karakterek. |
| [XmlDeclaration](../../xmldeclaration/)| A deklaráció tartalma. |


## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlNodeReader](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)