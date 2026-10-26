---
title: Read()
second_title: Aspose.Slides för C++ API-referens
description: Läser data från strömmen.
type: docs
weight: 14
url: /sv/system.security.cryptography/cryptostream/read/
---
## CryptoStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metod


Läser data från strömmen.

```cpp
int32_t System::Security::Cryptography::CryptoStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Måldatabuffert. |
| offset | **int32_t** | Förskjutning i målbufferten. |
| count | **int32_t** | Antal byte att läsa. |

### Returvärde

Antalet byte som faktiskt läses.

## CryptoStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metod


Läser data från strömmen.

```cpp
int32_t System::Security::Cryptography::CryptoStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Måldatabuffert. |
| offset | **int32_t** | Förskjutning i målbufferten. |
| count | **int32_t** | Antal byte att läsa. |

### Returvärde

Antalet byte som faktiskt läses.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [CryptoStream](../)
* Namnrymd [System::Security::Cryptography](../../)
* Bibliotek [Aspose.Slides](../../../)