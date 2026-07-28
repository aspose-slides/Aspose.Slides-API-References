---
title: Write()
second_title: Aspose.Slides C++ API referenciája
description: A megadott objektum karakterlánc ábrázolását a streambe írja.
type: docs
weight: 105
url: /hu/system.io/textwriter/write/
---
## TextWriter::Write(const SharedPtr\<Object\>\&) metódus


A megadott objektum karakterlánc ábrázolását a streambe írja.

```cpp
virtual void System::IO::TextWriter::Write(const SharedPtr<Object> &value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Az írandó objektum |

## TextWriter::Write(bool) metódus


A megadott logikai érték karakterlánc ábrázolását a streambe írja.

```cpp
virtual void System::IO::TextWriter::Write(bool value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | **bool** | Az írandó érték |

## TextWriter::Write(char_t) metódus


A megadott karaktert a streambe írja.

```cpp
virtual void System::IO::TextWriter::Write(char_t value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | char_t | Az írandó érték |

## TextWriter::Write(Decimal) metódus


A megadott [Decimal](../../../system/decimal/) objektum karakterlánc ábrázolását a streambe írja.

```cpp
virtual void System::IO::TextWriter::Write(Decimal value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [Decimal](../../../system/decimal/) | Az írandó objektum |

## TextWriter::Write(double) metódus


A megadott dupla pontosságú lebegőpontos érték karakterlánc ábrázolását a streambe írja.

```cpp
virtual void System::IO::TextWriter::Write(double value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | **double** | Az írandó érték |

## TextWriter::Write(int) metódus


A megadott 32 bites egész szám karakterlánc ábrázolását a streambe írja.

```cpp
virtual void System::IO::TextWriter::Write(int value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int | Az írandó érték |

## TextWriter::Write(int64_t) metódus


A megadott 64 bites egész szám karakterlánc ábrázolását a streambe írja.

```cpp
virtual void System::IO::TextWriter::Write(int64_t value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | **int64_t** | Az írandó érték |

## TextWriter::Write(float) metódus


A megadott egyszeres pontosságú lebegőpontos érték karakterlánc ábrázolását a streambe írja.

```cpp
virtual void System::IO::TextWriter::Write(float value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | **float** | Az írandó érték |

## TextWriter::Write(const String\&) metódus


A megadott karakterláncot a streambe írja.

```cpp
virtual void System::IO::TextWriter::Write(const String &value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Az írandó karakterlánc |

## TextWriter::Write(uint32_t) metódus


A megadott előjel nélküli 32 bites egész szám karakterlánc ábrázolását a streambe írja.

```cpp
virtual void System::IO::TextWriter::Write(uint32_t value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | **uint32_t** | Az írandó érték |

## TextWriter::Write(uint64_t) metódus


A megadott előjel nélküli 64 bites egész szám karakterlánc ábrázolását a streambe írja.

```cpp
virtual void System::IO::TextWriter::Write(uint64_t value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | **uint64_t** | Az írandó érték |

## TextWriter::Write(const ArrayPtr\<char_t\>\&) metódus


A megadott tömb összes karakterét a streambe írja.

```cpp
virtual void System::IO::TextWriter::Write(const ArrayPtr<char_t> &buffer)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Az írandó karaktereket tartalmazó tömb |

## TextWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) metódus


A megadott karaktertömbből származó UTF-16 karakterek meghatározott részét a streambe írja.

```cpp
virtual void System::IO::TextWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Az írandó karaktereket tartalmazó tömb |
| index | **int32_t** | A **buffer** tömbben a rész kezdőpozíciója (0-al kezdődő index) |
| count | **int32_t** | A részben írandó karakterek száma; -1 esetén a rész a **buffer** tömb végéig tart |

## TextWriter::Write(const char_t *) metódus


A megadott C-karakterláncot a streambe írja.

```cpp
virtual void System::IO::TextWriter::Write(const char_t *value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const char_t * | Az írandó C-karakterlánc |

## TextWriter::Write(const TypeInfo\&) metódus


A megadott [TypeInfo](../../../system/typeinfo/) objektum karakterlánc ábrázolását a streambe írja.

```cpp
virtual void System::IO::TextWriter::Write(const TypeInfo &value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [TypeInfo](../../../system/typeinfo/)\& | Az írandó objektum |

## TextWriter::Write(const String\&, const TArgs\&...) metódus


A megadott értékeket a megadott formátumnak megfelelően a streambe írja.

```cpp
template<class...> void System::IO::TextWriter::Write(const String &format, const TArgs &... args)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| TArgs | Az írandó értékek típusainak listája |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | A formátumkarakterlánc |
| args | const TArgs\&... | Az írandó értékek |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [Object](../../../system/object/)
* Osztály [TextWriter](../)
* Osztály [Decimal](../../../system/decimal/)
* Osztály [String](../../../system/string/)
* Osztály [TypeInfo](../../../system/typeinfo/)
* Névterület [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)