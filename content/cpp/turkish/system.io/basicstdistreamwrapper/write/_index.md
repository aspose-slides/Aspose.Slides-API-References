---
title: Write()
second_title: Aspose.Slides for C++ API Referansı
description: Eğer sarmalama modu ikili ise, belirtilen bayt dizisinden belirtilen alt aralığı akışa yazar; aksi takdirde belirtilen bayt dizisinden belirtilen alt aralığı char_type tipine dönüştürür ve ardından sonucu akışa yazar. Desteklenmiyor!
type: docs
weight: 79
url: /tr/system.io/basicstdistreamwrapper/write/
---
## BasicSTDIStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metodu


Eğer sarmalama modu ikili ise, belirtilen bayt dizisinden belirtilen alt aralığı akışa yazar, aksi takdirde belirtilen bayt dizisinden belirtilen alt aralığı **char_type** tipine dönüştürür ve ardından sonucu akışa yazar. Desteklenmiyor!

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Yazılacak baytları içeren dizi. |
| offset | **int32_t** | **buffer** içinde yazılacak alt aralığın başladığı 0 tabanlı indis. |
| count | **int32_t** | Yazılacak alt aralığın eleman sayısı. |

## BasicSTDIStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metodu


Belirtilen bayt dizisinden belirtilen alt aralığı akışa yazar.

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Yazılacak baytları içeren dizi görünümü |
| offset | **int32_t** | **buffer** içinde yazılacak alt aralığın başladığı 0 tabanlı indis |
| count | **int32_t** | Yazılacak alt aralığın eleman sayısı |

## İlgili

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [BasicSTDIStreamWrapper](../)
* Ad alanı [System::IO](../../)
* Kütüphane [Aspose.Slides](../../../)