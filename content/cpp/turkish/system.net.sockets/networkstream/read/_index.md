---
title: Read()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen sayıda baytı akıştan okur ve belirtilen bayt dizisine yazar.
type: docs
weight: 196
url: /tr/system.net.sockets/networkstream/read/
---
## NetworkStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) yöntemi


Belirtilen sayıda baytı akıştan okur ve belirtilen bayt dizisine yazar.

```cpp
int32_t System::Net::Sockets::NetworkStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Okunan baytların yazılacağı bayt dizisi. |
| offset | **int32_t** | Belirtilen dizideki bayt ofseti. |
| size | **int32_t** | Okunacak bayt sayısı. |

### Dönüş Değeri

Okunan bayt sayısı.

## NetworkStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) yöntemi


Belirtilen sayıda baytı akıştan okur ve belirtilen bayt dizisine yazar.

```cpp
int32_t System::Net::Sockets::NetworkStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Okunan baytların yazılacağı bayt dizisi görünümü |
| offset | **int32_t** | **buffer** içinde yazmaya başlanacak 0 tabanlı konum |
| size | **int32_t** | Okunacak bayt sayısı |

### Dönüş Değeri

Okunan bayt sayısı

## Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [NetworkStream](../)
* Ad alanı [System::Net::Sockets](../../)
* Kütüphane [Aspose.Slides](../../../)