---
title: Compare()
second_title: Aspose.Slides för C++ API-referens
description: Mindre-lika-större jämför två delsträngar.
type: docs
weight: 820
url: /sv/system/string/compare/
---
## String::Compare(const String\&, int, const String\&, int, int, bool) metod

Mindre-lika-större jämför två delsträngar.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, bool ignoreCase=false)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| strA | const [String](../)\& | Första strängen att jämföra. |
| indexA | int | Början av första strängens delsträng. |
| strB | const [String](../)\& | Andra strängen att jämföra. |
| indexB | int | Början av andra strängens delsträng. |
| length | int | Antal tecken att jämföra. |
| ignoreCase | **bool** | Anger om jämförelsen är skiftlägesokänslig. |

### Returvärde

Negativt värde om den första delsträngen är mindre än den andra, noll om de matchar, positivt värde annars.

## String::Compare(const String\&, int, const String\&, int, int, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) metod

Mindre-lika-större jämför två delsträngar.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &ci)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| strA | const [String](../)\& | Första strängen att jämföra. |
| indexA | int | Början av första strängens delsträng. |
| strB | const [String](../)\& | Andra strängen att jämföra. |
| indexB | int | Början av andra strängens delsträng. |
| length | int | Antal tecken att jämföra. |
| ignoreCase | **bool** | Anger om jämförelsen är skiftlägesokänslig. |
| ci | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Kultur att använda för jämförelsen. |

### Returvärde

Negativt värde om den första delsträngen är mindre än den andra, noll om de matchar, positivt värde annars.

## String::Compare(const String\&, const String\&, System::StringComparison) metod

Mindre-lika-större jämför två strängar.

```cpp
static int System::String::Compare(const String &strA, const String &strB, System::StringComparison comparison_type)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| strA | const [String](../)\& | Första strängen att jämföra. |
| strB | const [String](../)\& | Andra strängen att jämföra. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) läge. |

### Returvärde

Negativt värde om den första delsträngen är mindre än den andra, noll om de matchar, positivt värde annars.

## String::Compare(const String\&, int, const String\&, int, int, System::StringComparison) metod

Mindre-lika-större jämför två strängar.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, System::StringComparison comparison_type)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| strA | const [String](../)\& | Första strängen att jämföra. |
| indexA | int | Början av första strängens delsträng. |
| strB | const [String](../)\& | Andra strängen att jämföra. |
| indexB | int | Början av andra strängens delsträng. |
| length | int | Antal tecken att jämföra. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) läge. |

### Returvärde

Negativt värde om den första delsträngen är mindre än den andra, noll om de matchar, positivt värde annars.

## String::Compare(const String\&, const String\&, bool) metod

Mindre-lika-större jämför två strängar.

```cpp
static int System::String::Compare(const String &strA, const String &strB, bool ignoreCase=false)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| strA | const [String](../)\& | Första strängen att jämföra. |
| strB | const [String](../)\& | Andra strängen att jämföra. |
| ignoreCase | **bool** | Anger om jämförelsen är skiftlägesokänslig. |

### Returvärde

Negativt värde om den första delsträngen är mindre än den andra, noll om de matchar, positivt värde annars.

## String::Compare(const String\&, const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) metod

Mindre-lika-större jämför två strängar.

```cpp
static int System::String::Compare(const String &strA, const String &strB, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &ci)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| strA | const [String](../)\& | Första strängen att jämföra. |
| strB | const [String](../)\& | Andra strängen att jämföra. |
| ignoreCase | **bool** | Anger om jämförelsen är skiftlägesokänslig. |
| ci | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Kultur att använda för jämförelsen. |

### Returvärde

Negativt värde om den första delsträngen är mindre än den andra, noll om de matchar, positivt värde annars.

## Se även

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Klass [String](../)
* Klass [CultureInfo](../../../system.globalization/cultureinfo/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)