---
title: ReadAsync()
second_title: Aspose.Slides for C++ API Referansı
description: Geçerli akıştan bir bayt dizisini asenkron olarak okur, okunan bayt sayısı kadar akış içindeki konumu ilerletir ve iptal isteklerini izler.
type: docs
weight: 196
url: /tr/system.io/filestream/readasync/
---
## FileStream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) metodu

Geçerli akıştan bir bayt dizisini asenkron olarak okur, okunan bayt sayısı kadar akış içindeki konumu ilerletir ve iptal isteklerini izler.

```cpp
RTaskPtr<int32_t> System::IO::FileStream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Okunan baytların yazılacağı bayt dizisi. |
| offset | **int32_t** | **buffer** içinde yazmaya başlanacak 0 tabanlı konum. |
| count | **int32_t** | Okunacak bayt sayısı. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | İptal isteklerini izlemek için kullanılan token. |

### Dönüş Değeri

Asenkron okuma işlemini temsil eden bir görev. TResult parametresinin değeri, tampon içine okunan toplam bayt sayısını içerir. Sonuç değeri, mevcut bayt sayısı istenen sayıdan az ise istenen bayt sayısından daha az olabilir veya akışın sonuna ulaşılmışsa 0 (sıfır) olabilir.

## Ayrıca Bakınız

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [CancellationToken](../../../system.threading/cancellationtoken/)
* Sınıf [FileStream](../)
* Ad alanı [System::IO](../../)
* Kütüphane [Aspose.Slides](../../../)