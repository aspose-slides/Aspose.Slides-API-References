---
title: Write()
second_title: Aspose.Slides pro C++ – reference API
description: Zapíše zadaný znak do proudu.
type: docs
weight: 79
url: /cs/system.io/streamwriter/write/
---
## StreamWriter::Write(char_t) metoda

Zapíše zadaný znak do proudu.

```cpp
void System::IO::StreamWriter::Write(char_t value) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | char_t | Znak k zápisu |

## StreamWriter::Write(const String\&) metoda

Zapíše zadaný řetězec do proudu.

```cpp
void System::IO::StreamWriter::Write(const String &value) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Řetězec k zápisu |

## StreamWriter::Write(const SharedPtr\<Object\>\&) metoda

Zapíše textovou reprezentaci zadaného objektu do proudu.

```cpp
void System::IO::StreamWriter::Write(const SharedPtr<Object> &obj) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Objekt k zápisu |

## StreamWriter::Write(const ArrayPtr\<char_t\>\&) metoda

Zapíše všechny znaky z daného pole do proudu.

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Pole obsahující znaky k zápisu |

## StreamWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) metoda

Zapíše zadaný podrozsah znaků UTF-16 z určeného pole znaků do proudu.

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Pole obsahující znaky k zápisu |
| index | **int32_t** | Index od nuly prvku v **buffer**, od kterého podrozsah k zápisu začíná |
| count | **int32_t** | Počet znaků v podrozsahu k zápisu; -1 určuje, že podrozsah končí na konci pole **buffer** |

## StreamWriter::Write(const char_t *) metoda

Zapíše zadaný C-řetězec do proudu.

```cpp
void System::IO::StreamWriter::Write(const char_t *buffer) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const char_t * | C-řetězec k zápisu |

## StreamWriter::Write(const System::SharedPtr\<T\>\&) metoda

Zapíše textovou reprezentaci zadaného objektu do proudu.

```cpp
template<typename T> void System::IO::StreamWriter::Write(const System::SharedPtr<T> &obj)
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
* Library [Aspose.Slides](../../../)