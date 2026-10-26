---
title: operator!=()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Określa, czy wartość reprezentowana przez bieżący obiekt nie jest nullem.
type: docs
weight: 144
url: /pl/system/nullable/operator_not_equal/
---
## Nullable::operator!=(std::nullptr_t) const metoda


Określa, czy wartość reprezentowana przez bieżący obiekt nie jest nullem.

```cpp
bool System::Nullable<T>::operator!=(std::nullptr_t) const
```


### Wartość zwracana

True jeśli wartość reprezentowana przez bieżący obiekt nie jest nullem, w przeciwnym razie - false

## Nullable::operator!=(const T1\&) const metoda


Określa, czy wartość reprezentowana przez bieżący obiekt nie jest równa podanej wartości.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator!=(const T1 &other) const
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | Typ wartości, z którą porównywany jest obiekt |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| other | const T1\& | Stała referencja do wartości, z którą porównywany jest obiekt |

### Wartość zwracana

True jeśli wartość reprezentowana przez bieżący obiekt nie jest równa podanej wartości, w przeciwnym razie - false

## Nullable::operator!=(const Nullable\<T1\>\&) const metoda


Określa, czy wartość reprezentowana przez bieżący obiekt nie jest równa wartości reprezentowanej przez podany obiekt [Nullable](../).

```cpp
template<typename T1> bool System::Nullable<T>::operator!=(const Nullable<T1> &other) const
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | Podstawowy typ obiektu [Nullable](../), z którym porównywany jest obiekt |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Stała referencja do obiektu [Nullable](../), z którym porównywany jest obiekt |

### Wartość zwracana

True jeśli wartość reprezentowana przez bieżący obiekt nie jest równa wartości reprezentowanej przez podany obiekt [Nullable](../), w przeciwnym razie - false

## Zobacz także

* Klasa [Nullable](../)
* Struktura [IsNullable](../../isnullable/)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)