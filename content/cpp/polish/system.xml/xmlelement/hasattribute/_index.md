---
title: HasAttribute()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Określa, czy bieżący węzeł ma atrybut o określonej nazwie.
type: docs
weight: 300
url: /pl/system.xml/xmlelement/hasattribute/
---
## XmlElement::HasAttribute(String) metoda


Określa, czy bieżący węzeł ma atrybut o podanej nazwie.

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String name)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nazwa atrybutu do wyszukania. Jest to nazwa kwalifikowana. Dopasowywana jest do wartości **get_Name** pasującego węzła. |

### Wartość zwracana

**true** jeśli bieżący węzeł ma określony atrybut; w przeciwnym razie **false**.

## XmlElement::HasAttribute(String, String) metoda


Określa, czy bieżący węzeł ma atrybut o podanej nazwie lokalnej i identyfikatorze URI przestrzeni nazw.

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String localName, String namespaceURI)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Lokalna nazwa atrybutu do wyszukania. |
| namespaceURI | [String](../../../system/string/) | Identyfikator URI przestrzeni nazw atrybutu do wyszukania. |

### Wartość zwracana

**true** jeśli bieżący węzeł ma określony atrybut; w przeciwnym razie **false**.

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XmlElement](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)