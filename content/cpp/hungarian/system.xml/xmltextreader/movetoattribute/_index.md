---
title: MoveToAttribute()
second_title: Aspose.Slides C++ API referencia
description: A megadott névvel rendelkező attribútumra lép.
type: docs
weight: 508
url: /hu/system.xml/xmltextreader/movetoattribute/
---
## XmlTextReader::MoveToAttribute(String) metódus


A megadott névvel rendelkező attribútumra lép.

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String name) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | [String](../../../system/string/) | Az attribútum kvalifikált neve. |

### Visszatérési érték

**true** ha az attribútum megtalálható; egyébként **false**. Ha **false**, az olvasó pozíciója nem változik.

## XmlTextReader::MoveToAttribute(String, String) metódus


A megadott helyi névvel és névtér URI-val rendelkező attribútumra lép.

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String localName, String namespaceURI) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Az attribútum helyi neve. |
| namespaceURI | [String](../../../system/string/) | Az attribútum névtér URI-ja. |

### Visszatérési érték

**true** ha az attribútum megtalálható; egyébként **false**. Ha **false**, az olvasó pozíciója nem változik.

## XmlTextReader::MoveToAttribute(int32_t) metódus


A megadott indexű attribútumra lép.

```cpp
void System::Xml::XmlTextReader::MoveToAttribute(int32_t i) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| i | **int32_t** | Az attribútum indexe. |

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlTextReader](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)