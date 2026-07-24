---
title: ISmartArtShape
second_title: Aspose.Slides for C++ API Referansı
description: SmartArt diyagramı içinde bir şekli temsil eder
type: docs
weight: 40
url: /tr/aspose.slides.smartart/ismartartshape/
---
## ISmartArtShape sınıf


Represents a shape inside [SmartArt](../smartart/) diagram

```cpp
class ISmartArtShape : public virtual Aspose::Slides::IGeometryShape
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) | Eğer yoksa yeni bir yer tutucu ekler ve yer tutucu özelliklerini belirtilen bir taneye ayarlar. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../../aspose.slides/ishapeelement/)\>\> [CreateShapeElements](../../aspose.slides/igeometryshape/createshapeelements/)() | Şeklin öğelerinden oluşan bir dizi oluşturur ve döndürür. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantik kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipi nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer tipi nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../../aspose.slides/iadjustvalue/)\> [get_Adjustment](../../aspose.slides/igeometryshape/get_adjustment/)(**int32_t**) | Belirtilen indeksdeki şekil ayarlama değerini döndürür. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../../aspose.slides/iadjustvaluecollection/)\> [get_Adjustments](../../aspose.slides/igeometryshape/get_adjustments/)() | Şeklin ayarlama değerlerinin bir koleksiyonunu döndürür. Yalnızca okuma [IAdjustValueCollection](../../aspose.slides/iadjustvaluecollection/). |
| virtual [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/ishape/get_alternativetext/)() | Şekille ilişkili alternatif metni döndürür. Okuma [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/ishape/get_alternativetexttitle/)() | Şekille ilişkili alternatif metnin başlığını döndürür. Okuma [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/ishape/get_blackwhitemode/)() | Özellik, bir şeklin siyah-beyaz görüntü modunda nasıl render edileceğini belirtir. Okuma [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](../../aspose.slides/ishape/get_connectionsitecount/)() | Şeklin bağlantı noktası sayısını döndürür. Yalnızca okuma **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/ishape/get_customdata/)() | Şeklin özel verilerini döndürür. Yalnızca okuma [ICustomData](../../aspose.slides/icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/ishape/get_effectformat/)() | Şekle uygulanan piksel efektlerini içeren [EffectFormat](../../aspose.slides/effectformat/) nesnesini döndürür. Yalnızca okuma [IEffectFormat](../../aspose.slides/ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/ishape/get_fillformat/)() | Şeklin dolgu biçimlendirme özelliklerini içeren [FillFormat](../../aspose.slides/fillformat/) nesnesini döndürür. Yalnızca okuma [IFillFormat](../../aspose.slides/ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/ishape/get_frame/)() | Şekil çerçevesinin özelliklerini döndürür. Okuma [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual **float** [get_Height](../../aspose.slides/ishape/get_height/)() | Şeklin yüksekliğini, puan cinsinden alır. Okuma **float**. |
| virtual **bool** [get_Hidden](../../aspose.slides/ishape/get_hidden/)() | Şeklin gizli olup olmadığını belirler. Okuma **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkclick/)() | Fare tıklaması için tanımlanan köprüyü döndürür. Okuma [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmanager/)() | Köprü yöneticisi Yalnızca okuma [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmouseover/)() | Fare üzerine geldiğinde tanımlanan köprüyü döndürür. Okuma [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual **bool** [get_IsDecorative](../../aspose.slides/ishape/get_isdecorative/)() | ‘Dekoratif olarak işaretle’ seçeneğini alır. Okuma/yazma **bool**. |
| virtual **bool** [get_IsGrouped](../../aspose.slides/ishape/get_isgrouped/)() | Şeklin gruplanıp gruplanmadığını belirler. Yalnızca okuma **bool**. |
| virtual **bool** [get_IsTextHolder](../../aspose.slides/ishape/get_istextholder/)() | Şeklin TextHolder olup olmadığını belirler. Yalnızca okuma **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/ishape/get_lineformat/)() | Şeklin çizgi biçimlendirme özelliklerini içeren [LineFormat](../../aspose.slides/lineformat/) nesnesini döndürür. Yalnızca okuma [ILineFormat](../../aspose.slides/ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../../aspose.slides/ishape/get_name/)() | Şeklin adını döndürür. Okuma [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/)() | Şeklin ömrü boyunca sabit kalan ve PowerPoint ya da interop kodunun belge içindeki herhangi bir yerden şekle güvenilir şekilde başvurmasını sağlayan slayt kapsamlı benzersiz bir tanımlayıcı döndürür. Yalnızca okuma **uint32_t**. Ayrıca bakınız [IShape::get_UniqueId](../../aspose.slides/ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/ishape/get_parentgroup/)() | Şekil gruplanmışsa üst [GroupShape](../../aspose.slides/groupshape/) nesnesini döndürür. Aksi takdirde null döndürür. Yalnızca okuma [IGroupShape](../../aspose.slides/igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/ishape/get_placeholder/)() | Bir şekil için yer tutucuyu döndürür. Yalnızca okuma [IPlaceholder](../../aspose.slides/iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Sunumu döndürür. Yalnızca okuma [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/ishape/get_rawframe/)() | Ham şekil çerçevesinin özelliklerini döndürür. Okuma [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual **float** [get_Rotation](../../aspose.slides/ishape/get_rotation/)() | Belirtilen şeklin z ekseni etrafında döndürülmüş olduğu derece sayısını döndürür. Pozitif değer saat yönünde döndürmeyi, negatif değer saat yönünün tersine döndürmeyi gösterir. Okuma **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/ishape/get_shapelock/)() | Şeklin kilitlerini döndürür. Yalnızca okuma [IBaseShapeLock](../../aspose.slides/ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../../aspose.slides/ishapestyle/)\> [get_ShapeStyle](../../aspose.slides/igeometryshape/get_shapestyle/)() | Şeklin stil nesnesini döndürür. Yalnızca okuma [IShapeStyle](../../aspose.slides/ishapestyle/). |
| virtual [Aspose::Slides::ShapeType](../../aspose.slides/shapetype/) [get_ShapeType](../../aspose.slides/igeometryshape/get_shapetype/)() | Geometri ön ayar tipini döndürür. Not: değer değiştiğinde tüm ayar değerleri varsayılan değerlerine sıfırlanır. Okuma [Slides::ShapeType](../../aspose.slides/shapetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Temel slaytı döndürür. Yalnızca okuma [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrame](./get_textframe/)() | [SmartArt](../smartart/) şeklinin metnini döndürür. Yalnızca okuma [ITextFrame](../../aspose.slides/itextframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/ishape/get_threedformat/)() | Şeklin çizgi biçimlendirme özelliklerini içeren [ThreeDFormat](../../aspose.slides/threedformat/) nesnesini döndürür. Yalnızca okuma [IThreeDFormat](../../aspose.slides/ithreedformat/). |
| virtual **uint32_t** [get_UniqueId](../../aspose.slides/ishape/get_uniqueid/)() | Eklentiler veya diğer kodlar tarafından kullanılmak üzere tasarlanmış dahili, sunum kapsamlı bir tanımlayıcı döndürür. Bu değer kullanıcı veya programatik olarak yeniden atanabileceği için kalıcı benzersiz bir anahtar olarak ele alınmamalıdır. Yalnızca okuma **uint32_t**. Ayrıca bakınız [IShape::get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/). |
| virtual **float** [get_Width](../../aspose.slides/ishape/get_width/)() | Şeklin genişliğini puan cinsinden alır. Okuma **float**. |
| virtual **float** [get_X](../../aspose.slides/ishape/get_x/)() | Şeklin sol üst köşesinin x koordinatını puan cinsinden alır. Okuma **float**. |
| virtual **float** [get_Y](../../aspose.slides/ishape/get_y/)() | Şeklin sol üst köşesinin y koordinatını puan cinsinden alır. Okuma **float**. |
| virtual **int32_t** [get_ZOrderPosition](../../aspose.slides/ishape/get_zorderposition/)() | Z-sırasındaki bir şeklin konumunu döndürür. Shapes[0] sıralamanın arkasındaki şekli, Shapes[Shapes.Count - 1] ise sıralamanın önündeki şekli döndürür. Yalnızca okuma **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder/)() | Temel bir yer tutucu şekli döndürür (mevcut şeklin devralındığı yerleşim ve/veya ana slayttan gelen şekil). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../../aspose.slides/igeometrypath/)\>\> [GetGeometryPaths](../../aspose.slides/igeometryshape/getgeometrypaths/)() | Geometri şeklinin yolunun bir kopyasını döndürür. Koordinatlar şeklin sol üst köşesine göre relatif'tir. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun benzeri. Özel nesnelerin hash'lenmesini sağlar. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)() | Şekil küçük resmini döndürür. [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) şekil küçük resmi sınır türü varsayılan olarak kullanılır. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) | Şekil küçük resmini döndürür. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının benzeri. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün benzeri. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini gerçekleştirir. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) koruma nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun benzeri. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumları için özelleştirilmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize durumları için özelleştirilmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder/)() | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| virtual void [set_AlternativeText](../../aspose.slides/ishape/set_alternativetext/)([System::String](../../system/string/)) | Şekille ilişkili alternatif metni ayarlar. Yazma [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../../aspose.slides/ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Şekille ilişkili alternatif metnin başlığını ayarlar. Yazma [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../../aspose.slides/ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) | Özellik, bir şeklin siyah-beyaz görüntü modunda nasıl render edileceğini belirtir. Yazma [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| virtual void [set_Frame](../../aspose.slides/ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | Şekil çerçevesinin özelliklerini ayarlar. Yazma [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual void [set_Height](../../aspose.slides/ishape/set_height/)(**float**) | Şeklin yüksekliğini puan cinsinden ayarlar. Yazma **float**. |
| virtual void [set_Hidden](../../aspose.slides/ishape/set_hidden/)(**bool**) | Şeklin gizlenip gizlenmediğini ayarlar. Yazma **bool**. |
| virtual void [set_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | Fare tıklaması için tanımlanan köprüyü ayarlar. Yazma [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | Fare üzerine gelince tanımlanan köprüyü ayarlar. Yazma [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual void [set_IsDecorative](../../aspose.slides/ishape/set_isdecorative/)(**bool**) | ‘Dekoratif olarak işaretle’ seçeneğini ayarlar. Okuma/yazma **bool**. |
| virtual void [set_Name](../../aspose.slides/ishape/set_name/)([System::String](../../system/string/)) | Bir şeklin adını ayarlar. Yazma [System::String](../../system/string/). |
| virtual void [set_RawFrame](../../aspose.slides/ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | Ham şekil çerçevesinin özelliklerini ayarlar. Yazma [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual void [set_Rotation](../../aspose.slides/ishape/set_rotation/)(**float**) | Belirtilen şeklin z ekseni etrafında döndürülmüş olduğu derece sayısını ayarlar. Pozitif değer saat yönünde döndürmeyi, negatif değer saat yönünün tersine döndürmeyi gösterir. Yazma **float**. |
| virtual void [set_ShapeType](../../aspose.slides/igeometryshape/set_shapetype/)([Aspose::Slides::ShapeType](../../aspose.slides/shapetype/)) | Geometri ön ayar tipini ayarlar. Not: değer değiştiğinde tüm ayar değerleri varsayılan değerlerine sıfırlanır. Yazma [Slides::ShapeType](../../aspose.slides/shapetype/). |
| virtual void [set_Width](../../aspose.slides/ishape/set_width/)(**float**) | Şeklin genişliğini puan cinsinden ayarlar. Yazma **float**. |
| virtual void [set_X](../../aspose.slides/ishape/set_x/)(**float**) | Şeklin sol üst köşesinin x koordinatını puan cinsinden ayarlar. Yazma **float**. |
| virtual void [set_Y](../../aspose.slides/ishape/set_y/)(**float**) | Şeklin sol üst köşesinin y koordinatını puan cinsinden ayarlar. Yazma **float**. |
| virtual void [SetGeometryPath](../../aspose.slides/igeometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../../aspose.slides/igeometrypath/)\>) | Şekil geometrisini [IGeometryPath](../../aspose.slides/igeometrypath/) nesnesinden günceller. Koordinatlar şeklin sol üst köşesine göre relatif olmalıdır. Şeklin tipini ([ShapeType](../../aspose.slides/shapetype/)) [ShapeType::Custom](../../aspose.slides/shapetype/) olarak değiştirir. |
| virtual void [SetGeometryPaths](../../aspose.slides/igeometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../../aspose.slides/igeometrypath/)\>\>) | Şekil geometrisini [IGeometryPath](../../aspose.slides/igeometrypath/) dizisinden günceller. Koordinatlar şeklin sol üst köşesine göre relatif olmalıdır. Şeklin tipini ([ShapeType](../../aspose.slides/shapetype/)) [ShapeType::Custom](../../aspose.slides/shapetype/) olarak değiştirir. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını paylaşımlı yerine zayıf bir gösterici olarak ayarlar. Kapsayıcılardaki göstericilerin zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun benzeri. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını gerçekleştirir. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlemini gerçekleştirir. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) koruma nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | [Shape](../../aspose.slides/shape/) içeriğini SVG dosyası olarak kaydeder. |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | [Shape](../../aspose.slides/shape/) içeriğini SVG dosyası olarak kaydeder. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [IGeometryShape](../../aspose.slides/igeometryshape/)
* Ad alanı [Aspose::Slides::SmartArt](../)
* Kütüphane [Aspose.Slides](../../)