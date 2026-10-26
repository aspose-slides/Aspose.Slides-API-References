---
title: ReadToNextSibling()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Przesuwa XmlReader do następnego elementu siostrzego o określonej kwalifikowanej nazwie.
type: docs
weight: 924
url: /pl/system.xml/xmlreader/readtonextsibling/
---
## XmlReader::ReadToNextSibling(String) metoda


Przesuwa [XmlReader](../) do następnego elementu siostrzego o określonej kwalifikowanej nazwie.

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String name)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Kwalifikowana nazwa elementu siostrzego, do którego chcesz przejść. |

### Wartość zwracana

**true**, jeśli znaleziono pasujący element siostrzany; w przeciwnym razie **false**. Jeśli nie znaleziono pasującego elementu siostrzanego, [XmlReader](../) jest ustawiony na znacznik zamykający (wartość [XmlReader::get_NodeType](../get_nodetype/) jest [XmlNodeType::EndElement](../../xmlnodetype/)) elementu nadrzędnego.

## XmlReader::ReadToNextSibling(String, String) metoda


Przesuwa [XmlReader](../) do następnego elementu siostrzego o określonej nazwie lokalnej i URI przestrzeni nazw.

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String localName, String namespaceURI)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Lokalna nazwa elementu siostrzego, do którego chcesz przejść. |
| namespaceURI | [String](../../../system/string/) | URI przestrzeni nazw elementu siostrzego, do którego chcesz przejść. |

### Wartość zwracana

**true**, jeśli znaleziono pasujący element siostrzany; w przeciwnym razie **false**. Jeśli nie znaleziono pasującego elementu siostrzanego, [XmlReader](../) jest ustawiony na znacznik zamykający (wartość [XmlReader::get_NodeType](../get_nodetype/) jest [XmlNodeType::EndElement](../../xmlnodetype/)) elementu nadrzędnego.

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XmlReader](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)