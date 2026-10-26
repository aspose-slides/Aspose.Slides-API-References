---
title: ITable
second_title: Aspose.Slides için C++ API Referansı
description: Bir slayttaki tabloyu temsil eder.
type: docs
weight: 4018
url: /tr/aspose.slides/itable/
---
## ITable sınıfı

Bir slayttaki tabloyu temsil eder.

```cpp
class ITable : public virtual Aspose::Slides::IGraphicalObject,
               public Aspose::Slides::IBulkTextFormattable
```

## Yöntemler

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | Eğer yoksa yeni bir yer tutucu ekler ve yer tutucu özelliklerini belirtilen bir taneye ayarlar. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) sözdizimi kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipi nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer tipi nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | İki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder; IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | İki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder; IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Sadece iç amaçlar için. |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | Bir şekille ilişkili alternatif metni döndürür. Okuyun [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | Bir şekille ilişkili alternatif metnin başlığını döndürür. Okuyun [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | Özellik, bir şeklin siyah-beyaz görüntü modunda nasıl render edileceğini belirtir. Okuyun [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_Column](./get_column/)(**int32_t**) | Belirtilen indeksteki bir sütunu döndürür. Yalnızca okunur [Aspose::Slides::IColumn](../icolumn/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColumnCollection](../icolumncollection/)\> [get_Columns](./get_columns/)() | Sütunların koleksiyonunu döndürür. Yalnızca okunur [IColumnCollection](../icolumncollection/). |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | Şekildeki bağlantı noktalarının sayısını döndürür. Yalnızca okunur **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | Şeklin özel verilerini döndürür. Yalnızca okunur [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | [EffectFormat](../effectformat/) nesnesini döndürür; bu nesne bir şekle uygulanan piksel efektlerini içerir. Yalnızca okunur [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | [FillFormat](../fillformat/) nesnesini döndürür; bu nesne bir şeklin dolgu biçimlendirme özelliklerini içerir. Yalnızca okunur [IFillFormat](../ifillformat/). |
| virtual **bool** [get_FirstCol](./get_firstcol/)() | Bir tablonun ilk sütununun özel bir biçimle çizilmesi gerekip gerekmediğini belirler. Okuyun **bool**. |
| virtual **bool** [get_FirstRow](./get_firstrow/)() | Bir tablonun ilk satırının özel bir biçimle çizilmesi gerekip gerekmediğini belirler. Okuyun **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | Şekil çerçevesinin özelliklerini döndürür. Okuyun [IShapeFrame](../ishapeframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../igraphicalobject/get_graphicalobjectlock/)() | Şeklin kilitlerini döndürür. Yalnızca okunur [IGraphicalObjectLock](../igraphicalobjectlock/). |
| virtual **float** [get_Height](../ishape/get_height/)() | Şeklin yüksekliğini, puan cinsinden alır. Okuyun **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | Şeklin gizli olup olmadığını belirler. Okuyun **bool**. |
| virtual **bool** [get_HorizontalBanding](./get_horizontalbanding/)() | Çift satırların farklı bir biçimle çizilmesi gerekip gerekmediğini belirler. Okuyun **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Fare tıklaması için tanımlanan köprüyü döndürür. Okuyun [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Köprü yöneticisini döndürür. Yalnızca okunur [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Fare üzerine gelindiğinde tanımlanan köprüyü döndürür. Okuyun [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | 'Mark as decorative' seçeneğini ayarlar. Okunur/yazılır **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | Şeklin gruplanmış olup olmadığını belirler. Yalnızca okunur **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | Şeklin TextHolder olup olmadığını belirler. Yalnızca okunur **bool**. |
| virtual **bool** [get_LastCol](./get_lastcol/)() | Bir tablonun son sütununun özel bir biçimle çizilmesi gerekip gerekmediğini belirler. Okuyun **bool**. |
| virtual **bool** [get_LastRow](./get_lastrow/)() | Bir tablonun son satırının özel bir biçimle çizilmesi gerekip gerekmediğini belirler. Okuyun **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | [LineFormat](../lineformat/) nesnesini döndürür; bu nesne bir şeklin çizgi biçimlendirme özelliklerini içerir. Yalnızca okunur [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | Bir şeklin adını döndürür. Okuyun [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | Şeklin ömrü boyunca sabit kalan, slayt kapsamlı benzersiz bir tanımlayıcı döndürür ve PowerPoint ya da interop kodunun şekle belgenin herhangi bir yerinden güvenilir şekilde başvurmasını sağlar. Yalnızca okunur **uint32_t**. Ayrıca bakınız [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | Şekil gruplanmışsa üst [GroupShape](../groupshape/) nesnesini döndürür. Aksi takdirde null döndürür. Yalnızca okunur [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | Bir şekil için yer tutucuyu döndürür. Yalnızca okunur [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Sunumu döndürür. Yalnızca okunur [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | Ham şekil çerçevesinin özelliklerini döndürür. Okuyun [IShapeFrame](../ishapeframe/). |
| virtual **bool** [get_RightToLeft](./get_righttoleft/)() | Tablonun sağdan sola okuma düzenine sahip olup olmadığını belirler. Okur **bool**. |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını döndürür. Pozitif değer saat yönünde dönüşü, negatif değer saat yönünün tersine dönüşü gösterir. Okuyun **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_Row](./get_row/)(**int32_t**) | Belirtilen indeksteki bir satırı döndürür. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRowCollection](../irowcollection/)\> [get_Rows](./get_rows/)() | Satırların koleksiyonunu döndürür. Yalnızca okunur [IRowCollection](../irowcollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | Şeklin kilitlerini döndürür. Yalnızca okunur [IBaseShapeLock](../ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Temel slaytı döndürür. Yalnızca okunur [IBaseSlide](../ibaseslide/). |
| virtual [TableStylePreset](../tablestylepreset/) [get_StylePreset](./get_stylepreset/)() | Yerleşik tablo stilini alır veya ayarlar. Okuyun [TableStylePreset](../tablestylepreset/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITableFormat](../itableformat/)\> [get_TableFormat](./get_tableformat/)() | [TableFormat](../tableformat/) nesnesini döndürür; bu nesne bu tablo için biçimlendirme özelliklerini içerir. Yalnızca okunur [ITableFormat](../itableformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | [ThreeDFormat](../threedformat/) nesnesini döndürür; bu nesne bir şeklin çizgi biçimlendirme özelliklerini içerir. Yalnızca okunur [IThreeDFormat](../ithreedformat/). |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | Eklentiler veya diğer kodlar tarafından kullanılmak üzere sunum kapsamlı dahili bir tanımlayıcı döndürür. Bu değer kullanıcı tarafından veya programlı olarak yeniden atandığından kalıcı bir benzersiz anahtar olarak değerlendirilmemelidir. Yalnızca okunur **uint32_t**. Ayrıca bakınız [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual **bool** [get_VerticalBanding](./get_verticalbanding/)() | Çift sütunların farklı bir biçimle çizilmesi gerekip gerekmediğini belirler. Okuyun **bool**. |
| virtual **float** [get_Width](../ishape/get_width/)() | Şeklin genişliğini, puan cinsinden alır. Okuyun **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | Şeklin sol-üst köşesinin x-koordinatını, puan cinsinden alır. Okuyun **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | Şeklin sol-üst köşesinin y-koordinatını, puan cinsinden alır. Okuyun **float**. |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | Bir şeklin z-sırasındaki konumunu döndürür. Shapes[0] sıralamanın arkasındaki şekli, Shapes[Shapes.Count - 1] ise önündeki şekli döndürür. Yalnızca okunur **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | Temel bir yer tutucu şekli döndürür (geçerli şeklin miras aldığı düzen ve/veya ana slayttan bir şekil). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analogudur. Özel nesnelerin karma (hash) imzalarını etkinleştirir. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | Şekil küçük resmini döndürür. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) şekil küçük resmi sınır türü varsayılan olarak kullanılır. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | Şekil küçük resmini döndürür. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogudur. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\> [idx_get](./idx_get/)(**int32_t**, **int32_t**) | Belirtilen sütun ve satır indekslerindeki hücreyi döndürür. Yalnızca okunur [ICell](../icell/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün analogudur. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitleme işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analogudur. Özel tiplerin klonlanmasını etkinleştirir. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\> [MergeCells](./mergecells/)([System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\>, **bool**) | Komşu hücreleri birleştirir. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmalarını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmalarını etkinleştirir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumuna özel uygulaması. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize durumuna özel uygulaması. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | Bir şekille ilişkili alternatif metni ayarlar. Yaz [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Bir şekille ilişkili alternatif metnin başlığını ayarlar. Yaz [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | Özellik, bir şeklin siyah-beyaz gösterim modunda nasıl render edileceğini belirler. Yaz [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_FirstCol](./set_firstcol/)(**bool**) | Tablonun ilk sütununun özel bir biçimle çizilmesi gerekiyor mu belirler. Yaz **bool**. |
| virtual void [set_FirstRow](./set_firstrow/)(**bool**) | Tablonun ilk satırının özel bir biçimle çizilmesi gerekiyor mu belirler. Yaz **bool**. |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Şekil çerçevesinin özelliklerini ayarlar. Yaz [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | Şeklin yüksekliğini, puan cinsinden ayarlar. Yaz **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | Şeklin gizli olup olmadığını belirler. Yaz **bool**. |
| virtual void [set_HorizontalBanding](./set_horizontalbanding/)(**bool**) | Çift satırların farklı bir biçimle çizilmesi gerekiyor mu belirler. Yaz **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Fare tıklaması için tanımlanan köprüyü ayarlar. Yaz [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Fare üzerine gelindiğinde tanımlanan köprüyü ayarlar. Yaz [IHyperlink](../ihyperlink/). |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | 'Mark as decorative' seçeneğini ayarlar. Okunur/yazılır **bool**. |
| virtual void [set_LastCol](./set_lastcol/)(**bool**) | Tablonun son sütununun özel bir biçimle çizilmesi gerekiyor mu belirler. Yaz **bool**. |
| virtual void [set_LastRow](./set_lastrow/)(**bool**) | Tablonun son satırının özel bir biçimle çizilmesi gerekiyor mu belirler. Yaz **bool**. |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | Bir şeklin adını ayarlar. Yaz [System::String](../../system/string/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Ham şekil çerçevesinin özelliklerini ayarlar. Yaz [IShapeFrame](../ishapeframe/). |
| virtual void [set_RightToLeft](./set_righttoleft/)(**bool**) | Tablonun sağdan sola okuma düzenine sahip olup olmadığını belirler. Yazar **bool**. |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını ayarlar. Pozitif değer saat yönünde dönüşü, negatif değer saat yönünün tersine dönüşü gösterir. Yaz **float**. |
| virtual void [set_StylePreset](./set_stylepreset/)([TableStylePreset](../tablestylepreset/)) | Yerleşik tablo stilini alır veya ayarlar. Yaz [TableStylePreset](../tablestylepreset/). |
| virtual void [set_VerticalBanding](./set_verticalbanding/)(**bool**) | Çift sütunların farklı bir biçimle çizilmesi gerekiyor mu belirler. Yaz **bool**. |
| virtual void [set_Width](../ishape/set_width/)(**float**) | Şeklin genişliğini, puan cinsinden ayarlar. Yaz **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | Şeklin sol-üst köşesinin x-koordinatını, puan cinsinden ayarlar. Yaz **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | Şeklin sol-üst köşesinin y-koordinatını, puan cinsinden ayarlar. Yaz **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi olarak ayarlar (paylaşımlı yerine). Kapsayıcılardaki işaretçilerin zayıf moda geçişine izin verir. |
| virtual void [SetTextFormat](../ibulktextformattable/settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../iportionformat/)\>) | Tanımlı bölüm biçim özelliklerini tüm öğenin bölümlerine ayarlar. |
| virtual void [SetTextFormat](../ibulktextformattable/settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormat](../iparagraphformat/)\>) | Tanımlı paragraf biçim özelliklerini tüm öğenin paragraflarına ayarlar. |
| virtual void [SetTextFormat](../ibulktextformattable/settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormat](../itextframeformat/)\>) | Tanımlı metin çerçevesi biçim özelliklerini tüm öğenin metin çerçevelerine ayarlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını arttırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler ya da ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler ya da ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analogudur. Özel nesnelerin dizeye dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açma işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını arttırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler ya da ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler ya da ThisProtector kullanılmalıdır. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | [Shape](../shape/) içeriğini SVG dosyası olarak kaydeder. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | [Shape](../shape/) içeriğini SVG dosyası olarak kaydeder. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Bakınız

* Sınıf [IGraphicalObject](../igraphicalobject/)
* Sınıf [IBulkTextFormattable](../ibulktextformattable/)
* Ad alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)