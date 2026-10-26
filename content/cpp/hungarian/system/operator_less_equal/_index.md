---
title: operator<=()
second_title: Aspose.Slides C++ API referenciája
description: 
type: docs
weight: 2107
url: /hu/system/operator_less_equal/
---
## System::operator<=(std::nullptr_t, DateTime) függvény




```cpp
constexpr bool System::operator<=(std::nullptr_t, DateTime)
```

## System::operator<=(std::nullptr_t, const DateTimeOffset\&) függvény




```cpp
constexpr bool System::operator<=(std::nullptr_t, const DateTimeOffset &)
```

## System::operator<=(std::nullptr_t, const Nullable\<T\>\&) függvény


Mindig false értéket ad vissza.

```cpp
template<typename T> bool System::operator<=(std::nullptr_t, const Nullable<T> &)
```

## System::operator<=(const T1\&, const Nullable\<T2\>\&) függvény


Meghatározza, hogy a megadott érték kisebb-e vagy egyenlő a megadott [Nullable](../nullable/) objektum által képviselt értékkel, a [operator<=()](./) alkalmazásával ezekre az értékekre.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator<=(const T1 &some, const Nullable<T2> &other)
```


### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| T1 | Az első összehasonlított érték típusa |
| T2 | A [Nullable](../nullable/) objektum alapjául szolgáló típus, amely a második összehasonlított értéket képviseli |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| some | const T1\& | A konstans referenciája az értéknek, amelyet az első összehasonlítottként kell használni |
| other | const [Nullable](../nullable/)\<T2\>\& | A konstans referenciája a [Nullable](../nullable/) objektumra, amelynek képviselt értéke a második összehasonlítottként lesz használva |

### Visszatérési érték

True, ha az első összehasonlított kisebb vagy egyenlő a második összehasonlítottal, egyébként - false

## System::operator<=(std::nullptr_t, TimeSpan) függvény




```cpp
constexpr bool System::operator<=(std::nullptr_t, TimeSpan)
```

## Lásd még

* Class [DateTime](../datetime/)
* Class [DateTimeOffset](../datetimeoffset/)
* Class [Nullable](../nullable/)
* Class [TimeSpan](../timespan/)
* Struct [IsNullable](../isnullable/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)