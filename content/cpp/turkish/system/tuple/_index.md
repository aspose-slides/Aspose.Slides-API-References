---
title: Tuple
second_title: Aspose.Slides for C++ API Referansı
description: Tuple veri yapısını temsil eden sınıf. Azami öğe sayısı 8'dir.
type: docs
weight: 1353
url: /tr/system/tuple/
---
## Tuple sınıfı

Bir tuple veri yapısını temsil eden sınıf. Azami öğe sayısı 8'dir.

```cpp
template<typename ...>class Tuple : public System::Runtime::CompilerServices::ITuple
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Args | Tuple öğelerinin tipleri. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) override | Geçerli ve belirtilen nesnelerin aynı olup olmadığını belirler. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | C# [Object.Equals](../object/equals/) sözdizimini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans tipi nesneleri karşılaştırır. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | C# tarzı kayan nokta karşılaştırmasını taklit eder; iki NaN değeri IEC 60559:1989'a göre hiçbir değere, NaN dahil, eşit olmasa da eşit kabul edilir. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | C# tarzı kayan nokta karşılaştırmasını taklit eder; iki NaN değeri IEC 60559:1989'a göre hiçbir değere, NaN dahil, eşit olmasa da eşit kabul edilir. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| std::tuple_element\<[Index](../index/), tuple_t\>::type [get_Item](./get_item/)() const | [Tuple](./) nesnesinin bileşen değerini alır. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | C# [Object.GetHashCode()](../object/gethashcode/) metodunun analogu. Özel nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../object/gettype/) çağrısının analogu. |
| virtual [SharedPtr](../sharedptr/)\<[Object](../object/)\> [idx_get](../../system.runtime.compilerservices/ituple/idx_get/)(**int32_t**) const | Belirtilen indeks konumundaki öğeyi döndürür. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün analogu. |
| void [Lock](../object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../lockcontext/) bekçi nesnesini kullanın. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../object/memberwiseclone/) metodunun analogu. Özel tiplerin kopyalanmasını sağlar. |
|  [Object](../object/object/)() | Nesne oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../object/object/)([Object](../object/) const\&) | Kopya yapıcı. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını mümkün kılar. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Atama operatörü. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını mümkün kılar. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/)'in string ve nullptr durumu için uzmanlaşması. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/)'nin string durumları için uzmanlaşması. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşılan yerine) olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçişine izin verir. |
| int [SharedCount](../object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanın. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanın. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | C# [Object.ToString()](../object/tostring/) metodunun analogu. Özel nesnelerin string'e dönüştürülmesini sağlar. |
|  [Tuple](./tuple/)(Args...) | Bir tuple nesnesi oluşturur. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | C# typeof([System.Object](../object/)) yapısını uygular. |
| void [Unlock](../object/unlock/)() | C# lock() ifadesinin kilit açma işlemini uygular. Doğrudan çağırın veya [LockContext](../lockcontext/) bekçi nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanın. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler ve ThisProtector kullanın. |
| virtual  [~Object](../object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |
## Açıklamalar



```cpp
#include "system/smart_ptr.h"
#include "system/tuple.h"
#include <iostream>

int main()
{
  const auto tuple = System::MakeObject<System::Tuple<int, int, int>>(32, 16, 128);

  std::cout <<
    "Item 1: " << tuple->get_Item<0>() << std::endl <<
    "Item 2: " << tuple->get_Item<1>() << std::endl <<
    "Item 3: " << tuple->get_Item<2>() << std::endl;

  return 0;
}
/*
Bu kod örneği aşağıdaki çıktıyı üretir:
Öğe 1: 32
Öğe 2: 16
Öğe 3: 128
*/
```

## Ayrıca Bakınız

* Sınıf [ITuple](../../system.runtime.compilerservices/ituple/)
* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)