---
title: Compare()
second_title: Aspose.Slides pro C++ API Reference
description: Porovnává řetězce. Není implementováno.
type: docs
weight: 66
url: /cs/system.globalization/compareinfo/compare/
---
## CompareInfo::Compare(const String\&, const String\&) const metoda

Porovnává řetězce. Není implementováno.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, const String &string2) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | Řetězec na levé straně. |
| string2 | const [String](../../../system/string/)\& | Řetězec na pravé straně. |

### Návratová hodnota

Negativní hodnota, pokud řetězec vlevo předchází řetězci vpravo, nula pokud se shodují, kladná hodnota v ostatních případech.

## CompareInfo::Compare(const String\&, const String\&, CompareOptions) const metoda

Porovnává řetězce. Pouze režimy Ordinal a OrdinalIgnoreCase jsou podporovány.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &a, const String &b, CompareOptions options) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| a | const [String](../../../system/string/)\& | Řetězec na levé straně. |
| b | const [String](../../../system/string/)\& | Řetězec na pravé straně. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) typ porovnání. |

### Návratová hodnota

Negativní hodnota, pokud řetězec vlevo předchází řetězci vpravo, nula pokud se shodují, kladná hodnota v ostatních případech.

## CompareInfo::Compare(const String\&, int, int, const String\&, int, int) const metoda

Porovnává část jednoho řetězce s částí druhého řetězce. Není implementováno.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, int length1, const String &string2, int offset2, int length2) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | První řetězec. |
| offset1 | int | Počáteční index znaků v **string1**. |
| length1 | int | Počet znaků v **string1**, které se mají porovnat. |
| string2 | const [String](../../../system/string/)\& | Druhý řetězec. |
| offset2 | int | Počáteční index znaků v **string2**. |
| length2 | int | Počet znaků v **string2**, které se mají porovnat. |

### Návratová hodnota

Negativní hodnota, pokud první část řetězce předchází druhé části řetězce, nula pokud se shodují, kladná hodnota v ostatních případech.

## CompareInfo::Compare(const String\&, int, const String\&, int, CompareOptions) const metoda

Porovnává koncovou část jednoho řetězce s koncovou částí druhého řetězce pomocí metod porovnávání řetězců. Není implementováno.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, const String &string2, int offset2, CompareOptions options) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | První řetězec. |
| offset1 | int | Počáteční index znaků v **string1**. |
| string2 | const [String](../../../system/string/)\& | Druhý řetězec. |
| offset2 | int | Počáteční index znaků v **string2**. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) možnosti porovnání. |

### Návratová hodnota

Negativní hodnota, pokud první část řetězce předchází druhé části řetězce, nula pokud se shodují, kladná hodnota v ostatních případech.

## CompareInfo::Compare(const String\&, int, const String\&, int) const metoda

Porovnává koncovou část jednoho řetězce s koncovou částí druhého řetězce. Není implementováno.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, const String &string2, int offset2) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | První řetězec. |
| offset1 | int | Počáteční index znaků v **string1**. |
| string2 | const [String](../../../system/string/)\& | Druhý řetězec. |
| offset2 | int | Počáteční index znaků v **string2**. |

### Návratová hodnota

Negativní hodnota, pokud první část řetězce předchází druhé části řetězce, nula pokud se shodují, kladná hodnota v ostatních případech.

## CompareInfo::Compare(const String\&, int, int, const String\&, int, int, CompareOptions) const metoda

Porovnává část jednoho řetězce s částí druhého řetězce pomocí metod porovnávání řetězců. Není implementováno.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, int length1, const String &string2, int offset2, int length2, CompareOptions options) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | První řetězec. |
| offset1 | int | Počáteční index znaků v **string1**. |
| length1 | int | Počet znaků v **string1**, které se mají porovnat. |
| string2 | const [String](../../../system/string/)\& | Druhý řetězec. |
| offset2 | int | Počáteční index znaků v **string2**. |
| length2 | int | Počet znaků v **string2**, které se mají porovnat. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) možnosti porovnání. |

### Návratová hodnota

Negativní hodnota, pokud první část řetězce předchází druhé části řetězce, nula pokud se shodují, kladná hodnota v ostatních případech.

## Viz také

* Enum [CompareOptions](../../compareoptions/)
* Class [String](../../../system/string/)
* Class [CompareInfo](../)
* Namespace [System::Globalization](../../)
* Library [Aspose.Slides](../../../)