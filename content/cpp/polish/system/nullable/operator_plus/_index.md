---
title: operator+()
second_title: Aspose.Slides dla C++ – referencja API
description: Zwraca domyślnie skonstruowaną instancję klasy Nullable<T>.
type: docs
weight: 209
url: /pl/system/nullable/operator_plus/
---
## Nullable::operator+(std::nullptr_t) const metoda


Zwraca domyślnie skonstruowaną instancję klasy Nullable<T>.

```cpp
Nullable<T> System::Nullable<T>::operator+(std::nullptr_t) const
```

## Nullable::operator+(const T1\&) const metoda


Sumuje wartości nullable i nie-nullable.

```cpp
template<typename T1,typename> auto System::Nullable<T>::operator+(const T1 &other) const -> Nullable<decltype(get_Value()+other)>
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | Typ prawego operandu. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| other | const T1\& | wartość do dodania. |

### Wartość zwracana

Wynik sumowania.

## Nullable::operator+(const Nullable\<T1\>\&) const metoda


Sumuje wartości nullable.

```cpp
template<typename T1> auto System::Nullable<T>::operator+(const Nullable<T1> &other) const -> System::Nullable<decltype(get_Value()+other.get_Value())>
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | Typ prawego operandu. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | wartość do dodania. |

### Wartość zwracana

Wynik sumowania.

## Zobacz także

* Klasa [Nullable](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)