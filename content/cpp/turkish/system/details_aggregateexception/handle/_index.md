---
title: Handle()
second_title: Aspose.Slides için C++ API Referansı
description: Her iç istisna için bir işleyici fonksiyonunu çağırır ve işlenmemiş istisnaları yeniden fırlatır.
type: docs
weight: 66
url: /tr/system/details_aggregateexception/handle/
---
## Details_AggregateException::Handle(const Func\<Exception, bool\>\&) method

Inner exception'lar üzerinde bir işleyici fonksiyonunu çağırır ve işlenmemiş istisnaları yeniden fırlatır.

```cpp
void System::Details_AggregateException::Handle(const Func<Exception, bool> &predicate)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| predicate | const [Func](../../func/)\<[Exception](../../exception/), **bool**\>\& | Bir Exception alıp işlendiyse true dönen fonksiyon. |
## Açıklamalar

Tüm istisnalar işlendiyse, yöntem normal şekilde döner; aksi takdirde, işlenmemiş istisnaları içeren yeni bir AggregateException fırlatılır.

## Ayrıca Bakınız

* Typedef [Exception](../../exception/)
* Class [Func](../../func/)
* Class [Details_AggregateException](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)