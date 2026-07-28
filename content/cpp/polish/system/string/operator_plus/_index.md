---
title: operator+()
second_title: Aspose.Slides dla C++ – Referencja API
description: Operator konkatenacji ciągów.
type: docs
weight: 274
url: /pl/system/string/operator_plus/
---
## String::operator+(const String\&) const method


[String](../) operator konkatenacji.

```cpp
String System::String::operator+(const String &str) const
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) do dodania na koniec aktualnego. |

### Wartość zwracana

Połączony ciąg znaków.

## String::operator+(const T\&) const method


[String](../) konkatenacja z literałem łańcucha znaków lub wskaźnikiem na łańcuch znaków.

```cpp
template<typename T,std::enable_if_t< IsStringLiteral< T, char_t >::value > *> String System::String::operator+(const T &arg) const
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Jedna z form literału łańcucha znaków lub wskaźnika na łańcuch znaków. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| arg | const T\& | Obiekt do konkatenacji z bieżącym łańcuchem. |

### Wartość zwracana

Połączony ciąg znaków.

## String::operator+(char_t) const method


Dodaje znak na koniec łańcucha.

```cpp
String System::String::operator+(char_t x) const
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | char_t | Znak do dodania. |

### Wartość zwracana

[String](../) wynik konkatenacji.

## String::operator+(int) const method


Dodaje reprezentację ciągu znaków wartości całkowitej na koniec łańcucha.

```cpp
String System::String::operator+(int i) const
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| i | int | Wartość całkowita do konwersji na ciąg znaków i dodania. |

### Wartość zwracana

[String](../) wynik konkatenacji.

## String::operator+(uint32_t) const method


Dodaje reprezentację ciągu znaków wartości liczby całkowitej bez znaku na koniec łańcucha.

```cpp
String System::String::operator+(uint32_t i) const
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| i | **uint32_t** | Wartość do konwersji na ciąg znaków i dodania. |

### Wartość zwracana

[String](../) wynik konkatenacji.

## String::operator+(double) const method


Dodaje reprezentację ciągu znaków wartości zmiennoprzecinkowej na koniec łańcucha.

```cpp
String System::String::operator+(double d) const
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| d | **double** | Wartość do konwersji na ciąg znaków i dodania. |

### Wartość zwracana

[String](../) wynik konkatenacji.

## String::operator+(int64_t) const method


Dodaje reprezentację ciągu znaków wartości całkowitej na koniec łańcucha.

```cpp
String System::String::operator+(int64_t v) const
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| v | **int64_t** | Wartość do konwersji na ciąg znaków i dodania. |

### Wartość zwracana

[String](../) wynik konkatenacji.

## String::operator+(const T\&) const method


Dodaje reprezentację ciągu znaków obiektu typu referencyjnego na koniec łańcucha.

```cpp
template<typename T,std::enable_if_t< IsSmartPtr< T >::value > *> String System::String::operator+(const T &value) const
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | typ wskaźnika. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) do konwersji na ciąg znaków przy użyciu wywołania [ToString()](../tostring/) i dodania do bieżącego łańcucha. |

### Wartość zwracana

[String](../) wynik konkatenacji.

## String::operator+(const T\&) const method


Dodaje reprezentację ciągu znaków obiektu typu wartościowego na koniec łańcucha.

```cpp
template<typename T,std::enable_if_t<!IsSmartPtr< T >::value &&!std::is_scalar< T >::value &&!std::is_array< T >::value > *> String System::String::operator+(const T &value) const
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ wartościowy, na którym wywołuje się [ToString()](../tostring/). |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) do konwersji na ciąg znaków przy użyciu wywołania [ToString()](../tostring/) i dodania do bieżącego łańcucha. |

### Wartość zwracana

[String](../) wynik konkatenacji.

## String::operator+(T) const method


Dodaje reprezentację ciągu znaków wartości boolowskiej na koniec łańcucha.

```cpp
template<typename T,std::enable_if_t< std::is_same< T, bool >::value > *> String System::String::operator+(T arg) const
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ wartościowy do konkatenacji z łańcuchem. Musi być bool |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| arg | T | [Boolean](../../boolean/) wartość do konwersji na ciąg znaków i dodania. |

### Wartość zwracana

[String](../) wynik konkatenacji.

## Zobacz także

* Klasa [String](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)