---
title: BuildObject()
second_title: Aspose.Slides için C++ API Referansı
description: Paylaşımlı sahiplikle bir nesne oluşturur.
type: docs
weight: 2250
url: /tr/system/buildobject/
---
## System::BuildObject(Args&&...) fonksiyonu


Paylaşımlı sahiplikle bir nesne oluşturur.

```cpp
template<typename T,typename...> Details::ObjectBuilder<T, SharedPtr<T>> System::BuildObject(Args &&... args)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Oluşturulacak nesnenin türü |
| Args | Nesne oluşturma için argüman türleri |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| args | Args&&... | Nesne yapıcısına iletilecek argümanlar |

### Dönüş Değeri

ObjectBuilder, paylaşımlı gösterici oluşturma için yapılandırıldı
## Açıklamalar



Bir SharedPtr<T> oluşturur ve onun için bir builder döndürür
[Object](../object/) oluşturma, [Get()](../get/) çağrısı ile tamamlanmalıdır 

## Ayrıca Bakınız

* Typedef [SharedPtr](../sharedptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)