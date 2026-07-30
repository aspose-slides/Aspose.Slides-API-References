---
title: Write()
second_title: Aspose.Slides pro C++ API Reference
description: Vypíše řetězcovou reprezentaci zadaného objektu na standardní výstupní proud.
type: docs
weight: 1
url: /cs/system/console/write/
---
## Console::Write(const SharedPtr\<T\>\&) metoda


Vypíše řetězcovou reprezentaci zadaného objektu na standardní výstupní proud.

```cpp
template<class T> static void System::Console::Write(const SharedPtr<T> &object)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ objektu k výpisu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| object | const [SharedPtr](../../sharedptr/)\<T\>\& | [Object](../../object/) k výpisu |

## Console::Write(bool) metoda


Vypíše řetězcovou reprezentaci hodnoty bool na standardní výstupní proud.

```cpp
static void System::Console::Write(bool value)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | **bool** | Hodnota k výpisu |

## Console::Write(char_t) metoda


Vypíše zadanou znakovou hodnotu na standardní výstupní proud.

```cpp
static void System::Console::Write(char_t value)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | char_t | Hodnota k výpisu |

## Console::Write(const ArrayPtr\<char_t\>\&) metoda


Vypíše řetězcovou reprezentaci zadaného pole znaků na standardní výstupní proud.

```cpp
static void System::Console::Write(const ArrayPtr<char_t> &buffer)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | Pole k výpisu |

## Console::Write(const Decimal\&) metoda


Vypíše řetězcovou reprezentaci hodnoty [Decimal](../../decimal/) na standardní výstupní proud.

```cpp
static void System::Console::Write(const Decimal &value)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | Hodnota k výpisu |

## Console::Write(double) metoda


Vypíše řetězcovou reprezentaci hodnoty typu double na standardní výstupní proud.

```cpp
static void System::Console::Write(double value)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | **double** | Hodnota k výpisu |

## Console::Write(float) metoda


Vypíše řetězcovou reprezentaci hodnoty typu float na standardní výstupní proud.

```cpp
static void System::Console::Write(float value)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | **float** | Hodnota k výpisu |

## Console::Write(int32_t) metoda


Vypíše řetězcovou reprezentaci 32-bitové celočíselné hodnoty na standardní výstupní proud.

```cpp
static void System::Console::Write(int32_t value)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | **int32_t** | Hodnota k výpisu |

## Console::Write(int64_t) metoda


Vypíše řetězcovou reprezentaci 64-bitové celočíselné hodnoty na standardní výstupní proud.

```cpp
static void System::Console::Write(int64_t value)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | **int64_t** | Hodnota k výpisu |

## Console::Write(const String\&) metoda


Vypíše zadaný řetězcový objekt na standardní výstupní proud.

```cpp
static void System::Console::Write(const String &value)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Objekt řetězce k výpisu |

## Console::Write(const char_t *) metoda


Vypíše zadaný c-řetězec na standardní výstupní proud.

```cpp
static void System::Console::Write(const char_t *value)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const char_t * | C-řetězec k výpisu |

## Console::Write(const TypeInfo\&) metoda


Vypíše řetězcovou reprezentaci hodnoty [TypeInfo](../../typeinfo/) na standardní výstupní proud.

```cpp
static void System::Console::Write(const TypeInfo &value)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [TypeInfo](../../typeinfo/)\& | Hodnota k výpisu |

## Console::Write(uint32_t) metoda


Vypíše řetězcovou reprezentaci 32-bitové nezáporné celočíselné hodnoty na standardní výstupní proud.

```cpp
static void System::Console::Write(uint32_t value)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | **uint32_t** | Hodnota k výpisu |

## Console::Write(uint64_t) metoda


Vypíše řetězcovou reprezentaci 64-bitové nezáporné celočíselné hodnoty na standardní výstupní proud.

```cpp
static void System::Console::Write(uint64_t value)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | **uint64_t** | Hodnota k výpisu |

## Console::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) metoda


Vypíše řetězcovou reprezentaci zadaného rozsahu zadaného pole znaků na standardní výstupní proud.

```cpp
static void System::Console::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | Pole znaků |
| index | **int32_t** | Index v poli, kde začíná rozsah k výpisu |
| count | **int32_t** | Počet prvků v rozsahu k výpisu |

## Console::Write(const String\&, Args\&&...) metoda


Vypíše řetězcovou reprezentaci zadaných argumentů formátovaných podle zadaného formátu na standardní výstupní proud.

```cpp
template<class...> static void System::Console::Write(const String &format, Args &&... args)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| The | typy hodnot k výpisu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| format | const [String](../../string/)\& | Formát řetězce |
| args | Args\&&... | Hodnoty k výpisu |

## Console::Write(const char *) metoda




```cpp
static void System::Console::Write(const char *)=delete
```

## Viz také

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Třída [Console](../)
* Třída [Decimal](../../decimal/)
* Třída [String](../../string/)
* Třída [TypeInfo](../../typeinfo/)
* Jmenný prostor [System](../../)
* Library [Aspose.Slides](../../../)