---
title: ReadAsync()
second_title: Aspose.Slides for C++ API Referansı
description: Geçerli akıştan bir bayt dizisini asenkron olarak okur, okunan bayt sayısı kadar akış içinde konumu ilerletir ve iptal isteklerini izler.
type: docs
weight: 40
url: /tr/system.io/stream/readasync/
---
## Stream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) method

Geçerli akıştan bir bayt dizisini asenkron olarak okur, okunan bayt sayısı kadar akış içindeki konumu ilerletir ve iptal isteklerini izler.

```cpp
virtual RTaskPtr<int32_t> System::IO::Stream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Okunan baytların yazılacağı bayt dizisi. |
| offset | **int32_t** | **buffer** içinde yazmaya başlanacak 0-tabanlı konum. |
| count | **int32_t** | Okunacak bayt sayısı. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | İptal isteklerini izlemek için kullanılan belirteç. |

### Dönüş Değeri

Asenkron okuma işlemini temsil eden bir görev. TResult parametresinin değeri, baytlara okunan toplam bayt sayısını içerir. Sonuç değeri, mevcut kullanılabilir bayt sayısı istenen sayının altında olduğunda daha az olabilir veya akışın sonuna gelinmişse 0 (sıfır) olabilir.

## Stream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

Geçerli akıştan bir bayt dizisini asenkron olarak okur, okunan bayt sayısı kadar akış içindeki konumu ilerletir ve iptal isteklerini izler.

```cpp
RTaskPtr<int32_t> System::IO::Stream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Okunan baytların yazılacağı bayt dizisi. |
| offset | **int32_t** | **buffer** içinde yazmaya başlanacak 0-tabanlı konum. |
| count | **int32_t** | Okunacak bayt sayısı. |

### Dönüş Değeri

Asenkron okuma işlemini temsil eden bir görev. TResult parametresinin değeri, baytlara okunan toplam bayt sayısını içerir. Sonuç değeri, mevcut kullanılabilir bayt sayısı istenen sayının altında olduğunda daha az olabilir veya akışın sonuna gelinmişse 0 (sıfır) olabilir.

## Ayrıca Bakınız

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [CancellationToken](../../../system.threading/cancellationtoken/)
* Sınıf [Stream](../)
* Ad alanı [System::IO](../../)
* Library [Aspose.Slides](../../../)