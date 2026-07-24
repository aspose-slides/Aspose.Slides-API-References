---
title: IOleObjectFrame
second_title: Aspose.Slides for C++ API Referansı
description: Bir slaytta OLE nesnesini temsil eder.
type: docs
weight: 3095
url: /tr/aspose.slides/ioleobjectframe/
---
## IOleObjectFrame sınıf

Bir slaytta OLE nesnesini temsil eder.

```cpp
class IOleObjectFrame : public virtual Aspose::Slides::IGraphicalObject
```

## Yöntemler

| Method | Açıklama |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | Yeni bir yer tutucu yoksa ekler ve yer tutucu özelliklerini belirtilen birine ayarlar. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) söz dizimini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans tipindeki nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer tipindeki nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# tarzı kayan nokta karşılaştırmasını taklit eder; iki NaN, IEC 60559:1989'a göre NaN'ın herhangi bir değerle, NaN dahil, eşit olmamasına rağmen eşit kabul edilir. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# tarzı kayan nokta karşılaştırmasını taklit eder; iki NaN, IEC 60559:1989'a göre NaN'ın herhangi bir değerle, NaN dahil, eşit olmamasına rağmen eşit kabul edilir. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | Bir şekille ilişkili alternatif metni döndürür. Oku [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | Bir şekille ilişkili alternatif metnin başlığını döndürür. Oku [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | Özellik, bir şeklin siyah-beyaz görüntüleme modunda nasıl render edileceğini belirler. Oku [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | Şekildeki bağlantı noktalarının sayısını döndürür. Salt okunur **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | Şeklin özel verisini döndürür. Salt okunur [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | Şekle uygulanan piksel efektlerini içeren [EffectFormat](../effectformat/) nesnesini döndürür. Salt okunur [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)\> [get_EmbeddedData](./get_embeddeddata/)() | OLE gömülü verileri hakkında bilgi alır. Salt okunur [IOleEmbeddedDataInfo](../ioleembeddeddatainfo/). |
| virtual [System::String](../../system/string/) [get_EmbeddedFileLabel](./get_embeddedfilelabel/)() | Gömülü OLE nesnesinin dosya adını döndürür |
| virtual [System::String](../../system/string/) [get_EmbeddedFileName](./get_embeddedfilename/)() | Gömülü OLE nesnesinin yolunu döndürür |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | [FillFormat](../fillformat/) nesnesini döndürür; bu nesne bir şeklin dolgu biçimlendirme özelliklerini içerir. Salt okunur [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | Şekil çerçevesinin özelliklerini döndürür. Oku [IShapeFrame](../ishapeframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../igraphicalobject/get_graphicalobjectlock/)() | Şeklin kilitlerini döndürür. Salt okunur [IGraphicalObjectLock](../igraphicalobjectlock/). |
| virtual **float** [get_Height](../ishape/get_height/)() | Şeklin yüksekliğini, nokta cinsinden alır. Oku **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | Şeklin gizli olup olmadığını belirler. Oku **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Fare tıklaması için tanımlı hiperlinki döndürür. Oku [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Hiperlink yöneticisi. Salt okunur [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Fare üzerine gelindiğinde tanımlı hiperlinki döndürür. Oku [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | ‘Mark as decorative’ seçeneğini alır. Okunur/Yazılabilir **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | Şeklin gruplanıp gruplanmadığını belirler. Salt okunur **bool**. |
| virtual **bool** [get_IsObjectIcon](./get_isobjecticon/)() | Bir nesnenin simge olarak görünür olup olmadığını belirler. Oku **bool**. |
| virtual **bool** [get_IsObjectLink](./get_isobjectlink/)() | Bir nesnenin harici dosyaya bağlı olup olmadığını belirler. Salt okunur **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | Şeklin TextHolder olup olmadığını belirler. Salt okunur **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | [LineFormat](../lineformat/) nesnesini döndürür; bu nesne bir şeklin satır biçimlendirme özelliklerini içerir. Salt okunur [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_LinkFileName](./get_linkfilename/)() | Bağlı bir dosyanın tam yolunu döndürür. Kısa dosya adı kullanılacaktır. Salt okunur [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() | Bağlı bir dosyanın tam yolunu döndürür. Uzun dosya adı kullanılacaktır. Oku [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_LinkPathRelative](./get_linkpathrelative/)() | Var ise bağlı dosyanın göreli yolunu, yoksa boş bir dize döndürür. Salt okunur [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | Bir şeklin adını döndürür. Oku [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ObjectName](./get_objectname/)() | Bir nesnenin adını döndürür. Oku [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ObjectProgId](./get_objectprogid/)() | Bir nesnenin ProgID'sini döndürür. Salt okunur [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | Şeklin yaşam süresi boyunca sabit kalan ve PowerPoint ya da interop kodunun şekle belge içinde her yerden güvenilir şekilde referans vermesini sağlayan slayt kapsamlı benzersiz kimliği döndürür. Salt okunur **uint32_t**. Ayrıca bakınız [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | Şekil gruplanmışsa üst [GroupShape](../groupshape/) nesnesini döndürür. Aksi takdirde null döndürür. Salt okunur [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | Bir şeklin yer tutucusunu döndürür. Salt okunur [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Sunumu döndürür. Salt okunur [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | Ham şekil çerçevesinin özelliklerini döndürür. Oku [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | Belirtilen şeklin z ekseni etrafında döndürülme derecesini döndürür. Pozitif değer saat yönünde; negatif değer saat yönünün tersine döndürülmeyi gösterir. Oku **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | Şeklin kilitlerini döndürür. Salt okunur [IBaseShapeLock](../ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Temel slaytı döndürür. Salt okunur [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_SubstitutePictureFormat](./get_substitutepictureformat/)() | OleObject'in resim dolgu özellikleri nesnesini döndürür. Salt okunur [IPictureFillFormat](../ipicturefillformat/). |
| virtual [System::String](../../system/string/) [get_SubstitutePictureTitle](./get_substitutepicturetitle/)() | OleObject simgesi için başlığı döndürür. Oku [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | [ThreeDFormat](../threedformat/) nesnesini döndürür; bu nesne bir şeklin satır biçimlendirme özelliklerini içerir. Salt okunur [IThreeDFormat](../ithreedformat/). |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | Eklentiler veya diğer kodlar tarafından kullanılmak üzere içsel, sunum kapsamlı bir kimlik döndürür. Bu değer kullanıcı veya program tarafından yeniden atanabileceği için kalıcı benzersiz bir anahtar olarak değerlendirilmemelidir. Salt okunur **uint32_t**. Ayrıca bakınız [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual **bool** [get_UpdateAutomatic](./get_updateautomatic/)() | Bağlı gömülü nesnenin sunum açıldığında veya yazdırıldığında otomatik olarak güncellenip güncellenmediğini belirler. Oku **bool**. |
| virtual **float** [get_Width](../ishape/get_width/)() | Şeklin genişliğini, nokta cinsinden alır. Oku **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | Şeklin sol-üst köşesinin x koordinatını, nokta cinsinden alır. Oku **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | Şeklin sol-üst köşesinin y koordinatını, nokta cinsinden alır. Oku **float**. |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | Bir şeklin z-sırasındaki konumunu döndürür. Shapes[0] z-sırasının arkasındaki şekli, Shapes[Shapes.Count - 1] ise önündeki şekli döndürür. Salt okunur **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | Temel bir yer tutucu şekli döndürür (geçerli şeklin miras aldığı düzen ve/veya ana slayttan gelen şekil). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayaç veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin analoğu. Özel nesnelerin hashlenmesini sağlar. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | Şekil küçük resmini döndürür. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) şekil küçük resmi sınır tipi varsayılan olarak kullanılır. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | Şekil küçük resmini döndürür. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetim nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin analoğu. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekten hiçbir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekten hiçbir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) öğesinin dize ve nullptr durumu için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) öğesinin dize durumu için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | Bir şekille ilişkili alternatif metni ayarlar. Yaz [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Bir şekille ilişkili alternatif metnin başlığını ayarlar. Yaz [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | Özellik, bir şeklin siyah-beyaz görüntüleme modunda nasıl render edileceğini belirler. Yaz [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Şekil çerçevesinin özelliklerini ayarlar. Yaz [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | Şeklin yüksekliğini, nokta cinsinden ayarlar. Yaz **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | Şeklin gizli olup olmadığını belirler. Yaz **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Fare tıklaması için tanımlı hiperlinki ayarlar. Yaz [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Fare üzerine gelindiğinde tanımlı hiperlinki ayarlar. Yaz [IHyperlink](../ihyperlink/). |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | ‘Mark as decorative’ seçeneğini ayarlar. Oku/Yaz **bool**. |
| virtual void [set_IsObjectIcon](./set_isobjecticon/)(**bool**) | Bir nesnenin simge olarak görünür olup olmadığını ayarlar. Yaz **bool**. |
| virtual void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) | Bağlı bir dosyanın tam yolunu döndürür. Uzun dosya adı kullanılacaktır. Yaz [System::String](../../system/string/). |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | Bir şeklin adını ayarlar. Yaz [System::String](../../system/string/). |
| virtual void [set_ObjectName](./set_objectname/)([System::String](../../system/string/)) | Bir nesnenin adını ayarlar. Yaz [System::String](../../system/string/). |
| virtual void [set_ObjectProgId](./set_objectprogid/)([System::String](../../system/string/)) | Bir nesnenin ProgID'sini döndürür. Salt okunur [System::String](../../system/string/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Ham şekil çerçevesinin özelliklerini ayarlar. Yaz [IShapeFrame](../ishapeframe/). |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | Belirtilen şeklin z ekseni etrafında döndürülme derecesini ayarlar. Pozitif değer saat yönünde; negatif değer saat yönünün tersine döndürülmeyi gösterir. Yaz **float**. |
| virtual void [set_SubstitutePictureTitle](./set_substitutepicturetitle/)([System::String](../../system/string/)) | OleObject simgesi için başlığı ayarlar. Yaz [System::String](../../system/string/). |
| virtual void [set_UpdateAutomatic](./set_updateautomatic/)(**bool**) | Bağlı gömülü nesnenin sunum açıldığında veya yazdırıldığında otomatik olarak güncellenip güncellenmediğini belirler. Yaz **bool**. |
| virtual void [set_Width](../ishape/set_width/)(**float**) | Şeklin genişliğini, nokta cinsinden ayarlar. Yaz **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | Şeklin sol-üst köşesinin x koordinatını, nokta cinsinden ayarlar. Yaz **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | Şeklin sol-üst köşesinin y koordinatını, nokta cinsinden ayarlar. Yaz **float**. |
| virtual void [SetEmbeddedData](./setembeddeddata/)([System::SharedPtr](../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)\>) | OLE gömülü verileri hakkında bilgi ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşılan yerine) olarak ayarlar. Kapsayıcılardaki işaretçileri zayıf moda geçirmeyi sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin analoğu. Özel nesnelerin dizeye dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açmasını uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetim nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | [Shape](../shape/) içeriğini SVG dosyası olarak kaydeder. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | [Shape](../shape/) içeriğini SVG dosyası olarak kaydeder. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [IGraphicalObject](../igraphicalobject/)
* Ad alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)