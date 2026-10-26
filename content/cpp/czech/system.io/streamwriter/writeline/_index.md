---
title: WriteLine()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Zapíše znaky ukončení řádku do proudu.
type: docs
weight: 92
url: /cs/system.io/streamwriter/writeline/
---
## StreamWriter::WriteLine() metoda


Zapíše znaky ukončení řádku do proudu.

```cpp
void System::IO::StreamWriter::WriteLine() override
```

## StreamWriter::WriteLine(const String\&) metoda


Zapíše zadaný řetězec následovaný znaky ukončení řádku do proudu.

```cpp
void System::IO::StreamWriter::WriteLine(const String &value) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Řetězec k zápisu |

## StreamWriter::WriteLine(const SharedPtr\<Object\>\&) metoda


Zapíše textovou reprezentaci zadaného objektu následovanou znaky ukončení řádku do proudu.

```cpp
void System::IO::StreamWriter::WriteLine(const SharedPtr<Object> &obj) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Objekt k zápisu |

## StreamWriter::WriteLine(const ArrayPtr\<char_t\>\&) metoda


Zapíše všechny znaky ze zadaného pole následované znaky ukončení řádku do proudu.

```cpp
void System::IO::StreamWriter::WriteLine(const ArrayPtr<char_t> &buffer) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Pole obsahující znaky k zápisu |

## StreamWriter::WriteLine(const ArrayPtr\<char_t\>\&, int32_t, int32_t) metoda


Zapíše zadaný podrozsah znaků UTF-16 ze zadaného pole znaků následovaný znaky ukončení řádku do proudu.

```cpp
void System::IO::StreamWriter::WriteLine(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Pole obsahující znaky k zápisu |
| index | **int32_t** | Index založený na nule v **buffer**, kde začíná podrozsah k zápisu |
| count | **int32_t** | Počet znaků v podrozsahu k zápisu; -1 udává, že podrozsah končí na konci pole **buffer** |

## StreamWriter::WriteLine(const char_t *) metoda


Zapíše zadaný C-řetězec následovaný znaky ukončení řádku do proudu.

```cpp
void System::IO::StreamWriter::WriteLine(const char_t *buffer) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const char_t * | C-řetězec k zápisu |

## StreamWriter::WriteLine(const System::SharedPtr\<T\>\&) metoda


Zapíše textovou reprezentaci zadaného objektu následovanou znaky ukončení řádku do proudu.

```cpp
template<typename T> void System::IO::StreamWriter::WriteLine(const System::SharedPtr<T> &obj)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ objektu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const [System::SharedPtr](../../../system/sharedptr/)\<T\>\& | Objekt k zápisu |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [StreamWriter](../)
* Třída [String](../../../system/string/)
* Třída [Object](../../../system/object/)
* Jmenný prostor [System::IO](../../)
* Knihovna [Aspose.Slides](../../../)