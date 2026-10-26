---
title: WriteAsync()
second_title: Aspose.Slides for C++ API Referansı
description: Asenkron olarak mevcut akışa bir bayt dizisi yazar, bu akıştaki mevcut konumu yazılan bayt sayısı kadar ilerletir ve iptal isteklerini izler.
type: docs
weight: 261
url: /tr/system.io/filestream/writeasync/
---
## FileStream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) method


Akıcı bir şekilde mevcut akışa bir bayt dizisi yazar, bu akıştaki mevcut konumu yazılan bayt sayısı kadar ilerletir ve iptal isteklerini izler.

```cpp
TaskPtr System::IO::FileStream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Yazılacak baytları içeren dizi. |
| offset | **int32_t** | **buffer** içinde alt aralığın başladığı 0 tabanlı indeks. |
| count | **int32_t** | Yazılacak alt aralıktaki eleman sayısı. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | İptal isteklerini izlemek için kullanılan jeton. |

### Dönüş Değeri

Asenkron yazma işlemini temsil eden bir görev.

## Ayrıca Bakınız

* Tip Tanımı [TaskPtr](../../../system/taskptr/)
* Tip Tanımı [ArrayPtr](../../../system/arrayptr/)
* Sınıf [CancellationToken](../../../system.threading/cancellationtoken/)
* Sınıf [FileStream](../)
* Ad Alanı [System::IO](../../)
* Kütüphane [Aspose.Slides](../../../)