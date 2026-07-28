---
title: operator>()
second_title: Aspose.Slides C++ API referenciája
description: 
type: docs
weight: 2120
url: /hu/system/operator_greater/
---
## System::operator>(std::nullptr_t, DateTime) függvény

```cpp
constexpr bool System::operator>(std::nullptr_t, DateTime)
```

## System::operator>(std::nullptr_t, const DateTimeOffset\&) függvény

```cpp
constexpr bool System::operator>(std::nullptr_t, const DateTimeOffset &)
```

## System::operator>(std::nullptr_t, const Nullable\<T\>\&) függvény

Mindig hamis értéket ad vissza.

```cpp
template<typename T> bool System::operator>(std::nullptr_t, const Nullable<T> &)
```

## System::operator>(const T1\&, const Nullable\<T2\>\&) függvény

Meghatározza, hogy a megadott érték nagyobb-e, mint a megadott [Nullable](../nullable/) objektummal reprezentált érték, a [operator>()](./) alkalmazásával ezekre az értékekre.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator>(const T1 &some, const Nullable<T2> &other)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | Az első összehasonlított érték típusa |
| T2 | A [Nullable](../nullable/) objektum alaptípusa, amely a második összehasonlított értéket képviseli |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| some | const T1\& | Az első összehasonlítottként használandó érték konstans referenciája |
| other | const [Nullable](../nullable/)\<T2\>\& | A [Nullable](../nullable/) objektum konstans referenciája, amelynek a reprezentált értékét a második összehasonlítottként kell használni |

### Visszatérési érték

Igaz, ha az első összehasonlított nagyobb a második összehasonlítottnál, egyébként - hamis

## System::operator>(std::nullptr_t, TimeSpan) függvény

```cpp
constexpr bool System::operator>(std::nullptr_t, TimeSpan)
```

## Lásd még

* Osztály [DateTime](../datetime/)
* Osztály [DateTimeOffset](../datetimeoffset/)
* Osztály [Nullable](../nullable/)
* Osztály [TimeSpan](../timespan/)
* Struktúra [IsNullable](../isnullable/)
* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)