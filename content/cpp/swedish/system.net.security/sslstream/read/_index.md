---
title: Read()
second_title: Aspose.Slides för C++ API-referens
description: Läser det specificerade antalet byte från strömmen och skriver dem till den specificerade bytearrayen.
type: docs
weight: 391
url: /sv/system.net.security/sslstream/read/
---
## SslStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metod

Läser det specificerade antalet byte från strömmen och skriver dem till den specificerade bytearrayen.

```cpp
int32_t System::Net::Security::SslStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Bytearrayen att skriva de lästa byten till |
| offset | **int32_t** | En 0-baserad position i **buffer** att börja skriva på |
| count | **int32_t** | Antalet byte att läsa |

### Returvärde

Antalet lästa byte

## SslStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metod

Läser det specificerade antalet byte från strömmen och skriver dem till den specificerade bytearrayen.

```cpp
int32_t System::Net::Security::SslStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Bytearrayen att skriva de lästa byten till |
| offset | **int32_t** | En 0-baserad position i **buffer** att börja skriva på |
| count | **int32_t** | Antalet byte att läsa |

### Returvärde

Antalet lästa byte

## Se också

* Typdef [ArrayPtr](../../../system/arrayptr/)
* Klass [SslStream](../)
* Namnrymd [System::Net::Security](../../)
* Bibliotek [Aspose.Slides](../../../)