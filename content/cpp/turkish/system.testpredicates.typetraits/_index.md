---
title: "System::TestPredicates::TypeTraits"
second_title: Aspose.Slides for C++ API Referansı
description: 
type: docs
weight: 963
url: /tr/system.testpredicates.typetraits/
---
## Yapılar

| Struct | Açıklama |
| --- | --- |
| [has_data_method](./has_data_method/) | Bir tipin data() metoduna sahip olup olmadığını kontrol eder. Eğer varsa std::true_type miras alır, aksi takdirde std::false_type miras alır. |
| [has_data_method< System::Collections::BitArray, void >](./has_data_method_tmpl_system_collections_bitarray__void__end_tmpl/) | BitArray tipine özel bir özelleştirme; burada erişilemeyen boost tipini sağlar. |
| [has_print_to_method](./has_print_to_method/) | Verilen tipi ilk argüman olarak kabul eden PrintTo fonksiyonunun aşırı yüklemesini kontrol eder. Eğer bir aşırı yükleme varsa std::true_type miras alır, aksi takdirde std::false_type miras alır. |
| [IsCppContainer](./iscppcontainer/) | Belirli bir tipin STL tarzı konteyner olup olmadığını kontrol eder. Bunu yapmak için iterator ve const_iterator üye tiplerinin varlığını kontrol eder. İkisi de mevcutsa std::true_type miras alır, aksi takdirde std::false_type miras alır. |
| [IsEnumerable](./isenumerable/) | Tipin [System::Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/) özelleştirmesine temel tip olarak sahip olup olmadığını kontrol eder. Eğer öyleyse, value üyesi true olarak ayarlanır, aksi takdirde false olarak ayarlanır. |
| [LargestFPType](./largestfptype/) | Sağlanan en uzun kayan nokta tipi için bir takma ad sağlar. Kayan nokta olmayan tipleri görmezden gelir. |

## Typedef'ler

| Typedef | Açıklama |
| --- | --- |
| [AreFPandArithmetic](./arefpandarithmetic/) | **T1**'in aritmetik ve **T2**'in kayan nokta olduğunu, ya da tersini kontrol eder. Eğer öyleyse, value üyesini true olarak ayarlar, aksi takdirde false olur. |
| [AnyOfDecimal](./anyofdecimal/) | Tip argümanlarından en az birinin [System::Decimal](../system/decimal/) olup olmadığını kontrol eder. Eğer öyleyse, value üyesini true olarak ayarlar, aksi takdirde false olur. |
| [IsArray](./isarray/) | Tipin [System::Array](../system/array/) özelleştirmesi olup olmadığını kontrol eder. Eğer öyleyse, value üyesi true olarak ayarlanır, aksi takdirde false olarak ayarlanır. |
| [IsList](./islist/) | Tipin [System::Collections::Generic::List](../system.collections.generic/list/) özelleştirmesi olup olmadığını kontrol eder. Eğer öyleyse, value üyesi true olarak ayarlanır, aksi takdirde false olarak ayarlanır. |
| [BothArrayOrList](./botharrayorlist/) | Her iki tip argümanının da dizi veya liste olup olmadığını kontrol eder. Eğer öyleyse, value üyesi true olarak ayarlanır, aksi takdirde false olarak ayarlanır. |
| [BothEnumerable](./bothenumerable/) | Her iki tip argümanının da IEnumerable olup olmadığını kontrol eder. Eğer öyleyse, value üyesi true olarak ayarlanır, aksi takdirde false olarak ayarlanır. |