---
title: ExcelDataWorkbook
second_title: Aspose.Slides for C++ API Referansı
description: Genel kullanım için Excel verilerine erişim sağlayan bir çalışma kitabını temsil eder.
type: docs
weight: 14
url: /tr/aspose.slides.excel/exceldataworkbook/
---
## ExcelDataWorkbook sınıf

Genel kullanım için [Excel](../) verilerine erişim sağlayan bir çalışma kitabını temsil eder.

```cpp
class ExcelDataWorkbook : public Aspose::Slides::Excel::IExcelDataWorkbook
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) sözdizimini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans tipindeki nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer tipindeki nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
|  [ExcelDataWorkbook](./exceldataworkbook/)([System::String](../../system/string/)) | Belirtilen dosya yolunu kullanarak yeni bir örnek başlatır. |
|  [ExcelDataWorkbook](./exceldataworkbook/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Sağlanan akışı kullanarak sınıfın yeni bir örneğini başlatır. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [System::SharedPtr](../../system/sharedptr/)\<[IExcelDataCell](../iexceldatacell/)\> [GetCell](./getcell/)(**int32_t**, **int32_t**, **int32_t**) override | Belirtilen çalışma sayfasından hücreyi, indeksi ve hücre koordinatlarını kullanarak alır. |
| [System::SharedPtr](../../system/sharedptr/)\<[IExcelDataCell](../iexceldatacell/)\> [GetCell](./getcell/)([System::String](../../system/string/), **int32_t**, **int32_t**) override | Belirtilen çalışma sayfasından hücreyi, adını ve hücre koordinatlarını kullanarak alır. |
| [System::SharedPtr](../../system/sharedptr/)\<[IExcelDataCell](../iexceldatacell/)\> [GetCell](./getcell/)(**int32_t**, [System::String](../../system/string/)) override | Belirtilen çalışma sayfasından hücreyi, indeksi ve Excel tarzı hücre adı (ör. "B2") kullanarak alır. |
| [System::SharedPtr](../../system/sharedptr/)\<[IExcelDataCell](../iexceldatacell/)\> [GetCell](./getcell/)([System::String](../../system/string/), [System::String](../../system/string/)) override | Belirtilen çalışma sayfasından hücreyi Excel tarzı hücre adı (ör. "B2") kullanarak alır. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[IExcelDataCell](../iexceldatacell/)\>\>\> [GetCells](./getcells/)([System::String](../../system/string/), **bool**) override | Çalışma kitabından, belirtilen formülle eşleşen hücre koleksiyonunu alır. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<**int32_t**, [System::String](../../system/string/)\>\> [GetChartsFromWorksheet](./getchartsfromworksheet/)([System::String](../../system/string/)) override | Belirtilen [Excel](../) çalışma kitabının çalışma sayfasındaki tüm grafiklerin indekslerini ve adlarını içeren bir sözlüğü alır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin analoğu. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IList](../../system.collections.generic/ilist/)\<[System::String](../../system/string/)\>\> [GetWorksheetNames](./getworksheetnames/)() override | [Excel](../) çalışma kitabında bulunan tüm çalışma sayfalarının adlarını alır. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan türün bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlem nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin analoğu. Özel tiplerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'in string ve nullptr durumu için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'in string durumu için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşımlı referans sayacını azaltır. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını paylaşımlı yerine zayıf işaretçi olarak ayarlar. Kapsayıcılardaki işaretçileri zayıf moda geçiş yapmayı sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşımlı referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşımlı referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanın. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşımlı referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanın. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin analoğu. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açma işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlem nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanın. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanın. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## İlgili

* Sınıf [IExcelDataWorkbook](../iexceldataworkbook/)
* Ad alanı [Aspose::Slides::Excel](../)
* Kütüphane [Aspose.Slides](../../)