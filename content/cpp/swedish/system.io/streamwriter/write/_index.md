---
title: Write()
second_title: Aspose.Slides för C++ API-referens
description: Skriver det angivna tecknet till strömmen.
type: docs
weight: 79
url: /sv/system.io/streamwriter/write/
---
## StreamWriter::Write(char_t) metod


Skriver det angivna tecknet till strömmen.

```cpp
void System::IO::StreamWriter::Write(char_t value) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | char_t | Tecknet att skriva |

## StreamWriter::Write(const String\&) metod


Skriver den angivna strängen till strömmen.

```cpp
void System::IO::StreamWriter::Write(const String &value) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Strängen att skriva |

## StreamWriter::Write(const SharedPtr\<Object\>\&) metod


Skriver strängrepresentationen av det angivna objektet till strömmen.

```cpp
void System::IO::StreamWriter::Write(const SharedPtr<Object> &obj) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Objektet att skriva |

## StreamWriter::Write(const ArrayPtr\<char_t\>\&) metod


Skriver alla tecken från den angivna arrayen till strömmen.

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Arrayen som innehåller tecknen att skriva |

## StreamWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) metod


Skriver det angivna delintervallet av UTF-16-tecken från den angivna teckenarrayen till strömmen.

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Arrayen som innehåller tecknen att skriva |
| index | **int32_t** | Ett 0-baserat index för elementet i **buffer** där delintervallet som ska skrivas börjar |
| count | **int32_t** | Antalet tecken i delintervallet som ska skrivas; -1 anger att delintervallet slutar där **buffer**-arrayen slutar |

## StreamWriter::Write(const char_t *) metod


Skriver den angivna C-strängen till strömmen.

```cpp
void System::IO::StreamWriter::Write(const char_t *buffer) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const char_t * | C-strängen att skriva |

## StreamWriter::Write(const System::SharedPtr\<T\>\&) metod


Skriver strängrepresentationen av det angivna objektet till strömmen.

```cpp
template<typename T> void System::IO::StreamWriter::Write(const System::SharedPtr<T> &obj)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av objektet |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const [System::SharedPtr](../../../system/sharedptr/)\<T\>\& | Objektet att skriva |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [StreamWriter](../)
* Klass [String](../../../system/string/)
* Klass [Object](../../../system/object/)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)