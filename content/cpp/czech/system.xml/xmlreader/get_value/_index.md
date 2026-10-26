---
title: get_Value()
second_title: Aspose.Slides pro C++ - reference API
description: Když je přepsána v odvozené třídě, získá textovou hodnotu aktuálního uzlu.
type: docs
weight: 92
url: /cs/system.xml/xmlreader/get_value/
---
## XmlReader::get_Value() metoda


Když je přepsána v odvozené třídě, získá textovou hodnotu aktuálního uzlu.

```cpp
virtual String System::Xml::XmlReader::get_Value()=0
```


### Návratová hodnota

Vrácená hodnota závisí na hodnotě [XmlReader::get_NodeType](../get_nodetype/) uzlu.
## Poznámky



Následující tabulka uvádí typy uzlů, které mají hodnotu k vrácení. Všechny ostatní typy uzlů vrací [String::Empty](../../../system/string/empty/). 

| Typ uzlu | Hodnota |
| --- | --- |
| `[Attribute](../../../system/attribute/)`| Hodnota atributu. |
| `CDATA`| Obsah sekce CDATA. |
| `Comment`| Obsah komentáře. |
| `DocumentType`| Vnitřní podmnožina. |
| `ProcessingInstruction`| Celý obsah, s výjimkou cíle. |
| `SignificantWhitespace`| Mezery mezi značkami v modelu smíšeného obsahu. |
| `[Text](../../../system.text/)`| Obsah textového uzlu. |
| `Whitespace`| Mezery mezi značkami. |
| [XmlDeclaration](../../xmldeclaration/)| Obsah deklarace. |


## Viz také

* Třída [String](../../../system/string/)
* Třída [XmlReader](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)