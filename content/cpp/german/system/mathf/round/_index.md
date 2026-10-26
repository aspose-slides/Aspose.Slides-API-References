---
title: Round()
second_title: Aspose.Slides für C++ API Referenz
description: Rundet den angegebenen Wert auf den nächsten ganzzahligen Wert.
type: docs
weight: 157
url: /de/system/mathf/round/
---
## MathF::Round(float) Methode

Rundet den angegebenen Wert auf den nächsten ganzzahligen Wert.

```cpp
static float System::MathF::Round(float a)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | **float** | Der zu rundende Wert |

### Rückgabewert

**a** gerundet auf den nächsten ganzzahligen Wert

## MathF::Round(float, int) Methode

Rundet den angegebenen Wert auf den nächsten Wert mit der angegebenen Anzahl von Nachkommastellen.

```cpp
static float System::MathF::Round(float value, int digits)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | **float** | Der zu rundende Wert |
| digits | int | Die Anzahl der Nachkommastellen im gerundeten Wert |

### Rückgabewert

Die Zahl mit der angegebenen Stellenanzahl, die **value** am nächsten liegt

## MathF::Round(float, MidpointRounding) Methode

Rundet den angegebenen Wert auf die nächste ganze Zahl. Ein Parameter gibt das Verhalten der Funktion an, wenn der angegebene Wert gleichweit von zwei nächsten Zahlen entfernt ist.

```cpp
static float System::MathF::Round(float value, MidpointRounding mode)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | **float** | Der zu rundende Wert |
| mode | [MidpointRounding](../../midpointrounding/) | Gibt an, wie das Runden durchgeführt wird, wenn **value** gleichweit von zwei nächsten Zahlen entfernt ist. |

### Rückgabewert

**value** gerundet auf den nächsten ganzzahligen Wert

## MathF::Round(float, int, MidpointRounding) Methode

Rundet den angegebenen Wert auf den nächsten Wert mit der angegebenen Anzahl von Nachkommastellen. Ein Parameter gibt das Verhalten der Funktion an, wenn der angegebene Wert gleichweit von zwei nächsten Zahlen entfernt ist.

```cpp
static float System::MathF::Round(float value, int digits, MidpointRounding mode)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | **float** | Der zu rundende Wert |
| digits | int | Die Anzahl der Nachkommastellen im gerundeten Wert |
| mode | [MidpointRounding](../../midpointrounding/) | Gibt an, wie das Runden durchgeführt wird, wenn **value** gleichweit von zwei nächsten Zahlen entfernt ist. |

### Rückgabewert

Die Zahl mit der angegebenen Stellenanzahl, die **value** am nächsten liegt

## Siehe auch

* Enum [MidpointRounding](../../midpointrounding/)
* Struktur [MathF](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)