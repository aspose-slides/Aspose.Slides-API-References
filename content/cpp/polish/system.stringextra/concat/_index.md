---
title: Concat()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Łączy tablicę łańcuchów.
type: docs
weight: 1
url: /pl/system.stringextra/concat/
---
## System::StringExtra::Concat(const ArrayPtr\<String\>\&) funkcja


Łączy tablicę łańcuchów.

```cpp
String System::StringExtra::Concat(const ArrayPtr<String> &parts)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| parts | const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\& | [Array](../../system/array/) łańcuchów do połączenia. |

### Wartość zwracana

Połączony ciąg znaków.

## System::StringExtra::Concat(const String\&, const String\&) funkcja


Łączy łańcuchy znaków.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | Pierwszy łańcuch do połączenia. |
| str1 | const [String](../../system/string/)\& | Drugi łańcuch do połączenia. |

### Wartość zwracana

Połączone łańcuchy parametrów.

## System::StringExtra::Concat(const String\&, const String\&, const String\&) funkcja


Łączy łańcuchy znaków.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1, const String &str2)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | Pierwszy łańcuch do połączenia. |
| str1 | const [String](../../system/string/)\& | Drugi łańcuch do połączenia. |
| str2 | const [String](../../system/string/)\& | Trzeci łańcuch do połączenia. |

### Wartość zwracana

Połączone łańcuchy parametrów.

## System::StringExtra::Concat(const String\&, const String\&, const String\&, const String\&) funkcja


Łączy łańcuchy znaków.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1, const String &str2, const String &str3)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | Pierwszy łańcuch do połączenia. |
| str1 | const [String](../../system/string/)\& | Drugi łańcuch do połączenia. |
| str2 | const [String](../../system/string/)\& | Trzeci łańcuch do połączenia. |
| str3 | const [String](../../system/string/)\& | Czwarty łańcuch do połączenia. |

### Wartość zwracana

Połączone łańcuchy parametrów.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) funkcja


Konwertuje wiele obiektów na łańcuch i łączy powstałe łańcuchy. Specjalizacja dla [SmartPtr](../../system/smartptr/) typów.

```cpp
template<typename T> std::enable_if_t<IsSmartPtr<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) do konwersji i połączenia. |

### Wartość zwracana

Wartość [String](../../system/string/) połączona z reprezentacjami łańcuchowymi wszystkich przekazanych obiektów.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) funkcja


Konwertuje wiele obiektów na łańcuch i łączy powstałe łańcuchy. Specjalizacja dla typów arytmetycznych.

```cpp
template<typename T> std::enable_if_t<std::is_arithmetic<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) do konwersji i połączenia. |

### Wartość zwracana

Wartość [String](../../system/string/) połączona z reprezentacjami łańcuchowymi wszystkich przekazanych obiektów.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) funkcja


Konwertuje wiele obiektów na łańcuch i łączy powstałe łańcuchy. Specjalizacja dla struktur i innych typów wartościowych.

```cpp
template<typename T> std::enable_if_t<!IsSmartPtr<T>::value &&!std::is_arithmetic<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) do konwersji i połączenia. |

### Wartość zwracana

Wartość [String](../../system/string/) połączona z reprezentacjami łańcuchowymi wszystkich przekazanych obiektów.

## Zobacz także

* Typedef [ArrayPtr](../../system/arrayptr/)
* Klasa [String](../../system/string/)
* Struktura [IsSmartPtr](../../system/issmartptr/)
* Przestrzeń nazw [System::StringExtra](../)
* Biblioteka [Aspose.Slides](../../)