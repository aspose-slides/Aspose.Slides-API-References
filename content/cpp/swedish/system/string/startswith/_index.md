---
title: StartsWith()
second_title: Aspose.Slides för C++ API-referens
description: Kontrollerar om strängen börjar med den angivna delsträngen.
type: docs
weight: 469
url: /sv/system/string/startswith/
---
## String::StartsWith(const String\&) const method

Kontrollerar om strängen börjar med den angivna delsträngen.

```cpp
bool System::String::StartsWith(const String &value) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../)\& | Söksträng. |

### Returvärde

true om strängen börjar med den angivna delsträngen, false annars.

## String::StartsWith(const String\&, System::StringComparison) const method

Kontrollerar om strängen börjar med den angivna delsträngen.

```cpp
bool System::String::StartsWith(const String &value, System::StringComparison comparisonType) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../)\& | Söksträng. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) läge, se [System::StringComparison](../../stringcomparison/) för detaljer. |

### Returvärde

true om strängen börjar med den angivna delsträngen, false annars.

## String::StartsWith(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const method

Kontrollerar om strängen börjar med den angivna delsträngen.

```cpp
bool System::String::StartsWith(const String &value, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &culture=nullptr) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../)\& | Söksträng. |
| ignoreCase | **bool** | Anger om jämförelsen är skiftlägesokänslig. |
| culture | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Kultur som används vid strängjämförelse. |

### Returvärde

true om strängen börjar med den angivna delsträngen, false annars.

## Se även

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Klass [String](../)
* Klass [CultureInfo](../../../system.globalization/cultureinfo/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)