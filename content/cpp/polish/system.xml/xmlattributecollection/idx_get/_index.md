---
title: idx_get()
second_title: Aspose.Slides for C++ – odniesienie API
description: Zwraca atrybut o podanym indeksie.
type: docs
weight: 1
url: /pl/system.xml/xmlattributecollection/idx_get/
---
## XmlAttributeCollection::idx_get(int32_t) metoda


Zwraca atrybut o podanym indeksie.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(int32_t i)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| i | **int32_t** | Indeks atrybutu. |

### Wartość zwracana

Atrybut o podanym indeksie.

## XmlAttributeCollection::idx_get(const String\&) metoda


Zwraca atrybut o podanej nazwie.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &name)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | W pełni kwalifikowana nazwa atrybutu. |

### Wartość zwracana

Atrybut o podanej nazwie. Jeśli atrybut nie istnieje, metoda zwraca **nullptr**.

## XmlAttributeCollection::idx_get(const String\&, const String\&) metoda


Zwraca atrybut o podanej nazwie lokalnej i identyfikatorze zasobu Uniform Resource Identifier (URI) przestrzeni nazw.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &localName, const String &namespaceURI)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Lokalna nazwa atrybutu. |
| namespaceURI | const [String](../../../system/string/)\& | URI przestrzeni nazw atrybutu. |

### Wartość zwracana

Atrybut o podanej nazwie lokalnej i URI przestrzeni nazw. Jeśli atrybut nie istnieje, metoda zwraca **nullptr**.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlAttribute](../../xmlattribute/)
* Klasa [XmlAttributeCollection](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)