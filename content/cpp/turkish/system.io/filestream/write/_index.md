---
title: Write()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen bayt dizisinden belirtilen alt aralığı akışa yazar.
type: docs
weight: 248
url: /tr/system.io/filestream/write/
---
## FileStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metot


Belirtilen bayt dizisinden belirtilen alt aralığı akışa yazar.

```cpp
void System::IO::FileStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Yazılacak baytları içeren dizi. |
| offset | **int32_t** | Yazma alt aralığının başladığı **buffer** içindeki 0 tabanlı indeks. |
| count | **int32_t** | Yazılacak alt aralıktaki öğe sayısı. |

## FileStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metot


Belirtilen bayt dizisinden belirtilen alt aralığı akışa yazar.

```cpp
void System::IO::FileStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Yazılacak baytları içeren dizi görünümü. |
| offset | **int32_t** | Yazma alt aralığının başladığı **buffer** içindeki 0 tabanlı indeks. |
| count | **int32_t** | Yazılacak alt aralıktaki öğe sayısı. |

## Ayrıca Bakınız

* Tip Tanımı [ArrayPtr](../../../system/arrayptr/)
* Sınıf [FileStream](../)
* Ad Alanı [System::IO](../../)
* Kütüphane [Aspose.Slides](../../../)