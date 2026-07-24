---
title: ICell
second_title: Aspose.Slides için C++ API Referansı
description: Bir tabloda bir hücreyi temsil eder.
type: docs
weight: 1639
url: /tr/aspose.slides/icell/
---
## ICell sınıfı

Bir tabloda bir hücreyi temsil eder.

```cpp
class ICell : public Aspose::Slides::ISlideComponent
```

## Yöntemler

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiği kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans türü nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer türü nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | İki NaN değerinin eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder; IEC 60559:1989’a göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | İki NaN değerinin eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder; IEC 60559:1989’a göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual **bool** [get_AnchorCenter](./get_anchorcenter/)() | Bir hücre içinde metin kutusunun ortalanıp ortalanmadığını belirler. Okuma **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICellFormat](../icellformat/)\> [get_CellFormat](./get_cellformat/)() | Bu hücre için biçimlendirme özelliklerini içeren [CellFormat](../cellformat/) nesnesini döndürür. Salt okunur [ICellFormat](../icellformat/). |
| virtual **int32_t** [get_ColSpan](./get_colspan/)() | Mevcut hücrenin kapsayacağı üst tabloyun tablo ızgarasındaki sütun sayısını döndürür. Bu özellik, hücrelerin tablo içindeki diğer hücrelerin dikey sınırlarını kapsayarak birleşmiş görünmesini sağlar. Salt okunur **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_FirstColumn](./get_firstcolumn/)() | Hücrenin ilk sütununu alır. Salt okunur [IColumn](../icolumn/). |
| virtual **int32_t** [get_FirstColumnIndex](./get_firstcolumnindex/)() | Hücre tarafından kapsanan ilk sütunun indeksini döndürür. Salt okunur **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_FirstRow](./get_firstrow/)() | Hücrenin ilk satırını alır. Salt okunur [IRow](../irow/). |
| virtual **int32_t** [get_FirstRowIndex](./get_firstrowindex/)() | Hücre tarafından kapsanan ilk satırın indeksini döndürür. Salt okunur **int32_t**. |
| virtual **double** [get_Height](./get_height/)() | Hücrenin yüksekliğini döndürür. Salt okunur **double**. |
| virtual **bool** [get_IsMergedCell](./get_ismergedcell/)() | Hücre herhangi bir ayarlanmış hücreyle birleşmişse true, aksi takdirde false döndürür. Salt okunur **bool**. |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | Bir [TextFrame](../textframe/) içinde alt kenar boşluğunu döndürür. Okuma **double**. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | Bir [TextFrame](../textframe/) içinde sol kenar boşluğunu döndürür. Okuma **double**. |
| virtual **double** [get_MarginRight](./get_marginright/)() | Bir [TextFrame](../textframe/) içinde sağ kenar boşluğunu döndürür. Okuma **double**. |
| virtual **double** [get_MarginTop](./get_margintop/)() | Bir [TextFrame](../textframe/) içinde üst kenar boşluğunu döndürür. Okuma **double**. |
| virtual **double** [get_MinimalHeight](./get_minimalheight/)() | Bir hücrenin minimum yüksekliğini döndürür. Bu, hücre tarafından kapsanan tüm satırların minimum yüksekliklerinin toplamıdır. Salt okunur **double**. |
| virtual **double** [get_OffsetX](./get_offsetx/)() | Bir tablonun sol kenarı ile hücrenin sol kenarı arasındaki mesafeyi döndürür. Salt okunur **double**. |
| virtual **double** [get_OffsetY](./get_offsety/)() | Bir tablonun üst kenarı ile hücrenin üst kenarı arasındaki mesafeyi döndürür. Salt okunur **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Sunumu döndürür. Salt okunur [IPresentation](../ipresentation/). |
| virtual **int32_t** [get_RowSpan](./get_rowspan/)() | Bir birleşik hücrenin kapsadığı satır sayısını döndürür. Bu, diğer hücrelerdeki vMerge özniteliği ile birlikte, yatay bir birleştirmenin başlangıç hücresini belirlemek için kullanılır. Salt okunur **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Temel slaytı döndürür. Salt okunur [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [get_Table](./get_table/)() | Bir hücrenin üst [Table](../table/) nesnesini döndürür. Salt okunur [ITable](../itable/). |
| virtual [Aspose::Slides::TextAnchorType](../textanchortype/) [get_TextAnchorType](./get_textanchortype/)() | Metin bağlantı türünü döndürür. Okuma [Slides::TextAnchorType](../textanchortype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() | Bir hücrenin metin çerçevesini döndürür. Salt okunur [ITextFrame](../itextframe/). |
| virtual [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | Dikey metin tipini döndürür. Okuma [Slides::TextVerticalType](../textverticaltype/). |
| virtual **double** [get_Width](./get_width/)() | Hücrenin genişliğini döndürür. Salt okunur **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun benzeri. Özel nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının benzeri. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan türün bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün benzeri. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun benzeri. Özel tiplerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapıları başlatılır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Aslında hiçbir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımına izin verir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımına izin verir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumuna özgü özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize durumuna özgü özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [set_AnchorCenter](./set_anchorcenter/)(**bool**) | Bir hücre içinde metin kutusunun ortalanıp ortalanmadığını belirler. Yazma **bool**. |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | Bir [TextFrame](../textframe/) içinde alt kenar boşluğunu ayarlar. Yazma **double**. |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | Bir [TextFrame](../textframe/) içinde sol kenar boşluğunu ayarlar. Yazma **double**. |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | Bir [TextFrame](../textframe/) içinde sağ kenar boşluğunu ayarlar. Yazma **double**. |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | Bir [TextFrame](../textframe/) içinde üst kenar boşluğunu ayarlar. Yazma **double**. |
| virtual void [set_TextAnchorType](./set_textanchortype/)([Aspose::Slides::TextAnchorType](../textanchortype/)) | Metin bağlantı türünü ayarlar. Yazma [Slides::TextAnchorType](../textanchortype/). |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) | Dikey metin tipini ayarlar. Yazma [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf gösterici (shared yerine) olarak ayarlar. Kaplarda göstericileri zayıf moda geçişe izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| virtual void [SplitByColSpan](./splitbycolspan/)(**int32_t**) | Hücreyi sütun indeksine göre iki hücreye böler. |
| virtual void [SplitByHeight](./splitbyheight/)(**double**) | Hücreyi yükseklik ile böler. |
| virtual void [SplitByRowSpan](./splitbyrowspan/)(**int32_t**) | Hücreyi satır indeksine göre iki hücreye böler. |
| virtual void [SplitByWidth](./splitbywidth/)(**double**) | Hücreyi genişlik ile böler. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun benzeri. Özel nesnelerin dizeye dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açmasını uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapıları serbest bırakılır. |

## Ayrıca Bakınız

* Sınıf [ISlideComponent](../islidecomponent/)
* Ad alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)