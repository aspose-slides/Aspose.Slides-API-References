---
title: IChartDataCell
second_title: Aspose.Slides for C++ API Referansı
description: Grafik verileri için hücreyi temsil eder.
type: docs
weight: 664
url: /tr/aspose.slides.charts/ichartdatacell/
---
## IChartDataCell sınıfı


Grafik verileri için hücreyi temsil eder.

```cpp
class IChartDataCell : public virtual System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual void [Calculate](./calculate/)(**bool**) | Hücre bir formül içeriyorsa, değer bu formül temelinde güncellenir. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiği kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde referans türü nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde değer türü nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değere, NaN dahil, eşit olmadığı halde, iki NaN'in eşit kabul edildiği C#-stilindeki kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değere, NaN dahil, eşit olmadığı halde, iki NaN'in eşit kabul edildiği C#-stilindeki kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataWorksheet](../ichartdataworksheet/)\> [get_ChartDataWorksheet](./get_chartdataworksheet/)() | Çalışma sayfasını alır. Yalnızca okuma [IChartDataWorksheet](../ichartdataworksheet/). |
| virtual **int32_t** [get_Column](./get_column/)() | Hücrenin bulunduğu çalışma sayfasındaki sütunun dizinini döndürür. Yalnızca okuma **int32_t**. |
| virtual [System::String](../../system/string/) [get_CustomNumberFormat](./get_customnumberformat/)() | Sayıların ve tarihlerin özel görüntüleme biçimini alır. Değer boş ise PresetNumberFormat değeri kullanılacaktır. Okuma [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Formula](./get_formula/)() | A1-stilindeki formülü alır. |
| virtual **bool** [get_IsHidden](./get_ishidden/)() | Hücrenin gizli olup olmadığını belirler. Yalnızca okuma **bool**. |
| virtual **uint8_t** [get_PresetNumberFormat](./get_presetnumberformat/)() | Sayıların ve tarihlerin yerleşik görüntüleme biçimini alır. Ön ayar numarası [0..22] veya [37..49] aralığında olmalıdır. Okuma **uint8_t**. |
| virtual [System::String](../../system/string/) [get_R1C1Formula](./get_r1c1formula/)() | R1C1-stilindeki formülü alır. |
| virtual **int32_t** [get_Row](./get_row/)() | Hücrenin bulunduğu çalışma sayfasındaki satırın dizinini döndürür. Yalnızca okuma **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Value](./get_value/)() | Bir hücrenin değerini alır. Okuma [System::Object](../../system/object/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin, hedefTür tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlem nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumu için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dizeler durumu için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [set_CustomNumberFormat](./set_customnumberformat/)([System::String](../../system/string/)) | Sayıların ve tarihlerin özel görüntüleme biçimini ayarlar. Değer boş ise PresetNumberFormat değeri kullanılacaktır. Yazma [System::String](../../system/string/). |
| virtual void [set_Formula](./set_formula/)([System::String](../../system/string/)) | A1-stilindeki formülü ayarlar. |
| virtual void [set_PresetNumberFormat](./set_presetnumberformat/)(**uint8_t**) | Sayıların ve tarihlerin yerleşik görüntüleme biçimini ayarlar. Ön ayar numarası [0..22] veya [37..49] aralığında olmalıdır. Yazma **uint8_t**. |
| virtual void [set_R1C1Formula](./set_r1c1formula/)([System::String](../../system/string/)) | R1C1-stilindeki formülü ayarlar. |
| virtual void [set_Value](./set_value/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Bir hücrenin değerini ayarlar. Yazma [System::Object](../../system/object/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını paylaşımlı yerine zayıf gösterici olarak ayarlar. Kapsayıcılardaki göstericileri zayıf moda geçişe izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin dizeye dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlemini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlem nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi dağıtır. Tüm dahili veri yapılarını serbest bırakır. |
## Ayrıca Bakınız

* Sınıf [Object](../../system/object/)
* Ad Alanı [Aspose::Slides::Charts](../)
* Kütüphane [Aspose.Slides](../../)