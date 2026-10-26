---
title: Unbox()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Rozpakowuje typy wartości po konwersji do Object. Implementacja dla typów wyliczeniowych.
type: docs
weight: 53
url: /pl/system/objectext/unbox/
---
## ObjectExt::Unbox(const SmartPtr\<Object\>\&) metoda


Rozpakowuje typy wartości po konwersji do [Object](../../object/). Implementacja dla typów wyliczeniowych.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | [Enum](../../enum/) typ. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) do odpakowania. |

### Wartość zwracana

[Enum](../../enum/) wartość.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) metoda


Rozpakowuje typy wartości po konwersji do [Object](../../object/). Implementacja dla typów nie-enum i nie-nulowalnych.

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ wartości. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) do odpakowania. |

### Wartość zwracana

Wartość odpakowana.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) metoda


Rozpakowuje typy wartości po konwersji do [Object](../../object/). Implementacja dla typów nie-enum i nie-nulowalnych.

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ wartości. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) do odpakowania. |

### Wartość zwracana

Wartość odpakowana.

## ObjectExt::Unbox(E) metoda


Rozpakowuje typy wyliczeniowe do liczby całkowitej.

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::numeric_limits<T>::is_integer, T>::type System::ObjectExt::Unbox(E e)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ docelowy liczby całkowitej. |
| E | Typ źródłowy wyliczeniowy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| e | E | Wartość do odpakowania. |

### Wartość zwracana

Reprezentacja całkowita wyliczenia.

## ObjectExt::Unbox(E) metoda


Konwertuje typy wyliczeniowe.

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(E e)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ docelowy wyliczeniowy. |
| E | Typ źródłowy wyliczeniowy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| e | E | Wartość do odpakowania. |

### Wartość zwracana

Skonwertowana wartość wyliczenia.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) metoda


Rozpakowuje wartości ciągów znaków.

```cpp
String System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) do odpakowania |

### Wartość zwracana

[String](../../string/) reprezentacja zapakowanego ciągu znaków, może być null jeśli zapakowany ciąg był null.

## Zobacz także

* Klasa [SmartPtr](../../smartptr/)
* Klasa [Object](../../object/)
* Klasa [ObjectExt](../)
* Klasa [String](../../string/)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)