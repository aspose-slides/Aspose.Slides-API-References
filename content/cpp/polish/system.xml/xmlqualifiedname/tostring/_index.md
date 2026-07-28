---
title: ToString()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Zwraca wartość łańcucha znaków XmlQualifiedName.
type: docs
weight: 79
url: /pl/system.xml/xmlqualifiedname/tostring/
---
## XmlQualifiedName::ToString() const metoda


Zwraca wartość łańcucha znaków [XmlQualifiedName](../).

```cpp
String System::Xml::XmlQualifiedName::ToString() const override
```


### Wartość zwracana

Wartość łańcucha znaków [XmlQualifiedName](../) w formacie **namespace:localname**. Jeśli obiekt nie ma zdefiniowanej przestrzeni nazw, ta metoda zwraca jedynie nazwę lokalną.

## XmlQualifiedName::ToString(const String\&, const String\&) metoda


Zwraca wartość łańcucha znaków [XmlQualifiedName](../).

```cpp
static String System::Xml::XmlQualifiedName::ToString(const String &name, const String &ns)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Nazwa obiektu. |
| ns | const [String](../../../system/string/)\& | Przestrzeń nazw obiektu. |

### Wartość zwracana

Wartość łańcucha znaków [XmlQualifiedName](../) w formacie **namespace:localname**. Jeśli obiekt nie ma zdefiniowanej przestrzeni nazw, ta metoda zwraca jedynie nazwę lokalną.

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XmlQualifiedName](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)