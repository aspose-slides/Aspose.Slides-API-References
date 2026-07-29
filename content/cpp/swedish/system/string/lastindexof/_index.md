---
title: LastIndexOf()
second_title: Aspose.Slides för C++ API-referens
description: Bakåtsökning av delsträng.
type: docs
weight: 651
url: /sv/system/string/lastindexof/
---
## String::LastIndexOf(const String\&, int) const metod


Bakåtsökning av delsträng.

```cpp
int System::String::LastIndexOf(const String &str, int startIndex=INT32_MAX) const
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const [String](../)\& | Delsträng att söka efter. |
| startIndex | int | Position i källsträngen där sökningen ska börja. |

### Returvärde

[Index](../../index/) av den senast hittade delsträngen eller -1 om den inte hittas. För en tom uppslagssträng returneras alltid stränglängden.

## String::LastIndexOf(const String\&, System::StringComparison) const metod


Bakåtsökning av delsträng.

```cpp
int System::String::LastIndexOf(const String &str, System::StringComparison comparison_type) const
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const [String](../)\& | Delsträng att söka efter. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) läge. |

### Returvärde

[Index](../../index/) av den senast hittade delsträngen eller -1 om den inte hittas. För en tom uppslagssträng returneras alltid stränglängden.

## String::LastIndexOf(const String\&, int, System::StringComparison) const metod


Bakåtsökning av delsträng.

```cpp
int System::String::LastIndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const [String](../)\& | Delsträng att söka efter. |
| startIndex | int | Position i källsträngen där sökningen ska börja. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) läge. |

### Returvärde

[Index](../../index/) av den senast hittade delsträngen eller -1 om den inte hittas. För en tom uppslagssträng returneras alltid stränglängden.

## String::LastIndexOf(const String\&, int, int, StringComparison) const metod


Bakåtsökning av delsträng.

```cpp
int System::String::LastIndexOf(const String &value, int startIndex, int count, StringComparison comparisonType) const
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../)\& | Delsträng att söka efter. |
| startIndex | int | Position i källsträngen där sökningen ska börja. |
| count | int | Antal tecken att söka igenom. |
| comparisonType | [StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) läge. |

### Returvärde

[Index](../../index/) av den senast hittade delsträngen eller -1 om den inte hittas. För en tom uppslagssträng returneras alltid startIndex+count.

## String::LastIndexOf(char_t) const metod


Bakåtsökning av tecken.

```cpp
int System::String::LastIndexOf(char_t value) const
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | char_t | Tecken att söka efter. |

### Returvärde

[Index](../../index/) av den senast hittade teckenpositionen eller -1 om den inte hittas.

## String::LastIndexOf(char_t, int32_t) const metod


Bakåtsökning av tecken.

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex) const
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | char_t | Tecken att söka efter. |
| startIndex | **int32_t** | [Index](../../index/) att starta sökningen vid. |

### Returvärde

[Index](../../index/) av den senast hittade teckenpositionen sedan startIndex eller -1 om den inte hittas.

## String::LastIndexOf(char_t, int32_t, int32_t) const metod


Bakåtsökning av tecken.

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex, int32_t count) const
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | char_t | Tecken att söka efter. |
| startIndex | **int32_t** | [Index](../../index/) att starta sökningen vid. |
| count | **int32_t** | Antal tecken att söka igenom |

### Returvärde

[Index](../../index/) av den senast hittade teckenpositionen sedan startIndex eller -1 om den inte hittas.

## Se också

* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)