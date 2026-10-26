---
title: Compare()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Porównuje ciągi znaków. Niezaimplementowane.
type: docs
weight: 66
url: /pl/system.globalization/compareinfo/compare/
---
## CompareInfo::Compare(const String\&, const String\&) const method

Porównuje ciągi znaków. Niezaimplementowane.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, const String &string2) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | Ciąg LHS. |
| string2 | const [String](../../../system/string/)\& | Ciąg RHS. |

### Wartość zwracana

Ujemna wartość, jeśli ciąg LHS poprzedza ciąg RHS, zero, jeśli są równe, dodatnia wartość w przeciwnym razie.

## CompareInfo::Compare(const String\&, const String\&, CompareOptions) const method

Porównuje ciągi znaków. Obsługiwane są tylko tryby Ordinal i OrdinalIgnoreCase.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &a, const String &b, CompareOptions options) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| a | const [String](../../../system/string/)\& | Ciąg LHS. |
| b | const [String](../../../system/string/)\& | Ciąg RHS. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) typ porównania. |

### Wartość zwracana

Ujemna wartość, jeśli ciąg LHS poprzedza ciąg RHS, zero, jeśli są równe, dodatnia wartość w przeciwnym razie.

## CompareInfo::Compare(const String\&, int, int, const String\&, int, int) const method

Porównuje fragment jednego ciągu znaków z fragmentem drugiego ciągu znaków. Niezaimplementowane.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, int length1, const String &string2, int offset2, int length2) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | Pierwszy ciąg. |
| offset1 | int | Indeks początkowy znaków w **string1**. |
| length1 | int | Liczba znaków w **string1**, które mają być porównane. |
| string2 | const [String](../../../system/string/)\& | Drugi ciąg. |
| offset2 | int | Indeks początkowy znaków w **string2**. |
| length2 | int | Liczba znaków w **string2**, które mają być porównane. |

### Wartość zwracana

Ujemna wartość, jeśli fragment pierwszego ciągu poprzedza fragment drugiego ciągu, zero, jeśli są równe, dodatnia wartość w przeciwnym razie.

## CompareInfo::Compare(const String\&, int, const String\&, int, CompareOptions) const method

Porównuje końcowy fragment jednego ciągu znaków z końcowym fragmentem drugiego ciągu znaków, używając metod porównywania ciągów. Niezaimplementowane.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, const String &string2, int offset2, CompareOptions options) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | Pierwszy ciąg. |
| offset1 | int | Indeks początkowy znaków w **string1**. |
| string2 | const [String](../../../system/string/)\& | Drugi ciąg. |
| offset2 | int | Indeks początkowy znaków w **string2**. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) opcje porównania. |

### Wartość zwracana

Ujemna wartość, jeśli fragment pierwszego ciągu poprzedza fragment drugiego ciągu, zero, jeśli są równe, dodatnia wartość w przeciwnym razie.

## CompareInfo::Compare(const String\&, int, const String\&, int) const method

Porównuje końcowy fragment jednego ciągu znaków z końcowym fragmentem drugiego ciągu znaków. Niezaimplementowane.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, const String &string2, int offset2) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | Pierwszy ciąg. |
| offset1 | int | Indeks początkowy znaków w **string1**. |
| string2 | const [String](../../../system/string/)\& | Drugi ciąg. |
| offset2 | int | Indeks początkowy znaków w **string2**. |

### Wartość zwracana

Ujemna wartość, jeśli fragment pierwszego ciągu poprzedza fragment drugiego ciągu, zero, jeśli są równe, dodatnia wartość w przeciwnym razie.

## CompareInfo::Compare(const String\&, int, int, const String\&, int, int, CompareOptions) const method

Porównuje fragment jednego ciągu znaków z fragmentem drugiego ciągu znaków, używając metod porównywania ciągów. Niezaimplementowane.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, int length1, const String &string2, int offset2, int length2, CompareOptions options) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | Pierwszy ciąg. |
| offset1 | int | Indeks początkowy znaków w **string1**. |
| length1 | int | Liczba znaków w **string1**, które mają być porównane. |
| string2 | const [String](../../../system/string/)\& | Drugi ciąg. |
| offset2 | int | Indeks początkowy znaków w **string2**. |
| length2 | int | Liczba znaków w **string2**, które mają być porównane. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) opcje porównania. |

### Wartość zwracana

Ujemna wartość, jeśli fragment pierwszego ciągu poprzedza fragment drugiego ciągu, zero, jeśli są równe, dodatnia wartość w przeciwnym razie.

## Zobacz także

* Enum [CompareOptions](../../compareoptions/)
* Klasa [String](../../../system/string/)
* Klasa [CompareInfo](../)
* Przestrzeń nazw [System::Globalization](../../)
* Library [Aspose.Slides](../../../)