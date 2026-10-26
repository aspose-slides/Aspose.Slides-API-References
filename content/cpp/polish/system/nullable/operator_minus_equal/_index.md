---
title: operator-=()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Zwraca instancję klasy Nullable, która reprezentuje wartość null.
type: docs
weight: 248
url: /pl/system/nullable/operator_minus_equal/
---
## Nullable::operator-=(T1) metoda


Zwraca instancję klasy [Nullable](../), która reprezentuje wartość null.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-=(T1)
```

## Nullable::operator-=(const T1\&) metoda


Zastosowuje [operator-=()](./) do wartości reprezentowanej przez bieżący obiekt, używając określonej wartości jako argumentu po prawej stronie.

```cpp
template<typename T1,typename> std::enable_if<!IsNullable<T1>::value, Nullable<T>>::type System::Nullable<T>::operator-=(const T1 &other)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | Typ wartości używanej jako wartość po prawej stronie [operator-=()](./) |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| other | const T1\& | Stała referencja do wartości, która jest używana jako wartość po prawej stronie [operator-=()](./) zastosowanego do wartości reprezentowanej przez bieżący obiekt. |

### Wartość zwracana

Referencja do samego siebie

## Nullable::operator-=(const Nullable\<T1\>\&) metoda


Zastosowuje [operator-=()](./) do wartości reprezentowanej przez bieżący obiekt, używając wartości reprezentowanej przez określony obiekt [Nullable](../) jako argumentu po prawej stronie.

```cpp
template<typename T1> Nullable<T> System::Nullable<T>::operator-=(const Nullable<T1> &other)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | Podstawowy typ obiektu [Nullable](../), którego wartość jest używana jako argument po prawej stronie [operator-=()](./) |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Stała referencja do obiektu [Nullable](../), którego wartość jest używana jako argument po prawej stronie [operator-=()](./) zastosowanego do wartości reprezentowanej przez bieżący obiekt. |

### Wartość zwracana

Referencja do samego siebie

## Zobacz także

* Klasa [Nullable](../)
* Struktura [IsNullable](../../isnullable/)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)