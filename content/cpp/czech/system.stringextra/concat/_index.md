---
title: Concat()
second_title: Reference API Aspose.Slides pro C++
description: Spojuje pole řetězců.
type: docs
weight: 1
url: /cs/system.stringextra/concat/
---
## System::StringExtra::Concat(const ArrayPtr\<String\>\&) funkce


Spojuje pole řetězců.

```cpp
String System::StringExtra::Concat(const ArrayPtr<String> &parts)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| parts | const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\& | [Array](../../system/array/) řetězců ke spojení. |

### Návratová hodnota

Spojený řetězec.

## System::StringExtra::Concat(const String\&, const String\&) funkce


Spojuje řetězce.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | První řetězec ke spojení. |
| str1 | const [String](../../system/string/)\& | Druhý řetězec ke spojení. |

### Návratová hodnota

Spojené řetězce parametrů.

## System::StringExtra::Concat(const String\&, const String\&, const String\&) funkce


Spojuje řetězce.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1, const String &str2)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | První řetězec ke spojení. |
| str1 | const [String](../../system/string/)\& | Druhý řetězec ke spojení. |
| str2 | const [String](../../system/string/)\& | Třetí řetězec ke spojení. |

### Návratová hodnota

Spojené řetězce parametrů.

## System::StringExtra::Concat(const String\&, const String\&, const String\&, const String\&) funkce


Spojuje řetězce.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1, const String &str2, const String &str3)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | První řetězec ke spojení. |
| str1 | const [String](../../system/string/)\& | Druhý řetězec ke spojení. |
| str2 | const [String](../../system/string/)\& | Třetí řetězec ke spojení. |
| str3 | const [String](../../system/string/)\& | Čtvrtý řetězec ke spojení. |

### Návratová hodnota

Spojené řetězce parametrů.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) funkce


Převádí více objektů na řetězec a spojuje vzniklé řetězce. Specializace pro typy [SmartPtr](../../system/smartptr/).

```cpp
template<typename T> std::enable_if_t<IsSmartPtr<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) k převodu a spojení. |

### Návratová hodnota

[String](../../system/string/) hodnota spojená z řetězcových reprezentací všech předaných objektů.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) funkce


Převádí více objektů na řetězec a spojuje vzniklé řetězce. Specializace pro aritmetické typy.

```cpp
template<typename T> std::enable_if_t<std::is_arithmetic<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) k převodu a spojení. |

### Návratová hodnota

[String](../../system/string/) hodnota spojená z řetězcových reprezentací všech předaných objektů.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) funkce


Převádí více objektů na řetězec a spojuje vzniklé řetězce. Specializace pro struktury a jiné typy hodnot.

```cpp
template<typename T> std::enable_if_t<!IsSmartPtr<T>::value &&!std::is_arithmetic<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) k převodu a spojení. |

### Návratová hodnota

[String](../../system/string/) hodnota spojená z řetězcových reprezentací všech předaných objektů.

## Viz také

* Typedef [ArrayPtr](../../system/arrayptr/)
* Třída [String](../../system/string/)
* Struktura [IsSmartPtr](../../system/issmartptr/)
* Jmenný prostor [System::StringExtra](../)
* Knihovna [Aspose.Slides](../../)