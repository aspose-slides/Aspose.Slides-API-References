---
title: StringChartValue
second_title: Aspose.Slides for C++ API Referansı
description: "pptx sunum belgesinde iki şekilde saklanabilecek dize değerini temsil eder: 1) grafikle ilişkili çalışma kitabındaki hücrelerde; 2) doğrudan değer olarak."
type: docs
weight: 1340
url: /tr/aspose.slides.charts/stringchartvalue/
---
## StringChartValue sınıfı

Represent string value which can be stored in pptx presentation document in two ways: 1) in cell/cells of workbook related to chart; 2) as literal value.

```cpp
class StringChartValue : public Aspose::Slides::Charts::BaseChartValue,
                         public Aspose::Slides::Charts::IStringChartValue
```

## Metotlar

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiğini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans türü nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer türü nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN hiçbir değere eşit değildir, NaN dahil, fakat iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN hiçbir değere eşit değildir, NaN dahil, fakat iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [get_AsCell](./get_ascell/)(**int32_t**) override | Belirtilen indeks'teki bir grafik hücresini döndürür. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartCellCollection](../ichartcellcollection/)\> [get_AsCells](./get_ascells/)() override | Null değer atamasına izin verilmez. Döndürülen değer her zaman null değildir. [IChartCellCollection](../ichartcellcollection/)'yi okuyun. |
| [System::String](../../system/string/) [get_AsLiteralString](./get_asliteralstring/)() override | Değeri doğrudan dize olarak döndürür. [System::String](../../system/string/)'yi okuyun. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Data](./get_data/)() override | Data nesnesini döndürür. [System::Object](../../system/object/)'yi okuyun. |
| [Aspose::Slides::Charts::DataSourceType](../datasourcetype/) [get_DataSourceType](../basechartvalue/get_datasourcetype/)() override | Descendant sınıflarda AsCell, AsCells, AsLiteralString veya AsLiteralDouble özelliğinin hangisinin geçerli olduğunu belirtir. Başka bir deyişle Data özelliğinin değer tipini belirtir. [Charts::DataSourceType](../datasourcetype/)'yi okuyun. |
| [System::String](../../system/string/) [GetCellsAddressInWorkbook](./getcellsaddressinworkbook/)() override | DataSourceType özelliği [DataSourceType::Worksheet](../datasourcetype/) ise bu metod, dize verisini temsil eden çalışma kitabındaki hücrelerin adresini döndürür. Aksi takdirde boş dize döndürür. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun benzeri. Özel nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının benzeri. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün benzeri. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitleme işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun benzeri. Özel tiplerin klonlanmasını sağlar. |
| [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapılarını başlatır. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucu. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesnesini nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nın dize ve nullptr durumu için özelleştirilmiş hâli. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nın dize durumu için özelleştirilmiş hâli. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| void [set_AsCells](./set_ascells/)([System::SharedPtr](../../system/sharedptr/)\<[IChartCellCollection](../ichartcellcollection/)\>) override | Null değer atamasına izin verilmez. Döndürülen değer her zaman null değildir. [IChartCellCollection](../ichartcellcollection/)'ye yazın. |
| void [set_AsLiteralString](./set_asliteralstring/)([System::String](../../system/string/)) override | Değeri doğrudan dize olarak ayarlar. [System::String](../../system/string/)'ye yazın. |
| void [set_Data](./set_data/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Data nesnesini ayarlar. [System::Object](../../system/object/)'ye yazın. |
| void [set_DataSourceType](../basechartvalue/set_datasourcetype/)([Aspose::Slides::Charts::DataSourceType](../datasourcetype/)) override | Descendant sınıflarda AsCell, AsCells, AsLiteralString veya AsLiteralDouble özelliğinin hangisinin geçerli olduğunu belirtir. Başka bir deyişle Data özelliğinin değer tipini belirtir. [Charts::DataSourceType](../datasourcetype/)'ye yazın. |
| void [SetFromOneCell](./setfromonecell/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\>) override | Değeri belirtilen hücreden ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 'n' inci şablon argümanını zayıf gösterici (paylaşımlı yerine) olarak ayarlar. Kapsayıcılardaki göstergelerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| [System::String](../../system/string/) [ToString](./tostring/)() const override | Dize değer verisini döndürür. DataSourceType false ise ve hiçbir dize değeri atanmadıysa null döndürür. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Ayrıca

* Sınıf [BaseChartValue](../basechartvalue/)
* Sınıf [IStringChartValue](../istringchartvalue/)
* Ad alanı [Aspose::Slides::Charts](../)
* Kütüphane [Aspose.Slides](../../)