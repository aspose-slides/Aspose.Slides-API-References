---
title: IInk
second_title: Aspose.Slides for C++ API Referansı
description: Bir slayttaki mürekkep nesnesini temsil eder.
type: docs
weight: 1
url: /tr/aspose.slides.ink/iink/
---
## IInk sınıfı

Bir slayttaki mürekkep nesnesini temsil eder.

```cpp
class IInk : public virtual Aspose::Slides::IGraphicalObject
```

## Yöntemler

| Metot | Açıklama |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) | Hiçbir yer tutucu yoksa yeni bir yer tutucu ekler ve yer tutucu özelliklerini belirtilen birine ayarlar. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiğine göre karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipi nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer tipi nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | İki NaN değeri eşit kabul edilen C#-stili kayan nokta karşılaştırmasını taklit eder; IEC 60559:1989’a göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | İki NaN değeri eşit kabul edilen C#-stili kayan nokta karşılaştırmasını taklit eder; IEC 60559:1989’a göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/ishape/get_alternativetext/)() | Bir şekille ilişkili alternatif metni döndürür. Oku [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/ishape/get_alternativetexttitle/)() | Bir şekille ilişkili alternatif metnin başlığını döndürür. Oku [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/ishape/get_blackwhitemode/)() | Özellik, bir şeklin siyah-beyaz görüntüleme modunda nasıl render edileceğini belirtir. Oku [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](../../aspose.slides/ishape/get_connectionsitecount/)() | Şeklin bağlantı noktası sayısını döndürür. Yalnızca okunabilir **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/ishape/get_customdata/)() | Şeklin özel verilerini döndürür. Yalnızca okunabilir [ICustomData](../../aspose.slides/icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/ishape/get_effectformat/)() | Şekle uygulanan piksel efektlerini içeren [EffectFormat](../../aspose.slides/effectformat/) nesnesini döndürür. Yalnızca okunabilir [IEffectFormat](../../aspose.slides/ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/ishape/get_fillformat/)() | Şeklin dolgu biçimlendirme özelliklerini içeren [FillFormat](../../aspose.slides/fillformat/) nesnesini döndürür. Yalnızca okunabilir [IFillFormat](../../aspose.slides/ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/ishape/get_frame/)() | Şekil çerçevesinin özelliklerini döndürür. Oku [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)\> [get_GraphicalObjectLock](../../aspose.slides/igraphicalobject/get_graphicalobjectlock/)() | Şeklin kilitlerini döndürür. Yalnızca okunabilir [IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/). |
| virtual **float** [get_Height](../../aspose.slides/ishape/get_height/)() | Nokta cinsinden ölçülen şeklin yüksekliğini alır. Yalnızca okunabilir **float**. |
| virtual **bool** [get_Hidden](../../aspose.slides/ishape/get_hidden/)() | Şeklin gizli olup olmadığını belirler. Yalnızca okunabilir **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkclick/)() | Fare tıklaması için tanımlı köprüyü döndürür. Oku [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmanager/)() | Köprü yöneticisi. Yalnızca okunabilir [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmouseover/)() | Fare üzerine gelindiğinde tanımlı köprüyü döndürür. Oku [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual **bool** [get_IsDecorative](../../aspose.slides/ishape/get_isdecorative/)() | 'Dekoratif olarak işaretle' seçeneğini alır. Okuma/yazma **bool**. |
| virtual **bool** [get_IsGrouped](../../aspose.slides/ishape/get_isgrouped/)() | Şeklin gruplanmış olup olmadığını belirler. Yalnızca okunabilir **bool**. |
| virtual **bool** [get_IsTextHolder](../../aspose.slides/ishape/get_istextholder/)() | Şeklin TextHolder olup olmadığını belirler. Yalnızca okunabilir **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/ishape/get_lineformat/)() | Şeklin çizgi biçimlendirme özelliklerini içeren [LineFormat](../../aspose.slides/lineformat/) nesnesini döndürür. Yalnızca okunabilir [ILineFormat](../../aspose.slides/ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../../aspose.slides/ishape/get_name/)() | Şeklin adını döndürür. Oku [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/)() | Şeklin yaşam süresi boyunca sabit kalan ve PowerPoint ya da interop kodunun şekle evrenden güvenilir şekilde başvurmasını sağlayan slayt-kapsamlı benzersiz tanımlayıcıyı döndürür. Yalnızca okunabilir **uint32_t**. Ayrıca bkz. [IShape::get_UniqueId](../../aspose.slides/ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/ishape/get_parentgroup/)() | Şekil gruplandırılmışsa üst [GroupShape](../../aspose.slides/groupshape/) nesnesini döndürür. Aksi takdirde null döner. Yalnızca okunabilir [IGroupShape](../../aspose.slides/igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/ishape/get_placeholder/)() | Şekil için yer tutucuyu döndürür. Yalnızca okunabilir [IPlaceholder](../../aspose.slides/iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Sunumu döndürür. Yalnızca okunabilir [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/ishape/get_rawframe/)() | Ham şekil çerçevesinin özelliklerini döndürür. Oku [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual **float** [get_Rotation](../../aspose.slides/ishape/get_rotation/)() | Belirtilen şeklin z-ekseninde döndürüldüğü derece sayısını döndürür. Pozitif değer saat yönünde dönüş, negatif değer saat yönünün tersine döndürülür. Yalnızca okunabilir **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/ishape/get_shapelock/)() | Şeklin kilitlerini döndürür. Yalnızca okunabilir [IBaseShapeLock](../../aspose.slides/ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Temel slaytı döndürür. Yalnızca okunabilir [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/ishape/get_threedformat/)() | Şeklin çizgi biçimlendirme özelliklerini içeren [ThreeDFormat](../../aspose.slides/threedformat/) nesnesini döndürür. Yalnızca okunabilir [IThreeDFormat](../../aspose.slides/ithreedformat/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IInkTrace](../iinktrace/)\>\> [get_Traces](./get_traces/)() | [IInk](./) öğesindeki tüm izleri alır [IInkTrace](../iinktrace/). Yalnızca okunabilir. |
| virtual **uint32_t** [get_UniqueId](../../aspose.slides/ishape/get_uniqueid/)() | Eklentiler veya diğer kodlar tarafından kullanılmak üzere, sunum-kapsamlı iç tanımlayıcıyı döndürür. Bu değer kullanıcı veya program tarafından yeniden atanabileceği için kalıcı bir anahtar olarak kullanılmamalıdır. Yalnızca okunabilir **uint32_t**. Ayrıca bkz. [IShape::get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/). |
| virtual **float** [get_Width](../../aspose.slides/ishape/get_width/)() | Nokta cinsinden ölçülen şeklin genişliğini alır. Yalnızca okunabilir **float**. |
| virtual **float** [get_X](../../aspose.slides/ishape/get_x/)() | Nokta cinsinden ölçülen şeklin sol-üst köşesinin x koordinatını alır. Yalnızca okunabilir **float**. |
| virtual **float** [get_Y](../../aspose.slides/ishape/get_y/)() | Nokta cinsinden ölçülen şeklin sol-üst köşesinin y koordinatını alır. Yalnızca okunabilir **float**. |
| virtual **int32_t** [get_ZOrderPosition](../../aspose.slides/ishape/get_zorderposition/)() | Şeklin z-sırasındaki konumunu döndürür. Shapes[0] z-sırasının arkasındaki şekli, Shapes[Shapes.Count - 1] ise önündeki şekli verir. Yalnızca okunabilir **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder/)() | Temel bir yer tutucu şekli (geçerli şeklin devralındığı yerleşim ve/veya ana slayttan gelen şekil) döndürür. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayaç veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özel nesnelerin hash’lenmesini sağlar. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)() | Şekil küçük resmini döndürür. [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) şekil küçük resmi sınır tipi varsayılan olarak kullanılır. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) | Şekil küçük resmini döndürür. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin hedef tip tarafından tanımlanan bir örnek olup olmadığını kontrol eder. C# ‘is’ operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) koruyucu nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm iç veri yapılarının başlatılmasını yapar. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte bir şey kopyalamaz, sadece yeni bir nesne başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte bir şey kopyalamaz, sadece yeni bir nesne başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans-karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Dize ve nullptr durumu için [Object::ReferenceEquals](../../system/object/referenceequals/) özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Dizeler durumu için [Object::ReferenceEquals](../../system/object/referenceequals/) özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder/)() | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| virtual void [set_AlternativeText](../../aspose.slides/ishape/set_alternativetext/)([System::String](../../system/string/)) | Şekille ilişkili alternatif metni ayarlar. Yaz [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../../aspose.slides/ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Şekille ilişkili alternatif metnin başlığını ayarlar. Yaz [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../../aspose.slides/ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) | Özellik, bir şeklin siyah-beyaz görüntüleme modunda nasıl render edileceğini belirtir. Yaz [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| virtual void [set_Frame](../../aspose.slides/ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | Şekil çerçevesinin özelliklerini ayarlar. Yaz [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual void [set_Height](../../aspose.slides/ishape/set_height/)(**float**) | Şeklin yüksekliğini nokta cinsinden ayarlar. Yaz **float**. |
| virtual void [set_Hidden](../../aspose.slides/ishape/set_hidden/)(**bool**) | Şeklin gizli olup olmadığını belirler. Yaz **bool**. |
| virtual void [set_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | Fare tıklaması için tanımlı köprüyü ayarlar. Yaz [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | Fare üzerine gelindiğinde tanımlı köprüyü ayarlar. Yaz [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual void [set_IsDecorative](../../aspose.slides/ishape/set_isdecorative/)(**bool**) | 'Dekoratif olarak işaretle' seçeneğini ayarlar. Okuma/yazma **bool**. |
| virtual void [set_Name](../../aspose.slides/ishape/set_name/)([System::String](../../system/string/)) | Şeklin adını ayarlar. Yaz [System::String](../../system/string/). |
| virtual void [set_RawFrame](../../aspose.slides/ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | Ham şekil çerçevesinin özelliklerini ayarlar. Yaz [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual void [set_Rotation](../../aspose.slides/ishape/set_rotation/)(**float**) | Şeklin z-ekseninde döndürüldüğü derece sayısını ayarlar. Pozitif değer saat yönünde, negatif değer saat yönünün tersine döndürülür. Yaz **float**. |
| virtual void [set_Width](../../aspose.slides/ishape/set_width/)(**float**) | Şeklin genişliğini nokta cinsinden ayarlar. Yaz **float**. |
| virtual void [set_X](../../aspose.slides/ishape/set_x/)(**float**) | Şeklin sol-üst köşesinin x koordinatını nokta cinsinden ayarlar. Yaz **float**. |
| virtual void [set_Y](../../aspose.slides/ishape/set_y/)(**float**) | Şeklin sol-üst köşesinin y koordinatını nokta cinsinden ayarlar. Yaz **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n-inci şablon argümanını zayıf gösterici (shared yerine) yapar. Kapsayıcılardaki göstergelerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstergeler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstergeler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin string’e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açar. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) koruyucu nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstergeler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstergeler veya ThisProtector kullanılmalıdır. |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | [Shape](../../aspose.slides/shape/) içeriğini SVG dosyası olarak kaydeder. |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | [Shape](../../aspose.slides/shape/) içeriğini SVG dosyası olarak kaydeder. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapıları serbest bırakılır. |

## İlgili

* Sınıf [IGraphicalObject](../../aspose.slides/igraphicalobject/)
* Ad Alanı [Aspose::Slides::Ink](../)
* Kütüphane [Aspose.Slides](../../)