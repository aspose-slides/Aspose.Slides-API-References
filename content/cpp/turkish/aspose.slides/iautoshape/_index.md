---
title: IAutoShape
second_title: Aspose.Slides için C++ API Referansı
description: Bir AutoShape'i temsil eder.
type: docs
weight: 1366
url: /tr/aspose.slides/iautoshape/
---
## IAutoShape sınıfı

Bir [AutoShape](../autoshape/) temsil eder.

```cpp
class IAutoShape : public virtual Aspose::Slides::IGeometryShape
```

## Metotlar

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | Yeni bir yer tutucu ekler, yoksa ve yer tutucu özelliklerini belirtilen birine ayarlar. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [AddTextFrame](./addtextframe/)([System::String](../../system/string/)) | Şekle yeni bir [TextFrame](../textframe/) ekler. Şekil zaten [TextFrame](../textframe/) içeriyorsa metnini yalnızca değiştirir. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../igeometryshape/createshapeelements/)() | Şeklin öğelerinin dizisini oluşturur ve döndürür. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiği kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans tipi nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer tipi nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# stilinde kayan nokta karşılaştırmasını taklit eder; iki NaN, IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmamasına rağmen eşit kabul edilir. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# stilinde kayan nokta karşılaştırmasını taklit eder; iki NaN, IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmamasına rağmen eşit kabul edilir. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Sadece dahili amaçlar için. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../igeometryshape/get_adjustment/)(**int32_t**) | Belirtilen dizindeki şekil ayarlama değerini döndürür. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../igeometryshape/get_adjustments/)() | Şeklin ayarlama değerlerinin bir koleksiyonunu döndürür. Salt okunur [IAdjustValueCollection](../iadjustvaluecollection/). |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | Şekille ilişkili alternatif metni döndürür. Okuma [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | Şekille ilişkili alternatif metnin başlığını döndürür. Okuma [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAutoShapeLock](../iautoshapelock/)\> [get_AutoShapeLock](./get_autoshapelock/)() | [AutoShape](../autoshape/)'nin kilitlerini döndürür. Salt okunur [IAutoShapeLock](../iautoshapelock/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | Özellik, bir şeklin siyah-beyaz görüntü modunda nasıl render edileceğini belirtir. Okuma [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | Şeklin bağlantı noktalarının sayısını döndürür. Salt okunur **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | Şeklin özel verisini döndürür. Salt okunur [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | Şekle uygulanan piksel efektlerini içeren [EffectFormat](../effectformat/) nesnesini döndürür. Salt okunur [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | Şekil için dolgu biçimlendirme özelliklerini içeren [FillFormat](../fillformat/) nesnesini döndürür. Salt okunur [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | Şekil çerçevesinin özelliklerini döndürür. Okuma [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_Height](../ishape/get_height/)() | Şeklin yüksekliğini, puan cinsinden alır. Okuma **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | Şeklin gizli olup olmadığını belirler. Okuma **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Fare tıklaması için tanımlı köprüyü döndürür. Okuma [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Köprü yöneticisi. Salt okunur [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Fare üzerine gelindiğinde tanımlı köprüyü döndürür. Okuma [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | ‘Dekoratif olarak işaretle’ seçeneğini alır. Okuma/yazma **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | Şeklin gruplandığını belirler. Salt okunur **bool**. |
| virtual **bool** [get_IsTextBox](./get_istextbox/)() | Şeklin bir metin kutusu olup olmadığını belirtir. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | Şeklin TextHolder olup olmadığını belirler. Salt okunur **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | Şekil için satır biçimlendirme özelliklerini içeren [LineFormat](../lineformat/) nesnesini döndürür. Salt okunur [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | Bir şeklin adını döndürür. Okuma [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | Şeklin ömrü boyunca sabit kalan ve PowerPoint ya da interop kodunun şekle belgedeki herhangi bir yerden güvenilir şekilde başvurmasını sağlayan slayt kapsamında benzersiz bir tanımlayıcı döndürür. Salt okunur **uint32_t**. Ayrıca bakınız [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | Şekil gruplandırılmış ise üst [GroupShape](../groupshape/) nesnesini döndürür. Aksi takdirde null döndürür. Salt okunur [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | Şekil için yer tutucuyu döndürür. Salt okunur [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Sunumu döndürür. Salt okunur [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | Şeklin ham çerçeve özelliklerini döndürür. Okuma [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını döndürür. Pozitif değer saat yönünde dönüşü, negatif değer saat yönünün tersine dönüşü gösterir. Okuma **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | Şeklin kilitlerini döndürür. Salt okunur [IBaseShapeLock](../ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../igeometryshape/get_shapestyle/)() | Şeklin stil nesnesini döndürür. Salt okunur [IShapeStyle](../ishapestyle/). |
| virtual [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../igeometryshape/get_shapetype/)() | Geometri ön ayar tipini döndürür. Not: değer değiştiğinde tüm ayarlama değerleri varsayılan değerlerine sıfırlanır. Okuma [Slides::ShapeType](../shapetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Temel slaytı döndürür. Salt okunur [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() | [AutoShape](../autoshape/) için [TextFrame](../textframe/) nesnesini döndürür. Salt okunur [ITextFrame](../itextframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | Şekil için satır biçimlendirme özelliklerini içeren [ThreeDFormat](../threedformat/) nesnesini döndürür. Salt okunur [IThreeDFormat](../ithreedformat/). |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | Eklentiler veya diğer kodlar tarafından kullanılmak üzere içsel, sunum kapsamında bir tanımlayıcı döndürür. Bu değer kullanıcı veya program tarafından yeniden atanabileceği için kalıcı benzersiz bir anahtar olarak değerlendirilmemelidir. Salt okunur **uint32_t**. Ayrıca bakınız [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual **bool** [get_UseBackgroundFill](./get_usebackgroundfill/)() | Bu otomatik şeklin stil veya dolgu biçimi yerine slaytın arka plan dolgusuyla doldurulup doldurulmayacağını belirler. Okuma **bool**. |
| virtual **float** [get_Width](../ishape/get_width/)() | Şeklin genişliğini puan cinsinden alır. Okuma **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | Şeklin sol üst köşesinin x koordinatını puan cinsinden alır. Okuma **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | Şeklin sol üst köşesinin y koordinatını puan cinsinden alır. Okuma **float**. |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | Z-sırasındaki bir şeklin konumunu döndürür. Shapes[0] z-sırasının arkasındaki şekli, Shapes[Shapes.Count - 1] ise önündeki şekli döndürür. Salt okunur **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | Temel bir yer tutucu şekli döndürür (geçerli şeklin devralındığı yerleşim ve/veya ana slayttan bir şekil). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obje ile ilişkili referans sayacı veri yapısını alır. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../igeometryshape/getgeometrypaths/)() | Geometri şeklinin yolunun bir kopyasını döndürür. Koordinatlar şeklin sol üst köşesine göre relatiftir. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analogu. Özel nesnelerin hash'lenmesini sağlar. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | Şekil küçük resmini döndürür. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) şekil küçük resmi sınır tipi varsayılan olarak kullanılır. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | Şekil küçük resmini döndürür. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Objenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Objenin targetType tarafından tanımlanan tipe bir örnek temsil edip etmediğini kontrol eder. C# 'is' operatörünün analogu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın ya da [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analogu. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapıları başlatılır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'un dize ve nullptr durumu için özelleştirilmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'un dize durumları için özelleştirilmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | Bir şekille ilişkili alternatif metni ayarlar. Yaz [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Şekille ilişkili alternatif metnin başlığını ayarlar. Yaz [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | Özellik, bir şeklin siyah-beyaz görüntü modunda nasıl render edileceğini belirtir. Yaz [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Şekil çerçevesinin özelliklerini ayarlar. Yaz [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | Şeklin yüksekliğini puan cinsinden ayarlar. Yaz **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | Şeklin gizli olup olmadığını belirler. Yaz **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Fare tıklaması için tanımlı köprüyü ayarlar. Yaz [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Fare üzerine gelindiğinde tanımlı köprüyü ayarlar. Yaz [IHyperlink](../ihyperlink/). |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | ‘Dekoratif olarak işaretle’ seçeneğini ayarlar. Okuma/yazma **bool**. |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | Bir şeklin adını ayarlar. Yaz [System::String](../../system/string/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Şeklin ham çerçeve özelliklerini ayarlar. Yaz [IShapeFrame](../ishapeframe/). |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını ayarlar. Pozitif değer saat yönünde, negatif değer saat yönünün tersine dönüşü gösterir. Yaz **float**. |
| virtual void [set_ShapeType](../igeometryshape/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) | Geometri ön ayar tipini ayarlar. Not: değer değiştiğinde tüm ayarlama değerleri varsayılan değerlerine sıfırlanır. Yaz [Slides::ShapeType](../shapetype/). |
| virtual void [set_UseBackgroundFill](./set_usebackgroundfill/)(**bool**) | Bu otomatik şeklin stil veya dolgu biçimi yerine slaytın arka plan doldurmasıyla doldurulup doldurulmayacağını belirler. Yaz **bool**. |
| virtual void [set_Width](../ishape/set_width/)(**float**) | Şeklin genişliğini puan cinsinden ayarlar. Yaz **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | Şeklin sol üst köşesinin x koordinatını puan cinsinden ayarlar. Yaz **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | Şeklin sol üst köşesinin y koordinatını puan cinsinden ayarlar. Yaz **float**. |
| virtual void [SetGeometryPath](../igeometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) | [IGeometryPath](../igeometrypath/) nesnesinden şekil geometrisini günceller. Koordinatlar şeklin sol üst köşesine göre relatif olmalıdır. Şeklin tipini ([ShapeType](../shapetype/)) [ShapeType::Custom](../shapetype/) olarak değiştirir. |
| virtual void [SetGeometryPaths](../igeometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) | [IGeometryPath](../igeometrypath/) dizisinden şekil geometrisini günceller. Koordinatlar şeklin sol üst köşesine göre relatif olmalıdır. Şeklin tipini ([ShapeType](../shapetype/)) [ShapeType::Custom](../shapetype/) olarak değiştirir. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi olarak ayarlar (paylaşımlı yerine). Kapsayıcılardaki işaretçileri zayıf moda geçişe izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analogu. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açar. Doğrudan çağırın ya da [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | [Shape](../shape/) içeriğini SVG dosyası olarak kaydeder. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | [Shape](../shape/) içeriğini SVG dosyası olarak kaydeder. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapıları serbest bırakılır. |

## Ayrıca Bakınız

* Sınıf [IGeometryShape](../igeometryshape/)
* Ad alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)