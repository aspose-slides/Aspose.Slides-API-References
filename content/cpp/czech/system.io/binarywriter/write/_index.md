---
title: Write()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Zapíše zadanou nepodepsanou 8-bitovou celočíselnou hodnotu do výstupního proudu.
type: docs
weight: 92
url: /cs/system.io/binarywriter/write/
---
## BinaryWriter::Write(uint8_t) metoda

Zapíše zadanou nepodepsanou 8-bitovou celočíselnou hodnotu do výstupního proudu.

```cpp
virtual void System::IO::BinaryWriter::Write(uint8_t value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | **uint8_t** | Hodnota, která se má zapsat |

## BinaryWriter::Write(const ArrayPtr\<uint8_t\>\&, int, int) metoda

Zapíše zadaný podúsek bajtů ze zadaného pole bajtů do výstupního proudu.

```cpp
virtual void System::IO::BinaryWriter::Write(const ArrayPtr<uint8_t> &buffer, int index=0, int count=-1)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Pole obsahující bajty, které se mají zapsat |
| index | int | Index od nuly v **buffer**, kde podúsek k zápisu začíná |
| count | int | Počet prvků v podúseku k zápisu; -1 určuje, že podúsek končí na konci pole **buffer** |

## BinaryWriter::Write(const ArrayPtr\<char_t\>\&, int, int) metoda

Zapíše zadaný podúsek znaků UTF-16 ze zadaného pole znaků do výstupního proudu.

```cpp
virtual void System::IO::BinaryWriter::Write(const ArrayPtr<char_t> &buffer, int index=0, int count=-1)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Pole obsahující znaky, které se mají zapsat |
| index | int | Index od nuly v **buffer**, kde podúsek k zápisu začíná |
| count | int | Počet znaků v podúseku k zápisu; -1 určuje, že podúsek končí na konci pole **buffer** |

## BinaryWriter::Write(bool) metoda

Zapíše jeden bajt s hodnotou 0, pokud je **value** pravda, a 1, pokud je **value** nepravda, do výstupního proudu.

```cpp
virtual void System::IO::BinaryWriter::Write(bool value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | **bool** | Booleovská hodnota určující, jakou bajtovou hodnotu zapsat do výstupního proudu |

## BinaryWriter::Write(char16_t) metoda

Zapíše zadanou 16-bitovou širokou znakovou hodnotu do výstupního proudu.

```cpp
virtual void System::IO::BinaryWriter::Write(char16_t value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | char16_t | Hodnota, která se má zapsat |

## BinaryWriter::Write(int16_t) metoda

Zapíše zadanou 16-bitovou celočíselnou hodnotu do výstupního proudu.

```cpp
virtual void System::IO::BinaryWriter::Write(int16_t value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | **int16_t** | Hodnota, která se má zapsat |

## BinaryWriter::Write(int) metoda

Zapíše zadanou 32-bitovou celočíselnou hodnotu do výstupního proudu.

```cpp
virtual void System::IO::BinaryWriter::Write(int value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int | Hodnota, která se má zapsat |

## BinaryWriter::Write(int64_t) metoda

Zapíše zadanou 64-bitovou celočíselnou hodnotu do výstupního proudu.

```cpp
virtual void System::IO::BinaryWriter::Write(int64_t value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | **int64_t** | Hodnota, která se má zapsat |

## BinaryWriter::Write(uint16_t) metoda

Zapíše zadanou nepodepsanou 16-bitovou celočíselnou hodnotu do výstupního proudu.

```cpp
virtual void System::IO::BinaryWriter::Write(uint16_t value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | **uint16_t** | Hodnota, která se má zapsat |

## BinaryWriter::Write(uint32_t) metoda

Zapíše zadanou nepodepsanou 32-bitovou celočíselnou hodnotu do výstupního proudu.

```cpp
virtual void System::IO::BinaryWriter::Write(uint32_t value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | **uint32_t** | Hodnota, která se má zapsat |

## BinaryWriter::Write(uint64_t) metoda

Zapíše zadanou nepodepsanou 64-bitovou celočíselnou hodnotu do výstupního proudu.

```cpp
virtual void System::IO::BinaryWriter::Write(uint64_t value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | **uint64_t** | Hodnota, která se má zapsat |

## BinaryWriter::Write(float) metoda

Zapíše zadanou jednopřesnostní (float) hodnotu do výstupního proudu.

```cpp
virtual void System::IO::BinaryWriter::Write(float value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | **float** | Hodnota, která se má zapsat |

## BinaryWriter::Write(double) metoda

Zapíše zadanou dvojitou přesnost (double) hodnotu do výstupního proudu.

```cpp
virtual void System::IO::BinaryWriter::Write(double value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | **double** | Hodnota, která se má zapsat |

## BinaryWriter::Write(const Decimal\&) metoda

Zapíše bajtové znázornění zadané hodnoty [Decimal](../../../system/decimal/) do výstupního proudu.

```cpp
virtual void System::IO::BinaryWriter::Write(const Decimal &value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [Decimal](../../../system/decimal/)\& | Hodnota, která se má zapsat |

## BinaryWriter::Write(const String\&) metoda

Zapíše řetězec s předponou délky v aktuálním kódování do výstupního proudu.

```cpp
virtual void System::IO::BinaryWriter::Write(const String &value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Řetězec, který se má zapsat |

## BinaryWriter::Write(const char_t *) metoda

Zapíše řetězec s předponou délky v aktuálním kódování do výstupního proudu.

```cpp
virtual void System::IO::BinaryWriter::Write(const char_t *value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const char_t * | C-řetězec, který se má zapsat |

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [BinaryWriter](../)
* Třída [Decimal](../../../system/decimal/)
* Třída [String](../../../system/string/)
* Jmenný prostor [System::IO](../../)
* Knihovna [Aspose.Slides](../../../)