---
title: GetAttribute()
second_title: Aspose.Slides for C++ – Dokumentacja API
description: "Gdy jest przesłonięta w klasie pochodnej, pobiera wartość atrybutu o określonej wartości XmlReader::get_Name."
type: docs
weight: 599
url: /pl/system.xml/xmlreader/getattribute/
---
## XmlReader::GetAttribute(String) metoda


Gdy jest przesłonięta w klasie pochodnej, pobiera wartość atrybutu o określonej wartości [XmlReader::get_Name](../get_name/).

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Kwalifikowana nazwa atrybutu. |

### Wartość zwracana

Wartość określonego atrybutu. Jeśli atrybut nie zostanie znaleziony lub jego wartość jest [String::Empty](../../../system/string/empty/), zwracane jest **nullptr**.

## XmlReader::GetAttribute(String, String) metoda


Gdy jest przesłonięta w klasie pochodnej, pobiera wartość atrybutu o określonych wartościach [XmlReader::get_LocalName](../get_localname/) i [XmlReader::get_NamespaceURI](../get_namespaceuri/).

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name, String namespaceURI)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Lokalna nazwa atrybutu. |
| namespaceURI | [String](../../../system/string/) | URI przestrzeni nazw atrybutu. |

### Wartość zwracana

Wartość określonego atrybutu. Jeśli atrybut nie zostanie znaleziony lub jego wartość jest [String::Empty](../../../system/string/empty/), zwracane jest **nullptr**. Ta metoda nie przesuwa czytnika.

## XmlReader::GetAttribute(int32_t) metoda


Gdy jest przesłonięta w klasie pochodnej, pobiera wartość atrybutu o określonym indeksie.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(int32_t i)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| i | **int32_t** | Indeks atrybutu. Indeks jest zerowy. (Pierwszy atrybut ma indeks 0.) |

### Wartość zwracana

Wartość określonego atrybutu. Ta metoda nie przesuwa czytnika.

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XmlReader](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)