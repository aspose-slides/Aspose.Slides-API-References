---
title: WriteLine()
second_title: Aspose.Slides för C++ API-referens
description: Skriver radavslutningstecken till strömmen.
type: docs
weight: 118
url: /sv/system.io/textwriter/writeline/
---
## TextWriter::WriteLine() metod

Skriver radavslutningstecken till strömmen.

```cpp
virtual void System::IO::TextWriter::WriteLine()
```

## TextWriter::WriteLine(const SharedPtr\<Object\>\&) metod

Skriver strängrepresentationen av det angivna objektet följt av radavslutningstecknen till strömmen.

```cpp
virtual void System::IO::TextWriter::WriteLine(const SharedPtr<Object> &value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Objektet att skriva |

## TextWriter::WriteLine(bool) metod

Skriver strängrepresentationen av det angivna booleska värdet följt av radavslutningstecknen till strömmen.

```cpp
virtual void System::IO::TextWriter::WriteLine(bool value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **bool** | Värdet att skriva |

## TextWriter::WriteLine(char_t) metod

Skriver det angivna tecknet följt av radavslutningstecknen till strömmen.

```cpp
virtual void System::IO::TextWriter::WriteLine(char_t value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | char_t | Värdet att skriva |

## TextWriter::WriteLine(Decimal) metod

Skriver strängrepresentationen av det angivna [Decimal](../../../system/decimal/)-objektet följt av radavslutningstecknen till strömmen.

```cpp
virtual void System::IO::TextWriter::WriteLine(Decimal value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Decimal](../../../system/decimal/) | Objektet att skriva |

## TextWriter::WriteLine(double) metod

Skriver strängrepresentationen av det angivna dubbelprecision-flyttalsvärdet följt av radavslutningstecknen till strömmen.

```cpp
virtual void System::IO::TextWriter::WriteLine(double value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **double** | Värdet att skriva |

## TextWriter::WriteLine(int) metod

Skriver strängrepresentationen av det angivna 32-bit-heltalsvärdet följt av radavslutningstecknen till strömmen.

```cpp
virtual void System::IO::TextWriter::WriteLine(int value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int | Värdet att skriva |

## TextWriter::WriteLine(int64_t) metod

Skriver strängrepresentationen av det angivna 64-bit-heltalsvärdet följt av radavslutningstecknen till strömmen.

```cpp
virtual void System::IO::TextWriter::WriteLine(int64_t value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **int64_t** | Värdet att skriva |

## TextWriter::WriteLine(float) metod

Skriver strängrepresentationen av det angivna enkelprecision-flyttalsvärdet följt av radavslutningstecknen till strömmen.

```cpp
virtual void System::IO::TextWriter::WriteLine(float value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **float** | Värdet att skriva |

## TextWriter::WriteLine(const String\&) metod

Skriver den angivna strängen följt av radavslutningstecknen till strömmen.

```cpp
virtual void System::IO::TextWriter::WriteLine(const String &value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Strängen att skriva |

## TextWriter::WriteLine(uint32_t) metod

Skriver strängrepresentationen av det angivna 32-bit-osignerade heltalvärdet följt av radavslutningstecknen till strömmen.

```cpp
virtual void System::IO::TextWriter::WriteLine(uint32_t value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **uint32_t** | Värdet att skriva |

## TextWriter::WriteLine(uint64_t) metod

Skriver strängrepresentationen av det angivna 64-bit-osignerade heltalvärdet följt av radavslutningstecknen till strömmen.

```cpp
virtual void System::IO::TextWriter::WriteLine(uint64_t value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **uint64_t** | Värdet att skriva |

## TextWriter::WriteLine(const ArrayPtr\<char_t\>\&) metod

Skriver alla tecken från den angivna arrayen följt av radavslutningstecknen till strömmen.

```cpp
virtual void System::IO::TextWriter::WriteLine(const ArrayPtr<char_t> &buffer)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Arrayen som innehåller tecknen att skriva |

## TextWriter::WriteLine(const ArrayPtr\<char_t\>\&, int32_t, int32_t) metod

Skriver det angivna delintervallet av UTF-16-tecken från den angivna teckenarrayen följt av radavslutningstecknen till strömmen.

```cpp
virtual void System::IO::TextWriter::WriteLine(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Arrayen som innehåller tecknen att skriva |
| index | **int32_t** | Ett 0-baserat index i **buffer** där delintervallet som ska skrivas börjar |
| count | **int32_t** | Antalet tecken i delintervallet som ska skrivas; -1 anger att delintervallet slutar där **buffer**-arrayen slutar |

## TextWriter::WriteLine(const char_t *) metod

Skriver den angivna C-strängen följt av radavslutningstecknen till strömmen.

```cpp
virtual void System::IO::TextWriter::WriteLine(const char_t *value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const char_t * | C-strängen att skriva |

## TextWriter::WriteLine(const TypeInfo\&) metod

Skriver strängrepresentationen av det angivna [TypeInfo](../../../system/typeinfo/)-objektet följt av radavslutningstecknen till strömmen.

```cpp
virtual void System::IO::TextWriter::WriteLine(const TypeInfo &value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [TypeInfo](../../../system/typeinfo/)\& | Objektet att skriva |

## TextWriter::WriteLine(const String\&, const TArgs\&...) metod

Skriver de angivna värdena formaterade enligt det angivna formatet följt av radavslutningstecken till strömmen.

```cpp
template<class...> void System::IO::TextWriter::WriteLine(const String &format, const TArgs &... args)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TArgs | Listan med typer för värdena som ska skrivas |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | Strängformatet |
| args | const TArgs\&... | Värdena att skriva |

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [TextWriter](../)
* Class [Object](../../../system/object/)
* Class [Decimal](../../../system/decimal/)
* Class [String](../../../system/string/)
* Class [TypeInfo](../../../system/typeinfo/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)