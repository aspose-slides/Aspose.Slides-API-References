---
title: get_Value()
second_title: Aspose.Slides C++ API referencia
description: Visszaadja az aktuális csomópont szöveges értékét.
type: docs
weight: 79
url: /hu/system.xml/xmlvalidatingreader/get_value/
---
## XmlValidatingReader::get_Value() metódus

Visszaadja az aktuális csomópont szöveges értékét.

```cpp
String System::Xml::XmlValidatingReader::get_Value() override
```

### Visszatérési érték

A visszaadott érték a csomópont XmlValidatingReader::NodeType értékétől függ.

## Megjegyzések

Az alábbi táblázat felsorolja azokat a csomópont típusa, amelyeknek van visszaadható értékük. Az összes többi csomópont típus [String::Empty](../../../system/string/empty/) értéket ad vissza. 

| Csomópont típusa | Érték |
| --- | --- |
| [Attribute](../../../system/attribute/)| Az attribútum értéke. |
| CDATA| A CDATA szakasz tartalma. |
| Comment| A megjegyzés tartalma. |
| DocumentType| A belső részhalmaz. |
| ProcessingInstruction| A teljes tartalom, a célpont nélkül. |
| SignificantWhitespace| A kevert tartalom modellben a jelölés közötti szóköz. |
| [Text](../../../system.text/)| A szövegcsomópont tartalma. |
| Whitespace| A jelölés közötti szóköz. |
| [XmlDeclaration](../../xmldeclaration/)| A deklaráció tartalma. |

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlValidatingReader](../)
* Névterület [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)