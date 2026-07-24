---
title: SmartPtrInfo
second_title: Aspose.Slides C++ API Referansı
description: Final tipini bilmeden SmartPtr'in içeriğini test etmek ve değiştirmek için hizmet sınıfı. Çöp toplama ve döngü referanslarının tespiti vb. amaçlarla kullanılır. Bunu 'pointer to pointer' olarak düşünebilirsiniz. SmartPtr'in temel tipi olmadığı için kullanamıyoruz; bunun yerine bu 'info' sınıfını kullanıyoruz.
type: docs
weight: 1249
url: /tr/system/smartptrinfo/
---
## SmartPtrInfo sınıf

Hizmet sınıfı, final tipi bilinmeden [SmartPtr](../smartptr/)'nin içeriğini test etmek ve değiştirmek için kullanılır. Çöp toplama ve döngü referanslarının tespiti gibi amaçlar için kullanılır, vb. 'pointer to pointer' (işaretçiden işaretçiye) gibi düşünün. [SmartPtr](../smartptr/)'nin temel tipi olmadığı için kullanamıyoruz; bunun yerine bu 'info' sınıfını kullanıyoruz.

```cpp
class SmartPtrInfo
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| const void * [getInternalPtr](./getinternalptr/)() const | İşaret edilen işaretçinin işaret ettiği ham nesneyi alır. |
| [Object](../object/) * [getObject](./getobject/)() const | İşaret edilen işaretçinin işaret ettiği nesneyi alır. |
| [Object](../object/) * [getOwned](./getowned/)() const | Nesneye ait işaretçiyi alır. |
|  [operator bool](./operator_bool/)() const | Info nesnesinin null olmayan bir işaretçiye işaret edip etmediğini kontrol eder. |
| **bool** [operator!](./operator_not/)() const | Info nesnesinin null olmayan bir işaretçiye işaret etmediğini kontrol eder. |
| [Object](../object/) * [operator->](./operator_minus_greater/)() const | İşaret edilen işaretçi tarafından işaret edilen [Object](../object/)'in yöntemlerini çağırmaya izin verir. |
| **bool** [operator<](./operator_less/)(const [SmartPtrInfo](./)\&) const | İki info nesnesi tarafından referans verilen işaretçilerin değerlerini < ile karşılaştırır. |
|  [SmartPtrInfo](./smartptrinfo/)() | Boş bir [SmartPtrInfo](./) nesnesi oluşturur. |
| explicit  [SmartPtrInfo](./smartptrinfo/)(const [SmartPtr](../smartptr/)\<T\>\&) | Belirli bir akıllı işaretçi hakkında bilgi içeren [SmartPtrInfo](./) nesnesi oluşturur. |

## Ayrıca Bakınız

* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)