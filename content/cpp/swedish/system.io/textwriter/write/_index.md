---
title: Write()
second_title: Aspose.Slides för C++ API-referens
description: Skriver den strängrepresentation av det angivna objektet till strömmen.
type: docs
weight: 105
url: /sv/system.io/textwriter/write/
---
## TextWriter::Write(const SharedPtr\<Object\>\&) metod


Skriver den strängrepresentationen av det angivna objektet till strömmen.

```cpp
virtual void System::IO::TextWriter::Write(const SharedPtr<Object> &value)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Objektet att skriva |

## TextWriter::Write(bool) metod


Skriver den strängrepresentationen av det angivna booleska värdet till strömmen.

```cpp
virtual void System::IO::TextWriter::Write(bool value)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **bool** | Värdet att skriva |

## TextWriter::Write(char_t) metod


Skriver det angivna tecknet till strömmen.

```cpp
virtual void System::IO::TextWriter::Write(char_t value)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | char_t | Värdet att skriva |

## TextWriter::Write(Decimal) metod


Skriver den strängrepresentationen av det angivna [Decimal](../../../system/decimal/)-objektet till strömmen.

```cpp
virtual void System::IO::TextWriter::Write(Decimal value)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Decimal](../../../system/decimal/) | Objektet att skriva |

## TextWriter::Write(double) metod


Skriver den strängrepresentationen av det angivna dubbelprecisionsflyttalvärdet till strömmen.

```cpp
virtual void System::IO::TextWriter::Write(double value)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **double** | Värdet att skriva |

## TextWriter::Write(int) metod


Skriver den strängrepresentationen av det angivna 32-bitars heltalsvärdet till strömmen.

```cpp
virtual void System::IO::TextWriter::Write(int value)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int | Värdet att skriva |

## TextWriter::Write(int64_t) metod


Skriver den strängrepresentationen av det angivna 64-bitars heltalsvärdet till strömmen.

```cpp
virtual void System::IO::TextWriter::Write(int64_t value)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **int64_t** | Värdet att skriva |

## TextWriter::Write(float) metod


Skriver den strängrepresentationen av det angivna enkelprecisionsflyttalvärdet till strömmen.

```cpp
virtual void System::IO::TextWriter::Write(float value)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **float** | Värdet att skriva |

## TextWriter::Write(const String\&) metod


Skriver den angivna strängen till strömmen.

```cpp
virtual void System::IO::TextWriter::Write(const String &value)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Strängen att skriva |

## TextWriter::Write(uint32_t) metod


Skriver den strängrepresentationen av det angivna osignerade 32-bitars heltalsvärdet till strömmen.

```cpp
virtual void System::IO::TextWriter::Write(uint32_t value)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **uint32_t** | Värdet att skriva |

## TextWriter::Write(uint64_t) metod


Skriver den strängrepresentationen av det angivna osignerade 64-bitars heltalsvärdet till strömmen.

```cpp
virtual void System::IO::TextWriter::Write(uint64_t value)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **uint64_t** | Värdet att skriva |

## TextWriter::Write(const ArrayPtr\<char_t\>\&) metod


Skriver alla tecken från den angivna arrayen till strömmen.

```cpp
virtual void System::IO::TextWriter::Write(const ArrayPtr<char_t> &buffer)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Arrayen som innehåller tecknen att skriva |

## TextWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) metod


Skriver det angivna delintervallet av UTF-16-tecken från den angivna teckenarrayen till strömmen.

```cpp
virtual void System::IO::TextWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Arrayen som innehåller tecknen att skriva |
| index | **int32_t** | Ett 0-baserat index för elementet i **buffer** där delintervallet att skriva börjar |
| count | **int32_t** | Antalet tecken i delintervallet som ska skrivas; -1 anger att delintervallet slutar där **buffer**-arrayen slutar |

## TextWriter::Write(const char_t *) metod


Skriver den angivna c-strängen till strömmen.

```cpp
virtual void System::IO::TextWriter::Write(const char_t *value)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const char_t * | c-strängen att skriva |

## TextWriter::Write(const TypeInfo\&) metod


Skriver den strängrepresentationen av det angivna [TypeInfo](../../../system/typeinfo/)-objektet till strömmen.

```cpp
virtual void System::IO::TextWriter::Write(const TypeInfo &value)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [TypeInfo](../../../system/typeinfo/)\& | Objektet att skriva |

## TextWriter::Write(const String\&, const TArgs\&...) metod


Skriver de angivna värdena formaterade enligt det angivna formatet till strömmen.

```cpp
template<class...> void System::IO::TextWriter::Write(const String &format, const TArgs &... args)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TArgs | Listan av typer av värden att skriva |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | Strängformatet |
| args | const TArgs\&... | Värdena att skriva |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [Object](../../../system/object/)
* Klass [TextWriter](../)
* Klass [Decimal](../../../system/decimal/)
* Klass [String](../../../system/string/)
* Klass [TypeInfo](../../../system/typeinfo/)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)