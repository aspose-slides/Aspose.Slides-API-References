---
title: operator<()
second_title: Aspose.Slides dla C++ - odniesienie API
description: 
type: docs
weight: 2094
url: /pl/system/operator_less/
---
## System::operator<(std::nullptr_t, DateTime) funkcja




```cpp
constexpr bool System::operator<(std::nullptr_t, DateTime)
```

## System::operator<(std::nullptr_t, const DateTimeOffset\&) funkcja




```cpp
constexpr bool System::operator<(std::nullptr_t, const DateTimeOffset &)
```

## System::operator<(std::nullptr_t, const Nullable\<T\>\&) funkcja


Zawsze zwraca false.

```cpp
template<typename T> bool System::operator<(std::nullptr_t, const Nullable<T> &)
```

## System::operator<(const T1\&, const Nullable\<T2\>\&) funkcja


Określa, czy podana wartość jest mniejsza od wartości reprezentowanej przez określony obiekt [Nullable](../nullable/) poprzez zastosowanie [operator<()](./) do tych wartości.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator<(const T1 &some, const Nullable<T2> &other)
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| T1 | Typ pierwszej wartości porównywanej |
| T2 | Podstawowy typ obiektu [Nullable](../nullable/), który reprezentuje drugą wartość porównywaną |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| some | const T1\& | Stałe odniesienie do wartości, która ma być użyta jako pierwsza wartość porównywana |
| other | const [Nullable](../nullable/)\<T2\>\& | Stałe odniesienie do obiektu [Nullable](../nullable/), którego reprezentowana wartość ma być użyta jako druga wartość porównywana |

### Wartość zwracana

True jeśli pierwsza wartość porównywana jest mniejsza od drugiej wartości porównywanej, w przeciwnym razie - false

## System::operator<(std::nullptr_t, TimeSpan) funkcja




```cpp
constexpr bool System::operator<(std::nullptr_t, TimeSpan)
```

## Zobacz także

* Klasa [DateTime](../datetime/)
* Klasa [DateTimeOffset](../datetimeoffset/)
* Klasa [Nullable](../nullable/)
* Klasa [TimeSpan](../timespan/)
* Struktura [IsNullable](../isnullable/)
* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)