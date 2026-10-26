---
title: DbProviderFactories
second_title: Aspose.Slides for C++ API Referansı
description: "DB sağlayıcı fabrikalarını almak için API. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örneği yığına (stack) veya operator new kullanarak oluşturmamalısınız; aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları oluşur. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin."
type: docs
weight: 53
url: /tr/system.data.common/dbproviderfactories/
---
## DbProviderFactories sınıf


API to get DB provider factories. Objects of this sınıf should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this sınıf into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class DbProviderFactories
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[DbProviderFactory](../dbproviderfactory/)\> [GetFactory](./getfactory/)(const [String](../../system/string/)\&) | Adına göre DB provider factory alır. |
## Ayrıca Bakınız

* Ad alanı [System::Data::Common](../)
* Kütüphane [Aspose.Slides](../../)