---
title: MoveToAttribute()
second_title: Aspose.Slides dla C++ referencja API
description: Przechodzi do atrybutu o określonej nazwie.
type: docs
weight: 300
url: /pl/system.xml/xmlnodereader/movetoattribute/
---
## XmlNodeReader::MoveToAttribute(String) metoda


Przechodzi do atrybutu o określonej nazwie.

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [String](../../../system/string/) | W pełni kwalifikowana nazwa atrybutu. |

### Wartość zwracana

**true**, jeśli atrybut zostanie znaleziony; w przeciwnym razie **false**. Jeśli **false**, pozycja czytnika nie zmienia się.

## XmlNodeReader::MoveToAttribute(String, String) metoda


Przechodzi do atrybutu o określonej nazwie lokalnej i identyfikatorze URI przestrzeni nazw.

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name, String namespaceURI) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Lokalna nazwa atrybutu. |
| namespaceURI | [String](../../../system/string/) | Identyfikator URI przestrzeni nazw atrybutu. |

### Wartość zwracana

**true**, jeśli atrybut zostanie znaleziony; w przeciwnym razie **false**. Jeśli **false**, pozycja czytnika nie zmienia się.

## XmlNodeReader::MoveToAttribute(int32_t) metoda


Przechodzi do atrybutu o określonym indeksie.

```cpp
void System::Xml::XmlNodeReader::MoveToAttribute(int32_t attributeIndex) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| attributeIndex | **int32_t** | Indeks atrybutu. |

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XmlNodeReader](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)