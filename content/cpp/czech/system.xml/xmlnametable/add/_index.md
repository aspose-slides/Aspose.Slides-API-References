---
title: Add()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Když je přepsána v odvozené třídě, atomizuje zadaný řetězec a přidá jej do XmlNameTable.
type: docs
weight: 14
url: /cs/system.xml/xmlnametable/add/
---
## XmlNameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) metoda

Když je přepsána v odvozené třídě, atomizuje zadaný řetězec a přidá jej do [XmlNameTable](../).

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | Pole znaků obsahující název k přidání. |
| offset | **int32_t** | Nulový index do pole určující první znak názvu. |
| length | **int32_t** | Počet znaků v názvu. |

### Návratová hodnota

Nový atomizovaný řetězec nebo existující, pokud již existuje. Pokud je délka nulová, je vráceno [String::Empty](../../../system/string/empty/).

## XmlNameTable::Add(const String\&) metoda

Když je přepsána v odvozené třídě, atomizuje zadaný řetězec a přidá jej do [XmlNameTable](../).

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const String &array)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| array | const [String](../../../system/string/)\& | Název k přidání. |

### Návratová hodnota

Nový atomizovaný řetězec nebo existující, pokud již existuje.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [String](../../../system/string/)
* Třída [XmlNameTable](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)