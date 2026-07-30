---
title: operator<()
second_title: Aspose.Slides pro C++ API referenci
description: 
type: docs
weight: 2094
url: /cs/system/operator_less/
---
## System::operator<(std::nullptr_t, DateTime) funkce

```cpp
constexpr bool System::operator<(std::nullptr_t, DateTime)
```
## System::operator<(std::nullptr_t, const DateTimeOffset\&) funkce

```cpp
constexpr bool System::operator<(std::nullptr_t, const DateTimeOffset &)
```
## System::operator<(std::nullptr_t, const Nullable\<T\>\&) funkce

Vždy vrací false.

```cpp
template<typename T> bool System::operator<(std::nullptr_t, const Nullable<T> &)
```
## System::operator<(const T1\&, const Nullable\<T2\>\&) funkce

Určuje, zda je zadaná hodnota menší než hodnota reprezentovaná zadaným objektem [Nullable](../nullable/) použitím [operator<()](./) na tyto hodnoty.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator<(const T1 &some, const Nullable<T2> &other)
```

### Šablonové parametry

| Parametr | Popis |
| --- | --- |
| T1 | Typ první porovnávané hodnoty |
| T2 | Základní typ objektu [Nullable](../nullable/), který představuje druhou porovnávanou hodnotu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| some | const T1\& | Konstantní reference na hodnotu, která bude použita jako první porovnávaná hodnota |
| other | const [Nullable](../nullable/)\<T2\>\& | Konstantní reference na objekt [Nullable](../nullable/), jehož reprezentovaná hodnota bude použita jako druhá porovnávaná hodnota |

### Návratová hodnota

true pokud je první porovnávaná hodnota menší než druhá porovnávaná hodnota, jinak - false

```cpp
constexpr bool System::operator<(std::nullptr_t, TimeSpan)
```
## Viz také

* Třída [DateTime](../datetime/)
* Třída [DateTimeOffset](../datetimeoffset/)
* Třída [Nullable](../nullable/)
* Třída [TimeSpan](../timespan/)
* Struktura [IsNullable](../isnullable/)
* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)