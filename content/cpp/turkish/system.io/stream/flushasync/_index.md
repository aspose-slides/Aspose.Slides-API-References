---
title: FlushAsync()
second_title: Aspose.Slides for C++ API Referansı
description: Bu akış için tüm tamponları asenkron olarak temizler, tamponlanmış verilerin temel cihaza yazılmasını sağlar ve iptal isteklerini izler.
type: docs
weight: 118
url: /tr/system.io/stream/flushasync/
---
## Stream::FlushAsync(const Threading::CancellationToken\&) metodu

Bu akış için tüm tamponları asenkron olarak temizler, tamponlanmış verilerin temel cihaza yazılmasını sağlar ve iptal isteklerini izler.

```cpp
virtual TaskPtr System::IO::Stream::FlushAsync(const Threading::CancellationToken &cancellationToken)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | İptal isteklerini izlemek için kullanılan token. |

### Dönüş Değeri

Asenkron temizleme işlemini temsil eden bir görev.

## Stream::FlushAsync() metodu

Bu akış için tüm tamponları asenkron olarak temizler, tamponlanmış verilerin temel cihaza yazılmasını sağlar ve iptal isteklerini izler.

```cpp
TaskPtr System::IO::Stream::FlushAsync()
```

### Dönüş Değeri

Asenkron temizleme işlemini temsil eden bir görev.

## İlgili

* Typedef [TaskPtr](../../../system/taskptr/)
* Sınıf [CancellationToken](../../../system.threading/cancellationtoken/)
* Sınıf [Stream](../)
* İsim Alanı [System::IO](../../)
* Kütüphane [Aspose.Slides](../../../)