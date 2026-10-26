---
title: ConfigureAwait()
second_title: Aspose.Slides for C++ API Referansı
description: Bu görevdeki await'ların bağlam yakalama ile ilgili nasıl davranması gerektiğini yapılandırır.
type: docs
weight: 144
url: /tr/system.threading.tasks/task/configureawait/
---
## Task::ConfigureAwait(bool) const metodu

Bu görevdeki await'ların bağlam yakalama ile ilgili nasıl davranması gerektiğini yapılandırır.

```cpp
Runtime::CompilerServices::ConfiguredTaskAwaitable System::Threading::Tasks::Task::ConfigureAwait(bool continueOnCapturedContext) const
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | Yakalanan bağlamda devam edilip edilmeyeceği |

### Dönüş Değeri

[Runtime::CompilerServices::ConfiguredTaskAwaitable](../../../system.runtime.compilerservices/configuredtaskawaitable/) Yapılandırılmış bir awaitable

## Bakınız

* Sınıf [ConfiguredTaskAwaitable](../../../system.runtime.compilerservices/configuredtaskawaitable/)
* Sınıf [Task](../)
* Ad alanı [System::Threading::Tasks](../../)
* Kütüphane [Aspose.Slides](../../../)