---
title: WriteAsync()
second_title: Aspose.Slides for C++ API Referansı
description: Mevcut akışa asenkron olarak bir bayt dizisi yazar, bu akıştaki konumu yazılan bayt sayısı kadar ilerletir ve iptal isteklerini izler.
type: docs
weight: 66
url: /tr/system.io/stream/writeasync/
---
## Stream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) metodu


Asenkron olarak bir bayt dizisini geçerli akışa yazar, bu akıştaki konumu yazılan bayt sayısı kadar ilerletir ve iptal isteklerini izler.

```cpp
virtual TaskPtr System::IO::Stream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Yazılacak baytları içeren dizi. |
| offset | **int32_t** | **buffer** içinde yazma alt aralığının başladığı 0 tabanlı indeks. |
| count | **int32_t** | Yazılacak alt aralıktaki öğe sayısı. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | İptal isteklerini izlemek için kullanılan token. |

### Dönüş Değeri

Asenkron yazma işlemini temsil eden bir görev.

## Stream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metodu


Asenkron olarak bir bayt dizisini geçerli akışa yazar, bu akıştaki konumu yazılan bayt sayısı kadar ilerletir ve iptal isteklerini izler.

```cpp
TaskPtr System::IO::Stream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Yazılacak baytları içeren dizi. |
| offset | **int32_t** | **buffer** içinde yazma alt aralığının başladığı 0 tabanlı indeks. |
| count | **int32_t** | Yazılacak alt aralıktaki öğe sayısı. |

### Dönüş Değeri

Asenkron yazma işlemini temsil eden bir görev.

## Ayrıca Bakınız

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [CancellationToken](../../../system.threading/cancellationtoken/)
* Sınıf [Stream](../)
* AdAlanı [System::IO](../../)
* Library [Aspose.Slides](../../../)