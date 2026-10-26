---
title: MoveToAttribute()
second_title: Aspose.Slides dla C++ - odniesienie API
description: "Gdy metoda jest przesłonięta w klasie pochodnej, przechodzi do atrybutu o określonej wartości XmlReader::get_Name."
type: docs
weight: 625
url: /pl/system.xml/xmlreader/movetoattribute/
---
## XmlReader::MoveToAttribute(String) metoda


Gdy metoda jest przesłonięta w klasie pochodnej, przechodzi do atrybutu o określonej wartości [XmlReader::get_Name](../get_name/).

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [String](../../../system/string/) | W pełni kwalifikowana nazwa atrybutu. |

### Wartość zwracana

**true** jeśli atrybut został znaleziony; w przeciwnym razie **false**. Jeśli **false**, pozycja czytnika nie ulega zmianie.

## XmlReader::MoveToAttribute(String, String) metoda


Gdy metoda jest przesłonięta w klasie pochodnej, przechodzi do atrybutu o określonych wartościach [XmlReader::get_LocalName](../get_localname/) i [XmlReader::get_NamespaceURI](../get_namespaceuri/).

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name, String ns)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Lokalna nazwa atrybutu. |
| ns | [String](../../../system/string/) | Identyfikator URI przestrzeni nazw atrybutu. |

### Wartość zwracana

**true** jeśli atrybut został znaleziony; w przeciwnym razie **false**. Jeśli **false**, pozycja czytnika nie ulega zmianie.

## XmlReader::MoveToAttribute(int32_t) metoda


Gdy metoda jest przesłonięta w klasie pochodnej, przechodzi do atrybutu o określonym indeksie.

```cpp
virtual void System::Xml::XmlReader::MoveToAttribute(int32_t i)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| i | **int32_t** | Indeks atrybutu. |

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XmlReader](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)