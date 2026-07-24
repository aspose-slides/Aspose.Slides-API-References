---
title: CancellationTokenRegistration
second_title: Aspose.Slides for C++ API Referansı
description: İptal token geri çağırması için bir kaydı temsil eder.
type: docs
weight: 27
url: /tr/system.threading/cancellationtokenregistration/
---
## CancellationTokenRegistration sınıfı

Bir iptal token geri çağırması için bir kaydı temsil eder.

```cpp
class CancellationTokenRegistration
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| void [Dispose](./dispose/)() | Kayıt nesnesini temizler ve geri çağırmayı ilgili [CancellationTokenSource](../cancellationtokensource/)'den kaldırır. Bu yöntemi çağırdıktan sonra, kayıtlı geri çağırma, ilgili [CancellationTokenSource](../cancellationtokensource/) iptal edildiğinde artık çalıştırılmaz. |
## Açıklamalar

Bu sınıf, bir iptal token'ından geri çağırmanın kaydını kaldırmayı sağlar. Temizlendiğinde, geri çağırmayı ilgili [CancellationTokenSource](../cancellationtokensource/)'den kaldırır. Bu sınıf doğrudan oluşturulmamalıdır - [CancellationToken](../cancellationtoken/) kayıt yöntemleri tarafından döndürülür.

## Ayrıca Bakınız

* Namespace [System::Threading](../)
* Kütüphane [Aspose.Slides](../../)