---
title: DoTryFinally()
second_title: Aspose.Slides for C++ API referencia
description: Az egyetlen függvény, amely a C# try[-catch]-finally utasítás viselkedését utánozza. A C# try[-catch]-finally utasítás fordítása során, ha a fordító opciója a finally_statement_as_lambda beállítása igaz, az utasítás ezzel a metódus hívással kerül lefordításra.
type: docs
weight: 2445
url: /hu/system/dotryfinally/
---
## System::DoTryFinally(T\&&, F\&&) függvény


Az egyetlen függvény, amely a C#'s try[-catch]-finally utasítás viselkedését utánozza. A C#'s try[-catch]-finally utasítás fordítása során, ha a fordító opciója a finally_statement_as_lambda true értékre van állítva, az utasítás ezzel a metódus hívással kerül lefordításra.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_void<T>::value> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A függvényobjektum típusa, amely a try[-catch] részt valósítja meg az emulált try[-catch]-finally utasításban |
| F | A függvényobjektum típusa, amely a finally részt valósítja meg az emulált try[-catch]-finally utasításban |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| tryBlock | T\&& | A függvényobjektum, amelynek törzse tartalmazza a try[-catch] rész megvalósítását az emulált try[-catch]-finally utasításban |
| finallyBlock | F\&& | A függvényobjektum, amelynek törzse tartalmazza a finally rész megvalósítását az emulált try[-catch]-finally utasításban |

## System::DoTryFinally(T\&&, F\&&) függvény


Az egyetlen függvény, amely a C#'s try[-catch]-finally utasítás viselkedését utánozza. A C#'s try[-catch]-finally utasítás fordítása során, ha a fordító opciója a finally_statement_as_lambda true értékre van állítva, az utasítás ezzel a metódus hívással kerül lefordításra. Ez a túlterhelés azt az esetet kezeli, amikor a try[-catch] részt megvalósító függvényobjektum visszatérési értéke bool.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_boolref<T>::value, bool> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A függvényobjektum típusa, amely a try[-catch] részt valósítja meg az emulált try[-catch]-finally utasításban |
| F | A függvényobjektum típusa, amely a finally részt valósítja meg az emulált try[-catch]-finally utasításban |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| tryBlock | T\&& | A függvényobjektum, amelynek törzse tartalmazza a try[-catch] rész megvalósítását az emulált try[-catch]-finally utasításban |
| finallyBlock | F\&& | A függvényobjektum, amelynek törzse tartalmazza a finally rész megvalósítását az emulált try[-catch]-finally utasításban |

## System::DoTryFinally(T\&&, F\&&) függvény


Az egyetlen függvény, amely a C#'s try[-catch]-finally utasítás viselkedését utánozza. A C#'s try[-catch]-finally utasítás fordítása során, ha a fordító opciója a finally_statement_as_lambda true értékre van állítva, az utasítás ezzel a metódus hívással kerül lefordításra. Ez a túlterhelés azt az esetet kezeli, amikor a try[-catch] részt megvalósító függvényobjektum visszatérési értéke bool&.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_nonovoid_boolref<T>::value, std::optional<Details::ResultOf<T, bool &>>> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A függvényobjektum típusa, amely a try[-catch] részt valósítja meg az emulált try[-catch]-finally utasításban |
| F | A függvényobjektum típusa, amely a finally részt valósítja meg az emulált try[-catch]-finally utasításban |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| tryBlock | T\&& | A függvényobjektum, amelynek törzse tartalmazza a try[-catch] rész megvalósítását az emulált try[-catch]-finally utasításban |
| finallyBlock | F\&& | A függvényobjektum, amelynek törzse tartalmazza a finally rész megvalósítását az emulált try[-catch]-finally utasításban |

## Lásd még

* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)