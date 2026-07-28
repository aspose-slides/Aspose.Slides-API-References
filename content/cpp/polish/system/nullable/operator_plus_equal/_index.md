---
title: operator+=()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Resetuje bieżący obiekt, aby reprezentował wartość null.
type: docs
weight: 235
url: /pl/system/nullable/operator_plus_equal/
---
## Nullable::operator+=(std::nullptr_t) metoda

Resetuje bieżący obiekt tak, aby reprezentował wartość null.

```cpp
Nullable<T> System::Nullable<T>::operator+=(std::nullptr_t)
```

### Return Value

Kopia obiektu

## Nullable::operator+=(const T1\&) metoda

Stosuje [operator+=()](./) do wartości reprezentowanej przez bieżący obiekt, używając podanej wartości jako argumentu po prawej stronie.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, Nullable<T>>::type System::Nullable<T>::operator+=(const T1 &other)
```

### Template parameters

| Parametr | Opis |
| --- | --- |
| T1 | Typ wartości używanej jako wartość po prawej stronie [operator+=()](./) |

### Arguments

| Parametr | Typ | Opis |
| --- | --- | --- |
| other | const T1\& | Stała referencja do wartości, która jest używana jako wartość po prawej stronie [operator+=()](./) zastosowanego do wartości reprezentowanej przez bieżący obiekt. |

### Return Value

Referencja do obiektu

## Nullable::operator+=(const Nullable\<T1\>\&) metoda

Stosuje [operator+=()](./) do wartości reprezentowanej przez bieżący obiekt, używając wartości reprezentowanej przez określony obiekt [Nullable](../) jako argumentu po prawej stronie.

```cpp
template<typename T1> Nullable<T> System::Nullable<T>::operator+=(const Nullable<T1> &other)
```

### Template parameters

| Parametr | Opis |
| --- | --- |
| T1 | Podstawowy typ obiektu [Nullable](../), którego wartość jest używana jako argument po prawej stronie [operator+=()](./) |

### Arguments

| Parametr | Typ | Opis |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Stała referencja do obiektu [Nullable](../), którego wartość jest używana jako argument po prawej stronie [operator+=()](./) zastosowanego do wartości reprezentowanej przez bieżący obiekt. |

### Return Value

Referencja do obiektu

## See Also

* Klasa [Nullable](../)
* Struktura [IsNullable](../../isnullable/)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)