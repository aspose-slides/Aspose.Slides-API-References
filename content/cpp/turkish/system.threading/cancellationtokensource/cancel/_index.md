---
title: Cancel()
second_title: Aspose.Slides for C++ API Referansı
description: İptal isteğini iletir.
type: docs
weight: 40
url: /tr/system.threading/cancellationtokensource/cancel/
---
## CancellationTokenSource::Cancel() metod

İptal isteğini iletir.

```cpp
void System::Threading::CancellationTokenSource::Cancel()
```

## Açıklamalar

Tüm kayıtlı geri aramalar çağrılacaktır.

Sonraki çağrılar [get_IsCancellationRequested()](../get_iscancellationrequested/) true döndürecektir.

Geri aramalar bu çağrı sırasında senkron olarak yürütülür.

## Diğerlerine Bak

* Sınıf [CancellationTokenSource](../)
* Ad alanı [System::Threading](../../)
* Kütüphane [Aspose.Slides](../../../)