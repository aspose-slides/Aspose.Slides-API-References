---
title: Sign()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt das Vorzeichen des angegebenen signierten Ganzzahlwerts.
type: docs
weight: 274
url: /de/system/math/sign/
---
## Math::Sign(T) Methode


Bestimmt das Vorzeichen des angegebenen signierten Ganzzahlwerts.

```cpp
template<typename T> static std::enable_if<std::is_integral<T>::value &&!std::is_unsigned<T>::value, int>::type System::Math::Sign(T value)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der signierte Ganzzahltyp |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | T | Der Wert, dessen Vorzeichen ermittelt werden soll |

### Rückgabewert

- 1 wenn **value** kleiner als 0 ist; 0 wenn **value** gleich 0 ist; 1 wenn **value** größer als 0 ist

## Math::Sign(T) Methode


Bestimmt das Vorzeichen des angegebenen Gleitkommawerts.

```cpp
template<typename T> static std::enable_if<std::is_floating_point<T>::value, int>::type System::Math::Sign(T value)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Gleitkommatyp des Arguments |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | T | Der Wert, dessen Vorzeichen ermittelt werden soll |

### Rückgabewert

- 1 wenn **value** kleiner als 0 ist; 0 wenn **value** gleich 0 ist; 1 wenn **value** größer als 0 ist

## Math::Sign(const Decimal\&) Methode


Bestimmt das Vorzeichen des angegebenen Dezimalwerts.

```cpp
static int System::Math::Sign(const Decimal &value)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | Der Wert, dessen Vorzeichen ermittelt werden soll |

### Rückgabewert

- 1 wenn **value** kleiner als 0 ist; 0 wenn **value** gleich 0 ist; 1 wenn **value** größer als 0 ist

## Siehe auch

* Klasse [Decimal](../../decimal/)
* Struktur [Math](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)