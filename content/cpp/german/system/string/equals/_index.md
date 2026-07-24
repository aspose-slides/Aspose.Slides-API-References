---
title: Equals()
second_title: Aspose.Slides für C++ API-Referenz
description: String-Gleichheitsvergleich. Mehrere Modi, die von der Aufzählung StringComparison bereitgestellt werden, werden unterstützt.
type: docs
weight: 391
url: /de/system/string/equals/
---
## String::Equals(const String\&, System::StringComparison) const Methode

[String](../) Gleichheitsvergleich. Mehrere Modi, die von der Aufzählung StringComparison bereitgestellt werden, werden unterstützt.

```cpp
bool System::String::Equals(const String &str, System::StringComparison comparison_type) const
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) zum Vergleich mit dem aktuellen. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) Modus (siehe [System::StringComparison](../../stringcomparison/) für Details). |

### Return Value

true, wenn die Zeichenketten mit dem ausgewählten Vergleichstyp übereinstimmen, andernfalls false.

## String::Equals(const String\&) const Methode

[String](../) Gleichheitsvergleich. Verwendet den [System::StringComparison::Ordinal](../../stringcomparison/) Vergleichsmodus.

```cpp
bool System::String::Equals(const String &str) const
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) zum Vergleich mit dem aktuellen. |

### Return Value

true, wenn die Zeichenketten übereinstimmen, andernfalls false.

## String::Equals(const String\&, const String\&) Methode

Gleichheitsvergleich zweier Zeichenketten mit dem Ordial-Vergleichsmodus.

```cpp
static bool System::String::Equals(const String &strA, const String &strB)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | Erste Zeichenkette zum Vergleichen. |
| strB | const [String](../)\& | Zweite Zeichenkette zum Vergleichen. |

### Return Value

true, wenn die Zeichenketten übereinstimmen, andernfalls false.

## String::Equals(const String\&, const String\&, System::StringComparison) Methode

Vergleicht zwei Zeichenketten.

```cpp
static bool System::String::Equals(const String &strA, const String &strB, System::StringComparison comparison_type)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | Erste Zeichenkette zum Vergleichen. |
| strB | const [String](../)\& | Zweite Zeichenkette zum Vergleichen. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) Modus. |

### Return Value

true, wenn die Zeichenketten übereinstimmen, andernfalls false.

## Siehe Auch

* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)