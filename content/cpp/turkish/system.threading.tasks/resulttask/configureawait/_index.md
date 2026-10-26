---
title: ConfigureAwait()
second_title: Aspose.Slides için C++ API Referansı
description: Bu sonuç görevindeki await'ların bağlam yakalama ile ilgili nasıl davranması gerektiğini yapılandırır.
type: docs
weight: 27
url: /tr/system.threading.tasks/resulttask/configureawait/
---
## ResultTask::ConfigureAwait(bool) const yöntemi

Bu sonuç görevinde await'ların bağlam yakalama ile ilgili nasıl davranması gerektiğini yapılandırır.

```cpp
Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> System::Threading::Tasks::ResultTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | Yakalanan bağlamda devam edip etmeyeceği |

### Dönüş Değeri

Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> Sonuç için yapılandırılmış bir awaitable

## Açıklamalar

Bu, async/await desenleri için bağlam akışı üzerinde ayrıntılı kontrol sağlar.

## Ayrıca Bakınız

* Sınıf [ConfiguredResultTaskAwaitable](../../../system.runtime.compilerservices/configuredresulttaskawaitable/)
* Sınıf [ResultTask](../)
* Ad alanı [System::Threading::Tasks](../../)
* Kütüphane [Aspose.Slides](../../../)