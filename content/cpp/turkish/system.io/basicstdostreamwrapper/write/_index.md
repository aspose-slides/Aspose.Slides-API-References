---
title: Write()
second_title: Aspose.Slides for C++ API Referansı
description: Eğer sargı modu ikili ise, belirtilen bayt dizisinden belirtilen bayt alt aralığını akışa yazar, aksi takdirde belirtilen bayt dizisinden belirtilen bayt alt aralığını char_type tipine dönüştürür ve ardından sonucu akışa yazar.
type: docs
weight: 79
url: /tr/system.io/basicstdostreamwrapper/write/
---
## BasicSTDOStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metot

Eğer sargı modu ikili ise, belirtilen bayt dizisinden belirtilen bayt alt aralığını akışa yazar, aksi takdirde belirtilen bayt alt aralığını bayt dizisinden char_type tipine dönüştürür ve ardından sonucu akışa yazar.

```cpp
virtual void System::IO::BasicSTDOStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Yazılacak baytları içeren dizi |
| offset | **int32_t** | Yazılacak alt aralığın başladığı **buffer** içinde 0 tabanlı bir indeks |
| count | **int32_t** | Yazılacak alt aralığın eleman sayısı |

## BasicSTDOStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metot

Belirtilen bayt dizisinden belirtilen bayt alt aralığını akışa yazar.

```cpp
virtual void System::IO::BasicSTDOStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Yazılacak baytları içeren dizi görünümü |
| offset | **int32_t** | Yazılacak alt aralığın başladığı **buffer** içinde 0 tabanlı bir indeks |
| count | **int32_t** | Yazılacak alt aralığın eleman sayısı |

## İlgili

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [BasicSTDOStreamWrapper](../)
* AdAlanı [System::IO](../../)
* Kütüphane [Aspose.Slides](../../../)