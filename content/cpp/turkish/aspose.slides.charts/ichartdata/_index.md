---
title: IChartData
second_title: Aspose.Slides for C++ API Referansı
description: Grafik çizimi için kullanılan verileri temsil eder.
type: docs
weight: 651
url: /tr/aspose.slides.charts/ichartdata/
---
## IChartData sınıfı


Represents data used for a chart plotting.

```cpp
class IChartData : public virtual System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiğine göre nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipi nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer tipi nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategoryCollection](../ichartcategorycollection/)\> [get_Categories](./get_categories/)() | Birincil kategorileri alır (veya [IChartData::set_UseSecondaryCategories](./set_usesecondarycategories/) false olarak ayarlanmışsa birincil ve ikincil kategorileri alır). Yalnızca okuma [IChartCategoryCollection](../ichartcategorycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategory](../ichartcategory/)\> [get_Category](./get_category/)(**int32_t**) | Belirtilen indeksteki birincil kategoriyi döndürür. [get_UseSecondaryCategories](./get_usesecondarycategories/) false ise, tüm kategoriler arasından alır. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataWorkbook](../ichartdataworkbook/)\> [get_ChartDataWorkbook](./get_chartdataworkbook/)() | Grafik serileri veya kategorileri için kullanılan hücreleri oluşturmak üzere hücre fabrikasını alır. Yalnızca okuma [IChartDataWorkbook](../ichartdataworkbook/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) | Belirtilen indeksteki seriyi döndürür. |
| virtual [ChartDataSourceType](../chartdatasourcetype/) [get_DataSourceType](./get_datasourcetype/)() | Grafiğin veri kaynağını temsil eder |
| virtual [WorkbookType](../workbooktype/) [get_EmbeddedWorkbookType](./get_embeddedworkbooktype/)() | Gömülü çalışma kitabının türünü alır. [IChartData::get_DataSourceType](./get_datasourcetype/) [ChartDataSourceType::ExternalWorkbook](../chartdatasourcetype/) ise [WorkbookType::NotDefined](../workbooktype/) döndürür. Yalnızca okuma [WorkbookType](../workbooktype/). |
| virtual [System::String](../../system/string/) [get_ExternalWorkbookPath](./get_externalworkbookpath/)() | Verı kaynağı harici ise harici çalışma kitabı yolunu, aksi takdirde null değerini temsil eder |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategoryCollection](../ichartcategorycollection/)\> [get_SecondaryCategories](./get_secondarycategories/)() | [IChartData::get_UseSecondaryCategories](./get_usesecondarycategories/) true ise ikincil kategorileri alır. Yalnızca okuma [IChartCategoryCollection](../ichartcategorycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategory](../ichartcategory/)\> [get_SecondaryCategory](./get_secondarycategory/)(**int32_t**) | Belirtilen indeksteki ikincil kategoriyi döndürür. [get_UseSecondaryCategories](./get_usesecondarycategories/) false ise, [IChartData::get_SecondaryCategories](./get_secondarycategories/) null olur. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesCollection](../ichartseriescollection/)\> [get_Series](./get_series/)() | Serileri alır. Yalnızca okuma [IChartSeriesCollection](../ichartseriescollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_SeriesGroup](./get_seriesgroup/)([System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\>) |  |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_SeriesGroup](./get_seriesgroup/)(**int32_t**) | Belirtilen indeksteki seri grubunu döndürür. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroupCollection](../ichartseriesgroupcollection/)\> [get_SeriesGroups](./get_seriesgroups/)() | Seri gruplarını alır. Yalnızca okuma [IChartSeriesGroupCollection](../ichartseriesgroupcollection/). |
| virtual **bool** [get_UseSecondaryCategories](./get_usesecondarycategories/)() | false olarak ayarlanırsa [IChartData::get_SecondaryCategories](./get_secondarycategories/) null döndürür ve [IChartData::get_Categories](./get_categories/) içindeki veri hem birincil hem ikincil seriler için kullanılır. true olarak ayarlanırsa [IChartData::get_SecondaryCategories](./get_secondarycategories/) içindeki veri ikincil seriler için, [IChartData::get_Categories](./get_categories/) içindeki veri birincil seriler için kullanılır. Okuma **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özel nesnelerin karmalaştırılmasını sağlar. |
| virtual [System::String](../../system/string/) [GetRange](./getrange/)() | Grafik veri aralığını alır. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek türünü alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan türün bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucu. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IO::MemoryStream](../../system.io/memorystream/)\> [ReadWorkbookStream](./readworkbookstream/)() | Dahili olarak bulunan [Excel](../../aspose.slides.excel/) çalışma kitabını bellek içi akışa yazar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumuna özel uygulaması. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin stringler için özel uygulaması. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [set_UseSecondaryCategories](./set_usesecondarycategories/)(**bool**) | false olarak ayarlanırsa [IChartData::get_SecondaryCategories](./get_secondarycategories/) null döndürür ve [IChartData::get_Categories](./get_categories/) içindeki veri hem birincil hem ikincil seriler için kullanılır. true olarak ayarlanırsa [IChartData::get_SecondaryCategories](./get_secondarycategories/) içindeki veri ikincil seriler için, [IChartData::get_Categories](./get_categories/) içindeki veri birincil seriler için kullanılır. Yaz **bool**. |
| virtual void [SetExternalWorkbook](./setexternalworkbook/)([System::String](../../system/string/)) | Harici çalışma kitabını grafik için veri kaynağı olarak ayarlar. [Chart](../chart/) verisi hedef çalışma kitabından güncellenecek. |
| virtual void [SetExternalWorkbook](./setexternalworkbook/)([System::String](../../system/string/), **bool**) | Harici çalışma kitabını grafik için veri kaynağı olarak ayarlar. |
| virtual void [SetRange](./setrange/)([System::String](../../system/string/)) | Grafik veri aralığını ayarla. Seri ve kategoriler yeni veri aralığına göre güncellenecek. Veri aralığındaki seri sayısı grafik verisindeki seri sayısından büyükse, mevcut koleksiyondaki son serinin aynı tipinde ek seriler koleksiyonun sonuna eklenecek. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını paylaşılan yerine zayıf işaretçi olarak ayarla. Kapsayıcılardaki işaretçilerin zayıf moda geçişini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının güncel değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| virtual void [SwitchRowColumn](./switchrowcolumn/)() | Veriyi eksen boyunca değiştirir. X ekseninde çizilen veri Y eksenine, Y eksenindeki veri X eksenine geçer. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açmayı uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| virtual void [WriteWorkbookStream](./writeworkbookstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::MemoryStream](../../system.io/memorystream/)\>) | Dahili olarak bulunan [Excel](../../aspose.slides.excel/) çalışma kitabını kullanıcı tarafından belirlenen değerle başlatır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |
## İlgili

* Sınıf [Object](../../system/object/)
* Ad alanı [Aspose::Slides::Charts](../)
* Kütüphane [Aspose.Slides](../../)