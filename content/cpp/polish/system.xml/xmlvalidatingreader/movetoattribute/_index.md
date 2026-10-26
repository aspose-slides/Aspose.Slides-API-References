---
title: MoveToAttribute()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Przechodzi do atrybutu o określonej nazwie.
type: docs
weight: 456
url: /pl/system.xml/xmlvalidatingreader/movetoattribute/
---
## XmlValidatingReader::MoveToAttribute(String) metoda

Przechodzi do atrybutu o określonej nazwie.

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String name) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [String](../../../system/string/) | W pełni kwalifikowana nazwa atrybutu. |

### Wartość zwracana

**true** jeśli atrybut zostanie znaleziony; w przeciwnym razie **false**. Jeśli **false**, pozycja czytnika nie ulega zmianie.

## XmlValidatingReader::MoveToAttribute(String, String) metoda

Przechodzi do atrybutu o określonej nazwie lokalnej i Uniform Resource Identifier (URI) przestrzeni nazw.

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String localName, String namespaceURI) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Lokalna nazwa atrybutu. |
| namespaceURI | [String](../../../system/string/) | URI przestrzeni nazw atrybutu. |

### Wartość zwracana

**true** jeśli atrybut zostanie znaleziony; w przeciwnym razie **false**. Jeśli **false**, pozycja czytnika nie ulega zmianie.

## XmlValidatingReader::MoveToAttribute(int32_t) metoda

Przechodzi do atrybutu o określonym indeksie.

```cpp
void System::Xml::XmlValidatingReader::MoveToAttribute(int32_t i) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| i | **int32_t** | Indeks atrybutu. |

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XmlValidatingReader](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)