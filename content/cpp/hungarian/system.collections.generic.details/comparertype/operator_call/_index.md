---
title: operator()()
second_title: Aspose.Slides for C++ API referencia
description: Összehasonlítja az IComparable interfészt megvalósító értéktípusokat.
type: docs
weight: 1
url: /hu/system.collections.generic.details/comparertype/operator_call/
---
## ComparerType::operator()(const Q\&, const Q\&) const metódus

Összehasonlítja a [IComparable](../../../system/icomparable/) interfészt megvalósító értéktípusokat.

```cpp
template<typename Q> std::enable_if<std::is_base_of<System::IComparable<Q>, Q>::value||has_method_compareto<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Q | A összehasonlítandó típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| a | const Q\& | Bal oldal értéke. |
| b | const Q\& | Jobb oldal értéke. |

### Visszatérési érték

Igaz, ha **a** kisebbnek tekinthető, mint **b**, hamis egyébként.

## ComparerType::operator()(const Q\&, const Q\&) const metódus

Összehasonlítja az alapvető értéktípusokat és azokat az objektumokat, amelyek nem valósítják meg a [IComparable](../../../system/icomparable/) interfészt.

```cpp
template<typename Q> std::enable_if<!(std::is_base_of<IComparable<Q>, Q>::value||has_method_compareto<Q>::value)&&!std::is_floating_point<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Q | A összehasonlítandó típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| a | const Q\& | Bal oldal értéke. |
| b | const Q\& | Jobb oldal értéke. |

### Visszatérési érték

Igaz, ha **a** kisebbnek tekinthető, mint **b**, hamis egyébként.

## ComparerType::operator()(const Q\&, const Q\&) const metódus

Összehasonlítja a lebegőpontos típusokat.

```cpp
template<typename Q> std::enable_if<std::is_floating_point<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Q | A összehasonlítandó típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| a | const Q\& | Bal oldal értéke. |
| b | const Q\& | Jobb oldal értéke. |

### Visszatérési érték

Igaz, ha **a** kisebbnek tekinthető, mint **b**, hamis egyébként.

## Lásd még

* Osztály [IComparable](../../../system/icomparable/)
* Struktúra [has_method_compareto](../../has_method_compareto/)
* Struktúra [ComparerType](../)
* Névtér [System::Collections::Generic::Details](../../)
* Könyvtár [Aspose.Slides](../../../)