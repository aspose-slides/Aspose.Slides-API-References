---
title: get_Value()
second_title: Aspose.Slides for C++ API Referencia
description: Visszaadja az aktuális csomópont szöveges értékét.
type: docs
weight: 79
url: /hu/system.xml/xmltextreader/get_value/
---
## XmlTextReader::get_Value() metódus

Visszaadja az aktuális csomópont szöveges értékét.

```cpp
String System::Xml::XmlTextReader::get_Value() override
```

### Visszatérési érték

A visszaadott érték a csomópont [XmlTextReader::get_NodeType](../get_nodetype/) értékétől függ.

## Megjegyzés

Az alábbi táblázat felsorolja azokat a csomóponttípusokat, amelyeknek van visszatérítendő értékük. Minden más csomóponttípus [String::Empty](../../../system/string/empty/) értéket ad vissza.

| Csomópont típusa | Érték |
| --- | --- |
| [Attribute](../../../system/attribute/)| Az attribútum értéke. |
| CDATA| A CDATA szakasz tartalma. |
| Comment| A megjegyzés tartalma. |
| DocumentType| A belső részhalmaz. |
| ProcessingInstruction| A teljes tartalom, a cél nélkül. |
| SignificantWhitespace| Az `xml:space='preserve'` hatókörön belüli szóköz. |
| [Text](../../../system.text/)| A szöveges csomópont tartalma. |
| Whitespace| A jelölés között lévő szóköz. |
| [XmlDeclaration](../../xmldeclaration/)| A deklaráció tartalma. |

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlTextReader](../)
* Névterület [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)