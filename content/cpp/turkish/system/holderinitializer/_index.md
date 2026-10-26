---
title: HolderInitializer
second_title: Aspose.Slides for C++ API Referansı
description: Bu sınıf, nesne örneğine, lvalue veya rvalue farketmeksizin kalıcı bir referans elde etmek için kullanılır. Böyle bir referans elde etmek için, üç aşırı yüklemeye sahip 'HoldIfTemporary' yöntemini kullanın. Bunların ikisi rvalue'i parametre olarak alır ve sadece ona referansı döndürür. Üçüncüsü ise tersine, lvalue'i parametre olarak alır, bir işaretçi kopyası oluşturur ve ardından o kopyaya referans döndürür. Ayrıca sınıf, geçen değeri koşulsuz olarak tutmak için 'Hold' yöntemine sahiptir (yerel yığın üzerindeki değişkenlerin değerlerini veya onun alt referanslarını kopyalamak için kullanılır).
type: docs
weight: 1639
url: /tr/system/holderinitializer/
---
## HolderInitializer struct

Bu sınıf, nesne örneğine, lvalue veya rvalue farketmeksizin kalıcı bir referans elde etmek için kullanılır. Böyle bir referans elde etmek için, üç aşırı yüklemeye sahip olan 'HoldIfTemporary' yöntemini kullanın. Bunların ikisi rvalue'i parametre olarak alır ve sadece ona referansı döndürür. Üçüncüsü ise tersine, lvalue'i parametre olarak alır, bir işaretçi kopyası oluşturur ve ardından o kopyaya referans döndürür. Ayrıca sınıf, geçen değeri koşulsuz olarak tutmak için 'Hold' yöntemine sahiptir (yerel yığını üzerindeki değişkenlerin değerlerini veya onun alt referanslarını kopyalamak için kullanılır).

```cpp
template<typename T,bool>class HolderInitializer
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Tutulacak nesnenin tipi. |
| R | Doğru, eğer T bir referans tipi ise ([SmartPtr](../smartptr/) özelleştirmesi veya [System::String](../string/) tipi) ve geçici referansların tutulması gerçekten gerekli ise, aksi takdirde yanlış. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| const T\& [Hold](./hold/)(const T\&) | Verilen lvalue'i tutucuya kopyalar, ardından tutucu referansını döndürür. Çağıran, bu yöntemi geçilen değeri koşulsuz olarak tutmak için kullanmalıdır. |
| [HolderInitializer](./holderinitializer/)(T\&) | Tutucu referansını verilenle başlatır. |
| const T\& [HoldIfTemporary](./holdiftemporary/)(const T\&) | rvalue'e (const) referansı döndürür. |
| const T\& [HoldIfTemporary](./holdiftemporary/)(T\&) | rvalue'e (non-const) referansı döndürür. |
| const T\& [HoldIfTemporary](./holdiftemporary/)(T\&&) | Verilen lvalue'i tutucuya kopyalar, ardından tutucu referansını döndürür. |

## İlgili

* AdAlanı [System](../)
* Kütüphane [Aspose.Slides](../../)