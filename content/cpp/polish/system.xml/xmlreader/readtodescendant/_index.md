---
title: ReadToDescendant()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Przesuwa XmlReader do następnego elementu potomnego o określonej nazwie kwalifikowanej.
type: docs
weight: 911
url: /pl/system.xml/xmlreader/readtodescendant/
---
## XmlReader::ReadToDescendant(String) metoda


Przesuwa [XmlReader](../) do następnego elementu potomnego o określonej nazwie kwalifikowanej.

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String name)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Kwalifikowana nazwa elementu, do którego chcesz przejść. |

### Wartość zwracana

**true**, jeśli znaleziono pasujący element potomny; w przeciwnym razie **false**. Jeśli nie zostanie znaleziony pasujący element dziecka, [XmlReader](../) jest ustawiony na tag końcowy (wartość [XmlReader::get_NodeType](../get_nodetype/) to [XmlNodeType::EndElement](../../xmlnodetype/)) elementu. Jeśli [XmlReader](../) nie jest ustawiony na elemencie w momencie wywołania [XmlReader::ReadToDescendant(String)](./), ta metoda zwraca **false** i pozycja [XmlReader](../) nie zostaje zmieniona.

## XmlReader::ReadToDescendant(String, String) metoda


Przesuwa [XmlReader](../) do następnego elementu potomnego o określonej nazwie lokalnej i URI przestrzeni nazw.

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String localName, String namespaceURI)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Lokalna nazwa elementu, do którego chcesz przejść. |
| namespaceURI | [String](../../../system/string/) | URI przestrzeni nazw elementu, do którego chcesz przejść. |

### Wartość zwracana

**true**, jeśli znaleziono pasujący element potomny; w przeciwnym razie **false**. Jeśli nie zostanie znaleziony pasujący element dziecka, [XmlReader](../) jest ustawiony na tag końcowy (wartość [XmlReader::get_NodeType](../get_nodetype/) to [XmlNodeType::EndElement](../../xmlnodetype/)) elementu. Jeśli [XmlReader](../) nie jest ustawiony na elemencie w momencie wywołania [XmlReader::ReadToDescendant(String,String)](./), ta metoda zwraca **false** i pozycja [XmlReader](../) nie zostaje zmieniona.

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XmlReader](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)