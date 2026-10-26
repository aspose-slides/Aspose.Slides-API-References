---
title: Coalesce()
second_title: Aspose.Slides pro C++ API Reference
description: Implementace překladu operátoru '??' pro typy, které nejsou nullable.
type: docs
weight: 170
url: /cs/system/objectext/coalesce/
---
## ObjectExt::Coalesce(T0, T1) metoda

Implementace překladu operátoru '??' pro typy, které nejsou nullable.

```cpp
template<typename T0,typename T1> static auto System::ObjectExt::Coalesce(T0 value, T1 func)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T0 | LHS value type. |
| T1 | Type of lambda encapsulating RHS expression. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | T0 | LHS value. |
| func | T1 | RHS expression. |

### Návratová hodnota

Pokud není hodnota LHS null, vrátí LHS, jinak vypočítá výraz RHS a vrátí výsledek.

## ObjectExt::Coalesce(System::Nullable\<T0\>, T1) metoda

Implementace překladu operátoru '??' pro nullable typy.

```cpp
template<typename T0,typename T1> static T0 System::ObjectExt::Coalesce(System::Nullable<T0> value, T1 func)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T0 | LHS value type. |
| T1 | Type of lambda encapsulating RHS expression. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [System::Nullable](../../nullable/)\<T0\> | LHS value. |
| func | T1 | RHS expression. |

### Návratová hodnota

Pokud není hodnota LHS null, vrátí LHS, jinak vypočítá výraz RHS a vrátí výsledek.

## Viz také

* Třída [ObjectExt](../)
* Třída [Nullable](../../nullable/)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)