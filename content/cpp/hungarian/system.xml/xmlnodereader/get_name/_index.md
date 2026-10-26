---
title: get_Name()
second_title: Aspose.Slides a C++ API hivatkozása
description: Visszaadja az aktuális csomópont minősített nevét.
type: docs
weight: 14
url: /hu/system.xml/xmlnodereader/get_name/
---
## XmlNodeReader::get_Name() metódus


Visszaadja az aktuális csomópont minősített nevét.

```cpp
String System::Xml::XmlNodeReader::get_Name() override
```


### Visszatérési érték

Az aktuális csomópont minősített neve. Például a **Name** **bk:book**, ha az elem **<bk:book>**.
## Megjegyzések



A visszaadott név a [XmlNodeReader::get_NodeType](../get_nodetype/) értéktől függ. A következő csomópont típusok a felsorolt értékeket adják vissza. Minden más csomópont típus üres karakterláncot ad vissza. 

| Csomópont típusa | Név |
| --- | --- |
| [Attribute](../../../system/attribute/)| Az attribútum neve. |
| DocumentType| A dokumentumtípus neve. |
| Element| Az elem neve. |
| EntityReference| A hivatkozott entitás neve. |
| ProcessingInstruction| A feldolgozási utasítás célja. |
| [XmlDeclaration](../../xmldeclaration/)| A szó szerinti karakterlánc `xml`. |


## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlNodeReader](../)
* Névtere [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)