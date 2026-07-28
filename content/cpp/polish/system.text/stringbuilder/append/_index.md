---
title: Append()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Dodaje znak do buildera.
type: docs
weight: 118
url: /pl/system.text/stringbuilder/append/
---
## StringBuilder::Append(char_t) metoda


Dodaje znak do buildera.

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| c | char_t | Character value. |

### Wartość zwracana

Ten wskaźnik.

## StringBuilder::Append(char_t, int) metoda


Dodaje znaki do buildera.

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c, int count)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| c | char_t | Character value. |
| count | int | Ile razy powtórzyć wstawiany znak. |

### Wartość zwracana

Ten wskaźnik.

## StringBuilder::Append(const ArrayPtr\<char_t\>\&) metoda


Dodaje tablicę znaków do buildera.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| arr | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Znaki do dodania. |

### Wartość zwracana

Ten wskaźnik.

## StringBuilder::Append(const ArrayPtr\<char_t\>\&, int, int) metoda


Dodaje wycinek tablicy znaków do buildera.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr, int startIndex, int charCount)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| arr | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Znaki do dodania. |
| startIndex | int | Indeks początkowy wycinka. |
| charCount | int | Długość wycinka. |

### Wartość zwracana

Ten wskaźnik.

## StringBuilder::Append(const String\&) metoda


Dodaje ciąg znaków do buildera.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) do dodania. |

### Wartość zwracana

Ten wskaźnik.

## StringBuilder::Append(const String\&, int, int) metoda


Dodaje wycinek ciągu znaków do buildera.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str, int startIndex, int charCount)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) do dodania. |
| startIndex | int | Indeks początkowy wycinka. |
| charCount | int | Długość wycinka. |

### Wartość zwracana

Ten wskaźnik.

## StringBuilder::Append(const SharedPtr\<T\>\&) metoda


Dodaje reprezentację łańcucha obiektu do buildera.

```cpp
template<class T> StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<T> &obj)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | [Object](../../../system/object/) typ. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<T\>\& | [Object](../../../system/object/) do serializacji i dodania. |

### Wartość zwracana

Ten wskaźnik.

## StringBuilder::Append(const SharedPtr\<StringBuilder\>\&) metoda


Dodaje zawartość buildera do buildera.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<StringBuilder> &builder)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| builder | const [SharedPtr](../../../system/sharedptr/)\<[StringBuilder](../)\>\& | Builder, z którego dodać zawartość. |

### Wartość zwracana

Ten wskaźnik.

## StringBuilder::Append(float) metoda


Dodaje wartość zmiennoprzecinkową do buildera.

```cpp
StringBuilder * System::Text::StringBuilder::Append(float f)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| f | **float** | Wartość do serializacji i dodania. |

### Wartość zwracana

Ten wskaźnik.

## StringBuilder::Append(double) metoda


Dodaje wartość zmiennoprzecinkową do buildera.

```cpp
StringBuilder * System::Text::StringBuilder::Append(double df)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| df | **double** | Wartość do serializacji i dodania. |

### Wartość zwracana

Ten wskaźnik.

## StringBuilder::Append(int) metoda


Dodaje wartość całkowitą do buildera.

```cpp
StringBuilder * System::Text::StringBuilder::Append(int i)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| i | int | Wartość do serializacji i dodania. |

### Wartość zwracana

Ten wskaźnik.

## StringBuilder::Append(T) metoda


Dodaje wartość arytmetyczną do buildera.

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Append(T value)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ arytmetyczny. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | T | Wartość do serializacji i dodania. |

### Wartość zwracana

Ten wskaźnik.

## StringBuilder::Append(E) metoda


Dodaje reprezentację łańcucha wartości wyliczeniowej do buildera.

```cpp
template<class E> std::enable_if<std::is_enum<E>::value, StringBuilder *>::type System::Text::StringBuilder::Append(E e)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| E | [Enum](../../../system/enum/) typ. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| e | E | Wartość do serializacji i dodania. |

### Wartość zwracana

Ten wskaźnik.

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [StringBuilder](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [System::Text](../../)
* Biblioteka [Aspose.Slides](../../../)