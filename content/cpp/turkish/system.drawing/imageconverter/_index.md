---
title: ImageConverter
second_title: Aspose.Slides for C++ API Referansı
description: "Image nesnelerini bir veri tipinden diğerine dönüştürür. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tipin bir örneğini yığına veya operator new ile asla oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr göstericisine sarın ve bu göstericiyi fonksiyonlara argüman olarak geçirin."
type: docs
weight: 157
url: /tr/system.drawing/imageconverter/
---
## ImageConverter sınıfı

[Image](../image/) nesnelerini bir veri tipinden diğerine dönüştürür. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin bir örneğini yığına ya da operator new ile oluşturmaya asla izin vermeyin, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) göstericisine sarın ve bu göstericiyi fonksiyonlara argüman olarak geçirin.

```cpp
class ImageConverter : public System::ComponentModel::TypeConverter
```

## Yöntemler

| Method | Açıklama |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertFrom](../../system.componentmodel/typeconverter/convertfrom/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | Nesneleri dönüştürür. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertFrom](../../system.componentmodel/typeconverter/convertfrom/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../../system.componentmodel/itypedescriptorcontext/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | Nesneleri dönüştürür. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertFrom](../../system.componentmodel/typeconverter/convertfrom/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../../system.componentmodel/itypedescriptorcontext/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, const [System::String](../../system/string/)\&) | Dizeyi nesneye dönüştürür. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertFromInvariantString](../../system.componentmodel/typeconverter/convertfrominvariantstring/)(const [System::String](../../system/string/)\&) | Değişmez dizeyi nesneye dönüştürür. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertFromInvariantString](../../system.componentmodel/typeconverter/convertfrominvariantstring/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../../system.componentmodel/itypedescriptorcontext/)\>\&, const [System::String](../../system/string/)\&) | Değişmez dizeyi nesneye dönüştürür. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertFromString](../../system.componentmodel/typeconverter/convertfromstring/)(const [System::String](../../system/string/)\&) | Dizeyi nesneye dönüştürür. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertFromString](../../system.componentmodel/typeconverter/convertfromstring/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../../system.componentmodel/itypedescriptorcontext/)\>\&, const [System::String](../../system/string/)\&) | Dizeyi nesneye dönüştürür. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertFromString](../../system.componentmodel/typeconverter/convertfromstring/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../../system.componentmodel/itypedescriptorcontext/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, const [System::String](../../system/string/)\&) | Dizeyi nesneye dönüştürür. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertTo](./convertto/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::ComponentModel::ITypeDescriptorContext](../../system.componentmodel/itypedescriptorcontext/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&, const [System::TypeInfo](../../system/typeinfo/)\&) override | Nesneyi belirli türe dönüştürür. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertTo](../../system.componentmodel/typeconverter/convertto/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&, const [System::TypeInfo](../../system/typeinfo/)\&) | Nesneyi belirli türe dönüştürür. |
| [System::String](../../system/string/) [ConvertToInvariantString](../../system.componentmodel/typeconverter/converttoinvariantstring/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | Nesneyi değişmez dizeye dönüştürür. |
| [System::String](../../system/string/) [ConvertToInvariantString](../../system.componentmodel/typeconverter/converttoinvariantstring/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../../system.componentmodel/itypedescriptorcontext/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | Nesneyi değişmez dizeye dönüştürür. |
| [System::String](../../system/string/) [ConvertToString](../../system.componentmodel/typeconverter/converttostring/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | Nesneyi dizeye dönüştürür. |
| [System::String](../../system/string/) [ConvertToString](../../system.componentmodel/typeconverter/converttostring/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../../system.componentmodel/itypedescriptorcontext/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | Nesneyi dizeye dönüştürür. |
| [System::String](../../system/string/) [ConvertToString](../../system.componentmodel/typeconverter/converttostring/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../../system.componentmodel/itypedescriptorcontext/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | Nesneyi dizeye dönüştürür. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) anlamı kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans tipi nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer tipi nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# tarzı kayan nokta karşılaştırmasını taklit eder; iki NaN, IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit olmamasına rağmen eşit kabul edilir. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# tarzı kayan nokta karşılaştırmasını taklit eder; iki NaN, IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit olmamasına rağmen eşit kabul edilir. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayaç veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin analoğudur. Özel nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| [ImageConverter](./imageconverter/)() | [ImageConverter](./) yeni bir örnek oluşturur. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin örneği olup olmadığını denetler. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesi kilitlemeyi uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin analoğudur. Özel tiplerin klonlanmasını sağlar. |
| [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapılarını başlatır. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referans, değer tipi nesneyi nullptr ile karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | String ve nullptr durumu için [Object::ReferenceEquals](../../system/object/referenceequals/) özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | String durumları için [Object::ReferenceEquals](../../system/object/referenceequals/) özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf gösterici (paylaşılan yerine) olarak ayarlar. Kapsayıcılardaki göstericilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin analoğudur. Özel nesnelerin dizeye dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| [TypeConverter](../../system.componentmodel/typeconverter/typeconverter/)() | Yapıcı. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesi kilidi kaldırmayı uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [TypeConverter](../../system.componentmodel/typeconverter/)
* Ad alanı [System::Drawing](../)
* Kütüphane [Aspose.Slides](../../)