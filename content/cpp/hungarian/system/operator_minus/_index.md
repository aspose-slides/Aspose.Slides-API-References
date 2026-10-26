---
title: operator-()
second_title: Aspose.Slides for C++ API referencia
description: Kiszámítja a hét két napja közötti napok számát.
type: docs
weight: 2172
url: /hu/system/operator_minus/
---
## System::operator-(DayOfWeek, DayOfWeek) függvény


Kiszámítja a két hét napja közti napok számát.

```cpp
auto System::operator-(DayOfWeek a, DayOfWeek b)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| a | [DayOfWeek](../dayofweek/) | A kivonandó |
| b | [DayOfWeek](../dayofweek/) | A kivonandó |

### Visszatérési érték

A hétköznapok **a** és **b** közötti napok száma; a visszatérési érték negatív szám, ha *goes* után ****

## System::operator-(const T\&, const Decimal\&) függvény


Visszaad egy új [Decimal](../decimal/) osztály példányt, amely egy olyan értéket képvisel, amely a megadott [Decimal](../decimal/) objektum által képviselt érték kivonásának eredménye.

```cpp
template<typename T,typename _> Decimal System::operator-(const T &x, const Decimal &d)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| x | const T\& | Az érték, amelyből kivonásra kerül |
| d | const [Decimal](../decimal/)\& | [Decimal](../decimal/) objektum, amely a kivont értéket képviseli |

### Visszatérési érték

Új [Decimal](../decimal/) osztály példány, amely egy olyan értéket képvisel, amely **x**-ből **d** által képviselt érték kivonásának eredménye.

## System::operator-(MulticastDelegate\<T\>, MulticastDelegate\<T\>) függvény


Eltávolítja az összes visszahívást a jobb oldali delegátorból a bal oldali delegáta visszahíváslistájának végéről.

```cpp
template<typename T> MulticastDelegate<T> System::operator-(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | A delegáta, amelyből a visszahívásokat eltávolítják. |
| rhv | MulticastDelegate\<T\> | A delegáta, amelynek a visszahívásait eltávolítják. |

### Visszatérési érték

Visszaad egy delegátort, amely a bal oldali érték visszahívásait tartalmazza, de a jobb oldali értékét már nem tartalmazza.

## System::operator-(const T1\&, const Nullable\<T2\>\&) függvény


Kivon nemnull és nullable értékeket.

```cpp
template<typename T1,typename T2,typename> auto System::operator-(const T1 &some, const Nullable<T2> &other) -> System::Nullable<decltype(some - other.get_Value())>
```


### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| T1 | Bal operandus típusa. |
| T2 | Jobb operandus típusa. |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| some | const T1\& | Bal operandus. |
| other | const [Nullable](../nullable/)\<T2\>\& | Jobb operandus. |

### Visszatérési érték

Kivonás eredménye.

## Lásd még

* Enum [DayOfWeek](../dayofweek/)
* osztály [Decimal](../decimal/)
* osztály [Nullable](../nullable/)
* névtér [System](../)
* Library [Aspose.Slides](../../)