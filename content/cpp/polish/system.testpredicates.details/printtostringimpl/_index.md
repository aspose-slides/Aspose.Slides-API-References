---
title: PrintToStringImpl()
second_title: Aspose.Slides dla C++: Dokumentacja API
description: "Wypisuje podklasę System::Object do łańcucha znaków przy użyciu metody ToString()."
type: docs
weight: 14
url: /pl/system.testpredicates.details/printtostringimpl/
---
## System::TestPredicates::Details::PrintToStringImpl(const SharedPtr\<T\>\&, long long) funkcja


Wypisuje podklasę [System::Object](../../system/object/) do łańcucha znaków przy użyciu metody ToString().

```cpp
template<typename T> std::enable_if<System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const SharedPtr<T> &value, long long s)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Końcowy typ klasy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [SharedPtr](../../system/sharedptr/)\<T\>\& | Wskaźnik na obiekt do wypisania. |
| s | long long | Parametr usługowy służący jako selektor przeciążenia funkcji w zależności od typu tego parametru; wartość parametru jest ignorowana |

### Wartość zwracana

[String](../../system/string/) reprezentacja przekazanego obiektu lub "nullptr", jeśli **value** jest null.

## System::TestPredicates::Details::PrintToStringImpl(const WeakPtr\<T\>\&, long long) funkcja


Wypisuje podklasę [System::Object](../../system/object/) do łańcucha znaków przy użyciu metody ToString().

```cpp
template<typename T> std::enable_if<System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const WeakPtr<T> &value, long long s)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Końcowy typ klasy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [WeakPtr](../../system/weakptr/)\<T\>\& | Wskaźnik na obiekt do wypisania. |
| s | long long | Parametr usługowy służący jako selektor przeciążenia funkcji w zależności od typu tego parametru; wartość parametru jest ignorowana |

### Wartość zwracana

[String](../../system/string/) reprezentacja przekazanego obiektu lub "nullptr", jeśli **value** jest null.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) funkcja


Wypisuje obiekt do łańcucha znaków przy użyciu metody ToString().

```cpp
template<typename T> std::enable_if<!TypeTraits::has_print_to_method<T>::value &&System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ [Object](../../system/object/). |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) do wypisania. |
| s | long long | Parametr usługowy służący jako selektor przeciążenia funkcji w zależności od typu tego parametru; wartość parametru jest ignorowana |

### Wartość zwracana

[String](../../system/string/) reprezentacja przekazanego obiektu.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) funkcja


Wypisuje obiekt do łańcucha znaków przy użyciu metody PrintTo.

```cpp
template<typename T> std::enable_if<TypeTraits::has_print_to_method<T>::value &&!TypeTraits::IsEnumerable<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ [Object](../../system/object/). |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) do wypisania. |
| s | long long | Parametr usługowy służący jako selektor przeciążenia funkcji w zależności od typu tego parametru; wartość parametru jest ignorowana |

### Wartość zwracana

[String](../../system/string/) reprezentacja przekazanego obiektu.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) funkcja


Wypisuje obiekt do łańcucha znaków przy użyciu metody PrintTo.

```cpp
template<typename T> std::enable_if<TypeTraits::has_print_to_method<T>::value &&TypeTraits::IsEnumerable<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ [Object](../../system/object/). |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) do wypisania. |
| s | long long | Parametr usługowy służący jako selektor przeciążenia funkcji w zależności od typu tego parametru; wartość parametru jest ignorowana |

### Wartość zwracana

[String](../../system/string/) reprezentacja przekazanego obiektu.

## System::TestPredicates::Details::PrintToStringImpl(const std::pair\<T1, T2\>\&, long long) funkcja


Wypisuje parę do łańcucha znaków.

```cpp
template<typename T1,typename T2> std::string System::TestPredicates::Details::PrintToStringImpl(const std::pair<T1, T2> &value, long long s)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | Pierwszy typ argumentu pary. |
| T2 | Drugi typ argumentu pary. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const std::pair\<T1, T2\>\& | [Object](../../system/object/) do wypisania. |
| s | long long | Parametr usługowy służący jako selektor przeciążenia funkcji w zależności od typu tego parametru; wartość parametru jest ignorowana |

### Wartość zwracana

Połączone reprezentacje łańcuchowe obu komponentów pary: pierwszego i drugiego.

## System::TestPredicates::Details::PrintToStringImpl(const Collections::Generic::KeyValuePair\<T1, T2\>\&, long long) funkcja


Wypisuje parę do łańcucha znaków.

```cpp
template<typename T1,typename T2> std::string System::TestPredicates::Details::PrintToStringImpl(const Collections::Generic::KeyValuePair<T1, T2> &value, long long s)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | Pierwszy typ argumentu pary. |
| T2 | Drugi typ argumentu pary. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<T1, T2\>\& | [Object](../../system/object/) do wypisania. |
| s | long long | Parametr usługowy służący jako selektor przeciążenia funkcji w zależności od typu tego parametru; wartość parametru jest ignorowana |

### Wartość zwracana

Połączone reprezentacje łańcuchowe obu komponentów pary: pierwszego i drugiego.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) funkcja


Wypisuje kontenery w stylu STL do łańcucha znaków, wypisując ich elementy (nie więcej niż 32).

```cpp
template<typename T> std::enable_if<TypeTraits::IsCppContainer<T>::value &&!std::is_base_of<Object, T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &container, long long s)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ [Object](../../system/object/). |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| container | const T\& | [Object](../../system/object/) do wypisania. |
| s | long long | Parametr usługowy służący jako selektor przeciążenia funkcji w zależności od typu tego parametru; wartość parametru jest ignorowana |

### Wartość zwracana

Połączone reprezentacje łańcuchowe zawartych elementów.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, int) funkcja


Wypisuje inne typy do łańcucha znaków przy użyciu funkcji dostarczonych przez gtest.

```cpp
template<typename T> std::string System::TestPredicates::Details::PrintToStringImpl(const T &value, int s)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ [Object](../../system/object/). |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) do wypisania. |
| s | int | Parametr usługowy służący jako selektor przeciążenia funkcji w zależności od typu tego parametru; wartość parametru jest ignorowana |

### Wartość zwracana

[String](../../system/string/) reprezentacje przekazanego obiektu.

## Zobacz także

* Definicja typu [SharedPtr](../../system/sharedptr/)
* Klasa [WeakPtr](../../system/weakptr/)
* Klasa [KeyValuePair](../../system.collections.generic/keyvaluepair/)
* Klasa [Object](../../system/object/)
* Struktura [has_print_to_method](../../system.testpredicates.typetraits/has_print_to_method/)
* Struktura [IsEnumerable](../../system.testpredicates.typetraits/isenumerable/)
* Struktura [IsCppContainer](../../system.testpredicates.typetraits/iscppcontainer/)
* Przestrzeń nazw [System::TestPredicates::Details](../)
* Biblioteka [Aspose.Slides](../../)