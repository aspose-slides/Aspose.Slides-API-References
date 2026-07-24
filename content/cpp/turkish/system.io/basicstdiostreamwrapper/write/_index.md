---
title: Write()
second_title: Aspose.Slides for C++ API Referansı
description: Eğer sarmalama modu ikili ise, belirtilen bayt dizisinden belirtilen bayt alt aralığını akışa yazar; aksi takdirde belirtilen bayt dizisinden belirtilen bayt alt aralığını char_type türüne dönüştürür ve ardından sonucu akışa yazar.
type: docs
weight: 79
url: /tr/system.io/basicstdiostreamwrapper/write/
---
## BasicSTDIOStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metot

Eğer sarmalama modu ikili ise, belirtilen bayt dizisinden belirtilen bayt aralığını akışa yazar, aksi takdirde belirtilen bayt dizisinden belirtilen bayt aralığını char_type türüne dönüştürür ve ardından sonucu akışa yazar.

```cpp
virtual void System::IO::BasicSTDIOStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Yazılacak baytları içeren dizi |
| offset | **int32_t** | Yazma işleminin başlayacağı **buffer** içindeki 0 tabanlı indeks |
| count | **int32_t** | Yazılacak alt aralıktaki öğe sayısı |

## BasicSTDIOStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metot

Belirtilen bayt dizisinden belirtilen bayt aralığını akışa yazar.

```cpp
virtual void System::IO::BasicSTDIOStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Yazılacak baytları içeren dizi görünümü |
| offset | **int32_t** | Yazma işleminin başlayacağı **buffer** içindeki 0 tabanlı indeks |
| count | **int32_t** | Yazılacak alt aralıktaki öğe sayısı |

## Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [BasicSTDIOStreamWrapper](../)
* Ad alanı [System::IO](../../)
* Kütüphane [Aspose.Slides](../../../)