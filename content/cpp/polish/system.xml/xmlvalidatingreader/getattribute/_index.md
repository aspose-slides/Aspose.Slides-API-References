---
title: GetAttribute()
second_title: Aspose.Slides dla C++ Referencja API
description: Zwraca wartość atrybutu o określonej nazwie.
type: docs
weight: 443
url: /pl/system.xml/xmlvalidatingreader/getattribute/
---
## XmlValidatingReader::GetAttribute(String) metoda

Zwraca wartość atrybutu o określonej nazwie.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(String name) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [String](../../../system/string/) | W pełni kwalifikowana nazwa atrybutu. |

### Wartość zwracana

Wartość określonego atrybutu. Jeśli atrybut nie zostanie znaleziony, **nullptr** jest zwracany.

## XmlValidatingReader::GetAttribute(String, String) metoda

Zwraca wartość atrybutu o określonej nazwie lokalnej i Uniform Resource Identifier (URI) przestrzeni nazw.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(String localName, String namespaceURI) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Lokalna nazwa atrybutu. |
| namespaceURI | [String](../../../system/string/) | URI przestrzeni nazw atrybutu. |

### Wartość zwracana

Wartość określonego atrybutu. Jeśli atrybut nie zostanie znaleziony, **nullptr** jest zwracany. Ta metoda nie przemieszcza czytnika.

## XmlValidatingReader::GetAttribute(int32_t) metoda

Zwraca wartość atrybutu o określonym indeksie.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(int32_t i) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| i | **int32_t** | Indeks atrybutu. Indeks jest zerowo-bazowy. (Pierwszy atrybut ma indeks 0.) |

### Wartość zwracana

Wartość określonego atrybutu.

## Zobacz także

* Class [String](../../../system/string/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)