---
title: GetAwaiter()
second_title: Aspose.Slides for C++ API Referansı
description: Bu sonuç görevi için Await ile kullanılmak üzere bir awaiter alır.
type: docs
weight: 53
url: /tr/system.threading.tasks/resulttask/getawaiter/
---
## ResultTask::GetAwaiter() const metot

Bu sonuç görevi için Await ile kullanılacak bir awaiter alır.

```cpp
Runtime::CompilerServices::ResultTaskAwaiter<T> System::Threading::Tasks::ResultTask<T>::GetAwaiter() const
```

### Dönüş Değeri

Runtime::CompilerServices::ResultTaskAwaiter<T> Sonucu döndüren bir awaiter örneği

## Açıklamalar

Await edildiğinde, coroutine sonuç değeri mevcut olacak şekilde devam eder.

## İlgili

* Sınıf [ResultTaskAwaiter](../../../system.runtime.compilerservices/resulttaskawaiter/)
* Sınıf [ResultTask](../)
* Ad Alanı [System::Threading::Tasks](../../)
* Kütüphane [Aspose.Slides](../../../)