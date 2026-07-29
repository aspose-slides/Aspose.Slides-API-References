---
title: IndexOf()
second_title: Aspose.Slides för C++ API-referens
description: Framåtsökning av delsträng.
type: docs
weight: 625
url: /sv/system/string/indexof/
---
## String::IndexOf(const String\&, System::StringComparison) const metod

Framåtsökning av delsträng.

```cpp
int System::String::IndexOf(const String &str, System::StringComparison comparison_type) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const [String](../)\& | Delsträng att söka efter. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/)-läge. |

### Returvärde

[Index](../../index/) för den först hittade delsträngen eller -1 om den inte hittas. För en tom söksträng returneras alltid 0.

## String::IndexOf(char_t, int) const metod

Framåtsökning av tecken.

```cpp
int System::String::IndexOf(char_t c, int startIndex=0) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| c | char_t | Tecken att söka efter. |
| startIndex | int | [Index](../../index/) att påbörja sökningen vid. |

### Returvärde

[Index](../../index/) för den första teckenpositionen från startIndex eller -1 om den inte hittas.

## String::IndexOf(char_t, int, int) const metod

Framåtsökning av tecken i delsträng.

```cpp
int System::String::IndexOf(char_t c, int startIndex, int count) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| c | char_t | Tecken att söka efter. |
| startIndex | int | [Index](../../index/) att påbörja sökningen vid. |
| count | int | Antal tecken att söka igenom. |

### Returvärde

[Index](../../index/) för den första teckenpositionen från startIndex eller -1 om den inte hittas.

## String::IndexOf(const String\&, int) const metod

Framåtsökning av delsträng.

```cpp
int System::String::IndexOf(const String &str, int startIndex=0) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const [String](../)\& | Delsträng att söka efter. |
| startIndex | int | Position i källsträngen att börja söka igenom. |

### Returvärde

[Index](../../index/) för den först hittade delsträngen eller -1 om den inte hittas. För en tom söksträng returneras alltid startIndex.

## String::IndexOf(const String\&, int, System::StringComparison) const metod

Framåtsökning av delsträng.

```cpp
int System::String::IndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const [String](../)\& | Delsträng att söka efter. |
| startIndex | int | Position i källsträngen att börja söka igenom. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/)-läge. |

### Returvärde

[Index](../../index/) för den först hittade delsträngen eller -1 om den inte hittas. För en tom söksträng returneras alltid startIndex.

## String::IndexOf(const String\&, int, int, System::StringComparison) const metod

Framåtsökning av delsträng.

```cpp
int System::String::IndexOf(const String &value, int startIndex, int count, System::StringComparison comparisonType) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../)\& | Delsträng att söka efter. |
| startIndex | int | Position i källsträngen att börja söka igenom. |
| count | int | antal tecken att söka igenom. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/)-läge. |

### Returvärde

[Index](../../index/) för den först hittade delsträngen eller -1 om den inte hittas. För en tom söksträng returneras alltid startIndex.

## String::IndexOf(const String\&, int, int) const metod

Framåtsökning av delsträng.

```cpp
int System::String::IndexOf(const String &str, int startIndex, int count) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const [String](../)\& | Delsträng att söka efter. |
| startIndex | int | Position i källsträngen att börja söka igenom. |
| count | int | antal tecken att söka igenom. |

### Returvärde

[Index](../../index/) för den först hittade delsträngen eller -1 om den inte hittas. För en tom söksträng returneras alltid startIndex.

## Se även

* Enum [StringComparison](../../stringcomparison/)
* Klass [String](../)
* Namnrymd [System](../../)
* Library [Aspose.Slides](../../../)