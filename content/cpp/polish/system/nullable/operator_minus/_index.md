---
title: operator-()
second_title: Aspose.Slides dla C++ – Odniesienie API
description: Odejmuje wartości nullable i wartości null-pointerowe.
type: docs
weight: 222
url: /pl/system/nullable/operator_minus/
---
## Nullable::operator-(T1) const metoda


Odejmuje wartości nullable i null-pointerowe.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-(T1) const
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | Typ prawego operanda, powinien być nullptr_t. |

### Wartość zwracana

Pusty obiekt [Nullable](../).

## Nullable::operator-(const T1&) const metoda


Odejmuje wartości nullable i nie-nullable.

```cpp
template<typename T1,typename> auto System::Nullable<T>::operator-(const T1 &other) const -> Nullable<decltype(get_Value() - other)>
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | Typ prawego operanda. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| other | const T1& | wartość do odjęcia. |

### Wartość zwracana

Wynik odejmowania.

## Nullable::operator-(const Nullable<T1>&) const metoda


Odejmuje wartości nullable.

```cpp
template<typename T1> auto System::Nullable<T>::operator-(const Nullable<T1> &other) const -> System::Nullable<decltype(get_Value() - other.get_Value())>
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | Typ prawego operanda. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| other | const [Nullable](../)<T1>& | wartość do odjęcia. |

### Wartość zwracana

Wynik odejmowania.

## Zobacz także

* Klasa [Nullable](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)