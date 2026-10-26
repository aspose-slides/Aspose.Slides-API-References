---
title: Write()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Zapisuje řetězcovou reprezentaci zadaného objektu do proudu.
type: docs
weight: 105
url: /cs/system.io/textwriter/write/
---
## TextWriter::Write(const SharedPtr\<Object\>\&) metoda

Zapisuje řetězcovou reprezentaci zadaného objektu do proudu.

```cpp
virtual void System::IO::TextWriter::Write(const SharedPtr<Object> &value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Objekt k zápisu |

## TextWriter::Write(bool) metoda

Zapisuje řetězcovou reprezentaci zadané boolovské hodnoty do proudu.

```cpp
virtual void System::IO::TextWriter::Write(bool value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | **bool** | Hodnota k zápisu |

## TextWriter::Write(char_t) metoda

Zapisuje zadaný znak do proudu.

```cpp
virtual void System::IO::TextWriter::Write(char_t value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | char_t | Hodnota k zápisu |

## TextWriter::Write(Decimal) metoda

Zapisuje řetězcovou reprezentaci zadaného [Decimal](../../../system/decimal/) objektu do proudu.

```cpp
virtual void System::IO::TextWriter::Write(Decimal value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [Decimal](../../../system/decimal/) | Objekt k zápisu |

## TextWriter::Write(double) metoda

Zapisuje řetězcovou reprezentaci zadané double-přesné desetinné hodnoty do proudu.

```cpp
virtual void System::IO::TextWriter::Write(double value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | **double** | Hodnota k zápisu |

## TextWriter::Write(int) metoda

Zapisuje řetězcovou reprezentaci zadané 32-bitové celočíselné hodnoty do proudu.

```cpp
virtual void System::IO::TextWriter::Write(int value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int | Hodnota k zápisu |

## TextWriter::Write(int64_t) metoda

Zapisuje řetězcovou reprezentaci zadané 64-bitové celočíselné hodnoty do proudu.

```cpp
virtual void System::IO::TextWriter::Write(int64_t value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | **int64_t** | Hodnota k zápisu |

## TextWriter::Write(float) metoda

Zapisuje řetězcovou reprezentaci zadané single-přesné desetinné hodnoty do proudu.

```cpp
virtual void System::IO::TextWriter::Write(float value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | **float** | Hodnota k zápisu |

## TextWriter::Write(const String\&) metoda

Zapisuje zadaný řetězec do proudu.

```cpp
virtual void System::IO::TextWriter::Write(const String &value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Řetězec k zápisu |

## TextWriter::Write(uint32_t) metoda

Zapisuje řetězcovou reprezentaci zadané nepodepsané 32-bitové celočíselné hodnoty do proudu.

```cpp
virtual void System::IO::TextWriter::Write(uint32_t value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | **uint32_t** | Hodnota k zápisu |

## TextWriter::Write(uint64_t) metoda

Zapisuje řetězcovou reprezentaci zadané nepodepsané 64-bitové celočíselné hodnoty do proudu.

```cpp
virtual void System::IO::TextWriter::Write(uint64_t value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | **uint64_t** | Hodnota k zápisu |

## TextWriter::Write(const ArrayPtr\<char_t\>\&) metoda

Zapisuje všechny znaky ze zadaného pole do proudu.

```cpp
virtual void System::IO::TextWriter::Write(const ArrayPtr<char_t> &buffer)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Pole obsahující znaky k zápisu |

## TextWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) metoda

Zapisuje zadaný podřetězec znaků UTF-16 ze zadaného pole znaků do proudu.

```cpp
virtual void System::IO::TextWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Pole obsahující znaky k zápisu |
| index | **int32_t** | Nulový index v **buffer**, od kterého podřetězec začíná |
| count | **int32_t** | Počet znaků v podřetězci; -1 značí, že podřetězec končí na konci pole **buffer** |

## TextWriter::Write(const char_t *) metoda

Zapisuje zadaný c-string do proudu.

```cpp
virtual void System::IO::TextWriter::Write(const char_t *value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const char_t * | C-string k zápisu |

## TextWriter::Write(const TypeInfo\&) metoda

Zapisuje řetězcovou reprezentaci zadaného [TypeInfo](../../../system/typeinfo/) objektu do proudu.

```cpp
virtual void System::IO::TextWriter::Write(const TypeInfo &value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [TypeInfo](../../../system/typeinfo/)\& | Objekt k zápisu |

## TextWriter::Write(const String\&, const TArgs\&...) metoda

Zapisuje zadané hodnoty formátované podle zadaného formátu do proudu.

```cpp
template<class...> void System::IO::TextWriter::Write(const String &format, const TArgs &... args)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| TArgs | Seznam typů hodnot, které mají být zapsány |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | Formát řetězce |
| args | const TArgs\&... | Hodnoty k zápisu |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [Object](../../../system/object/)
* Třída [TextWriter](../)
* Třída [Decimal](../../../system/decimal/)
* Třída [String](../../../system/string/)
* Třída [TypeInfo](../../../system/typeinfo/)
* Jmenný prostor [System::IO](../../)
* Library [Aspose.Slides](../../../)