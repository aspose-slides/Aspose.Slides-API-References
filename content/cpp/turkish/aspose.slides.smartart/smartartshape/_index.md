---
title: SmartArtShape
second_title: Aspose.Slides için C++ API Referansı
description: SmartArt şekli temsil eder
type: docs
weight: 105
url: /tr/aspose.slides.smartart/smartartshape/
---
## SmartArtShape sınıfı

[SmartArt](../smartart/) şekli temsil eder

```cpp
class SmartArtShape : public Aspose::Slides::GeometryShape,
                      public Aspose::Slides::SmartArt::ISmartArtShape
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) override | Yer tutucu yoksa yeni bir yer tutucu ekler ve yer tutucu özelliklerini belirtilen birine ayarlar. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../../aspose.slides/ishapeelement/)\>\> [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements/)() override | Şeklin öğelerinden oluşan bir dizi oluşturur ve döndürür. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiğini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipi nesneleri C# stilinde karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer tipi nesneleri C# stilinde karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değere, NaN dahil, eşit olmamasına rağmen iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değere, NaN dahil, eşit olmamasına rağmen iki NaN'in eşit kabul edildiği C# tarzı çift duyarlıklı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../../aspose.slides/iadjustvalue/)\> [get_Adjustment](../../aspose.slides/geometryshape/get_adjustment/)(**int32_t**) override | Belirtilen dizindeki bir şeklin ayar değerini döndürür. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../../aspose.slides/iadjustvaluecollection/)\> [get_Adjustments](../../aspose.slides/geometryshape/get_adjustments/)() override | Şeklin ayar değerlerinin bir koleksiyonunu döndürür. Salt okunur [IAdjustValueCollection](../../aspose.slides/iadjustvaluecollection/). |
| [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/shape/get_alternativetext/)() override | Bir şekille ilişkili alternatif metni döndürür. Okuma [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/shape/get_alternativetexttitle/)() override | Bir şekille ilişkili alternatif metnin başlığını döndürür. Okuma [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/shape/get_blackwhitemode/)() override | Özellik, bir şeklin siyah-beyaz görüntü modunda nasıl render edileceğini belirler. Okuma [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../../aspose.slides/shape/get_connectionsitecount/)() override | Şekildeki bağlantı noktalarının sayısını döndürür. Salt okunur **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/shape/get_customdata/)() override | Şeklin özel verilerini döndürür. Salt okunur [ICustomData](../../aspose.slides/icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/shape/get_effectformat/)() override | [EffectFormat](../../aspose.slides/effectformat/) nesnesini döndürür; bu nesne bir şekle uygulanmış piksel efektlerini içerir. Not: efekt özellikleri olmayan belirli şekil tipleri için null dönebilir. Salt okunur [IEffectFormat](../../aspose.slides/ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/shape/get_fillformat/)() override | [FillFormat](../../aspose.slides/fillformat/) nesnesini döndürür; bu nesne bir şeklin doldurma biçimlendirme özelliklerini içerir. Not: doldurma özellikleri olmayan belirli şekil tipleri için null dönebilir. Salt okunur [IFillFormat](../../aspose.slides/ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/shape/get_frame/)() override | Şekil çerçevesinin özelliklerini döndürür. Okuma [IShapeFrame](../../aspose.slides/ishapeframe/). |
| **float** [get_Height](../../aspose.slides/shape/get_height/)() override | Şeklin yüksekliğini, puan cinsinden alır. Okuma **float**. |
| **bool** [get_Hidden](../../aspose.slides/shape/get_hidden/)() override | Şeklin gizli olup olmadığını belirler. Okuma **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/shape/get_hyperlinkclick/)() override | Fare tıklaması için tanımlı bağlantıyı döndürür. Okuma [IHyperlink](../../aspose.slides/ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/shape/get_hyperlinkmanager/)() override | Bağlantı yöneticisini döndürür. Salt okunur [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/shape/get_hyperlinkmouseover/)() override | Fare üzerindeyken tanımlı bağlantıyı döndürür. Okuma [IHyperlink](../../aspose.slides/ihyperlink/). |
| **bool** [get_IsDecorative](../../aspose.slides/shape/get_isdecorative/)() override | 'Dekoratif olarak işaretle' seçeneğini alır. Okuma/yazma **bool**. |
| **bool** [get_IsGrouped](../../aspose.slides/shape/get_isgrouped/)() override | Şeklin gruplanıp gruplanmadığını belirler. Salt okunur **bool**. |
| **bool** [get_IsTextHolder](../../aspose.slides/shape/get_istextholder/)() override | Şeklin TextHolder_PPT olup olmadığını belirler. Salt okunur **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/shape/get_lineformat/)() override | [LineFormat](../../aspose.slides/lineformat/) nesnesini döndürür; bu nesne bir şeklin çizgi biçimlendirme özelliklerini içerir. Not: çizgi özellikleri olmayan belirli şekil tipleri için null dönebilir. Salt okunur [ILineFormat](../../aspose.slides/ilineformat/). |
| [System::String](../../system/string/) [get_Name](../../aspose.slides/shape/get_name/)() override | Bir şeklin adını döndürür. Null olmamalıdır. Gerekirse boş string değeri kullanın. Okuma [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/)() override | Şeklin ömrü boyunca sabit kalan ve PowerPoint ya da interop kodunun şekle belge içinde her yerden güvenilir bir şekilde referans vermesini sağlayan slayt ölçeğinde benzersiz bir tanımlayıcı döndürür. Salt okunur **uint32_t**. Ayrıca bakınız [Shape::get_UniqueId](../../aspose.slides/shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/shape/get_parentgroup/)() override | Şekil gruplanmışsa üst [GroupShape](../../aspose.slides/groupshape/) nesnesini döndürür. Aksi takdirde null döner. Salt okunur [IGroupShape](../../aspose.slides/igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/shape/get_placeholder/)() override | Bir şeklin yer tutucusunu döndürür. Şeklin yer tutucusu yoksa null döner. Salt okunur [IPlaceholder](../../aspose.slides/iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/shape/get_presentation/)() override | Bir slaydın üst sunumunu döndürür. Salt okunur [IPresentation](../../aspose.slides/ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/shape/get_rawframe/)() override | Ham şekil çerçevesinin özelliklerini döndürür. Okuma [IShapeFrame](../../aspose.slides/ishapeframe/). |
| **float** [get_Rotation](../../aspose.slides/shape/get_rotation/)() override | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını döndürür. Pozitif değer saat yönünde, negatif değer saat yönünün tersinde döndürülmeyi gösterir. Okuma **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/shape/get_shapelock/)() override | Şeklin kilitlerini döndürür. Salt okunur [IBaseShapeLock](../../aspose.slides/ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../../aspose.slides/ishapestyle/)\> [get_ShapeStyle](../../aspose.slides/geometryshape/get_shapestyle/)() override | Şeklin stil nesnesini döndürür. Salt okunur [IShapeStyle](../../aspose.slides/ishapestyle/). |
| [Aspose::Slides::ShapeType](../../aspose.slides/shapetype/) [get_ShapeType](./get_shapetype/)() override | Geometri ön ayar tipini döndürür. Not: değer değiştiğinde tüm ayar değerleri varsayılan değerlerine sıfırlanır. Okuma [Slides::ShapeType](../../aspose.slides/shapetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/shape/get_slide/)() override | Bir şeklin üst slaydını döndürür. Salt okunur [IBaseSlide](../../aspose.slides/ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrame](./get_textframe/)() override | [SmartArt](../smartart/) şeklinin metnini döndürür. Salt okunur [ITextFrame](../../aspose.slides/itextframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/shape/get_threedformat/)() override | [ThreeDFormat](../../aspose.slides/threedformat/) nesnesini döndürür; bu nesne bir şeklin 3D efekt özelliklerini içerir. Not: 3D özellikleri olmayan belirli şekil tipleri için null dönebilir. Salt okunur [IThreeDFormat](../../aspose.slides/ithreedformat/). |
| **uint32_t** [get_UniqueId](../../aspose.slides/shape/get_uniqueid/)() override | Eklentiler veya diğer kodlar tarafından kullanılmak üzere, sunum ölçeğinde dahili bir tanımlayıcı döndürür. Bu değer kullanıcı tarafından veya program aracılığıyla yeniden atanabileceği için kalıcı bir benzersiz anahtar olarak ele alınmamalıdır. Salt okunur **uint32_t**. Ayrıca bakınız [Shape::get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/). |
| **float** [get_Width](../../aspose.slides/shape/get_width/)() override | Şeklin genişliğini, puan cinsinden alır. Okuma **float**. |
| **float** [get_X](../../aspose.slides/shape/get_x/)() override | Şeklin sol üst köşesinin x koordinatını, puan cinsinden alır. Okuma **float**. |
| **float** [get_Y](../../aspose.slides/shape/get_y/)() override | Şeklin sol üst köşesinin y koordinatını, puan cinsinden alır. Okuma **float**. |
| **int32_t** [get_ZOrderPosition](../../aspose.slides/shape/get_zorderposition/)() override | Bir şeklin z-sırasındaki konumunu döndürür. Shapes[0] sıralamanın arkasındaki şekli, Shapes[Shapes.Count - 1] ise önündeki şekli döndürür. Salt okunur **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder/)() override | Temel bir yer tutucu şekli döndürür (geçerli şeklin türediği düzen ve/veya ana slayttan gelen şekil). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../../aspose.slides/igeometrypath/)\>\> [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths/)() override | Geometri şeklinin yolunun kopyasını döndürür. Koordinatlar şeklin sol üst köşesine göre relatifir. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özel nesnelerin hash'lenmesini sağlar. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)() override | Şekil küçük resmini döndürür. Varsayılan olarak [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) şekil küçük resim sınır tipi kullanılır. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) override | Şekil küçük resmini döndürür. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../../aspose.slides/shape/getvisualbounds/)() | Şeklin, işlenmiş içeriğinden hesaplanan görsel sınırlarını alır. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin hedef tip tarafından tanımlanan bir örnek olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlemci nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin klonlanmasını sağlar. |
| [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapıları başlatılır. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımına izin verir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımına izin verir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumu için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumları için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder/)() override | Bu şeklin bir yer tutucu olmadığını belirtir. |
| void [set_AlternativeText](../../aspose.slides/shape/set_alternativetext/)([System::String](../../system/string/)) override | Bir şekille ilişkili alternatif metni ayarlar. Yazma [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../../aspose.slides/shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Bir şekille ilişkili alternatif metnin başlığını ayarlar. Yazma [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../../aspose.slides/shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) override | Özellik, bir şeklin siyah-beyaz görüntü modunda nasıl render edileceğini belirler. Yazma [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| void [set_Frame](../../aspose.slides/shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | Şekil çerçevesinin özelliklerini ayarlar. Yazma [IShapeFrame](../../aspose.slides/ishapeframe/). |
| void [set_Height](../../aspose.slides/shape/set_height/)(**float**) override | Şeklin yüksekliğini, puan cinsinden ayarlar. Yazma **float**. |
| void [set_Hidden](../../aspose.slides/shape/set_hidden/)(**bool**) override | Şeklin gizli olup olmadığını belirler. Yazma **bool**. |
| void [set_HyperlinkClick](../../aspose.slides/shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | Fare tıklaması için tanımlı bağlantıyı ayarlar. Yazma [IHyperlink](../../aspose.slides/ihyperlink/). |
| void [set_HyperlinkMouseOver](../../aspose.slides/shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | Fare üzerindeyken tanımlı bağlantıyı ayarlar. Yazma [IHyperlink](../../aspose.slides/ihyperlink/). |
| void [set_IsDecorative](../../aspose.slides/shape/set_isdecorative/)(**bool**) override | 'Dekoratif olarak işaretle' seçeneğini ayarlar. Okuma/yazma **bool**. |
| void [set_Name](../../aspose.slides/shape/set_name/)([System::String](../../system/string/)) override | Bir şeklin adını ayarlar. Null olmamalıdır. Gerekirse boş string kullanın. Yazma [System::String](../../system/string/). |
| void [set_RawFrame](../../aspose.slides/shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | Ham şekil çerçevesinin özelliklerini ayarlar. Yazma [IShapeFrame](../../aspose.slides/ishapeframe/). |
| void [set_Rotation](../../aspose.slides/shape/set_rotation/)(**float**) override | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını ayarlar. Pozitif değer saat yönünde, negatif değer saat yönünün tersinde döndürülmeyi gösterir. Yazma **float**. |
| void [set_ShapeType](./set_shapetype/)([Aspose::Slides::ShapeType](../../aspose.slides/shapetype/)) override | Geometri ön ayar tipini ayarlar. Not: değer değiştiğinde tüm ayar değerleri varsayılan değerlerine sıfırlanır. Yazma [Slides::ShapeType](../../aspose.slides/shapetype/). |
| void [set_Width](../../aspose.slides/shape/set_width/)(**float**) override | Şeklin genişliğini, puan cinsinden ayarlar. Yazma **float**. |
| void [set_X](../../aspose.slides/shape/set_x/)(**float**) override | Şeklin sol üst köşesinin x koordinatını, puan cinsinden ayarlar. Yazma **float**. |
| void [set_Y](../../aspose.slides/shape/set_y/)(**float**) override | Şeklin sol üst köşesinin y koordinatını, puan cinsinden ayarlar. Yazma **float**. |
| void [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../../aspose.slides/igeometrypath/)\>) override | [IGeometryPath](../../aspose.slides/igeometrypath/) nesnesinden şekil geometrisini günceller. Koordinatlar şeklin sol üst köşesine göre relatif olmalıdır. Şeklin tipini ([ShapeType](../../aspose.slides/shapetype/)) [ShapeType::Custom](../../aspose.slides/shapetype/) olarak değiştirir. |
| void [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../../aspose.slides/igeometrypath/)\>\>) override | [IGeometryPath](../../aspose.slides/igeometrypath/) dizisinden şekil geometrisini günceller. Koordinatlar şeklin sol üst köşesine göre relatif olmalıdır. Şeklin tipini ([ShapeType](../../aspose.slides/shapetype/)) [ShapeType::Custom](../../aspose.slides/shapetype/) olarak değiştirir. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf gösterici (paylaşımlı yerine) olarak ayarlar. Kapsayıcılardaki göstericilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açmasını uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlemci nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | [Shape](../../aspose.slides/shape/) içeriğini SVG dosyası olarak kaydeder. |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | [Shape](../../aspose.slides/shape/) içeriğini SVG dosyası olarak kaydeder. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [GeometryShape](../../aspose.slides/geometryshape/)
* Sınıf [ISmartArtShape](../ismartartshape/)
* Ad alanı [Aspose::Slides::SmartArt](../)
* Kütüphane [Aspose.Slides](../../)