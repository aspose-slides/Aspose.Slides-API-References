---
title: Write()
second_title: Aspose.Slides pro C++ API Reference
description: Zapíše zadaný znak do proudu.
type: docs
weight: 40
url: /cs/system.io/stringwriter/write/
---
## StringWriter::Write(char_t) metoda


Zapíše zadaný znak do proudu.

```cpp
virtual void System::IO::StringWriter::Write(char_t value) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | char_t | Hodnota k zápisu |

## StringWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) metoda


Zapíše zadaný podrozsah znaků z určeného pole znaků do proudu.

```cpp
virtual void System::IO::StringWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Pole obsahující znaky k zápisu |
| index | **int32_t** | Index od nuly v **buffer**, kde začíná podrozsah k zápisu |
| count | **int32_t** | Počet znaků v podrozsahu k zápisu |

## StringWriter::Write(const String\&) metoda


Zapíše zadaný řetězec do proudu.

```cpp
virtual void System::IO::StringWriter::Write(const String &value) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Řetězec k zápisu |

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [StringWriter](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [System::IO](../../)
* Knihovna [Aspose.Slides](../../../)