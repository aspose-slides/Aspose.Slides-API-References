---
title: Cell
second_title: Aspose.Slides for C++ API Referansı
description: Bir tablonun hücresini temsil eder.
type: docs
weight: 300
url: /tr/aspose.slides/cell/
---
## Cell sınıfı

Bir tablonun hücresini temsil eder.

```cpp
class Cell : public Aspose::Slides::IDOMObject,
             public Aspose::Slides::ICell
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) sözdizimini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türü nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer türü nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | İki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder; ancak IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | İki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder; ancak IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Sadece dahili amaçlar için. |
| **bool** [get_AnchorCenter](./get_anchorcenter/)() override | Bir hücre içinde metin kutusunun ortalanıp ortalanmadığını belirler. Okuma **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICellFormat](../icellformat/)\> [get_CellFormat](./get_cellformat/)() override | Bu hücre için biçimlendirme özelliklerini içeren [CellFormat](../cellformat/) nesnesini döndürür. Salt-okunur [ICellFormat](../icellformat/). |
| **int32_t** [get_ColSpan](./get_colspan/)() override | Geçerli hücrenin kapsayacağı, üst tablonun tablo ızgarasındaki ızgara sütun sayısını döndürür. Bu özellik, hücrelerin tablo içindeki diğer hücrelerin dikey sınırlarını kapsayarak birleştirilmiş gibi görünmesini sağlar. Salt-okunur **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_FirstColumn](./get_firstcolumn/)() override | Hücrenin ilk sütununu alır. Salt-okunur [IColumn](../icolumn/). |
| **int32_t** [get_FirstColumnIndex](./get_firstcolumnindex/)() override | Hücre tarafından kapsanan ilk sütunun dizinini döndürür. Salt-okunur **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_FirstRow](./get_firstrow/)() override | Hücrenin ilk satırını alır. Salt-okunur [IRow](../irow/). |
| **int32_t** [get_FirstRowIndex](./get_firstrowindex/)() override | Hücre tarafından kapsanan ilk satırın dizinini döndürür. Salt-okunur **int32_t**. |
| **double** [get_Height](./get_height/)() override | Hücrenin yüksekliğini döndürür. Salt-okunur **double**. |
| **bool** [get_IsMergedCell](./get_ismergedcell/)() override | Hücre herhangi bir ayarlanmış hücreyle birleştirilmişse true, aksi takdirde false döndürür. Salt-okunur **bool**. |
| **double** [get_MarginBottom](./get_marginbottom/)() override | Bir [TextFrame](../textframe/) içindeki alt kenar boşluğunu döndürür. Okuma **double**. |
| **double** [get_MarginLeft](./get_marginleft/)() override | Bir [TextFrame](../textframe/) içindeki sol kenar boşluğunu döndürür. Okuma **double**. |
| **double** [get_MarginRight](./get_marginright/)() override | Bir [TextFrame](../textframe/) içindeki sağ kenar boşluğunu döndürür. Okuma **double**. |
| **double** [get_MarginTop](./get_margintop/)() override | Bir [TextFrame](../textframe/) içindeki üst kenar boşluğunu döndürür. Okuma **double**. |
| **double** [get_MinimalHeight](./get_minimalheight/)() override | Bir hücrenin minimum yüksekliğini döndürür. Bu, hücre tarafından kapsanan tüm satırların minimal yüksekliklerinin toplamıdır. Salt-okunur **double**. |
| **double** [get_OffsetX](./get_offsetx/)() override | Tablonun sol tarafından hücrenin sol tarafına olan mesafeyi döndürür. Salt-okunur **double**. |
| **double** [get_OffsetY](./get_offsety/)() override | Tablonun üst tarafından hücrenin üst tarafına olan mesafeyi döndürür. Salt-okunur **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](./get_presentation/)() override | Bir hücrenin üst sunumunu döndürür. Salt-okunur [IPresentation](../ipresentation/). |
| **int32_t** [get_RowSpan](./get_rowspan/)() override | Birleştirilmiş bir hücrenin kapsadığı satır sayısını döndürür. Bu, diğer hücrelerdeki vMerge özniteliği ile birlikte yatay birleştirme başlangıç hücresini belirtmek için kullanılır. Salt-okunur **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](./get_slide/)() override | Bir hücrenin üst slaytını döndürür. Salt-okunur [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [get_Table](./get_table/)() override | Bir hücre için üst [Table](../table/) nesnesini döndürür. Salt-okunur [ITable](../itable/). |
| [Aspose::Slides::TextAnchorType](../textanchortype/) [get_TextAnchorType](./get_textanchortype/)() override | Metin çapa tipini döndürür. Okuma [Slides::TextAnchorType](../textanchortype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() override | Bir hücrenin metin çerçevesini döndürür. Salt-okunur [ITextFrame](../itextframe/). |
| [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() override | Dikey metnin tipini döndürür. Okuma [Slides::TextVerticalType](../textverticaltype/). |
| **double** [get_Width](./get_width/)() override | Hücrenin genişliğini döndürür. Salt-okunur **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analogudur. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün analogu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetmen nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analogu. Özel tiplerin klonlanmasını sağlar. |
| [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapılarını başlatır. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucu. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesnesini nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | String ve nullptr durumları için [Object::ReferenceEquals](../../system/object/referenceequals/)'nın özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumları için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| void [set_AnchorCenter](./set_anchorcenter/)(**bool**) override | Bir hücre içinde metin kutusunun ortalanıp ortalanmadığını belirler. Yazma **bool**. |
| void [set_MarginBottom](./set_marginbottom/)(**double**) override | Bir [TextFrame](../textframe/) içinde alt kenar boşluğunu ayarlar. Yazma **double**. |
| void [set_MarginLeft](./set_marginleft/)(**double**) override | Bir [TextFrame](../textframe/) içinde sol kenar boşluğunu ayarlar. Yazma **double**. |
| void [set_MarginRight](./set_marginright/)(**double**) override | Bir [TextFrame](../textframe/) içinde sağ kenar boşluğunu ayarlar. Yazma **double**. |
| void [set_MarginTop](./set_margintop/)(**double**) override | Bir [TextFrame](../textframe/) içinde üst kenar boşluğunu ayarlar. Yazma **double**. |
| void [set_TextAnchorType](./set_textanchortype/)([Aspose::Slides::TextAnchorType](../textanchortype/)) override | Metin çapa tipini ayarlar. Yazma [Slides::TextAnchorType](../textanchortype/). |
| void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) override | Dikey metin tipini ayarlar. Yazma [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını paylaşılan yerine zayıf işaretçi olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçileri veya ThisProtector'ı kullanın. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçileri veya ThisProtector'ı kullanın. |
| void [SplitByColSpan](./splitbycolspan/)(**int32_t**) override | Hücreyi sütun dizinine göre iki hücreye böler. |
| void [SplitByHeight](./splitbyheight/)(**double**) override | Hücreyi yüksekliğe göre böler. |
| void [SplitByRowSpan](./splitbyrowspan/)(**int32_t**) override | Hücreyi satır dizinine göre iki hücreye böler. |
| void [SplitByWidth](./splitbywidth/)(**double**) override | Hücreyi genişliğe göre böler. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analogu. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açmasını uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetmen nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçileri veya ThisProtector'ı kullanın. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçileri veya ThisProtector'ı kullanın. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [IDOMObject](../idomobject/)
* Sınıf [ICell](../icell/)
* İsim Alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)