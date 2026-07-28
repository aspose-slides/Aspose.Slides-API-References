---
title: operator()()
second_title: Aspose.Slides C++ API referencia
description: Összehasonlító függvény olyan típusokhoz, amelyeknél elérhető a < operátor.
type: docs
weight: 27
url: /hu/system.collections.generic/compareradapter/operator_call/
---
## ComparerAdapter::operator()(const Q\&, const Q\&) const metódus


[Comparison](../../../system/comparison/) függvény olyan típusokhoz, amelyeknél elérhető a < operátor.

```cpp
template<typename Q> std::enable_if<detail::has_operator_less<Q>::value, bool>::type System::Collections::Generic::ComparerAdapter<T>::operator()(const Q &x, const Q &y) const
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Q | Type being compared; template for type conversion availability. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | const Q\& | First value to compare. |
| y | const Q\& | Second value to compare. |

### Visszatérési érték

Igaz, ha **x** kisebbnek tekinthető, mint **y**, egyébként hamis.

## ComparerAdapter::operator()(const Q\&, const Q\&) const metódus


[Comparison](../../../system/comparison/) függvény olyan típusokhoz, amelyeknél nem elérhető a < operátor.

```cpp
template<typename Q> std::enable_if<!detail::has_operator_less<Q>::value, bool>::type System::Collections::Generic::ComparerAdapter<T>::operator()(const Q &x, const Q &y) const
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Q | Type being compared; template for type conversion availability. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | const Q\& | First value to compare. |
| y | const Q\& | Second value to compare. |

### Visszatérési érték

Igaz, ha a komparátor be van állítva és **x** kisebbnek tekinthető, mint **y**, egyébként hamis.

## Lásd még

* Struktúra [ComparerAdapter](../)
* Névtér [System::Collections::Generic](../../)
* Könyvtár [Aspose.Slides](../../../)