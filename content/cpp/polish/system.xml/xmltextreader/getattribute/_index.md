---
title: GetAttribute()
second_title: Odwołanie API Aspose.Slides dla C++
description: Zwraca wartość atrybutu o określonej nazwie.
type: docs
weight: 495
url: /pl/system.xml/xmltextreader/getattribute/
---
## XmlTextReader::GetAttribute(String) metoda

Zwraca wartość atrybutu o określonej nazwie.

```cpp
String System::Xml::XmlTextReader::GetAttribute(String name) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [String](../../../system/string/) | W pełni kwalifikowana nazwa atrybutu. |

### Wartość zwracana

Wartość określonego atrybutu. Jeśli atrybut nie zostanie znaleziony, zwracane jest **nullptr**.

## XmlTextReader::GetAttribute(String, String) metoda


Zwraca wartość atrybutu o określonej nazwie lokalnej i identyfikatorze URI przestrzeni nazw.

```cpp
String System::Xml::XmlTextReader::GetAttribute(String localName, String namespaceURI) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Lokalna nazwa atrybutu. |
| namespaceURI | [String](../../../system/string/) | Identyfikator URI przestrzeni nazw atrybutu. |

### Wartość zwracana

Wartość określonego atrybutu. Jeśli atrybut nie zostanie znaleziony, zwracane jest **nullptr**. Ta metoda nie przemieszcza czytnika.

## XmlTextReader::GetAttribute(int32_t) metoda


Zwraca wartość atrybutu o określonym indeksie.

```cpp
String System::Xml::XmlTextReader::GetAttribute(int32_t i) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| i | **int32_t** | Indeks atrybutu. Indeks jest zerowy. (Pierwszy atrybut ma indeks 0.) |

### Wartość zwracana

Wartość określonego atrybutu.

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XmlTextReader](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)