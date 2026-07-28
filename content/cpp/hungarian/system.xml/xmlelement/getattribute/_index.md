---
title: GetAttribute()
second_title: Aspose.Slides for C++ API referenciája
description: Visszaadja a megadott névű attribútum értékét.
type: docs
weight: 209
url: /hu/system.xml/xmlelement/getattribute/
---
## XmlElement::GetAttribute(String) metódus

Visszaadja a megadott névű attribútum értékét.

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String name)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | [String](../../../system/string/) | A lekérdezendő attribútum neve. Ez egy minősített név. A megtalált csomópont **get_Name** értékével van összehasonlítva. |

### Visszatérési érték

A megadott attribútum értéke. Ha nincs megfelelő attribútum, vagy az attribútumnak nincs megadott vagy alapértelmezett értéke, akkor egy üres string kerül visszaadásra.

## XmlElement::GetAttribute(String, String) metódus

Visszaadja a megadott helyi névű és névtér-URI-vel rendelkező attribútum értékét.

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String localName, String namespaceURI)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| localName | [String](../../../system/string/) | A lekérdezendő attribútum helyi neve. |
| namespaceURI | [String](../../../system/string/) | A lekérdezendő attribútum névtér-URI-ja. |

### Visszatérési érték

A megadott attribútum értéke. Ha nincs megfelelő attribútum, vagy az attribútumnak nincs megadott vagy alapértelmezett értéke, akkor egy üres string kerül visszaadásra.

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlElement](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)