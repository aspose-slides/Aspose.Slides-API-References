---
title: InkActions
second_title: Aspose.Slides için C++ API Referansı
description: İnkt eylemlerinin kökünü temsil eder.
type: docs
weight: 66
url: /tr/aspose.slides.ink/inkactions/
---
## InkActions sınıfı

İnkt eylemlerinin kökünü temsil eder.

```cpp
class InkActions : public Aspose::Slides::GraphicalObject,
                   public Aspose::Slides::Ink::IInkActions
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) override | Yeni bir yer tutucu ekler, eğer yoksa ve yer tutucu özelliklerini belirtilen birine ayarlar. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) mantığını kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipi nesneleri C# stilinde karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer tipi nesneleri C# stilinde karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 standardına göre NaN hiçbir değerle, NaN dahil, eşit olmamakla birlikte, C# tarzı kayan nokta karşılaştırmasını taklit eder; iki NaN eşit kabul edilir. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 standardına göre NaN hiçbir değerle, NaN dahil, eşit olmamakla birlikte, C# tarzı kayan nokta karşılaştırmasını taklit eder; iki NaN eşit kabul edilir. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/shape/get_alternativetext/)() override | Bir şekille ilişkilendirilmiş alternatif metni döndürür. Oku [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/shape/get_alternativetexttitle/)() override | Bir şekille ilişkilendirilmiş alternatif metnin başlığını döndürür. Oku [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/shape/get_blackwhitemode/)() override | Özellik, bir şeklin siyah-beyaz görüntü modunda nasıl render edileceğini belirtir. Oku [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../../aspose.slides/shape/get_connectionsitecount/)() override | Şekildeki bağlantı noktalarının sayısını döndürür. Sadece okuma **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/shape/get_customdata/)() override | Şeklin özel verilerini döndürür. Sadece okuma [ICustomData](../../aspose.slides/icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/shape/get_effectformat/)() override | Piksel efektlerini içeren [EffectFormat](../../aspose.slides/effectformat/) nesnesini döndürür. Not: bazı şekil türleri için null dönebilir; bu şekillerde etki özellikleri yoktur. Sadece okuma [IEffectFormat](../../aspose.slides/ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/shape/get_fillformat/)() override | Dolgu biçimlendirme özelliklerini içeren [FillFormat](../../aspose.slides/fillformat/) nesnesini döndürür. Not: bazı şekil türleri için null dönebilir; bu şekillerde dolgu özellikleri yoktur. Sadece okuma [IFillFormat](../../aspose.slides/ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/shape/get_frame/)() override | Şekil çerçevesinin özelliklerini döndürür. Oku [IShapeFrame](../../aspose.slides/ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)\> [get_GraphicalObjectLock](../../aspose.slides/graphicalobject/get_graphicalobjectlock/)() override | Şekil kilitlerini döndürür. Sadece okuma [IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/). |
| **float** [get_Height](../../aspose.slides/shape/get_height/)() override | Şeklin yüksekliğini, puan cinsinden alır. Oku **float**. |
| **bool** [get_Hidden](../../aspose.slides/shape/get_hidden/)() override | Şeklin gizli olup olmadığını belirler. Oku **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/shape/get_hyperlinkclick/)() override | Fare tıklaması için tanımlanan hiperveyi döndürür. Oku [IHyperlink](../../aspose.slides/ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/shape/get_hyperlinkmanager/)() override | Hipervey yöneticisini döndürür. Sadece okuma [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/shape/get_hyperlinkmouseover/)() override | Fare üzerindeyken tanımlanan hiperveyi döndürür. Oku [IHyperlink](../../aspose.slides/ihyperlink/). |
| **bool** [get_IsDecorative](../../aspose.slides/shape/get_isdecorative/)() override | 'Mark as decorative' seçeneğini alır. Okuma/yazma **bool**. |
| **bool** [get_IsGrouped](../../aspose.slides/shape/get_isgrouped/)() override | Şeklin gruplanıp gruplanmadığını belirler. Sadece okuma **bool**. |
| **bool** [get_IsTextHolder](../../aspose.slides/shape/get_istextholder/)() override | Şeklin TextHolder_PPT olup olmadığını belirler. Sadece okuma **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/shape/get_lineformat/)() override | Çizgi biçimlendirme özelliklerini içeren [LineFormat](../../aspose.slides/lineformat/) nesnesini döndürür. Not: bazı şekil türleri için null dönebilir; bu şekillerde çizgi özellikleri yoktur. Sadece okuma [ILineFormat](../../aspose.slides/ilineformat/). |
| [System::String](../../system/string/) [get_Name](../../aspose.slides/shape/get_name/)() override | Bir şeklin adını döndürür. Null olmamalıdır. Gerekirse boş dize kullanın. Oku [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/)() override | Slayt kapsamındaki benzersiz kimliği döndürür; şeklin ömrü boyunca sabit kalır ve PowerPoint ya da interop kodunun şekle her yerden güvenilir referans vermesini sağlar. Sadece okuma **uint32_t**. Ayrıca bakınız [Shape::get_UniqueId](../../aspose.slides/shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/shape/get_parentgroup/)() override | Şekil gruplanmışsa üst [GroupShape](../../aspose.slides/groupshape/) nesnesini döndürür. Aksi takdirde null döner. Sadece okuma [IGroupShape](../../aspose.slides/igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/shape/get_placeholder/)() override | Bir şekil için yer tutucuyu döndürür. Şeklin yer tutucusu yoksa null döner. Sadece okuma [IPlaceholder](../../aspose.slides/iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/shape/get_presentation/)() override | Bir slaydın üst sunumunu döndürür. Sadece okuma [IPresentation](../../aspose.slides/ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/shape/get_rawframe/)() override | Ham şekil çerçevesinin özelliklerini döndürür. Oku [IShapeFrame](../../aspose.slides/ishapeframe/). |
| **float** [get_Rotation](../../aspose.slides/shape/get_rotation/)() override | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını döndürür. Pozitif değer saat yönünde, negatif değer saat yönünün tersine. Oku **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/shape/get_shapelock/)() override | Şekil kilitlerini döndürür. Sadece okuma [IBaseShapeLock](../../aspose.slides/ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/shape/get_slide/)() override | Şeklin üst slaydını döndürür. Sadece okuma [IBaseSlide](../../aspose.slides/ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/shape/get_threedformat/)() override | [ThreeDFormat](../../aspose.slides/threedformat/) nesnesini döndürür; şekil için 3D etki özelliklerini içerir. Not: bazı şekil türleri için null dönebilir; bu şekillerde 3D özellikleri yoktur. Sadece okuma [IThreeDFormat](../../aspose.slides/ithreedformat/). |
| **uint32_t** [get_UniqueId](../../aspose.slides/shape/get_uniqueid/)() override | Eklentiler veya diğer kodlar için kullanılan dahili, sunum kapsamlı kimliği döndürür. Bu değer kullanıcı veya program tarafından yeniden atanabileceği için kalıcı benzersiz anahtar olarak kullanılmamalıdır. Sadece okuma **uint32_t**. Ayrıca bakınız [Shape::get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/). |
| **float** [get_Width](../../aspose.slides/shape/get_width/)() override | Şeklin genişliğini, puan cinsinden alır. Oku **float**. |
| **float** [get_X](../../aspose.slides/shape/get_x/)() override | Şeklin sol üst köşesinin x koordinatını, puan cinsinden alır. Oku **float**. |
| **float** [get_Y](../../aspose.slides/shape/get_y/)() override | Şeklin sol üst köşesinin y koordinatını, puan cinsinden alır. Oku **float**. |
| **int32_t** [get_ZOrderPosition](../../aspose.slides/shape/get_zorderposition/)() override | Şeklin z-sırasındaki konumunu döndürür. Shapes[0] arka taraftaki şekli, Shapes[Shapes.Count - 1] ön taraftaki şekli döndürür. Sadece okuma **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder/)() override | Temel bir yer tutucu şekli döndürür (geçerli şeklin miras aldığı düzen ve/veya ana slayttan gelen şekil). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayaç veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analogu. Özel nesnelerin hash oluşturmasını sağlar. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)() override | Şekil küçük resmini döndürür. [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) şekil küçük resmi sınırları türü varsayılan olarak kullanılır. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) override | Şekil küçük resmini döndürür. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogu. |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../../aspose.slides/shape/getvisualbounds/)() | Şeklin işlenmiş içeriğinden hesaplanan görsel sınırlarını alır. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin, hedef tip tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analogu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlemci nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analogu. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapıları başlatılır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte bir şey kopyalamaz; sadece yeni nesneyi başlatır ve alt sınıfların kopya yapısını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte bir şey kopyalamaz; sadece yeni nesneyi başlatır ve alt sınıfların kopya yapısını etkinleştirir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans karşılaştırması yapar. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumu için özelleştirilmiş hali. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize durumları için özelleştirilmiş hali. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder/)() override | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| void [set_AlternativeText](../../aspose.slides/shape/set_alternativetext/)([System::String](../../system/string/)) override | Bir şekille ilişkilendirilmiş alternatif metni ayarlar. Yaz [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../../aspose.slides/shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Bir şekille ilişkilendirilmiş alternatif metnin başlığını ayarlar. Yaz [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../../aspose.slides/shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) override | Özellik, bir şeklin siyah-beyaz görüntü modunda nasıl render edileceğini belirtir. Yaz [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| void [set_Frame](../../aspose.slides/shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | Şekil çerçevesinin özelliklerini ayarlar. Yaz [IShapeFrame](../../aspose.slides/ishapeframe/). |
| void [set_Height](../../aspose.slides/shape/set_height/)(**float**) override | Şeklin yüksekliğini, puan cinsinden ayarlar. Yaz **float**. |
| void [set_Hidden](../../aspose.slides/shape/set_hidden/)(**bool**) override | Şeklin gizli olup olmadığını belirler. Yaz **bool**. |
| void [set_HyperlinkClick](../../aspose.slides/shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | Fare tıklaması için tanımlanan hiperveyi ayarlar. Yaz [IHyperlink](../../aspose.slides/ihyperlink/). |
| void [set_HyperlinkMouseOver](../../aspose.slides/shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | Fare üzerindeyken tanımlanan hiperveyi ayarlar. Yaz [IHyperlink](../../aspose.slides/ihyperlink/). |
| void [set_IsDecorative](../../aspose.slides/shape/set_isdecorative/)(**bool**) override | 'Mark as decorative' seçeneğini ayarlar. Okuma/yazma **bool**. |
| void [set_Name](../../aspose.slides/shape/set_name/)([System::String](../../system/string/)) override | Bir şeklin adını ayarlar. Null olmamalıdır. Gerekirse boş dize kullanın. Yaz [System::String](../../system/string/). |
| void [set_RawFrame](../../aspose.slides/shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | Ham şekil çerçevesinin özelliklerini ayarlar. Yaz [IShapeFrame](../../aspose.slides/ishapeframe/). |
| void [set_Rotation](../../aspose.slides/shape/set_rotation/)(**float**) override | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını ayarlar. Pozitif saat yönünde, negatif saat yönünün tersine. Yaz **float**. |
| void [set_Width](../../aspose.slides/shape/set_width/)(**float**) override | Şeklin genişliğini, puan cinsinden ayarlar. Yaz **float**. |
| void [set_X](../../aspose.slides/shape/set_x/)(**float**) override | Şeklin sol üst köşesinin x koordinatını, puan cinsinden ayarlar. Yaz **float**. |
| void [set_Y](../../aspose.slides/shape/set_y/)(**float**) override | Şeklin sol üst köşesinin y koordinatını, puan cinsindeki ayarlar. Yaz **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf bir işaretçi olarak ayarlar (paylaşımlı yerine). Kapsayıcılardaki işaretçileri zayıf moda geçiş yapmayı sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analogu. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açmasını uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlemci nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | [Shape](../../aspose.slides/shape/) içeriğini SVG dosyası olarak kaydeder. |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | [Shape](../../aspose.slides/shape/) içeriğini SVG dosyası olarak kaydeder. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## İlgili

* Sınıf [GraphicalObject](../../aspose.slides/graphicalobject/)
* Sınıf [IInkActions](../iinkactions/)
* İsim alanı [Aspose::Slides::Ink](../)
* Kütüphane [Aspose.Slides](../../)