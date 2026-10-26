---
title: MoveToAttribute()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Przechodzi do atrybutu o określonej nazwie.
type: docs
weight: 508
url: /pl/system.xml/xmltextreader/movetoattribute/
---
## XmlTextReader::MoveToAttribute(String) metoda


Przechodzi do atrybutu o określonej nazwie.

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String name) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [String](../../../system/string/) | W pełni kwalifikowana nazwa atrybutu. |

### Wartość zwracana

**true** if the attribute is found; otherwise, **false**. If **false**, the reader's position does not change.

## XmlTextReader::MoveToAttribute(String, String) metoda


Przechodzi do atrybutu o określonej nazwie lokalnej i URI przestrzeni nazw.

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String localName, String namespaceURI) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Lokalna nazwa atrybutu. |
| namespaceURI | [String](../../../system/string/) | URI przestrzeni nazw atrybutu. |

### Wartość zwracana

**true** if the attribute is found; otherwise, **false**. If **false**, the reader's position does not change.

## XmlTextReader::MoveToAttribute(int32_t) metoda


Przechodzi do atrybutu o określonym indeksie.

```cpp
void System::Xml::XmlTextReader::MoveToAttribute(int32_t i) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| i | **int32_t** | Indeks atrybutu. |

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XmlTextReader](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)