---
title: ReadToFollowing()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Czyta aż do znalezienia elementu o określonej kwalifikowanej nazwie.
type: docs
weight: 898
url: /pl/system.xml/xmlreader/readtofollowing/
---
## XmlReader::ReadToFollowing(String) metoda

Czyta aż do znalezienia elementu o określonej kwalifikowanej nazwie.

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String name)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Kwalifikowana nazwa elementu. |

### Wartość zwracana

**true** jeśli znaleziono pasujący element; w przeciwnym razie **false** i [XmlReader](../) znajduje się w stanie końca pliku.

## XmlReader::ReadToFollowing(String, String) metoda

Czyta aż do znalezienia elementu o określonej nazwie lokalnej i URI przestrzeni nazw.

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String localName, String namespaceURI)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Lokalna nazwa elementu. |
| namespaceURI | [String](../../../system/string/) | URI przestrzeni nazw elementu. |

### Wartość zwracana

**true** jeśli znaleziono pasujący element; w przeciwnym razie **false** i [XmlReader](../) znajduje się w stanie końca pliku.

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XmlReader](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)