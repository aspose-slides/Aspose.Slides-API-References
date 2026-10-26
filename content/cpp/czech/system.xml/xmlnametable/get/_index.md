---
title: Get()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Při přepsání v odvozené třídě získá atomizovaný řetězec obsahující stejné znaky jako určený rozsah znaků v daném poli.
type: docs
weight: 1
url: /cs/system.xml/xmlnametable/get/
---
## XmlNameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) metoda

Při přepsání v odvozené třídě získá atomizovaný řetězec obsahující stejné znaky jako určený rozsah znaků v daném poli.

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | Pole znaků obsahující název, který se má vyhledat. |
| offset | **int32_t** | Index v poli začínající od nuly určuje první znak názvu. |
| length | **int32_t** | Počet znaků v názvu. |

### Návratová hodnota

Atomizovaný řetězec nebo **nullptr**, pokud řetězec ještě nebyl atomizován. Pokud je **length** nula, je vráceno [String::Empty](../../../system/string/empty/).

## XmlNameTable::Get(const String\&) metoda

Při přepsání v odvozené třídě získá atomizovaný řetězec obsahující stejnou hodnotu jako zadaný řetězec.

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const String &array)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| array | const [String](../../../system/string/)\& | Název, který se má vyhledat. |

### Návratová hodnota

Atomizovaný řetězec nebo **nullptr**, pokud řetězec ještě nebyl atomizován.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [String](../../../system/string/)
* Třída [XmlNameTable](../)
* Jmenný prostor [System::Xml](../../)
* Library [Aspose.Slides](../../../)