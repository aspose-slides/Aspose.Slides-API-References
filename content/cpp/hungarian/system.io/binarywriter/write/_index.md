---
title: Write()
second_title: Aspose.Slides C++ API referenciája
description: Az adott előjeles nélküli 8 bites egész értéket írja a kimeneti adatfolamba.
type: docs
weight: 92
url: /hu/system.io/binarywriter/write/
---
## BinaryWriter::Write(uint8_t) metódus


Az adott **uint8_t** típusú előjeles nélküli 8 bites egész értéket írja a kimeneti adatfolamba.

```cpp
virtual void System::IO::BinaryWriter::Write(uint8_t value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | **uint8_t** | Az írandó érték |

## BinaryWriter::Write(const ArrayPtr\<uint8_t\>\&, int, int) metódus


Az adott **ArrayPtr\<uint8_t\>** típusú bájttömbből a megadott bájt-alrészt írja a kimeneti adatfolamba.

```cpp
virtual void System::IO::BinaryWriter::Write(const ArrayPtr<uint8_t> &buffer, int index=0, int count=-1)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Az írandó bájtokat tartalmazó tömb |
| index | int | 0-alapú index a **buffer** tömbben, ahol a írandó alrész kezdődik |
| count | int | A írandó alrész elemeinek száma; a -1 érték azt jelzi, hogy az alrész a **buffer** tömb végénél ér véget |

## BinaryWriter::Write(const ArrayPtr\<char_t\>\&, int, int) metódus


Az adott karaktertömbből a megadott UTF-16 karakter-alrészt írja a kimeneti adatfolamba.

```cpp
virtual void System::IO::BinaryWriter::Write(const ArrayPtr<char_t> &buffer, int index=0, int count=-1)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Az írandó karaktereket tartalmazó tömb |
| index | int | 0-alapú index a **buffer** tömbben, ahol a írandó alrész kezdődik |
| count | int | A írandó alrész karaktereinek száma; a -1 érték azt jelzi, hogy az alrész a **buffer** tömb végénél ér véget |

## BinaryWriter::Write(bool) metódus


Az egy bájtot írja a kimeneti adatfolamba, amelynek értéke 0, ha **value** 'true', és 1, ha **value** 'false'.

```cpp
virtual void System::IO::BinaryWriter::Write(bool value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | **bool** | A bájt értékét meghatározó logikai érték |

## BinaryWriter::Write(char16_t) metódus


Az adott 16 bites széles karakter értéket írja a kimeneti adatfolamba.

```cpp
virtual void System::IO::BinaryWriter::Write(char16_t value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | char16_t | Az írandó érték |

## BinaryWriter::Write(int16_t) metódus


Az adott 16 bites egész értéket írja a kimeneti adatfolamba.

```cpp
virtual void System::IO::BinaryWriter::Write(int16_t value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | **int16_t** | Az írandó érték |

## BinaryWriter::Write(int) metódus


Az adott 32 bites egész értéket írja a kimeneti adatfolamba.

```cpp
virtual void System::IO::BinaryWriter::Write(int value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int | Az írandó érték |

## BinaryWriter::Write(int64_t) metódus


Az adott 64 bites egész értéket írja a kimeneti adatfolamba.

```cpp
virtual void System::IO::BinaryWriter::Write(int64_t value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | **int64_t** | Az írandó érték |

## BinaryWriter::Write(uint16_t) metódus


Az adott **uint16_t** típusú előjeles nélküli 16 bites egész értéket írja a kimeneti adatfolamba.

```cpp
virtual void System::IO::BinaryWriter::Write(uint16_t value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | **uint16_t** | Az írandó érték |

## BinaryWriter::Write(uint32_t) metódus


Az adott **uint32_t** típusú előjeles nélküli 32 bites egész értéket írja a kimeneti adatfolamba.

```cpp
virtual void System::IO::BinaryWriter::Write(uint32_t value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | **uint32_t** | Az írandó érték |

## BinaryWriter::Write(uint64_t) metódus


Az adott **uint64_t** típusú előjeles nélküli 64 bites egész értéket írja a kimeneti adatfolamba.

```cpp
virtual void System::IO::BinaryWriter::Write(uint64_t value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | **uint64_t** | Az írandó érték |

## BinaryWriter::Write(float) metódus


Az adott egyszeres pontosságú lebegőpontos értéket írja a kimeneti adatfolamba.

```cpp
virtual void System::IO::BinaryWriter::Write(float value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | **float** | Az írandó érték |

## BinaryWriter::Write(double) metódus


Az adott dupla pontosságú lebegőpontos értéket írja a kimeneti adatfolamba.

```cpp
virtual void System::IO::BinaryWriter::Write(double value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | **double** | Az írandó érték |

## BinaryWriter::Write(const Decimal\&) metódus


Az adott [Decimal](../../../system/decimal/) érték bájtábrázolását írja a kimeneti adatfolamba.

```cpp
virtual void System::IO::BinaryWriter::Write(const Decimal &value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [Decimal](../../../system/decimal/)\& | Az írandó érték |

## BinaryWriter::Write(const String\&) metódus


A jelenlegi kódolásban egy hossz-előtaggal ellátott karakterláncot ír a kimeneti adatfolamba.

```cpp
virtual void System::IO::BinaryWriter::Write(const String &value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Az írandó karakterlánc |

## BinaryWriter::Write(const char_t *) metódus


A jelenlegi kódolásban egy hossz-előtaggal ellátott karakterláncot ír a kimeneti adatfolamba.

```cpp
virtual void System::IO::BinaryWriter::Write(const char_t *value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const char_t * | Az írandó C-karakterlánc |

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [BinaryWriter](../)
* Osztály [Decimal](../../../system/decimal/)
* Osztály [String](../../../system/string/)
* Névterület [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)