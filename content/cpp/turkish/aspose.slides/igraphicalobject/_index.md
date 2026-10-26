---
title: IGraphicalObject
second_title: Aspose.Slides for C++ API Referansı
description: Soyut grafiksel nesneyi temsil eder.
type: docs
weight: 2458
url: /tr/aspose.slides/igraphicalobject/
---
## IGraphicalObject sınıf


Represents abstract graphical object.

```cpp
class IGraphicalObject : public virtual Aspose::Slides::IShape
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | Yeni bir yer tutucu ekler, eğer yoksa ve yer tutucu özelliklerini belirtilen birine ayarlar. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiğini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türündeki nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer türündeki nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değerle, NaN dahil, eşit olmamasına rağmen iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değerle, NaN dahil, eşit olmamasına rağmen iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | Bir şekille ilişkili alternatif metni döndürür. [System::String](../../system/string/)'yi okuyunuz. |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | Bir şekille ilişkili alternatif metnin başlığını döndürür. [System::String](../../system/string/)'yi okuyunuz. |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | Özellik, bir şeklin siyah-beyaz görüntü modunda nasıl işleneceğini belirtir. [Slides::BlackWhiteMode](../blackwhitemode/)'yi okuyunuz. |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | Şeklin bağlantı noktası sayısını döndürür. Salt okunur **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | Şeklin özel verisini döndürür. Salt okunur [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | [EffectFormat](../effectformat/) nesnesini döndürür; bu nesne şekle uygulanan piksel efektlerini içerir. Salt okunur [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | [FillFormat](../fillformat/) nesnesini döndürür; bu nesne bir şeklin doldurma biçimlendirme özelliklerini içerir. Salt okunur [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | Şekil çerçevesinin özelliklerini döndürür. [IShapeFrame](../ishapeframe/)'yi okuyunuz. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](./get_graphicalobjectlock/)() | Şeklin kilitlerini döndürür. Salt okunur [IGraphicalObjectLock](../igraphicalobjectlock/). |
| virtual **float** [get_Height](../ishape/get_height/)() | Şeklin yüksekliğini, puan cinsinden alır. Okunur **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | Şeklin gizli olup olmadığını belirler. Okunur **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Fare tıklaması için tanımlanan hiperveği döndürür. [IHyperlink](../ihyperlink/)'yi okuyunuz. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Hipervek yöneticisi. Salt okunur [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Fare üzerindeyken tanımlanan hiperveği döndürür. [IHyperlink](../ihyperlink/)'yi okuymuş. |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | ‘Dekoratif olarak işaretle’ seçeneğini alır. Okunur/yazılır **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | Şeklin grup halinde olup olmadığını belirler. Salt okunur **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | Şeklin TextHolder olup olmadığını belirler. Salt okunur **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | [LineFormat](../lineformat/) nesnesini döndürür; bu nesne bir şeklin çizgi biçimlendirme özelliklerini içerir. Salt okunur [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | Bir şeklin adını döndürür. [System::String](../../system/string/)'yi okuyunuz. |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | Şeklin ömrü boyunca sabit kalan ve PowerPoint ya da interop kodunun şekle belge içinde güvenilir bir şekilde başvurmasını sağlayan, slayt kapsamlı benzersiz bir tanımlayıcı döndürür. Salt okunur **uint32_t**. Ayrıca [IShape::get_UniqueId](../ishape/get_uniqueid/)'ye bakınız. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | Şekil grup halinde ise üst [GroupShape](../groupshape/) nesnesini döndürür. Aksi takdirde null döndürür. Salt okunur [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | Bir şeklin yer tutucusunu döndürür. Salt okunur [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Sunumu döndürür. Salt okunur [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | Ham şekil çerçevesinin özelliklerini döndürür. [IShapeFrame](../ishapeframe/)'yi okuyunuz. |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | Belirtilen şeklin z ekseni etrafında döndürülme derecesini döndürür. Pozitif değer saat yönünde dönüşü, negatif değer saat yönünün tersine dönüşü gösterir. Okunur **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | Şeklin kilitlerini döndürür. Salt okunur [IBaseShapeLock](../ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Temel slaytı döndürür. Salt okunur [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | [ThreeDFormat](../threedformat/) nesnesini döndürür; bu nesne bir şeklin çizgi biçimlendirme özelliklerini içerir. Salt okunur [IThreeDFormat](../ithreedformat/). |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | İçsel, sunum kapsamlı bir tanımlayıcı döndürür; bu tanımlayıcı eklentiler veya diğer kodlar tarafından kullanılmak içindir. Kullanıcı veya program tarafından yeniden atanabileceği için kalıcı benzersiz bir anahtar olarak ele alınmamalıdır. Salt okunur **uint32_t**. Ayrıca [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)'ye bakınız. |
| virtual **float** [get_Width](../ishape/get_width/)() | Şeklin genişliğini puan cinsinden alır. Okunur **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | Şeklin sol üst köşesinin x koordinatını puan cinsinden alır. Okunur **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | Şeklin sol üst köşesinin y koordinatını puan cinsinden alır. Okunur **float**. |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | Bir şeklin z-sırasındaki konumunu döndürür. Shapes[0] z-sırasının arkasındaki şekli, Shapes[Shapes.Count - 1] ise önündeki şekli döndürür. Salt okunur **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | Temel bir yer tutucu şekli döndürür (geçerli şeklin devralındığı düzen ve/veya ana slayttan gelen şekil). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin analoğu. Özel nesnelerin hashlenmesini sağlar. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | Şekil küçük resmini döndürür. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) şekil küçük resmi sınırları türü varsayılan olarak kullanılır. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | Şekil küçük resmini döndürür. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin, hedefTür tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitleme işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetim nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin analoğu. Özel tiplerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referans olarak değer türü nesneyi nullptr ile karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumu için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dizeler durumu için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | Bir şekille ilişkili alternatif metni ayarlar. [System::String](../../system/string/)'yi yazınız. |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Bir şekille ilişkili alternatif metnin başlığını ayarlar. [System::String](../../system/string/)'yi yazınız. |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | Özellik, bir şeklin siyah-beyaz görüntü modunda nasıl işleneceğini belirtir. [Slides::BlackWhiteMode](../blackwhitemode/)'yi yazınız. |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Şekil çerçevesinin özelliklerini ayarlar. [IShapeFrame](../ishapeframe/)'yi yazınız. |
| virtual void [set_Height](../ishape/set_height/)(**float**) | Şeklin yüksekliğini puan cinsinden ayarlar. **float**'ı yazınız. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | Şeklin gizli olup olmadığını belirler. **bool**'ı yazınız. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Fare tıklaması için tanımlanan hiperveği ayarlar. [IHyperlink](../ihyperlink/)'yi yazınız. |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Fare üzerindeyken tanımlanan hiperveği ayarlar. [IHyperlink](../ihyperlink/)'yi yazınız. |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | ‘Dekoratif olarak işaretle’ seçeneğini ayarlar. Okunur/yazılır **bool**. |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | Bir şeklin adını ayarlar. [System::String](../../system/string/)'yi yazınız. |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Ham şekil çerçevesinin özelliklerini ayarlar. [IShapeFrame](../ishapeframe/)'yi yazınız. |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | Belirtilen şeklin z ekseni etrafında döndürülme derecesini ayarlar. Pozitif değer saat yönünde, negatif değer saat yönünün tersine dönüşü gösterir. **float**'ı yazınız. |
| virtual void [set_Width](../ishape/set_width/)(**float**) | Şeklin genişliğini puan cinsinden ayarlar. **float**'ı yazınız. |
| virtual void [set_X](../ishape/set_x/)(**float**) | Şeklin sol üst köşesinin x koordinatını puan cinsinden ayarlar. **float**'ı yazınız. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | Şeklin sol üst köşesinin y koordinatını puan cinsinden ayarlar. **float**'ı yazınız. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf gösterici (paylaşımlı yerine) olarak ayarlar. Kapsayıcılardaki göstericileri zayıf moda geçiş yapmayı sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin analoğu. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetim nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | [Shape](../shape/) içeriğini SVG dosyası olarak kaydeder. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | [Shape](../shape/) içeriğini SVG dosyası olarak kaydeder. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [IShape](../ishape/)
* Ad alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)