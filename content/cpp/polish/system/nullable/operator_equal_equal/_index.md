---
title: operator==()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Określa, czy wartość reprezentowana przez bieżący obiekt jest null.
type: docs
weight: 118
url: /pl/system/nullable/operator_equal_equal/
---
## Nullable::operator==(std::nullptr_t) const metoda


Określa, czy wartość reprezentowana przez bieżący obiekt jest równa null.

```cpp
bool System::Nullable<T>::operator==(std::nullptr_t) const
```


### Wartość zwracana

True jeśli wartość reprezentowana przez bieżący obiekt jest równa null, w przeciwnym razie - false

## Nullable::operator==(const T1\&) const metoda


Określa, czy wartość reprezentowana przez bieżący obiekt jest równa określonej wartości.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator==(const T1 &other) const
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | Typ wartości, z którą należy porównać |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| other | const T1\& | Stała referencja do wartości, z którą należy porównać |

### Wartość zwracana

True jeśli wartość reprezentowana przez bieżący obiekt jest równa określonej wartości, w przeciwnym razie - false

## Nullable::operator==(const Nullable\<T1\>\&) const metoda


Określa, czy wartość reprezentowana przez bieżący obiekt jest równa wartości reprezentowanej przez określony [Nullable](../) obiekt.

```cpp
template<typename T1> bool System::Nullable<T>::operator==(const Nullable<T1> &other) const
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | Podstawowy typ obiektu [Nullable](../), z którym należy porównać |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Stała referencja do obiektu [Nullable](../), z którym należy porównać |

### Wartość zwracana

True jeśli wartość reprezentowana przez bieżący obiekt jest równa wartości reprezentowanej przez określony [Nullable](../) obiekt, w przeciwnym razie - false

## Zobacz także

* Klasa [Nullable](../)
* Struktura [IsNullable](../../isnullable/)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)