---
title: Round()
second_title: Aspose.Slides für C++ API-Referenz
description: Rundet den angegebenen Wert auf den nächsten ganzzahligen Wert.
type: docs
weight: 157
url: /de/system/math/round/
---
## Math::Round(double) Methode

Rundet den angegebenen Wert auf den nächsten ganzzahligen Wert.

```cpp
static double System::Math::Round(double a)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | **double** | Der zu rundende Wert |

### Rückgabewert

**a** gerundet auf den nächsten ganzzahligen Wert

## Math::Round(double, int) Methode

Rundet den angegebenen Wert auf den nächsten Wert mit der angegebenen Anzahl von Nachkommastellen.

```cpp
static double System::Math::Round(double value, int digits)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | **double** | Der zu rundende Wert |
| digits | int | Die Anzahl der Nachkommastellen im gerundeten Wert |

### Rückgabewert

Die Zahl mit der angegebenen Anzahl von Nachkommastellen, die **value** am nächsten liegt

## Math::Round(double, MidpointRounding) Methode

Rundet den angegebenen Wert auf die nächste ganze Zahl. Ein Parameter gibt das Verhalten der Funktion an, wenn der angegebene Wert genau zwischen zwei nächsten Zahlen liegt.

```cpp
static double System::Math::Round(double value, MidpointRounding mode)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | **double** | Der zu rundende Wert |
| mode | [MidpointRounding](../../midpointrounding/) | Gibt an, wie das Runden durchgeführt wird, wenn **value** gleichermaßen nahe an den beiden nächsten Zahlen liegt. |

### Rückgabewert

**value** gerundet auf den nächsten ganzzahligen Wert

## Math::Round(double, int, MidpointRounding) Methode

Rundet den angegebenen Wert auf den nächsten Wert mit der angegebenen Anzahl von Nachkommastellen. Ein Parameter gibt das Verhalten der Funktion an, wenn der angegebene Wert genau zwischen zwei nächsten Zahlen liegt.

```cpp
static double System::Math::Round(double value, int digits, MidpointRounding mode)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | **double** | Der zu rundende Wert |
| digits | int | Die Anzahl der Nachkommastellen im gerundeten Wert |
| mode | [MidpointRounding](../../midpointrounding/) | Gibt an, wie das Runden durchgeführt wird, wenn **value** gleichermaßen nahe an den beiden nächsten Zahlen liegt. |

### Rückgabewert

Die Zahl mit der angegebenen Anzahl von Nachkommastellen, die **value** am nächsten liegt

## Math::Round(const Decimal\&) Methode

Rundet den angegebenen Wert auf den nächsten ganzzahligen Wert.

```cpp
static Decimal System::Math::Round(const Decimal &d)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | Der zu rundende Wert |

### Rückgabewert

**d** gerundet auf den nächsten ganzzahligen Wert

## Math::Round(const Decimal\&, int) Methode

Rundet den angegebenen Wert auf den nächsten Wert mit der angegebenen Anzahl von Nachkommastellen.

```cpp
static Decimal System::Math::Round(const Decimal &value, int digits)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | Der zu rundende Wert |
| digits | int | Die Anzahl der Nachkommastellen im gerundeten Wert |

### Rückgabewert

Die Zahl mit der angegebenen Anzahl von Nachkommastellen, die **value** am nächsten liegt

## Math::Round(const Decimal\&, MidpointRounding) Methode

Rundet den angegebenen Wert auf die nächste ganze Zahl. Ein Parameter gibt das Verhalten der Funktion an, wenn der angegebene Wert genau zwischen zwei nächsten Zahlen liegt.

```cpp
static Decimal System::Math::Round(const Decimal &d, MidpointRounding mode)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | Der zu rundende Wert |
| mode | [MidpointRounding](../../midpointrounding/) | Gibt an, wie das Runden durchgeführt wird, wenn **value** gleichermaßen nahe an den beiden nächsten Zahlen liegt. |

### Rückgabewert

**d** gerundet auf den nächsten ganzzahligen Wert

## Math::Round(const Decimal\&, int, MidpointRounding) Methode

Rundet den angegebenen Wert auf den nächsten Wert mit der angegebenen Anzahl von Nachkommastellen. Ein Parameter gibt das Verhalten der Funktion an, wenn der angegebene Wert genau zwischen zwei nächsten Zahlen liegt.

```cpp
static Decimal System::Math::Round(const Decimal &d, int digits, MidpointRounding mode)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | Der zu rundende Wert |
| digits | int | Die Anzahl der Nachkommastellen im gerundeten Wert |
| mode | [MidpointRounding](../../midpointrounding/) | Gibt an, wie das Runden durchgeführt wird, wenn **value** gleichermaßen nahe an den beiden nächsten Zahlen liegt. |

### Rückgabewert

Die Zahl mit der angegebenen Anzahl von Nachkommastellen, die **value** am nächsten liegt

## Siehe auch

* Enum [MidpointRounding](../../midpointrounding/)
* Klasse [Decimal](../../decimal/)
* Struct [Math](../)
* Namensraum [System](../../)
* Library [Aspose.Slides](../../../)