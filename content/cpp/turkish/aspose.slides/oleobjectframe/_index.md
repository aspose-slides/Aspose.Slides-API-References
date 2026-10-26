---
title: OleObjectFrame
second_title: Aspose.Slides for C++ API Referansı
description: Bir slayt üzerindeki OLE nesnesini temsil eder.
type: docs
weight: 4603
url: /tr/aspose.slides/oleobjectframe/
---
## OleObjectFrame sınıfı

Bir slayt üzerindeki OLE nesnesini temsil eder.

```cpp
class OleObjectFrame : public Aspose::Slides::GraphicalObject,
                       public Aspose::Slides::IOleObjectFrame
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Yeni bir yer tutucu ekler, eğer yoksa ve yer tutucu özelliklerini belirtilen bir taneye ayarlar. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objeleri C# [Object.Equals](../../system/object/equals/) semantiği kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipi nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer tipi nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'ın hiçbir değerle, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'ın hiçbir değerle, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Bir şekille ilişkili alternatif metni döndürür. [System::String](../../system/string/) oku. |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Bir şekille ilişkili alternatif metnin başlığını döndürür. [System::String](../../system/string/) oku. |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | Bu özellik, bir şeklin siyah-beyaz görüntü modunda nasıl render edileceğini belirtir. [Slides::BlackWhiteMode](../blackwhitemode/) oku. |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Şekildeki bağlantı noktalarının sayısını döndürür. Yalnızca okuma **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Şeklin özel verisini döndürür. Yalnızca okuma [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | [EffectFormat](../effectformat/) nesnesini döndürür; bu nesne bir şekle uygulanan piksel efektlerini içerir. Not: Efekt özelliği olmayan bazı şekil türleri için null döndürebilir. Yalnızca okuma [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)\> [get_EmbeddedData](./get_embeddeddata/)() override | OLE gömülü verileri hakkında bilgi alır. [IOleEmbeddedDataInfo](../ioleembeddeddatainfo/) oku. |
| [System::String](../../system/string/) [get_EmbeddedFileLabel](./get_embeddedfilelabel/)() override | Gömülü OLE nesnesinin dosya adını döndürür |
| [System::String](../../system/string/) [get_EmbeddedFileName](./get_embeddedfilename/)() override | Gömülü OLE nesnesinin yolunu döndürür |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | [FillFormat](../fillformat/) nesnesini döndürür; bu nesne bir şeklin dolgu biçimlendirme özelliklerini içerir. Not: Dolgu özelliği olmayan bazı şekil türleri için null döndürebilir. Yalnızca okuma [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Şekil çerçevesinin özelliklerini döndürür. [IShapeFrame](../ishapeframe/) oku. |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../graphicalobject/get_graphicalobjectlock/)() override | Şeklin kilitlerini döndürür. Yalnızca okuma [IGraphicalObjectLock](../igraphicalobjectlock/). |
| **float** [get_Height](../shape/get_height/)() override | Şeklin yüksekliğini, puan cinsinden alır. Okuma **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Şeklin gizli olup olmadığını belirler. Okuma **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Fare tıklaması için tanımlı hiperlinki döndürür. [IHyperlink](../ihyperlink/) oku. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Hiperlink yöneticisini döndürür. Yalnızca okuma [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Fare üzerindeyken tanımlı hiperlinki döndürür. [IHyperlink](../ihyperlink/) oku. |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | 'Dekoratif olarak işaretle' seçeneğini alır. Okuma/Yazma **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Şeklin gruplandırılmış olup olmadığını belirler. Yalnızca okuma **bool**. |
| **bool** [get_IsObjectIcon](./get_isobjecticon/)() override | Nesnenin simge olarak görünür olup olmadığını belirler. Okuma **bool**. |
| **bool** [get_IsObjectLink](./get_isobjectlink/)() override | Nesnenin dış dosyaya bağlanıp bağlanmadığını belirler. Yalnızca okuma **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Şeklin TextHolder_PPT olup olmadığını belirler. Yalnızca okuma **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | [LineFormat](../lineformat/) nesnesini döndürür; bu nesne bir şeklin çizgi biçimlendirme özelliklerini içerir. Not: Çizgi özelliği olmayan bazı şekil türleri için null döndürebilir. Yalnızca okuma [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_LinkFileName](./get_linkfilename/)() override | Bağlantılı bir dosyanın tam yolunu döndürür. Kısa dosya adı kullanılacak. Yalnızca okuma [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() override | Bağlantılı bir dosyanın tam yolunu döndürür. Uzun dosya adı kullanılacak. [System::String](../../system/string/) oku. |
| [System::String](../../system/string/) [get_LinkPathRelative](./get_linkpathrelative/)() override | Mevcutsa bağlantılı dosyanın göreli yolunu döndürür, aksi takdirde boş bir dize döndürür. Yalnızca okuma [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Bir şeklin adını döndürür. Null olmamalıdır. Gerekirse boş dize değeri kullanın. [System::String](../../system/string/) oku. |
| [System::String](../../system/string/) [get_ObjectName](./get_objectname/)() override | Bir nesnenin adını döndürür. [System::String](../../system/string/) oku. |
| [System::String](../../system/string/) [get_ObjectProgId](./get_objectprogid/)() override | Bir nesnenin ProgID'sini döndürür. Yalnızca okuma [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Slayta özgü benzersiz bir tanımlayıcı döndürür; bu tanımlayıcı şeklin ömrü boyunca sabit kalır ve PowerPoint ya da interop kodunun belge içinde herhangi bir yerden şekle güvenilir şekilde başvurmasını sağlar. Yalnızca okuma **uint32_t**. Ayrıca bakınız [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Şekil gruplanmışsa üst [GroupShape](../groupshape/) nesnesini döndürür. Aksi takdirde null döndürür. Yalnızca okuma [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Şekil için yer tutucuyu döndürür. Şekilde yer tutucu yoksa null döndürür. Yalnızca okuma [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Bir slaydın üst sunumunu döndürür. Yalnızca okuma [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Ham şekil çerçevesinin özelliklerini döndürür. [IShapeFrame](../ishapeframe/) oku. |
| **float** [get_Rotation](../shape/get_rotation/)() override | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını döndürür. Pozitif değer saat yönünde döndürmeyi, negatif değer saat yönünün tersinde döndürmeyi gösterir. Okuma **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Şeklin kilitlerini döndürür. Yalnızca okuma [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Şeklin üst slaytını döndürür. Yalnızca okuma [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_SubstitutePictureFormat](./get_substitutepictureformat/)() override | OleObject görüntü dolgu özellikleri nesnesini döndürür. Yalnızca okuma [IPictureFillFormat](../ipicturefillformat/). |
| [System::String](../../system/string/) [get_SubstitutePictureTitle](./get_substitutepicturetitle/)() override | OleObject simgesi için başlığı döndürür. [System::String](../../system/string/) oku. |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | Şeklin 3D efekt özelliklerini içeren [ThreeDFormat](../threedformat/) nesnesini döndürür. Not: 3D özelliği olmayan bazı şekil türleri için null döndürebilir. Yalnızca okuma [IThreeDFormat](../ithreedformat/). |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | İçsel, sunum kapsamlı bir tanımlayıcı döndürür; bu, eklentiler veya diğer kodlar tarafından kullanılmak içindir. Bu değer kullanıcı tarafından ya da programatik olarak yeniden atanabileceği için kalıcı benzersiz bir anahtar olarak kabul edilmemelidir. Yalnızca okuma **uint32_t**. Ayrıca bakınız [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **bool** [get_UpdateAutomatic](./get_updateautomatic/)() override | Bağlantılı gömülü nesnenin sunum açıldığında veya yazdırıldığında otomatik olarak güncellenip güncellenmediğini belirler. Okuma **bool**. |
| **float** [get_Width](../shape/get_width/)() override | Şeklin genişliğini, puan cinsinden alır. Okuma **float**. |
| **float** [get_X](../shape/get_x/)() override | Şeklin sol üst köşesinin x koordinatını, puan cinsinden alır. Okuma **float**. |
| **float** [get_Y](../shape/get_y/)() override | Şeklin sol üst köşesinin y koordinatını, puan cinsinden alır. Okuma **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Bir şeklin z-sırasındaki konumunu döndürür. Shapes[0] z-sırasının arkasındaki şekli, Shapes[Shapes.Count - 1] ise önündeki şekli döndürür. Yalnızca okuma **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Temel bir yer tutucu şekli döndürür (geçerli şeklin devralındığı düzen ve/veya ana slayttan şekil). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özel nesnelerin hash'lenmesini sağlar. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | Şekil küçük resmini döndürür. Varsayılan olarak [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) şekil küçük resim sınır türü kullanılır. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Şekil küçük resmini döndürür. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | Şeklin, render edilen içeriğinden hesaplanan görsel sınırlarını alır. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan türün bir örneği olup olmadığını denetler. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() deyiminin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) izleme nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapıları başlatılır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucu. Gerçekte hiçbir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referans, değer tipi nesneyi nullptr ile karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumuna özel bir uygulaması. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize durumuna özel bir uygulaması. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | Şekille ilişkili alternatif metni ayarlar. [System::String](../../system/string/) yaz. |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Şekille ilişkili alternatif metnin başlığını ayarlar. [System::String](../../system/string/) yaz. |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | Bu özellik, şeklin siyah-beyaz görüntü modunda nasıl render edileceğini belirtir. [Slides::BlackWhiteMode](../blackwhitemode/) yaz. |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Şekil çerçevesinin özelliklerini ayarlar. [IShapeFrame](../ishapeframe/) yaz. |
| void [set_Height](../shape/set_height/)(**float**) override | Şeklin yüksekliğini, puan cinsinden ayarlar. **float** yaz. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | Şeklin gizli olup olmadığını belirler. **bool** yaz. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Fare tıklaması için tanımlı hiperlinki ayarlar. [IHyperlink](../ihyperlink/) yaz. |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Fare üzerindeyken tanımlı hiperlinki ayarlar. [IHyperlink](../ihyperlink/) yaz. |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | 'Dekoratif olarak işaretle' seçeneğini ayarlar. Okuma/Yazma **bool**. |
| void [set_IsObjectIcon](./set_isobjecticon/)(**bool**) override | Nesnenin simge olarak görünür olup olmadığını belirler. **bool** yaz. |
| void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) override | Bağlantılı bir dosyanın tam yolunu döndürür. Uzun dosya adı kullanılacak. [System::String](../../system/string/) yaz. |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | Bir şeklin adını ayarlar. Null olmamalıdır. Gerekirse boş dize değeri kullanın. [System::String](../../system/string/) yaz. |
| void [set_ObjectName](./set_objectname/)([System::String](../../system/string/)) override | Bir nesnenin adını ayarlar. [System::String](../../system/string/) yaz. |
| void [set_ObjectProgId](./set_objectprogid/)([System::String](../../system/string/)) override | Bir nesnenin ProgID'sini döndürür. Yalnızca okuma [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Ham şekil çerçevesinin özelliklerini ayarlar. [IShapeFrame](../ishapeframe/) yaz. |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını ayarlar. Pozitif değer saat yönünde döndürmeyi, negatif değer saat yönünün tersinde döndürmeyi gösterir. **float** yaz. |
| void [set_SubstitutePictureTitle](./set_substitutepicturetitle/)([System::String](../../system/string/)) override | OleObject simgesi için başlığı ayarlar. [System::String](../../system/string/) yaz. |
| void [set_UpdateAutomatic](./set_updateautomatic/)(**bool**) override | Bağlantılı gömülü nesnenin sunum açıldığında veya yazdırıldığında otomatik olarak güncellenip güncellenmediğini belirler. **bool** yaz. |
| void [set_Width](../shape/set_width/)(**float**) override | Şeklin genişliğini, puan cinsinden ayarlar. **float** yaz. |
| void [set_X](../shape/set_x/)(**float**) override | Şeklin sol üst köşesinin x koordinatını, puan cinsinden ayarlar. **float** yaz. |
| void [set_Y](../shape/set_y/)(**float**) override | Şeklin sol üst köşesinin y koordinatını, puan cinsinden ayarlar. **float** yaz. |
| void [SetEmbeddedData](./setembeddeddata/)([System::SharedPtr](../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)\>) override | OLE gömülü verileri hakkında bilgiyi ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf bir gösterici (paylaşılan yerine) ayarlar. Kapsayıcılardaki göstericileri zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanın. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanın. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin dizeye dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() deyiminin kilidini açar. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) izleme nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanın. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanın. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | [Shape](../shape/) içeriğini SVG dosyası olarak kaydeder. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | [Shape](../shape/) içeriğini SVG dosyası olarak kaydeder. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Notlar

Aşağıdaki örnek, OLE Object çerçevelerine nasıl erişileceğini gösterir. 
```cpp
// PPTX'i bir sunum nesnesine yükler
auto pres = System::MakeObject<Presentation>(u"AccessingOLEObjectFrame.pptx");

// İlk slayta erişir
auto slide = pres->get_Slides()->idx_get(0);
// Şekli OleObjectFrame'e dönüştürür
System::SharedPtr<OleObjectFrame> oleObjectFrame = System::AsCast<OleObjectFrame>(slide->get_Shapes()->idx_get(0));
// OLE nesnesini okur ve diske yazar
if (oleObjectFrame != nullptr)
{
    // Gömülü dosya verisini alır
    System::ArrayPtr<uint8_t> data = oleObjectFrame->get_EmbeddedData()->get_EmbeddedFileData();
    // Gömülü dosya uzantısını alır
    System::String fileExtention = oleObjectFrame->get_EmbeddedData()->get_EmbeddedFileExtension();
    // Çıkarılan dosyayı kaydetmek için bir yol oluşturur
    System::String extractedPath = System::String(u"excelFromOLE_out") + fileExtention;
    // Çıkarılan veriyi kaydeder
    auto stream = System::MakeObject<System::IO::FileStream>(extractedPath,
                                                             System::IO::FileMode::Create,
                                                             System::IO::FileAccess::Write);
    stream->Write(data, 0, data->get_Length());
}
```

## Ayrıca Bakınız

* Sınıf [GraphicalObject](../graphicalobject/)
* Sınıf [IOleObjectFrame](../ioleobjectframe/)
* Ad Alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)