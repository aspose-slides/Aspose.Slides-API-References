---
title: Write()
second_title: Aspose.Slides för C++ API-referens
description: Skriver det angivna tecknet till strömmen.
type: docs
weight: 40
url: /sv/system.io/stringwriter/write/
---
## StringWriter::Write(char_t) metod

Skriver det angivna tecknet till strömmen.

```cpp
virtual void System::IO::StringWriter::Write(char_t value) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | char_t | Värdet att skriva |

## StringWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) metod

Skriver det angivna delintervallet av tecken från den angivna teckenarrayen till strömmen.

```cpp
virtual void System::IO::StringWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Arrayen som innehåller tecknen att skriva |
| index | **int32_t** | Ett 0-baserat index för elementet i **buffer** där delintervallet att skriva börjar |
| count | **int32_t** | Antalet tecken i delintervallet att skriva |

## StringWriter::Write(const String\&) metod

Skriver den angivna strängen till strömmen.

```cpp
virtual void System::IO::StringWriter::Write(const String &value) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Strängen att skriva |

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [StringWriter](../)
* Klass [String](../../../system/string/)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)