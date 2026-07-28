---
title: Equals()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Porównanie równości ciągów. Wspierane są różne tryby udostępnione przez wyliczenie StringComparison.
type: docs
weight: 391
url: /pl/system/string/equals/
---
## String::Equals(const String\&, System::StringComparison) const metoda

[String](../) porównanie równości. Wspierane są różne tryby określone przez wyliczenie StringComparison.

```cpp
bool System::String::Equals(const String &str, System::StringComparison comparison_type) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) do porównania z bieżącym. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) tryb (zobacz [System::StringComparison](../../stringcomparison/) po szczegóły). |

### Wartość zwracana

true jeśli ciągi pasują przy użyciu wybranego typu porównania, false w przeciwnym razie.

## String::Equals(const String\&) const metoda

[String](../) porównanie równości. Używa trybu porównania [System::StringComparison::Ordinal](../../stringcomparison/).

```cpp
bool System::String::Equals(const String &str) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) do porównania z bieżącym. |

### Wartość zwracana

true jeśli ciągi pasują, false w przeciwnym razie.

## String::Equals(const String\&, const String\&) metoda

Porównuje dwa ciągi przy użyciu trybu porównania Ordial.

```cpp
static bool System::String::Equals(const String &strA, const String &strB)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| strA | const [String](../)\& | Pierwszy ciąg do porównania. |
| strB | const [String](../)\& | Drugi ciąg do porównania. |

### Wartość zwracana

true jeśli ciągi pasują, false w przeciwnym razie.

## String::Equals(const String\&, const String\&, System::StringComparison) metoda

Porównuje dwa ciągi.

```cpp
static bool System::String::Equals(const String &strA, const String &strB, System::StringComparison comparison_type)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| strA | const [String](../)\& | Pierwszy ciąg do porównania. |
| strB | const [String](../)\& | Drugi ciąg do porównania. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) tryb. |

### Wartość zwracana

true jeśli ciągi pasują, false w przeciwnym razie.

## Zobacz także

* Wyliczenie [StringComparison](../../stringcomparison/)
* Klasa [String](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)