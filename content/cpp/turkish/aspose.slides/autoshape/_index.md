---
title: AutoShape
second_title: Aspose.Slides for C++ API Referansı
description: Bir AutoShape'i temsil eder.
type: docs
weight: 66
url: /tr/aspose.slides/autoshape/
---
## AutoShape sınıfı

Bir [AutoShape](./) temsil eder.

```cpp
class AutoShape : public Aspose::Slides::GeometryShape,
                  public Aspose::Slides::IAutoShape
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Hiçbiri yoksa yeni bir yer tutucu ekler ve yer tutucu özelliklerini belirtilen birine ayarlar. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [AddTextFrame](./addtextframe/)([System::String](../../system/string/)) override | Bir şekle yeni bir [TextFrame](../textframe/) ekler. Şekilde zaten [TextFrame](../textframe/) varsa yalnızca metnini değiştirir. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../geometryshape/createshapeelements/)() override | Şeklin öğelerinin bir dizisini oluşturur ve döndürür. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) anlamı ile karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türündeki nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer türündeki nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | İki NaN'ın, IEC 60559:1989'a göre NaN'ın herhangi bir değerle, NaN dahil, eşit olmamasına rağmen, eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | İki NaN'ın, IEC 60559:1989'a göre NaN'ın herhangi bir değerle, NaN dahil, eşit olmamasına rağmen, eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../geometryshape/get_adjustment/)(**int32_t**) override | Belirtilen indeksdeki bir şeklin ayarlama değerini döndürür. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../geometryshape/get_adjustments/)() override | Şeklin ayarlama değerlerinin bir koleksiyonunu döndürür. Yalnızca okuma [IAdjustValueCollection](../iadjustvaluecollection/). |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Bir şekille ilişkili alternatif metni döndürür. Okuma [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Bir şekille ilişkili alternatif metnin başlığını döndürür. Okuma [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAutoShapeLock](../iautoshapelock/)\> [get_AutoShapeLock](./get_autoshapelock/)() override | AutoShape'ın kilitlerini döndürür. Yalnızca okuma [IAutoShapeLock](../iautoshapelock/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | Özellik, bir şeklin siyah-beyaz görüntüleme modunda nasıl render edileceğini belirtir. Okuma [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Şeklin bağlantı noktası sayısını döndürür. Yalnızca okuma **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Şeklin özel verisini döndürür. Yalnızca okuma [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | [EffectFormat](../effectformat/) nesnesini döndürür; bu nesne bir şekle uygulanan piksel efektlerini içerir. Not: efekt özellikleri olmayan bazı şekil türleri için null döndürebilir. Yalnızca okuma [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | [FillFormat](../fillformat/) nesnesini döndürür; bu nesne bir şeklin doldurma biçimlendirme özelliklerini içerir. Not: doldurma özellikleri olmayan bazı şekil türleri için null döndürebilir. Yalnızca okuma [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Şekil çerçevesinin özelliklerini döndürür. Okuma [IShapeFrame](../ishapeframe/). |
| **float** [get_Height](../shape/get_height/)() override | Şeklin yüksekliğini, puan cinsinden alır. Okuma **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Şeklin gizli olup olmadığını belirler. Okuma **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Fare tıklaması için tanımlı köprüyü döndürür. Okuma [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Köprü yöneticisini döndürür. Yalnızca okuma [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Fare üzerindeyken tanımlı köprüyü döndürür. Okuma [IHyperlink](../ihyperlink/). |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | ‘Dekoratif olarak işaretle’ seçeneğini alır. Okuma/yazma **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Şeklin gruplanıp gruplanmadığını belirler. Yalnızca okuma **bool**. |
| **bool** [get_IsTextBox](./get_istextbox/)() override | Şeklin bir metin kutusu olup olmadığını belirtir. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Şeklin TextHolder_PPT olup olmadığını belirler. Yalnızca okuma **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | [LineFormat](../lineformat/) nesnesini döndürür; bu nesne bir şeklin satır biçimlendirme özelliklerini içerir. Not: satır özellikleri olmayan bazı şekil türleri için null döndürebilir. Yalnızca okuma [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Bir şeklin adını döndürür. Null olmamalıdır. Gerektiğinde boş string değeri kullanın. Okuma [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Şeklin ömrü boyunca sabit kalan ve PowerPoint ya da interop kodunun şekle belgede herhangi bir yerden güvenilir şekilde başvurmasını sağlayan slayt kapsamlı benzersiz kimliği döndürür. Yalnızca okuma **uint32_t**. Ayrıca bakınız [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Şekil gruplanmışsa üst [GroupShape](../groupshape/) nesnesini döndürür. Aksi takdirde null döndürür. Yalnızca okuma [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Bir şeklin yer tutucusunu döndürür. Şeklin yer tutucusu yoksa null döndürür. Yalnızca okuma [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Bir slaydın üst sunumunu döndürür. Yalnızca okuma [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Ham şekil çerçevesinin özelliklerini döndürür. Okuma [IShapeFrame](../ishapeframe/). |
| **float** [get_Rotation](../shape/get_rotation/)() override | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını döndürür. Pozitif değer saat yönünde dönüş, negatif değer saat yönünün tersinde dönüş gösterir. Okuma **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Şeklin kilitlerini döndürür. Yalnızca okuma [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../geometryshape/get_shapestyle/)() override | Şeklin stil nesnesini döndürür. Yalnızca okuma [IShapeStyle](../ishapestyle/). |
| [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../geometryshape/get_shapetype/)() override | Geometri ön ayar tipini döndürür. Not: değer değiştiğinde tüm ayarlama değerleri varsayılan değerlerine sıfırlanır. Okuma [Slides::ShapeType](../shapetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Bir şeklin üst slaydını döndürür. Yalnızca okuma [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() override | [AutoShape](./) için [TextFrame](../textframe/) nesnesini döndürür. Yalnızca okuma [ITextFrame](../itextframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | Bir şeklin 3D etkisi özelliklerini içeren [ThreeDFormat](../threedformat/) nesnesini döndürür. Not: 3D özellikleri olmayan bazı şekil türleri için null döndürebilir. Yalnızca okuma [IThreeDFormat](../ithreedformat/). |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | Eklentiler veya diğer kodlar tarafından kullanılmak üzere tasarlanmış, içsel bir sunum kapsamlı kimliği döndürür. Bu değer kullanıcı tarafından veya programatik olarak yeniden atanabileceği için kalıcı benzersiz bir anahtar gibi kullanılmamalıdır. Yalnızca okuma **uint32_t**. Ayrıca bakınız [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **bool** [get_UseBackgroundFill](./get_usebackgroundfill/)() override | Bu autoşeklin slaytın arka plan dolgusuyla, stil veya dolgu biçimi yerine doldurulup doldurulmayacağını belirler. Okuma **bool**. |
| **float** [get_Width](../shape/get_width/)() override | Şeklin genişliğini, puan cinsinden alır. Okuma **float**. |
| **float** [get_X](../shape/get_x/)() override | Şeklin sol üst köşesinin x koordinatını, puan cinsinden alır. Okuma **float**. |
| **float** [get_Y](../shape/get_y/)() override | Şeklin sol üst köşesinin y koordinatını, puan cinsinden alır. Okuma **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Bir şeklin z-sırasındaki konumunu döndürür. Shapes[0] z-sırasının arkasındaki şekli, Shapes[Count - 1] ise önündeki şekli döndürür. Yalnızca okuma **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Temel bir yer tutucu şekli döndürür (geçerli şeklin miras aldığı yerleşim ve/veya ana slayttan alınan şekil). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../geometryshape/getgeometrypaths/)() override | Geometri şeklinin yolunun bir kopyasını döndürür. Koordinatlar şeklin sol üst köşesine göre relatiftir. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğudur. Özel nesnelerin hash'lenmesini etkinleştirir. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | Şeklin küçük resmini döndürür. Varsayılan olarak [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) şekil küçük resmi sınırları türü kullanılır. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Şeklin küçük resmini döndürür. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | Şeklin render edilmiş içeriğine göre hesaplanan görsel sınırlarını alır. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan türe bir örnek olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğudur. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumu için özelleştirmesidir. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumları için özelleştirmesidir. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | Bir şekille ilişkili alternatif metni ayarlar. Yazma [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Bir şekille ilişkili alternatif metnin başlığını ayarlar. Yazma [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | Özellik, bir şeklin siyah-beyaz görüntüleme modunda nasıl render edileceğini belirtir. Yazma [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Şekil çerçevesinin özelliklerini ayarlar. Yazma [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | Şeklin yüksekliğini, puan cinsinden ayarlar. Yazma **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | Şeklin gizli olup olmadığını belirler. Yazma **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Fare tıklaması için tanımlı köprüyü ayarlar. Yazma [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Fare üzerindeyken tanımlı köprüyü ayarlar. Yazma [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | ‘Dekoratif olarak işaretle’ seçeneğini ayarlar. Okuma/yazma **bool**. |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | Bir şeklin adını ayarlar. Null olmamalıdır. Gerektiğinde boş string değeri kullanın. Yazma [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Ham şekil çerçevesinin özelliklerini ayarlar. Yazma [IShapeFrame](../ishapeframe/). |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını ayarlar. Pozitif değer saat yönünde dönüş, negatif değer saat yönünün tersinde dönüş gösterir. Yazma **float**. |
| void [set_ShapeType](../geometryshape/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) override | Geometri ön ayar tipini ayarlar. Not: değer değiştiğinde tüm ayarlama değerleri varsayılan değerlerine sıfırlanır. Yazma [Slides::ShapeType](../shapetype/). |
| void [set_UseBackgroundFill](./set_usebackgroundfill/)(**bool**) override | Bu autoşeklin slaytın arka plan dolgusuyla, stil veya dolgu biçimi yerine doldurulup doldurulmayacağını belirler. Yazma **bool**. |
| void [set_Width](../shape/set_width/)(**float**) override | Şeklin genişliğini, puan cinsinden ayarlar. Yazma **float**. |
| void [set_X](../shape/set_x/)(**float**) override | Şeklin sol üst köşesinin x koordinatını, puan cinsinden ayarlar. Yazma **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | Şeklin sol üst köşesinin y koordinatını, puan cinsinden ayarlar. Yazma **float**. |
| void [SetGeometryPath](../geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) override | Şekil geometrisini [IGeometryPath](../igeometrypath/) nesnesinden günceller. Koordinatlar şeklin sol üst köşesine göre relatif olmalıdır. Şeklin tipini ([ShapeType](../shapetype/)) [ShapeType::Custom](../shapetype/) olarak değiştirir. |
| void [SetGeometryPaths](../geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) override | [IGeometryPath](../igeometrypath/) dizisinden şekil geometrisini günceller. Koordinatlar şeklin sol üst köşesine göre relatif olmalıdır. Şeklin tipini ([ShapeType](../shapetype/)) [ShapeType::Custom](../shapetype/) olarak değiştirir. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf gösterici (shared yerine) olarak ayarlar. Kapsayıcılardaki göstericilerin zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanın. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanın. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açmasını uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanın. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanın. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | [Shape](../shape/) içeriğini SVG dosyası olarak kaydeder. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | [Shape](../shape/) içeriğini SVG dosyası olarak kaydeder. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [GeometryShape](../geometryshape/)
* Sınıf [IAutoShape](../iautoshape/)
* Ad alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)