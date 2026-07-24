---
title: Read()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen akımdan belirtilen sayıda baytı okur ve bunları belirtilen bayt dizisine yazar.
type: docs
weight: 183
url: /tr/system.io/filestream/read/
---
## FileStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metod

Akıttan belirtilen sayıda baytı okur ve bunları belirtilen bayt dizisine yazar.

```cpp
int32_t System::IO::FileStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Okunan baytların yazılacağı bayt dizisi. |
| offset | **int32_t** | Yazmaya başlanacak **buffer** içinde 0 tabanlı konum. |
| count | **int32_t** | Okunacak bayt sayısı. |

### Dönüş Değeri

Okunan bayt sayısı.

## FileStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metod

Akıttan belirtilen sayıda baytı okur ve bunları belirtilen bayt dizisine yazar.

```cpp
int32_t System::IO::FileStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Okunan baytların yazılacağı bayt dizi görünümü. |
| offset | **int32_t** | Yazmaya başlanacak **buffer** içinde 0 tabanlı konum. |
| count | **int32_t** | Okunacak bayt sayısı. |

### Dönüş Değeri

Okunan bayt sayısı.

## Ayrıca Bakınız

* Tip Tanımı [ArrayPtr](../../../system/arrayptr/)
* Sınıf [FileStream](../)
* İsim Uzayı [System::IO](../../)
* Kütüphane [Aspose.Slides](../../../)