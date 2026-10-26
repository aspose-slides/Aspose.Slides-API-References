---
title: Sign()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt das Vorzeichen des angegebenen vorzeichenbehafteten Ganzzahlwerts.
type: docs
weight: 274
url: /de/system/mathf/sign/
---
## MathF::Sign(T) Methode


Bestimmt das Vorzeichen des angegebenen vorzeichenbehafteten Ganzzahlwerts.

```cpp
template<typename T> static std::enable_if<std::is_integral<T>::value &&!std::is_unsigned<T>::value, int>::type System::MathF::Sign(T value)
```


### Vorlagenparameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der vorzeichenbehaftete Ganzzahltyp |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | T | Der Wert, dessen Vorzeichen ermittelt werden soll |

### Rückgabewert

- 1, wenn **value** kleiner als 0 ist; 0, wenn **value** gleich 0 ist; 1, wenn **value** größer als 0 ist

## MathF::Sign(T) Methode


Bestimmt das Vorzeichen des angegebenen Fließkommawerts.

```cpp
template<typename T> static std::enable_if<std::is_floating_point<T>::value, int>::type System::MathF::Sign(T value)
```


### Vorlagenparameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Fließkommatyp des Arguments |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | T | Der Wert, dessen Vorzeichen ermittelt werden soll |

### Rückgabewert

- 1, wenn **value** kleiner als 0 ist; 0, wenn **value** gleich 0 ist; 1, wenn **value** größer als 0 ist

## Siehe auch

* Struct [MathF](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)