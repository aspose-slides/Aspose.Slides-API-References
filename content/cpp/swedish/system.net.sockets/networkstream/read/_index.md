---
title: Read()
second_title: Aspose.Slides för C++ API-referens
description: Läser det angivna antalet byte från strömmen och skriver dem till den angivna byte-arrayen.
type: docs
weight: 196
url: /sv/system.net.sockets/networkstream/read/
---
## NetworkStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metod

Läser det angivna antalet byte från strömmen och skriver dem till den angivna byte-arrayen.

```cpp
int32_t System::Net::Sockets::NetworkStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Byte-arrayen där de lästa bytena kommer att skrivas. |
| offset | **int32_t** | Förskjutningen i byte i den angivna arrayen. |
| size | **int32_t** | Antalet byte att läsa. |

### Returvärde

Antalet lästa byte.

## NetworkStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metod

Läser det angivna antalet byte från strömmen och skriver dem till den angivna byte-arrayen.

```cpp
int32_t System::Net::Sockets::NetworkStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Byte-arrayvyn att skriva de lästa bytena till |
| offset | **int32_t** | En 0-baserad position i **buffer** att börja skriva på |
| size | **int32_t** | Antalet byte att läsa |

### Returvärde

Antalet byte lästa

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [NetworkStream](../)
* Namnrymd [System::Net::Sockets](../../)
* Bibliotek [Aspose.Slides](../../../)