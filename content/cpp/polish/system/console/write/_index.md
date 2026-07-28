---
title: Write()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Wypisuje reprezentację znakową określonego obiektu na standardowy strumień wyjściowy.
type: docs
weight: 1
url: /pl/system/console/write/
---
## Console::Write(const SharedPtr\<T\>\&) metoda


Wypisuje reprezentację znakową określonego obiektu na standardowy strumień wyjściowy.

```cpp
template<class T> static void System::Console::Write(const SharedPtr<T> &object)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ obiektu do wypisania |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| object | const [SharedPtr](../../sharedptr/)\<T\>\& | [Object](../../object/) do wypisania |

## Console::Write(bool) metoda


Wypisuje reprezentację znakową wartości bool na standardowy strumień wyjściowy.

```cpp
static void System::Console::Write(bool value)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | **bool** | Wartość do wypisania |

## Console::Write(char_t) metoda


Wypisuje określoną wartość znaku na standardowy strumień wyjściowy.

```cpp
static void System::Console::Write(char_t value)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | char_t | Wartość do wypisania |

## Console::Write(const ArrayPtr\<char_t\>\&) metoda


Wypisuje reprezentację znakową określonej tablicy znaków na standardowy strumień wyjściowy.

```cpp
static void System::Console::Write(const ArrayPtr<char_t> &buffer)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | Tablica do wypisania |

## Console::Write(const Decimal\&) metoda


Wypisuje reprezentację znakową wartości [Decimal](../../decimal/) na standardowy strumień wyjściowy.

```cpp
static void System::Console::Write(const Decimal &value)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | Wartość do wypisania |

## Console::Write(double) metoda


Wypisuje reprezentację znakową podwójnej precyzji liczby zmiennoprzecinkowej na standardowy strumień wyjściowy.

```cpp
static void System::Console::Write(double value)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | **double** | Wartość do wypisania |

## Console::Write(float) metoda


Wypisuje reprezentację znakową pojedynczej precyzji liczby zmiennoprzecinkowej na standardowy strumień wyjściowy.

```cpp
static void System::Console::Write(float value)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | **float** | Wartość do wypisania |

## Console::Write(int32_t) metoda


Wypisuje reprezentację znakową 32-bitowej wartości całkowitej na standardowy strumień wyjściowy.

```cpp
static void System::Console::Write(int32_t value)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | **int32_t** | Wartość do wypisania |

## Console::Write(int64_t) metoda


Wypisuje reprezentację znakową 64-bitowej wartości całkowitej na standardowy strumień wyjściowy.

```cpp
static void System::Console::Write(int64_t value)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | **int64_t** | Wartość do wypisania |

## Console::Write(const String\&) metoda


Wypisuje określony obiekt typu String na standardowy strumień wyjściowy.

```cpp
static void System::Console::Write(const String &value)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Obiekt string do wypisania |

## Console::Write(const char_t *) metoda


Wypisuje określony c-string na standardowy strumień wyjściowy.

```cpp
static void System::Console::Write(const char_t *value)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const char_t * | C-string do wypisania |

## Console::Write(const TypeInfo\&) metoda


Wypisuje reprezentację znakową wartości [TypeInfo](../../typeinfo/) na standardowy strumień wyjściowy.

```cpp
static void System::Console::Write(const TypeInfo &value)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [TypeInfo](../../typeinfo/)\& | Wartość do wypisania |

## Console::Write(uint32_t) metoda


Wypisuje reprezentację znakową nieujemnej 32-bitowej wartości całkowitej na standardowy strumień wyjściowy.

```cpp
static void System::Console::Write(uint32_t value)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | **uint32_t** | Wartość do wypisania |

## Console::Write(uint64_t) metoda


Wypisuje reprezentację znakową nieujemnej 64-bitowej wartości całkowitej na standardowy strumień wyjściowy.

```cpp
static void System::Console::Write(uint64_t value)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | **uint64_t** | Wartość do wypisania |

## Console::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) metoda


Wypisuje reprezentację znakową określonego zakresu określonej tablicy znaków na standardowy strumień wyjściowy.

```cpp
static void System::Console::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | Tablica znaków |
| index | **int32_t** | Indeks w tablicy, od którego rozpoczyna się zakres do wypisania |
| count | **int32_t** | Liczba elementów w zakresie do wypisania |

## Console::Write(const String\&, Args\&&...) metoda


Wypisuje reprezentację znakową określonych argumentów sformatowanych zgodnie z podanym formatem na standardowy strumień wyjściowy.

```cpp
template<class...> static void System::Console::Write(const String &format, Args &&... args)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| The | typów wartości do wypisania |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| format | const [String](../../string/)\& | Format łańcucha znaków |
| args | Args\&&... | Wartości do wypisania |

## Console::Write(const char *) metoda




```cpp
static void System::Console::Write(const char *)=delete
```

## Zobacz także

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Klasa [Console](../)
* Klasa [Decimal](../../decimal/)
* Klasa [String](../../string/)
* Klasa [TypeInfo](../../typeinfo/)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)