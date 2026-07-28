---
title: get_Name()
second_title: Aspose.Slides dla C++ referencja API
description: Zwraca w pełni kwalifikowaną nazwę bieżącego węzła.
type: docs
weight: 14
url: /pl/system.xml/xmltextreader/get_name/
---
## XmlTextReader::get_Name() metoda

Zwraca w pełni kwalifikowaną nazwę bieżącego węzła.

```cpp
String System::Xml::XmlTextReader::get_Name() override
```

### Wartość zwracana

W pełni kwalifikowana nazwa bieżącego węzła. Na przykład, **Name** to **bk:book** dla elementu **<bk:book>**.

## Uwagi

Zwracana nazwa zależy od wartości [XmlTextReader::get_NodeType](../get_nodetype/) węzła. Następujące typy węzłów zwracają wymienione wartości. Wszystkie pozostałe typy węzłów zwracają pusty łańcuch. 

| Typ węzła | Nazwa |
| --- | --- |
| [Attribute](../../../system/attribute/)| Nazwa atrybutu. |
| DocumentType| Nazwa typu dokumentu. |
| Element| Nazwa znacznika. |
| EntityReference| Nazwa odwoływanego bytu. |
| ProcessingInstruction| Cel instrukcji przetwarzania. |
| [XmlDeclaration](../../xmldeclaration/)| Literał `xml`. |

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XmlTextReader](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)