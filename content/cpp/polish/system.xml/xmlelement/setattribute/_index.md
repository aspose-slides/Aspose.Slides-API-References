---
title: SetAttribute()
second_title: Aspose.Slides dla C++ – referencja API
description: Ustawia wartość atrybutu o podanej nazwie.
type: docs
weight: 222
url: /pl/system.xml/xmlelement/setattribute/
---
## XmlElement::SetAttribute(String, String) metoda

Ustawia wartość atrybutu o podanej nazwie.

```cpp
virtual void System::Xml::XmlElement::SetAttribute(String name, String value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nazwa atrybutu, który ma zostać utworzony lub zmodyfikowany. Jest to nazwa kwalifikowana. Jeśli nazwa zawiera dwukropek, jest ona rozdzielana na prefiks i komponent nazwy lokalnej. |
| value | [String](../../../system/string/) | Wartość, którą należy ustawić dla atrybutu. |

## XmlElement::SetAttribute(String, String, String) metoda

Ustawia wartość atrybutu o podanej nazwie lokalnej i identyfikatorze URI przestrzeni nazw.

```cpp
virtual String System::Xml::XmlElement::SetAttribute(String localName, String namespaceURI, String value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Nazwa lokalna atrybutu. |
| namespaceURI | [String](../../../system/string/) | Identyfikator URI przestrzeni nazw atrybutu. |
| value | [String](../../../system/string/) | Wartość, którą należy ustawić dla atrybutu. |

### Wartość zwracana

Wartość atrybutu.

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XmlElement](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)