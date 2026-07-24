---
title: Shape
second_title: Aspose.Slides için C++ API Referansı
description: Bir slayttaki şekli temsil eder.
type: docs
weight: 5084
url: /tr/aspose.slides/shape/
---
## Shape sınıfı

Bir slayttaki şekli temsil eder.

```cpp
class Shape : public virtual Aspose::Slides::IShape,
              public Aspose::Slides::IDOMObject
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](./addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Yeni bir yer tutucu ekler, eğer mevcut değilse ve yer tutucu özelliklerini belirtilen birine ayarlar. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objeleri C# [Object.Equals](../../system/object/equals/) semantiği kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipi nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer tipi nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'ın hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'ın eşit kabul edildiği C#-tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'ın hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'ın eşit kabul edildiği C#-tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [System::String](../../system/string/) [get_AlternativeText](./get_alternativetext/)() override | Bir şekille ilişkili alternatif metni döndürür. Okuyun [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](./get_alternativetexttitle/)() override | Bir şekille ilişkili alternatif metnin başlığını döndürür. Okuyun [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](./get_blackwhitemode/)() override | Özellik, bir şeklin siyah-beyaz görüntüleme modunda nasıl render edileceğini belirtir. Okuyun [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](./get_connectionsitecount/)() override | Şeklin bağlantı noktası sayısını döndürür. Salt okunur **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](./get_customdata/)() override | Şeklin özel verilerini döndürür. Salt okunur [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() override | [EffectFormat](../effectformat/) nesnesini döndürür; bu nesne bir şekle uygulanan piksel efektlerini içerir. Not: efekt özellikleri olmayan bazı şekil türleri için null döndürebilir. Salt okunur [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() override | [FillFormat](../fillformat/) nesnesini döndürür; bu nesne bir şekil için dolgu biçimlendirme özelliklerini içerir. Not: dolgu özellikleri olmayan bazı şekil türleri için null döndürebilir. Salt okunur [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](./get_frame/)() override | Şekil çerçevesinin özelliklerini döndürür. Okuyun [IShapeFrame](../ishapeframe/). |
| **float** [get_Height](./get_height/)() override | Şeklin yüksekliğini, puan cinsinden alır. Salt okunur **float**. |
| **bool** [get_Hidden](./get_hidden/)() override | Şeklin gizli olup olmadığını belirler. Salt okunur **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](./get_hyperlinkclick/)() override | Fare tıklaması için tanımlanan köprüyü döndürür. Okuyun [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](./get_hyperlinkmanager/)() override | Köprü yöneticisini döndürür. Salt okunur [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](./get_hyperlinkmouseover/)() override | Fare üzerine gelindiğinde tanımlanan köprüyü döndürür. Okuyun [IHyperlink](../ihyperlink/). |
| **bool** [get_IsDecorative](./get_isdecorative/)() override | 'Mark as decorative' seçeneğini alır. Okuma/yazma **bool**. |
| **bool** [get_IsGrouped](./get_isgrouped/)() override | Şeklin gruplanıp gruplanmadığını belirler. Salt okunur **bool**. |
| **bool** [get_IsTextHolder](./get_istextholder/)() override | Şeklin TextHolder_PPT olup olmadığını belirler. Salt okunur **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() override | [LineFormat](../lineformat/) nesnesini döndürür; bu nesne bir şekil için satır biçimlendirme özelliklerini içerir. Not: satır özellikleri olmayan bazı şekil türleri için null döndürebilir. Salt okunur [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](./get_name/)() override | Bir şeklin adını döndürür. Null olmamalıdır. Gerekirse boş string değeri kullanın. Okuyun [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](./get_officeinteropshapeid/)() override | Şeklin ömrü boyunca sabit kalan ve PowerPoint ya da interop kodunun şekli belgede herhangi bir yerden güvenilir şekilde referans almasını sağlayan slayt kapsamlı benzersiz kimliği döndürür. Salt okunur **uint32_t**. Ayrıca bkz. [Shape::get_UniqueId](./get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](./get_parentgroup/)() override | Şekil gruplanmışsa üst [GroupShape](../groupshape/) nesnesini döndürür. Aksi takdirde null döndürür. Salt okunur [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](./get_placeholder/)() override | Bir şekil için yer tutucuyu döndürür. Şeklin yer tutucusu yoksa null döndürür. Salt okunur [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](./get_presentation/)() override | Bir slayın üst sunumunu döndürür. Salt okunur [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](./get_rawframe/)() override | Ham şekil çerçevesinin özelliklerini döndürür. Okuyun [IShapeFrame](../ishapeframe/). |
| **float** [get_Rotation](./get_rotation/)() override | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını döndürür. Pozitif değer saat yönünde döndürmeyi, negatif değer saat yönünün tersinde döndürmeyi gösterir. Salt okunur **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](./get_shapelock/)() override | Şeklin kilitlerini döndürür. Salt okunur [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](./get_slide/)() override | Bir şeklin üst slaytını döndürür. Salt okunur [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() override | [ThreeDFormat](../threedformat/) nesnesini döndürür; bu nesne bir şekle ait 3D efekt özelliklerini içerir. Not: 3D özellikleri olmayan bazı şekil türleri için null döndürebilir. Salt okunur [IThreeDFormat](../ithreedformat/). |
| **uint32_t** [get_UniqueId](./get_uniqueid/)() override | Eklentiler veya diğer kodlar tarafından kullanılmak üzere, içsel, sunum kapsamlı bir tanımlayıcı döndürür. Bu değer kullanıcı tarafından veya programatik olarak yeniden atanabileceği için kalıcı benzersiz bir anahtar olarak ele alınmamalıdır. Salt okunur **uint32_t**. Ayrıca bkz. [Shape::get_OfficeInteropShapeId](./get_officeinteropshapeid/). |
| **float** [get_Width](./get_width/)() override | Şeklin genişliğini, puan cinsinden alır. Salt okunur **float**. |
| **float** [get_X](./get_x/)() override | Şeklin sol üst köşesinin x koordinatını, puan cinsinden alır. Salt okunur **float**. |
| **float** [get_Y](./get_y/)() override | Şeklin sol üst köşesinin y koordinatını, puan cinsinden alır. Salt okunur **float**. |
| **int32_t** [get_ZOrderPosition](./get_zorderposition/)() override | Bir şeklin z-sırasındaki konumunu döndürür. Shapes[0] z-sırasının arkasındaki şekli, Shapes[Shapes.Count - 1] ise önündeki şekli döndürür. Salt okunur **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](./getbaseplaceholder/)() override | Temel bir yer tutucu şekli döndürür (geçerli şeklin miras aldığı düzen ve/veya ana slayttan gelen şekil). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analogudur. Özelleştirilmiş nesnelerin hashlenmesini sağlar. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)() override | Şeklin küçük resmini döndürür. Varsayılan olarak [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) şekil küçük resim sınır tipi kullanılır. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Şeklin küçük resmini döndürür. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogudur. |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](./getvisualbounds/)() | Render edilmiş içeriğinden hesaplanan şeklin görsel sınırlarını alır. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin, hedefTip tarafından tanımlanan türün bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analogudur. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analogudur. Özelleştirilmiş tiplerin klonlanmasını sağlar. |
| [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapılarını başlatır. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans kıyaslaması yapar. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'in dize ve nullptr durumu için özelleştirmesidir. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'in dize durumları için özelleştirmesidir. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| void [RemovePlaceholder](./removeplaceholder/)() override | Bu şeklin bir yer tutucu olmadığını belirtir. |
| void [set_AlternativeText](./set_alternativetext/)([System::String](../../system/string/)) override | Bir şekille ilişkili alternatif metni ayarlar. Yazın [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](./set_alternativetexttitle/)([System::String](../../system/string/)) override | Bir şekille ilişkili alternatif metnin başlığını ayarlar. Yazın [System::String](../../system/string/). |
| void [set_BlackWhiteMode](./set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | Özellik, bir şeklin siyah-beyaz görüntüleme modunda nasıl render edileceğini belirtir. Yazın [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_Frame](./set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Şekil çerçevesinin özelliklerini ayarlar. Yazın [IShapeFrame](../ishapeframe/). |
| void [set_Height](./set_height/)(**float**) override | Şeklin yüksekliğini, puan cinsinden ayarlar. Yazın **float**. |
| void [set_Hidden](./set_hidden/)(**bool**) override | Şeklin gizli olup olmadığını belirler. Yazın **bool**. |
| void [set_HyperlinkClick](./set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Fare tıklaması için tanımlanan köprüyü ayarlar. Yazın [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](./set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Fare üzerine gelindiğinde tanımlanan köprüyü ayarlar. Yazın [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](./set_isdecorative/)(**bool**) override | 'Mark as decorative' seçeneğini ayarlar. Okuma/yazma **bool**. |
| void [set_Name](./set_name/)([System::String](../../system/string/)) override | Bir şeklin adını ayarlar. Null olmamalıdır. Gerekirse boş string değeri kullanın. Yazın [System::String](../../system/string/). |
| void [set_RawFrame](./set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Ham şekil çerçevesinin özelliklerini ayarlar. Yazın [IShapeFrame](../ishapeframe/). |
| void [set_Rotation](./set_rotation/)(**float**) override | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını ayarlar. Pozitif değer saat yönünde döndürmeyi, negatif değer saat yönünün tersinde döndürmeyi gösterir. Yazın **float**. |
| void [set_Width](./set_width/)(**float**) override | Şeklin genişliğini, puan cinsinden ayarlar. Yazın **float**. |
| void [set_X](./set_x/)(**float**) override | Şeklin sol üst köşesinin x koordinatını, puan cinsinden ayarlar. Yazın **float**. |
| void [set_Y](./set_y/)(**float**) override | Şeklin sol üst köşesinin y koordinatını, puan cinsinden ayarlar. Yazın **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşımlı değil) olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analogudur. Özelleştirilmiş nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WriteAsSvg](./writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | [Shape](./) içeriğini SVG dosyası olarak kaydeder. |
| void [WriteAsSvg](./writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | [Shape](./) içeriğini SVG dosyası olarak kaydeder. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Diğer Bilgiler

* Sınıf [IShape](../ishape/)
* Sınıf [IDOMObject](../idomobject/)
* Ad alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)