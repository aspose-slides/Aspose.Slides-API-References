---
title: Coalesce()
second_title: Aspose.Slides für C++ API-Referenz
description: Implementierung der Übersetzung des '??'-Operators für nicht nullable Typen.
type: docs
weight: 170
url: /de/system/objectext/coalesce/
---
## ObjectExt::Coalesce(T0, T1) Methode

Implementierung der Übersetzung des '??'-Operators für nicht nullable Typen.

```cpp
template<typename T0,typename T1> static auto System::ObjectExt::Coalesce(T0 value, T1 func)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T0 | LHS value type. |
| T1 | Type of lambda encapsulating RHS expression. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | T0 | LHS value. |
| func | T1 | RHS expression. |

### Rückgabewert

Wenn der LHS-Wert nicht null ist, wird LHS zurückgegeben, andernfalls wird der RHS-Ausdruck berechnet und das Ergebnis zurückgegeben.

## ObjectExt::Coalesce(System::Nullable\<T0\>, T1) Methode

Implementierung der Übersetzung des '??'-Operators für nullable Typen.

```cpp
template<typename T0,typename T1> static T0 System::ObjectExt::Coalesce(System::Nullable<T0> value, T1 func)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T0 | LHS value type. |
| T1 | Type of lambda encapsulating RHS expression. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [System::Nullable](../../nullable/)\<T0\> | LHS value. |
| func | T1 | RHS expression. |

### Rückgabewert

Wenn der LHS-Wert nicht null ist, wird LHS zurückgegeben, andernfalls wird der RHS-Ausdruck berechnet und das Ergebnis zurückgegeben.

## Siehe auch

* Klasse [ObjectExt](../)
* Klasse [Nullable](../../nullable/)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)