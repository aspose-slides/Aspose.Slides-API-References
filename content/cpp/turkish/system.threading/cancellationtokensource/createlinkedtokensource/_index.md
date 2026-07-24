---
title: CreateLinkedTokenSource()
second_title: Aspose.Slides for C++ API Referansı
description: Sağlanan belirteçlerden herhangi biri iptal edildiğinde iptal olan bağlı bir token kaynağı oluşturur.
type: docs
weight: 66
url: /tr/system.threading/cancellationtokensource/createlinkedtokensource/
---
## CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken&, const CancellationToken&) metod

Sağlanan belirteçlerden herhangi biri iptal edildiğinde iptal olan bağlı bir token kaynağı oluşturur.

```cpp
static SharedPtr<CancellationTokenSource> System::Threading::CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken &token1, const CancellationToken &token2)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| token1 | const [CancellationToken](../../cancellationtoken/)\& | İzlenecek ilk iptal belirteci. |
| token2 | const [CancellationToken](../../cancellationtoken/)\& | İzlenecek ikinci iptal belirteci. |

### Dönüş Değeri

Her iki giriş belirtecinden biri iptal edildiğinde iptal olacak yeni token kaynağı.

## Açıklamalar

Dönen kaynak, giriş belirtecinden biri zaten iptal edilmişse hemen iptal olur.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [CancellationTokenSource](../)
* Sınıf [CancellationToken](../../cancellationtoken/)
* Ad alanı [System::Threading](../../)
* Library [Aspose.Slides](../../../)