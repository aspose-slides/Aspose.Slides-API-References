---
title: Read()
second_title: Aspose.Slides for C++ API Referansı
description: Eğer sarma modu ikili ise, akıştan belirtilen sayıda baytı okur, aksi takdirde belirtilen sayıda karakteri okuyup uint8_t türüne dönüştürür. Okumanın sonucunu belirtilen bayt dizisine yazar.
type: docs
weight: 66
url: /tr/system.io/basicstdiostreamwrapper/read/
---
## BasicSTDIOStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metot

Eğer sarmalama modu ikili ise, akıştan belirtilen sayıda baytı okur, aksi takdirde belirtilen sayıda karakteri okuyup **uint8_t** türüne dönüştürür. Okuma sonucunu belirtilen bayt dizisine yazar.

```cpp
virtual int32_t System::IO::BasicSTDIOStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Okunan baytların yazılacağı bayt dizisi |
| offset | **int32_t** | **buffer** içinde 0 tabanlı, yazmaya başlanacak konum |
| count | **int32_t** | Okunacak bayt sayısı |

### Dönüş Değeri

Okunan bayt veya karakter sayısı

## BasicSTDIOStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metot

Akıştan belirtilen sayıda baytı okur ve bunları belirtilen bayt dizisine yazar.

```cpp
virtual int32_t System::IO::BasicSTDIOStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Okunan baytların yazılacağı bayt dizisi görünümü |
| offset | **int32_t** | **buffer** içinde 0 tabanlı, yazmaya başlanacak konum |
| count | **int32_t** | Okunacak bayt sayısı |

### Dönüş Değeri

Okunan bayt sayısı

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [BasicSTDIOStreamWrapper](../)
* Ad alanı [System::IO](../../)
* Library [Aspose.Slides](../../../)