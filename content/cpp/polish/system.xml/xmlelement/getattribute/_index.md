---
title: GetAttribute()
second_title: Odwołanie API Aspose.Slides dla C++
description: Zwraca wartość atrybutu o określonej nazwie.
type: docs
weight: 209
url: /pl/system.xml/xmlelement/getattribute/
---
## XmlElement::GetAttribute(String) metoda

Zwraca wartość atrybutu o podanej nazwie.

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String name)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nazwa atrybutu do pobrania. Jest to nazwa kwalifikowana. Jest dopasowywana do wartości **get_Name** pasującego węzła. |

### Wartość zwracana

Wartość określonego atrybutu. Zwracany jest pusty ciąg, jeśli nie znaleziono pasującego atrybutu lub jeśli atrybut nie ma określonej ani domyślnej wartości.

## XmlElement::GetAttribute(String, String) metoda

Zwraca wartość atrybutu o podanej nazwie lokalnej i identyfikatorze URI przestrzeni nazw.

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String localName, String namespaceURI)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Nazwa lokalna atrybutu do pobrania. |
| namespaceURI | [String](../../../system/string/) | Identyfikator URI przestrzeni nazw atrybutu do pobrania. |

### Wartość zwracana

Wartość określonego atrybutu. Zwracany jest pusty ciąg, jeśli nie znaleziono pasującego atrybutu lub jeśli atrybut nie ma określonej ani domyślnej wartości.

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XmlElement](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)