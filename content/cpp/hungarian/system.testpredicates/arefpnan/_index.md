---
title: AreFPNaN()
second_title: Aspose.Slides for C++ API-referencia
description: Névtér részletek
type: docs
weight: 1
url: /hu/system.testpredicates/arefpnan/
---
## System::TestPredicates::AreFPNaN(T1, T2) függvény


névtér [Details](../../system.testpredicates.details/)

```cpp
template<typename T1,typename T2> std::enable_if<std::numeric_limits<T1>::has_quiet_NaN &&std::numeric_limits<T2>::has_quiet_NaN, bool>::type System::TestPredicates::AreFPNaN(T1 lhs, T2 rhs)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | Első lebegőpontos típus. |
| T2 | Második lebegőpontos típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs | T1 | Első lebegőpontos érték. |
| rhs | T2 | Második lebegőpontos érték. |

### Visszatérési érték

Igaz, ha mind a **lhs**, mind a **rhs** lebegőpontos érték, hamis egyébként.
## Megjegyzések


Ellenőrzi, hogy két lebegőpontos érték is NaN-e. Kezeli azt az esetet, amikor a nem jelző NaN támogatott. 
## System::TestPredicates::AreFPNaN(T1, T2) függvény


Ellenőrzi, hogy két lebegőpontos érték is NaN-e. Kezeli azt az esetet, amikor a nem jelző NaN nem támogatott.

```cpp
template<typename T1,typename T2> std::enable_if<!std::numeric_limits<T1>::has_quiet_NaN||!std::numeric_limits<T2>::has_quiet_NaN, bool>::type System::TestPredicates::AreFPNaN(T1 lhs, T2 rhs)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | Első lebegőpontos típus. |
| T2 | Második lebegőpontos típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs | T1 | Első lebegőpontos érték. |
| rhs | T2 | Második lebegőpontos érték. |

### Visszatérési érték

Mindig hamis értékkel tér vissza, mivel a NaN érték nem támogatott.

## Lásd még

* Névtér [System::TestPredicates](../)
* Könyvtár [Aspose.Slides](../../)