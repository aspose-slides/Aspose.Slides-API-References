---
title: WriteLine()
second_title: Aspose.Slides för C++ API-referens
description: Skriver radavslutningstecken till strömmen.
type: docs
weight: 92
url: /sv/system.io/streamwriter/writeline/
---
## StreamWriter::WriteLine() metod

Skriver radavslutningstecken till strömmen.

```cpp
void System::IO::StreamWriter::WriteLine() override
```

## StreamWriter::WriteLine(const String\&) metod

Skriver den angivna strängen följt av radavslutningstecken till strömmen.

```cpp
void System::IO::StreamWriter::WriteLine(const String &value) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Strängen att skriva |

## StreamWriter::WriteLine(const SharedPtr\<Object\>\&) metod

Skriver strängrepresentationen av det angivna objektet följt av radavslutningstecken till strömmen.

```cpp
void System::IO::StreamWriter::WriteLine(const SharedPtr<Object> &obj) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Objektet att skriva |

## StreamWriter::WriteLine(const ArrayPtr\<char_t\>\&) metod

Skriver alla tecken från den angivna arrayen följt av radavslutningstecken till strömmen.

```cpp
void System::IO::StreamWriter::WriteLine(const ArrayPtr<char_t> &buffer) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Arrayen som innehåller tecknen att skriva |

## StreamWriter::WriteLine(const ArrayPtr\<char_t\>\&, int32_t, int32_t) metod

Skriver det angivna delintervallet av UTF-16-tecken från den angivna teckenarrayen följt av radavslutningstecken till strömmen.

```cpp
void System::IO::StreamWriter::WriteLine(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Arrayen som innehåller tecknen att skriva |
| index | **int32_t** | Ett 0-baserat index för elementet i **buffer** där delintervallet som ska skrivas börjar |
| count | **int32_t** | Antalet tecken i delintervallet som ska skrivas; -1 anger att delintervallet slutar där **buffer**-arrayen slutar |

## StreamWriter::WriteLine(const char_t *) metod

Skriver den angivna C-strängen följt av radavslutningstecken till strömmen.

```cpp
void System::IO::StreamWriter::WriteLine(const char_t *buffer) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const char_t * | C-strängen att skriva |

## StreamWriter::WriteLine(const System::SharedPtr\<T\>\&) metod

Skriver strängrepresentationen av det angivna objektet följt av radavslutningstecken till strömmen.

```cpp
template<typename T> void System::IO::StreamWriter::WriteLine(const System::SharedPtr<T> &obj)
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