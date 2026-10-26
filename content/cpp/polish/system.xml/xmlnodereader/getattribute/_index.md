---
title: GetAttribute()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Zwraca wartość atrybutu o podanej nazwie.
type: docs
weight: 287
url: /pl/system.xml/xmlnodereader/getattribute/
---
## XmlNodeReader::GetAttribute(String) metoda

Zwraca wartość atrybutu o podanej nazwie.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [String](../../../system/string/) | W pełni kwalifikowana nazwa atrybutu. |

### Wartość zwracana

Wartość podanego atrybutu. Jeśli atrybut nie zostanie znaleziony, **nullptr** zostanie zwrócony.

## XmlNodeReader::GetAttribute(String, String) metoda

Zwraca wartość atrybutu o podanej nazwie lokalnej i identyfikatorze URI przestrzeni nazw.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name, String namespaceURI) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Lokalna nazwa atrybutu. |
| namespaceURI | [String](../../../system/string/) | Identyfikator URI przestrzeni nazw atrybutu. |

### Wartość zwracana

Wartość podanego atrybutu. Jeśli atrybut nie zostanie znaleziony, **nullptr** zostanie zwrócony.

## XmlNodeReader::GetAttribute(int32_t) metoda

Zwraca wartość atrybutu o podanym indeksie.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(int32_t attributeIndex) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| attributeIndex | **int32_t** | Indeks atrybutu. Indeks jest zerowo-bazowany. (Pierwszy atrybut ma indeks 0.) |

### Wartość zwracana

Wartość podanego atrybutu.

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XmlNodeReader](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)