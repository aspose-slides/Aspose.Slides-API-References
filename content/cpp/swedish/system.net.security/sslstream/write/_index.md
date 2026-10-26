---
title: Write()
second_title: Aspose.Slides för C++ API-referens
description: Skriver den angivna byte-arrayen till strömmen.
type: docs
weight: 404
url: /sv/system.net.security/sslstream/write/
---
## SslStream::Write(const ArrayPtr\<uint8_t\>\&) metod

Skriver den angivna byte-arrayen till strömmen.

```cpp
void System::Net::Security::SslStream::Write(const ArrayPtr<uint8_t> &buffer)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Byte-arrayen att skriva. |

## SslStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metod

Skriver det angivna delintervallet av byte från den angivna byte-arrayen till strömmen.

```cpp
void System::Net::Security::SslStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Arrayen som innehåller byte att skriva |
| offset | **int32_t** | Ett 0-baserat index för elementet i **buffer** där det delintervallet som ska skrivas börjar |
| count | **int32_t** | Antalet element i delintervallet som ska skrivas |

## SslStream::Write(const System::Details::ArrayView\<uint8_t\>\&) metod

Skriver den angivna byte-arrayen till strömmen.

```cpp
void System::Net::Security::SslStream::Write(const System::Details::ArrayView<uint8_t> &buffer)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Byte-arrayen att skriva. |

## SslStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metod

Skriver det angivna delintervallet av byte från den angivna byte-arrayen till strömmen.

```cpp
void System::Net::Security::SslStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Arrayen som innehåller byte att skriva |
| offset | **int32_t** | Ett 0-baserat index för elementet i **buffer** där det delintervallet som ska skrivas börjar |
| count | **int32_t** | Antalet element i delintervallet som ska skrivas |

## Se även

* Typdefinition [ArrayPtr](../../../system/arrayptr/)
* Klass [SslStream](../)
* Namnrymd [System::Net::Security](../../)
* Bibliotek [Aspose.Slides](../../../)