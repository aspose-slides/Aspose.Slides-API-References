---
title: Split()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Rozdělí řetězec podle znaku.
type: docs
weight: 768
url: /cs/system/string/split/
---
## String::Split(char_t, StringSplitOptions) const metoda


Rozdělí řetězec podle znaku.

```cpp
ArrayPtr<String> System::String::Split(char_t separator=u' ', StringSplitOptions opt=StringSplitOptions::None) const
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| separator | char_t | Znak, podle kterého se řetězec rozdělí. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Možnosti rozdělení. |

### Návratová hodnota

[Array](../../array/) podřetězců.

## String::Split(char_t, int32_t, StringSplitOptions) const metoda


Rozdělí řetězec podle znaku.

```cpp
ArrayPtr<String> System::String::Split(char_t separator, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| separator | char_t | Znak, podle kterého se řetězec rozdělí. |
| count | **int32_t** | Maximální počet podřetězců, které se vrátí. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Možnosti rozdělení. |

### Návratová hodnota

[Array](../../array/) podřetězců.

## String::Split(char_t, char_t, StringSplitOptions) const metoda


Rozdělí řetězec podle jednoho ze dvou znaků.

```cpp
ArrayPtr<String> System::String::Split(char_t separatorA, char_t separatorB, StringSplitOptions opt=StringSplitOptions::None) const
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| separatorA | char_t | První znak, podle kterého se řetězec rozdělí. |
| separatorB | char_t | Druhý znak, podle kterého se řetězec rozdělí. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Možnosti rozdělení. |

### Návratová hodnota

[Array](../../array/) podřetězců.

## String::Split(const ArrayPtr\<char_t\>\&, StringSplitOptions) const metoda


Rozdělí řetězec podle jednoho ze zadaných znaků.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) znaků oddělovačů. Pokud je prázdné, jakýkoli znak mezery se považuje za oddělovač. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Možnosti rozdělení. |

### Návratová hodnota

[Array](../../array/) podřetězců.

## String::Split(const ArrayPtr\<char_t\>\&, int32_t, StringSplitOptions) const metoda


Rozdělí řetězec podle jednoho ze zadaných znaků.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) znaků oddělovačů. Pokud je prázdné, jakýkoli znak mezery se považuje za oddělovač. |
| count | **int32_t** | Maximální počet podřetězců, které se vrátí. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Možnosti rozdělení. |

### Návratová hodnota

[Array](../../array/) podřetězců.

## String::Split(const String\&, StringSplitOptions) const metoda


Rozdělí řetězec podle podřetězce.

```cpp
ArrayPtr<String> System::String::Split(const String &separator, StringSplitOptions opt=StringSplitOptions::None) const
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| separator | const [String](../)\& | Podřetězec fungující jako oddělovač. Pokud je prázdné, znak mezery funguje jako oddělovač. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Možnosti rozdělení. |

### Návratová hodnota

[Array](../../array/) podřetězců.

## String::Split(const String\&, int, StringSplitOptions) const metoda


Rozdělí řetězec podle podřetězce.

```cpp
ArrayPtr<String> System::String::Split(const String &separator, int count, StringSplitOptions opt=StringSplitOptions::None) const
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| separator | const [String](../)\& | Podřetězec fungující jako oddělovač. Pokud je prázdné, znak mezery funguje jako oddělovač. |
| count | int | Maximální počet prvků v poli rozdělení. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Možnosti rozdělení. |

### Návratová hodnota

[Array](../../array/) podřetězců.

## String::Split(const ArrayPtr\<String\>\&, StringSplitOptions) const metoda


Rozdělí řetězec podle podřetězce.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) řetězců oddělovačů. Pokud je prázdné, nedojde k rozdělení. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Možnosti rozdělení. |

### Návratová hodnota

[Array](../../array/) podřetězců.

## String::Split(const ArrayPtr\<String\>\&, int, StringSplitOptions) const metoda


Rozdělí řetězec podle podřetězce. V současné době podporuje pouze pole oddělovačů s nulovým nebo jedním prvkem.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, int count, StringSplitOptions opt=StringSplitOptions::None) const
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) řetězců oddělovačů. Pokud je prázdné, nedojde k rozdělení. |
| count | int | Maximální počet prvků v poli rozdělení. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Možnosti rozdělení. |

### Návratová hodnota

[Array](../../array/) podřetězců.

## Viz také

* Enum [StringSplitOptions](../../stringsplitoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)