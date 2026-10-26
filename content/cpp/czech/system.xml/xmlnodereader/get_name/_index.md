---
title: get_Name()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Vrací kvalifikovaný název aktuálního uzlu.
type: docs
weight: 14
url: /cs/system.xml/xmlnodereader/get_name/
---
## XmlNodeReader::get_Name() metoda


Vrací kvalifikovaný název aktuálního uzlu.

```cpp
String System::Xml::XmlNodeReader::get_Name() override
```


### Návratová hodnota

Kvalifikovaný název aktuálního uzlu. Například **Name** je **bk:book** pro prvek **<bk:book>**.
## Poznámky



Vrácený název závisí na hodnotě [XmlNodeReader::get_NodeType](../get_nodetype/) uzlu. Následující typy uzlů vracejí uvedené hodnoty. Všechny ostatní typy uzlů vracejí prázdný řetězec. 

| Typ uzlu | Název |
| --- | --- |
| [Attribute](../../../system/attribute/)| Název atributu. |
| DocumentType| Název typu dokumentu. |
| Element| Název značky. |
| EntityReference| Název odkazované entity. |
| ProcessingInstruction| Cíl instrukce zpracování. |
| [XmlDeclaration](../../xmldeclaration/)| Doslovný řetězec `xml`. |


## Viz také

* Třída [String](../../../system/string/)
* Třída [XmlNodeReader](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)