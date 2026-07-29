---
title: Write()
second_title: Aspose.Slides för C++ API-referens
description: Skriver den angivna delsekvensen av byte från den angivna bytearrayen till strömmen.
type: docs
weight: 209
url: /sv/system.net.sockets/networkstream/write/
---
## NetworkStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

Skriver den angivna delsekvensen av byte från den angivna bytearrayen till strömmen.

```cpp
void System::Net::Sockets::NetworkStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Arrayen som innehåller byte att skriva. |
| offset | **int32_t** | Offset i byte i den angivna arrayen. |
| size | **int32_t** | Antalet element i delsekvensen som ska skrivas. |

## NetworkStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method

Skriver den angivna delsekvensen av byte från den angivna bytearrayen till strömmen.

```cpp
void System::Net::Sockets::NetworkStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Arrayvyn som innehåller byte att skriva |
| offset | **int32_t** | Ett 0-baserat index för elementet i **buffer** där delsekvensen som ska skrivas börjar |
| size | **int32_t** | Antalet element i delsekvensen som ska skrivas |

## Se även

* Typdefinition [ArrayPtr](../../../system/arrayptr/)
* Klass [NetworkStream](../)
* Namnrymd [System::Net::Sockets](../../)
* Bibliotek [Aspose.Slides](../../../)