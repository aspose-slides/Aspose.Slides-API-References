---
title: Read()
second_title: Aspose.Slides for C++ API Referansı
description: Eğer sarmalama modu ikili ise, akıştan belirtilen sayıda baytı okur, aksi takdirde belirtilen sayıda karakteri okuyup uint8_t tipine dönüştürür. Okuma sonucunu belirtilen bayt dizisine yazar. Desteklenmiyor!
type: docs
weight: 66
url: /tr/system.io/basicstdostreamwrapper/read/
---
## BasicSTDOStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) yöntemi


Eğer sarmalama modu ikili ise, akıştan belirtilen sayıda baytı okur, aksi takdirde belirtilen sayıda karakteri okuyup **uint8_t** tipine dönüştürür. Okumanın sonucunu belirtilen bayt dizisine yazar. Desteklenmiyor!

```cpp
virtual int32_t System::IO::BasicSTDOStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Okunan baytların yazılacağı bayt dizisi |
| offset | **int32_t** | **buffer** içinde yazmaya başlanacak 0 tabanlı konum |
| count | **int32_t** | Okunacak bayt sayısı |

### Dönüş Değeri

Okunan bayt veya karakter sayısı

## BasicSTDOStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) yöntemi


Akıştan belirtilen sayıda baytı okur ve bunları belirtilen bayt dizisine yazar.

```cpp
virtual int32_t System::IO::BasicSTDOStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Okunan baytların yazılacağı bayt dizisi görünümü |
| offset | **int32_t** | **buffer** içinde yazmaya başlanacak 0 tabanlı konum |
| count | **int32_t** | Okunacak bayt sayısı |

### Dönüş Değeri

Okunan bayt sayısı

## Ayrıca Bakınız

* Tip tanımı [ArrayPtr](../../../system/arrayptr/)
* Sınıf [BasicSTDOStreamWrapper](../)
* İsim alanı [System::IO](../../)
* Kütüphane [Aspose.Slides](../../../)