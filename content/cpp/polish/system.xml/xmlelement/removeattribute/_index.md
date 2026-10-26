---
title: RemoveAttribute()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Usuwa atrybut według nazwy.
type: docs
weight: 235
url: /pl/system.xml/xmlelement/removeattribute/
---
## XmlElement::RemoveAttribute(String) metoda

Usuwa atrybut według nazwy.

```cpp
virtual void System::Xml::XmlElement::RemoveAttribute(String name)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nazwa atrybutu do usunięcia. Jest to nazwa kwalifikowana. Jest porównywana z wartością **get_Name** pasującego węzła. |

## XmlElement::RemoveAttribute(String, String) metoda

Usuwa atrybut o określonej nazwie lokalnej i identyfikatorze URI przestrzeni nazw. (Jeśli usunięty atrybut ma wartość domyślną, zostaje ona natychmiast przywrócona).

```cpp
virtual void System::Xml::XmlElement::RemoveAttribute(String localName, String namespaceURI)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Lokalna nazwa atrybutu do usunięcia. |
| namespaceURI | [String](../../../system/string/) | URI przestrzeni nazw atrybutu do usunięcia. |

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XmlElement](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)