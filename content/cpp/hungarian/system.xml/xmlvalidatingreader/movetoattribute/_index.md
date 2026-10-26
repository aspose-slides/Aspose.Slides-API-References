---
title: MoveToAttribute()
second_title: Aspose.Slides C++ API-referencia
description: Átmozdul a megadott névvel rendelkező attribútumra.
type: docs
weight: 456
url: /hu/system.xml/xmlvalidatingreader/movetoattribute/
---
## XmlValidatingReader::MoveToAttribute(String) metódus


Átmozdul a megadott névvel rendelkező attribútumra.

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String name) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | [String](../../../system/string/) | Az attribútum minősített neve. |

### Visszatérési érték

**true** ha az attribútum megtalálható; egyébként **false**. Ha **false**, az olvasó pozíciója nem változik.

## XmlValidatingReader::MoveToAttribute(String, String) metódus


Átmozdul a megadott helyi névvel és névtér Uniform Resource Identifier (URI) -val rendelkező attribútumra.

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String localName, String namespaceURI) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Az attribútum helyi neve. |
| namespaceURI | [String](../../../system/string/) | Az attribútum névtér URI-ja. |

### Visszatérési érték

**true** ha az attribútum megtalálható; egyébként **false**. Ha **false**, az olvasó pozíciója nem változik.

## XmlValidatingReader::MoveToAttribute(int32_t) metódus


Átmozdul a megadott indexű attribútumra.

```cpp
void System::Xml::XmlValidatingReader::MoveToAttribute(int32_t i) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| i | **int32_t** | Az attribútum indexe. |

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlValidatingReader](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)