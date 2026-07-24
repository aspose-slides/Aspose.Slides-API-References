---
title: CancellationToken
second_title: Aspose.Slides for C++ API Referansı
description: İşlemlerin iptal edilmesi gerektiğini bildiren bildirimi yayar. Bu sınıf, iş parçacıkları arasında iş birliğine dayalı iptal mekanizması sağlar; bir iş parçacığının diğerlerine bir işlemin iptal edilmesi gerektiğini bildirmesine olanak tanır.
type: docs
weight: 14
url: /tr/system.threading/cancellationtoken/
---
## CancellationToken sınıfı

Propagates notification that operations should be canceled. This class provides a mechanism for cooperative cancellation between threads, allowing one thread to notify others that an operation should be canceled.

```cpp
class CancellationToken : public System::Details::BoxableObjectBase
```

## Metotlar

| Method | Açıklama |
| --- | --- |
|  [CancellationToken](./cancellationtoken/)() | Varsayılan yapıcı. |
| **bool** [get_CanBeCanceled](./get_canbecanceled/)() const | Bu token'in iptal durumunda olabilme yeteneğine sahip olup olmadığını alır. |
| **bool** [get_IsCancellationRequested](./get_iscancellationrequested/)() const | Bu token için iptal isteği yapılıp yapılmadığını alır. |
| static [CancellationToken](./) [get_None](./get_none/)() | Boş bir [System::Threading::CancellationToken](./) değeri döndürür. |
| [CancellationTokenRegistration](../cancellationtokenregistration/) [Register](./register/)(const [Action](../../system/action/)<>\&) const | İptal talep edildiğinde çağrılacak bir geri aramayı kaydeder. |
| void [ThrowIfCancellationRequested](./throwifcancellationrequested/)() const | İptal talep edilmişse bir OperationCanceledException fırlatır. |
## Notlar

A [CancellationToken](./) yalnızca ilişkilendirilmiş [CancellationTokenSource](../cancellationtokensource/) aracılığıyla iptal edilebilir. 

## Ayrıca bakınız

* Ad alanı [System::Threading](../)
* Kütüphane [Aspose.Slides](../../)