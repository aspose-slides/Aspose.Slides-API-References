---
title: FlushAsync()
second_title: Aspose.Slides for C++ API Referansı
description: Bu akış için tüm tamponları asenkron olarak temizler, tamponlanmış verilerin temel cihaza yazılmasını sağlar ve iptal isteklerini izler.
type: docs
weight: 157
url: /tr/system.io/filestream/flushasync/
---
## FileStream::FlushAsync(const Threading::CancellationToken\&) metodu

Bu akış için tüm tamponları asenkron olarak temizler, tamponlanmış verilerin temel cihaza yazılmasını sağlar ve iptal isteklerini izler.

```cpp
TaskPtr System::IO::FileStream::FlushAsync(const Threading::CancellationToken &cancellationToken) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | İptal isteklerini izlemek için kullanılan belirteç. |

### Dönüş Değeri

Asenkron flush işlemini temsil eden bir görev.

## Ayrıca Bakınız

* Typedef [TaskPtr](../../../system/taskptr/)
* Sınıf [CancellationToken](../../../system.threading/cancellationtoken/)
* Sınıf [FileStream](../)
* Ad Alanı [System::IO](../../)
* Library [Aspose.Slides](../../../)