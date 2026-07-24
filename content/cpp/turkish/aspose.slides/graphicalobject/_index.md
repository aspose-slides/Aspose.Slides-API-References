---
title: GraphicalObject
second_title: Aspose.Slides for C++ API Referansı
description: Soyut grafik nesneyi temsil eder.
type: docs
weight: 1171
url: /tr/aspose.slides/graphicalobject/
---
## GraphicalObject sınıfı

Soyut grafik nesneyi temsil eder.

```cpp
class GraphicalObject : public Aspose::Slides::Shape,
                        public virtual Aspose::Slides::IGraphicalObject
```

## Yöntemler

| Metod | Açıklama |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Yeni bir yer tutucu yoksa ekler ve yer tutucu özelliklerini belirtilen bir yer tutucuya ayarlar. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) anlamını kullanan nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipindeki nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer tipindeki nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'ın hiçbir değerle, NaN dahil, eşit olmaması gerektiği halde, iki NaN'ı eşit kabul eden C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'ın hiçbir değerle, NaN dahil, eşit olmaması gerektiği halde, iki NaN'ı eşit kabul eden C# tarzı çift duyarlıklı (double) kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Bir şekille ilişkili alternatif metni döndürür. Okuyun [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Bir şekille ilişkili alternatif metnin başlığını döndürür. Okuyun [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | Bir şeklin siyah-beyaz görüntü modunda nasıl render edileceğini belirten özelliktir. Okuyun [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Şekildeki bağlantı noktalarının sayısını döndürür. Yalnızca okunur **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Şeklin özel verilerini döndürür. Yalnızca okunur [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | Şekle uygulanan piksel efektlerini içeren [EffectFormat](../effectformat/) nesnesini döndürür. Not: Efekt özelliklerine sahip olmayan bazı şekil türleri için null dönebilir. Yalnızca okunur [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | Şeklin doldurma biçimlendirme özelliklerini içeren [FillFormat](../fillformat/) nesnesini döndürür. Not: Doldurma özelliklerine sahip olmayan bazı şekil türleri için null dönebilir. Yalnızca okunur [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Şekil çerçevesinin özelliklerini döndürür. Okuyun [IShapeFrame](../ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](./get_graphicalobjectlock/)() override | Şeklin kilitlerini döndürür. Yalnızca okunur [IGraphicalObjectLock](../igraphicalobjectlock/). |
| **float** [get_Height](../shape/get_height/)() override | Şeklin yüksekliğini, point cinsinden alır. Okunur **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Şeklin gizli olup olmadığını belirler. Okunur **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Fare tıklaması için tanımlı hiperlinki döndürür. Okuyun [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Hiperlink yöneticisini döndürür. Yalnızca okunur [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Fare üzerine gelindiğinde tanımlı hiperlinki döndürür. Okuyun [IHyperlink](../ihyperlink/). |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | 'Mark as decorative' seçeneğini alır. Okunur/yazılır **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Şeklin gruplandırılmış olup olmadığını belirler. Yalnızca okunur **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Şeklin TextHolder_PPT olup olmadığını belirler. Yalnızca okunur **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | [LineFormat](../lineformat/) nesnesini, bir şekil için çizgi biçimlendirme özelliklerini içeren, döndürür. Not: Çizgi özelliklerine sahip olmayan bazı şekil türleri için null dönebilir. Yalnızca okunur [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Bir şeklin adını döndürür. Null olmamalıdır. Gerekirse boş string değeri kullanın. Okuyun [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Şeklin ömrü boyunca sabit kalan ve PowerPoint ya da interop kodunun şekle belgenin herhangi bir yerinden güvenilir şekilde referans vermesini sağlayan, slayt kapsamında benzersiz bir tanımlayıcı döndürür. Yalnızca okunur **uint32_t**. Ayrıca bkz. [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Şekil gruplandırılmışsa ebeveyn [GroupShape](../groupshape/) nesnesini döndürür. Aksi halde null döner. Yalnızca okunur [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Bir şekil için yer tutucuyu döndürür. Şeklin yer tutucusu yoksa null döner. Yalnızca okunur [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Bir slaytın üst belgesini döndürür. Yalnızca okunur [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Ham şekil çerçevesinin özelliklerini döndürür. Okuyun [IShapeFrame](../ishapeframe/). |
| **float** [get_Rotation](../shape/get_rotation/)() override | Belirtilen şeklin z-ekseni etrafında döndürülen derece sayısını döndürür. Pozitif değer saat yönünde döndürmeyi, negatif değer saat yönünün tersine döndürmeyi gösterir. Okunur **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Şeklin kilitlerini döndürür. Yalnızca okunur [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Şeklin ebeveyn slaytını döndürür. Yalnızca okunur [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | [ThreeDFormat](../threedformat/) nesnesini, bir şekil için 3D efekt özelliklerini içeren, döndürür. Not: 3D özelliklerine sahip olmayan bazı şekil türleri için null dönebilir. Yalnızca okunur [IThreeDFormat](../ithreedformat/). |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | Eklentiler veya diğer kodlar tarafından kullanılmak üzere tasarlanmış, içsel, sunum kapsamlı bir tanımlayıcı döndürür. Bu değer kullanıcı tarafından veya programlı olarak yeniden atanabileceğinden, kalıcı bir benzersiz anahtar olarak değerlendirilmemelidir. Yalnızca okunur **uint32_t**. Ayrıca bkz. [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **float** [get_Width](../shape/get_width/)() override | Şeklin genişliğini, point cinsinden alır. Okunur **float**. |
| **float** [get_X](../shape/get_x/)() override | Şeklin sol üst köşesinin x koordinatını, point cinsinden alır. Okunur **float**. |
| **float** [get_Y](../shape/get_y/)() override | Şeklin sol üst köşesinin y koordinatını, point cinsinden alır. Okunur **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Bir şeklin z-sırasındaki konumunu döndürür. Shapes[0] z-sırasının arkasındaki şekli, Shapes[Shapes.Count - 1] ise önündeki şekli döndürür. Yalnızca okunur **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Temel bir yer tutucu şekli döndürür (geçerli şeklin miras aldığı düzen ve/veya ana slayttan bir şekil). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analogudur. Özel nesnelerin hashlenmesini sağlar. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | Şekil küçük resmini döndürür. Varsayılan olarak [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) şekil küçük resmi sınır türü kullanılır. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Şekil küçük resmini döndürür. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogudur. |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | Şeklin işlenmiş içeriğinden hesaplanan görsel sınırlarını alır. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin hedef tip tarafından tanımlanan türün bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analogudur. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analogudur. Özel tiplerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referansla değer tipindeki nesneyi nullptr ile karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumuna özel bir versiyonudur. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize durumuna özel bir versiyonudur. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | Bu şeklin yer tutucu olmadığını tanımlar. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | Şekille ilişkili alternatif metni ayarlar. Yazın [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Şekille ilişkili alternatif metnin başlığını ayarlar. Yazın [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | Şeklin siyah-beyaz görüntü modunda nasıl render edileceğini belirten özelliği ayarlar. Yazın [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Şekil çerçevesinin özelliklerini ayarlar. Yazın [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | Şeklin yüksekliğini, point cinsinden ayarlar. Yazın **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | Şeklin gizli olup olmadığını belirler. Yazın **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Fare tıklaması için tanımlı hiperlinki ayarlar. Yazın [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Fare üzerine gelme için tanımlı hiperlinki ayarlar. Yazın [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | 'Mark as decorative' seçeneğini ayarlar. Okunur/yazılır **bool**. |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | Bir şeklin adını ayarlar. Null olmamalıdır. Gerekirse boş dize değeri kullanın. Yazın [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Ham şekil çerçevesinin özelliklerini ayarlar. Yazın [IShapeFrame](../ishapeframe/). |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | Belirtilen şeklin z-ekseni etrafında döndürülen derece sayısını ayarlar. Pozitif değer saat yönünde döndürmeyi, negatif değer saat yönünün tersine döndürmeyi gösterir. Yazın **float**. |
| void [set_Width](../shape/set_width/)(**float**) override | Şeklin genişliğini, point cinsinden ayarlar. Yazın **float**. |
| void [set_X](../shape/set_x/)(**float**) override | Şeklin sol üst köşesinin x koordinatını, point cinsinden ayarlar. Yazın **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | Şeklin sol üst köşesinin y koordinatını, point cinsinden ayarlar. Yazın **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşımlı yerine) olarak ayarlar. Kapsayıcılardaki işaretçileri zayıf moda geçiş yapmaya izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analogudur. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidi açmasını uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | [Shape](../shape/) içeriğini SVG dosyası olarak kaydeder. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | [Shape](../shape/) içeriğini SVG dosyası olarak kaydeder. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## İlgili

* Sınıf [Shape](../shape/)
* Sınıf [IGraphicalObject](../igraphicalobject/)
* AdAlanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)