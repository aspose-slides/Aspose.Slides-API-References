---
title: InitObject()
second_title: Aspose.Slides for C++ API Referansı
description: Paylaşımlı sahiplikle bir nesnenin başlatılmasını başlatır.
type: docs
weight: 2263
url: /tr/system/initobject/
---
## System::InitObject(const SharedPtr\<T\>\&) function

Paylaşımlı sahiplikle bir nesnenin başlatılmasını başlatır.

```cpp
template<typename T> Details::ObjectBuilder<T, SharedPtr<T>> System::InitObject(const SharedPtr<T> &object)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Başlatılacak nesnenin tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<T\>\& | [Object](../object/) başlatmak için |

### Dönüş Değeri

ObjectBuilder configured for shared pointer construction

## Açıklamalar

[Object](../object/) başlatması [Get()](../get/) çağrısı ile tamamlanmalıdır

## Ayrıca Bakınız

* Typedef [SharedPtr](../sharedptr/)
* Ad Alanı [System](../)
* Library [Aspose.Slides](../../)