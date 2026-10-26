---
title: Write()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen bayt dizisinden akışa belirtilen bayt alt aralığını yazar.
type: docs
weight: 209
url: /tr/system.net.sockets/networkstream/write/
---
## NetworkStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) yöntemi

Belirtilen bayt dizisinden akışa yazmak için belirtilen bayt alt aralığını yazar.

```cpp
void System::Net::Sockets::NetworkStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Yazılacak baytları içeren dizi. |
| offset | **int32_t** | Belirtilen dizide bayt cinsinden ofset. |
| size | **int32_t** | Yazılacak alt aralıktaki öğe sayısı. |

## NetworkStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) yöntemi

Belirtilen bayt dizisinden akışa yazmak için belirtilen bayt alt aralığını yazar.

```cpp
void System::Net::Sockets::NetworkStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Yazılacak baytları içeren dizi görünümü |
| offset | **int32_t** | **buffer** içinde alt aralığın başladığı 0 tabanlı öğe indeksi |
| size | **int32_t** | Yazılacak alt aralıktaki öğe sayısı |

## İlgili

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [NetworkStream](../)
* Ad alanı [System::Net::Sockets](../../)
* Kütüphane [Aspose.Slides](../../../)