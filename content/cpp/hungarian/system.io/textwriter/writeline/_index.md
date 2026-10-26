---
title: WriteLine()
second_title: Aspose.Slides for C++ API referencia
description: Sorvége karaktereket ír a folyamathoz.
type: docs
weight: 118
url: /hu/system.io/textwriter/writeline/
---
## TextWriter::WriteLine() metódus

Írja a sorvége karaktereket a folyamathoz.

```cpp
virtual void System::IO::TextWriter::WriteLine()
```

## TextWriter::WriteLine(const SharedPtr\<Object\>\&) metódus

Az adott objektum karakterlánc ábrázolását, majd a sorvége karaktereket írja a folyamathoz.

```cpp
virtual void System::IO::TextWriter::WriteLine(const SharedPtr<Object> &value)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Az írandó objektum |

## TextWriter::WriteLine(bool) metódus

Az adott logikai érték karakterlánc ábrázolását, majd a sorvége karaktereket írja a folyamathoz.

```cpp
virtual void System::IO::TextWriter::WriteLine(bool value)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | **bool** | Az írandó érték |

## TextWriter::WriteLine(char_t) metódus

A megadott karaktert, majd a sorvége karaktereket írja a folyamathoz.

```cpp
virtual void System::IO::TextWriter::WriteLine(char_t value)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | char_t | Az írandó érték |

## TextWriter::WriteLine(Decimal) metódus

Az adott [Decimal](../../../system/decimal/) objektum karakterlánc ábrázolását, majd a sorvége karaktereket írja a folyamathoz.

```cpp
virtual void System::IO::TextWriter::WriteLine(Decimal value)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [Decimal](../../../system/decimal/) | Az írandó objektum |

## TextWriter::WriteLine(double) metódus

Az adott dupla pontosságú lebegőpontos érték karakterlánc ábrázolását, majd a sorvége karaktereket írja a folyamathoz.

```cpp
virtual void System::IO::TextWriter::WriteLine(double value)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | **double** | Az írandó érték |

## TextWriter::WriteLine(int) metódus

Az adott 32-bites egész érték karakterlánc ábrázolását, majd a sorvége karaktereket írja a folyamathoz.

```cpp
virtual void System::IO::TextWriter::WriteLine(int value)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int | Az írandó érték |

## TextWriter::WriteLine(int64_t) metódus

Az adott 64-bites egész érték karakterlánc ábrázolását, majd a sorvége karaktereket írja a folyamathoz.

```cpp
virtual void System::IO::TextWriter::WriteLine(int64_t value)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | **int64_t** | Az írandó érték |

## TextWriter::WriteLine(float) metódus

Az adott egyszeres pontosságú lebegőpontos érték karakterlánc ábrázolását, majd a sorvége karaktereket írja a folyamathoz.

```cpp
virtual void System::IO::TextWriter::WriteLine(float value)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | **float** | Az írandó érték |

## TextWriter::WriteLine(const String\&) metódus

A megadott karakterláncot, majd a sorvége karaktereket írja a folyamathoz.

```cpp
virtual void System::IO::TextWriter::WriteLine(const String &value)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Az írandó karakterlánc |

## TextWriter::WriteLine(uint32_t) metódus

Az adott előjel nélküli 32-bites egész érték karakterlánc ábrázolását, majd a sorvége karaktereket írja a folyamathoz.

```cpp
virtual void System::IO::TextWriter::WriteLine(uint32_t value)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | **uint32_t** | Az írandó érték |

## TextWriter::WriteLine(uint64_t) metódus

Az adott előjel nélküli 64-bites egész érték karakterlánc ábrázolását, majd a sorvége karaktereket írja a folyamathoz.

```cpp
virtual void System::IO::TextWriter::WriteLine(uint64_t value)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | **uint64_t** | Az írandó érték |

## TextWriter::WriteLine(const ArrayPtr\<char_t\>\&) metódus

Az adott tömb összes karakterét, majd a sorvége karaktereket írja a folyamathoz.

```cpp
virtual void System::IO::TextWriter::WriteLine(const ArrayPtr<char_t> &buffer)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Az írandó karaktereket tartalmazó tömb |

## TextWriter::WriteLine(const ArrayPtr\<char_t\>\&, int32_t, int32_t) metódus

Az adott karaktertömbből a megadott UTF-16 karakterek részhalmazát, majd a sorvége karaktereket írja a folyamathoz.

```cpp
virtual void System::IO::TextWriter::WriteLine(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Az írandó karaktereket tartalmazó tömb |
| index | **int32_t** | **buffer** tömbben a 0-bázisú index, ahol az írandó részhalmaz kezdődik |
| count | **int32_t** | Az írandó részhalmazban lévő karakterek száma; a -1 azt jelzi, hogy a részhalmaz akkor ér véget, amikor a **buffer** tömb véget ér |

## TextWriter::WriteLine(const char_t *) metódus

A megadott C-karakterláncot, majd a sorvége karaktereket írja a folyamathoz.

```cpp
virtual void System::IO::TextWriter::WriteLine(const char_t *value)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const char_t * | Az írandó C-karakterlánc |

## TextWriter::WriteLine(const TypeInfo\&) metódus

Az adott [TypeInfo](../../../system/typeinfo/) objektum karakterlánc ábrázolását, majd a sorvége karaktereket írja a folyamathoz.

```cpp
virtual void System::IO::TextWriter::WriteLine(const TypeInfo &value)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [TypeInfo](../../../system/typeinfo/)\& | Az írandó objektum |

## TextWriter::WriteLine(const String\&, const TArgs\&...) metódus

A megadott értékeket a megadott formátumnak megfelelően formázva, majd a sorvége karaktereket írja a folyamathoz.

```cpp
template<class...> void System::IO::TextWriter::WriteLine(const String &format, const TArgs &... args)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| TArgs | Az írandó értékek típusainak listája |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | A karakterlánc formátuma |
| args | const TArgs\&... | Az írandó értékek |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [TextWriter](../)
* Osztály [Object](../../../system/object/)
* Osztály [Decimal](../../../system/decimal/)
* Osztály [String](../../../system/string/)
* Osztály [TypeInfo](../../../system/typeinfo/)
* Névtér [System::IO](../../)
* Library [Aspose.Slides](../../../)