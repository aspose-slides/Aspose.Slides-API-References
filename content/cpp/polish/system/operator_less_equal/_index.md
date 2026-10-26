---
title: operator<=()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description:
type: docs
weight: 2107
url: /pl/system/operator_less_equal/
---
## System::operator<=(std::nullptr_t, DateTime) funkcja




```cpp
constexpr bool System::operator<=(std::nullptr_t, DateTime)
```

## System::operator<=(std::nullptr_t, const DateTimeOffset\&) funkcja




```cpp
constexpr bool System::operator<=(std::nullptr_t, const DateTimeOffset &)
```

## System::operator<=(std::nullptr_t, const Nullable\<T\>\&) funkcja


Zawsze zwraca false.

```cpp
template<typename T> bool System::operator<=(std::nullptr_t, const Nullable<T> &)
```

## System::operator<=(const T1\&, const Nullable\<T2\>\&) funkcja


Określa, czy podana wartość jest mniejsza lub równa wartości reprezentowanej przez określony obiekt [Nullable](../nullable/) poprzez zastosowanie [operator<=()](./) do tych wartości.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator<=(const T1 &some, const Nullable<T2> &other)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | Typ pierwszego porównywanego elementu |
| T2 | Podstawowy typ obiektu [Nullable](../nullable/) reprezentującego drugą porównywaną wartość |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| some | const T1\& | Stała referencja do wartości, która ma być użyta jako pierwszy porównywany element |
| other | const [Nullable](../nullable/)\<T2\>\& | Stała referencja do obiektu [Nullable](../nullable/), którego reprezentowana wartość ma być użyta jako drugi porównywany element |

### Wartość zwracana

True, jeśli pierwszy porównywany element jest mniejszy lub równy drugiemu, w przeciwnym razie - false

## System::operator<=(std::nullptr_t, TimeSpan) funkcja




```cpp
constexpr bool System::operator<=(std::nullptr_t, TimeSpan)
```

## Zobacz także

* Klasa [DateTime](../datetime/)
* Klasa [DateTimeOffset](../datetimeoffset/)
* Klasa [Nullable](../nullable/)
* Klasa [TimeSpan](../timespan/)
* Struktura [IsNullable](../isnullable/)
* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)