---
title: IChart
second_title: Aspose.Slides for C++ API Referansı
description: Bir slaytta grafik bir çizelgeyi temsil eder.
type: docs
weight: 573
url: /tr/aspose.slides.charts/ichart/
---
## IChart sınıfı

Represents an graphic chart on a slide.

```cpp
class IChart : public virtual Aspose::Slides::IGraphicalObject,
               public Aspose::Slides::Charts::IFormattedTextContainer,
               public Aspose::Slides::Theme::IOverrideThemeable
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) | Eğer yoksa yeni bir yer tutucu ekler ve yer tutucu özelliklerini belirtilen birine ayarlar. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](../../aspose.slides.theme/ithemeable/createthemeeffective/)() | Bu temalandırılabilir nesne için etkili bir tema döndürür. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiği kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde referans tipi nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde değer tipi nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değerle, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değerle, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı çift duyarlıklı karşılaştırmayı taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/ishape/get_alternativetext/)() | Bir şekille ilişkilendirilmiş alternatif metni döndürür. Oku [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/ishape/get_alternativetexttitle/)() | Bir şekille ilişkilendirilmiş alternatif metnin başlığını döndürür. Oku [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAxesManager](../iaxesmanager/)\> [get_Axes](./get_axes/)() | Grafik eksenlerine erişim sağlar. Yalnızca okuma [IAxesManager](../iaxesmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_BackWall](./get_backwall/)() | 3D grafiğin arka duvarının biçimini değiştirmeyi sağlayan bir nesneyi döndürür. Yalnızca okuma [IChartWall](../ichartwall/). |
| virtual [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/ishape/get_blackwhitemode/)() | Bir şeklin siyah-beyaz görüntü modunda nasıl görüntüleneceğini belirten özellik. Oku [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](./)\> [get_Chart](../ichartcomponent/get_chart/)() | Grafiği döndürür. Yalnızca okuma [IChart](./). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartData](../ichartdata/)\> [get_ChartData](./get_chartdata/)() | Bir grafik ile ilişkilendirilmiş bağlantılı veya gömülü veri hakkında bilgi döndürür. Yalnızca okuma [IChartData](../ichartdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataTable](../idatatable/)\> [get_ChartDataTable](./get_chartdatatable/)() | Grafiğin bir veri tablosunu döndürür. Yalnızca okuma [IDataTable](../idatatable/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_ChartTitle](./get_charttitle/)() | Grafik başlığını döndürür. Yalnızca okuma [IChartTitle](../icharttitle/). |
| virtual **int32_t** [get_ConnectionSiteCount](../../aspose.slides/ishape/get_connectionsitecount/)() | Şekildeki bağlantı noktalarının sayısını döndürür. Yalnızca okuma **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/ishape/get_customdata/)() | Şeklin özel verilerini döndürür. Yalnızca okuma [ICustomData](../../aspose.slides/icustomdata/). |
| virtual [DisplayBlanksAsType](../displayblanksastype/) [get_DisplayBlanksAs](./get_displayblanksas/)() | Grafikte boş hücrelerin nasıl çizileceğini döndürür. Oku [DisplayBlanksAsType](../displayblanksastype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/ishape/get_effectformat/)() | [EffectFormat](../../aspose.slides/effectformat/) nesnesini döndürür; bu nesne bir şekle uygulanan piksel efektlerini içerir. Yalnızca okuma [IEffectFormat](../../aspose.slides/ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/ishape/get_fillformat/)() | [FillFormat](../../aspose.slides/fillformat/) nesnesini döndürür; bu nesne bir şeklin dolgu biçimlendirme özelliklerini içerir. Yalnızca okuma [IFillFormat](../../aspose.slides/ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_Floor](./get_floor/)() | 3D grafiğin tabanının biçimini değiştirmeyi sağlayan bir nesneyi döndürür. Yalnızca okuma [IChartWall](../ichartwall/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/ishape/get_frame/)() | Şekil çerçevesinin özelliklerini döndürür. Oku [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)\> [get_GraphicalObjectLock](../../aspose.slides/igraphicalobject/get_graphicalobjectlock/)() | Şeklin kilitlerini döndürür. Yalnızca okuma [IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/). |
| virtual **bool** [get_HasDataTable](./get_hasdatatable/)() | Bir grafiğin veri tablosu olup olmadığını belirler. Oku **bool**. |
| virtual **bool** [get_HasLegend](./get_haslegend/)() | Bir grafiğin açıklama kutusu (legend) olup olmadığını belirler. Oku **bool**. |
| virtual **bool** [get_HasRoundedCorners](./get_hasroundedcorners/)() | Grafik alanının yuvarlak köşelere sahip olacağını belirler. Oku **bool**. |
| virtual **bool** [get_HasTitle](./get_hastitle/)() | Bir grafiğin görünür başlığı olup olmadığını belirler. Oku **bool**. |
| virtual **float** [get_Height](../../aspose.slides/ishape/get_height/)() | Şeklin yüksekliğini, puan cinsinden alır. Oku **float**. |
| virtual **bool** [get_Hidden](../../aspose.slides/ishape/get_hidden/)() | Şeklin gizli olup olmadığını belirler. Oku **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkclick/)() | Fare tıklaması için tanımlanmış köprüyü döndürür. Oku [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmanager/)() | Köprü yöneticisi. Yalnızca okuma [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmouseover/)() | Fare üzerine gelindiğinde tanımlanan köprüyü döndürür. Oku [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual **bool** [get_IsDecorative](../../aspose.slides/ishape/get_isdecorative/)() | ‘Dekoratif olarak işaretle’ seçeneğini alır. Okuma/yazma **bool**. |
| virtual **bool** [get_IsGrouped](../../aspose.slides/ishape/get_isgrouped/)() | Şeklin gruplandırılıp gruplandırılmadığını belirler. Yalnızca okuma **bool**. |
| virtual **bool** [get_IsTextHolder](../../aspose.slides/ishape/get_istextholder/)() | Şeklin TextHolder olup olmadığını belirler. Yalnızca okuma **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegend](../ilegend/)\> [get_Legend](./get_legend/)() | Bir grafik için açıklama kutusunu (legend) döndürür. Yalnızca okuma [ILegend](../ilegend/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/ishape/get_lineformat/)() | [LineFormat](../../aspose.slides/lineformat/) nesnesini döndürür; bu nesne bir şeklin çizgi biçimlendirme özelliklerini içerir. Yalnızca okuma [ILineFormat](../../aspose.slides/ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../../aspose.slides/ishape/get_name/)() | Bir şeklin adını döndürür. Oku [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/)() | Şeklin ömrü boyunca sabit kalan ve PowerPoint ya da interop kodunun şekle belge içinde her yerden güvenilir bir şekilde referans vermesini sağlayan slayt kapsamlı benzersiz tanımlayıcıyı döndürür. Yalnızca okuma **uint32_t**. Ayrıca bakınız [IShape::get_UniqueId](../../aspose.slides/ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/ishape/get_parentgroup/)() | Şekil gruplandırılmışsa üst [GroupShape](../../aspose.slides/groupshape/) nesnesini döndürür. Aksi takdirde null döndürür. Yalnızca okuma [IGroupShape](../../aspose.slides/igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/ishape/get_placeholder/)() | Bir şekil için yer tutucuyu döndürür. Yalnızca okuma [IPlaceholder](../../aspose.slides/iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartPlotArea](../ichartplotarea/)\> [get_PlotArea](./get_plotarea/)() | Bir grafiğin çizim alanını temsil eder. Yalnızca okuma [IChartPlotArea](../ichartplotarea/). |
| virtual **bool** [get_PlotVisibleCellsOnly](./get_plotvisiblecellsonly/)() | Yalnızca görünür hücrelerin çizilip çizilmediğini belirler. Hem görünür hem gizli hücrelerin çizilmesi için false. Oku **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Sunumu döndürür. Yalnızca okuma [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/ishape/get_rawframe/)() | Ham şekil çerçevesinin özelliklerini döndürür. Oku [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual **float** [get_Rotation](../../aspose.slides/ishape/get_rotation/)() | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını döndürür. Pozitif değer saat yönünde döndürmeyi, negatif değer saat yönünün tersini gösterir. Oku **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRotation3D](../irotation3d/)\> [get_Rotation3D](./get_rotation3d/)() | Bir grafiğin 3D dönüşünü döndürür. Yalnızca okuma [IRotation3D](../irotation3d/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/ishape/get_shapelock/)() | Şeklin kilitlerini döndürür. Yalnızca okuma [IBaseShapeLock](../../aspose.slides/ibaseshapelock/). |
| virtual **bool** [get_ShowDataLabelsOverMaximum](./get_showdatalabelsovermaximum/)() | Grafiğin maksimum değerinin üzerindeki veri etiketlerinin gösterileceğini belirler. Oku **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_SideWall](./get_sidewall/)() | 3D grafiğin yan duvarının biçimini değiştirmeyi sağlayan bir nesneyi döndürür. Yalnızca okuma [IChartWall](../ichartwall/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Temel slaytı döndürür. Yalnızca okuma [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [StyleType](../styletype/) [get_Style](./get_style/)() | Grafiğin stilini döndürür. Oku [StyleType](../styletype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Grafik metin formatını döndürür. Yalnızca okuma [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/)\> [get_ThemeManager](../../aspose.slides.theme/ioverridethemeable/get_thememanager/)() | Geçersiz kılma tema yöneticisini döndürür. Yalnızca okuma [IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/ishape/get_threedformat/)() | [ThreeDFormat](../../aspose.slides/threedformat/) nesnesini döndürür; bu nesne bir şeklin çizgi biçimlendirme özelliklerini içerir. Yalnızca okuma [IThreeDFormat](../../aspose.slides/ithreedformat/). |
| virtual [ChartType](../charttype/) [get_Type](./get_type/)() | Grafik tipini döndürür. Oku [ChartType](../charttype/). |
| virtual **uint32_t** [get_UniqueId](../../aspose.slides/ishape/get_uniqueid/)() | Eklentiler veya diğer kodlar tarafından kullanılmak üzere tasarlanmış dahili, sunum kapsamlı bir tanımlayıcıyı döndürür. Bu değer kullanıcı veya program tarafından yeniden atanabileceği için kalıcı bir benzersiz anahtar olarak ele alınmamalıdır. Yalnızca okuma **uint32_t**. Ayrıca bakınız [IShape::get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_UserShapes](./get_usershapes/)() | Grafiğin üzerindeki çizilen şekilleri belirtir. Yalnızca okuma [IGroupShape](../../aspose.slides/igroupshape/). |
| virtual **float** [get_Width](../../aspose.slides/ishape/get_width/)() | Şeklin genişliğini puan cinsinden alır. Oku **float**. |
| virtual **float** [get_X](../../aspose.slides/ishape/get_x/)() | Şeklin sol üst köşesinin x koordinatını puan cinsinden alır. Oku **float**. |
| virtual **float** [get_Y](../../aspose.slides/ishape/get_y/)() | Şeklin sol üst köşesinin y koordinatını puan cinsinden alır. Oku **float**. |
| virtual **int32_t** [get_ZOrderPosition](../../aspose.slides/ishape/get_zorderposition/)() | Bir şeklin z-düzenindeki konumunu döndürür. Shapes[0] z-düzeninin arkasındaki şekli, Shapes[Shapes.Count - 1] ise önündeki şekli döndürür. Yalnızca okuma **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder/)() | Temel bir yer tutucu şekli döndürür (geçerli şeklin miras aldığı yerleşim ve/veya ana slayttan bir şekil). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun benzeri. Özel nesnelerin hashlenmesini sağlar. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)() | Şekil küçük resmini döndürür. [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) şekil küçük resmi sınır türü varsayılan olarak kullanılır. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) | Şekil küçük resmini döndürür. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının benzeri. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün benzeri. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun benzeri. Özel tiplerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucu. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumu için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize durumu için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder/)() | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| virtual void [set_AlternativeText](../../aspose.slides/ishape/set_alternativetext/)([System::String](../../system/string/)) | Bir şekille ilişkilendirilmiş alternatif metni ayarlar. Yaz [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../../aspose.slides/ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Bir şekille ilişkilendirilmiş alternatif metnin başlığını ayarlar. Yaz [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../../aspose.slides/ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) | Bir şeklin siyah-beyaz görüntü modunda nasıl render edileceğini belirten özellik. Yaz [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| virtual void [set_DisplayBlanksAs](./set_displayblanksas/)([DisplayBlanksAsType](../displayblanksastype/)) | Grafikte boş hücrelerin nasıl çizileceğini ayarlar. Yaz [DisplayBlanksAsType](../displayblanksastype/). |
| virtual void [set_Frame](../../aspose.slides/ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | Şekil çerçevesinin özelliklerini ayarlar. Yaz [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual void [set_HasDataTable](./set_hasdatatable/)(**bool**) | Bir grafiğin veri tablosu olup olmadığını belirler. Yaz **bool**. |
| virtual void [set_HasLegend](./set_haslegend/)(**bool**) | Bir grafiğin açıklama kutusu (legend) olup olmadığını belirler. Yaz **bool**. |
| virtual void [set_HasRoundedCorners](./set_hasroundedcorners/)(**bool**) | Grafik alanının yuvarlak köşelere sahip olacağını belirler. Yaz **bool**. |
| virtual void [set_HasTitle](./set_hastitle/)(**bool**) | Bir grafiğin görünür başlığı olup olmadığını belirler. Yaz **bool**. |
| virtual void [set_Height](../../aspose.slides/ishape/set_height/)(**float**) | Şeklin yüksekliğini puan cinsinden ayarlar. Yaz **float**. |
| virtual void [set_Hidden](../../aspose.slides/ishape/set_hidden/)(**bool**) | Şeklin gizli olup olmadığını ayarlar. Yaz **bool**. |
| virtual void [set_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | Fare tıklaması için tanımlanan köprüyü ayarlar. Yaz [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | Fare üzerine gelindiğinde tanımlanan köprüyü ayarlar. Yaz [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual void [set_IsDecorative](../../aspose.slides/ishape/set_isdecorative/)(**bool**) | ‘Dekoratif olarak işaretle’ seçeneğini ayarlar. Okuma/yazma **bool**. |
| virtual void [set_Name](../../aspose.slides/ishape/set_name/)([System::String](../../system/string/)) | Bir şeklin adını ayarlar. Yaz [System::String](../../system/string/). |
| virtual void [set_PlotVisibleCellsOnly](./set_plotvisiblecellsonly/)(**bool**) | Yalnızca görünür hücrelerin çizilip çizilmediğini belirler. Hem görünür hem gizli hücrelerin çizilmesi için false. Yaz **bool**. |
| virtual void [set_RawFrame](../../aspose.slides/ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | Ham şekil çerçevesinin özelliklerini ayarlar. Yaz [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual void [set_Rotation](../../aspose.slides/ishape/set_rotation/)(**float**) | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını ayarlar. Pozitif değer saat yönünde döndürmeyi, negatif değer saat yönünün tersini gösterir. Yaz **float**. |
| virtual void [set_ShowDataLabelsOverMaximum](./set_showdatalabelsovermaximum/)(**bool**) | Grafiğin maksimum değerinin üzerindeki veri etiketlerinin gösterileceğini belirler. Yaz **bool**. |
| virtual void [set_Style](./set_style/)([StyleType](../styletype/)) | Grafiğin stilini ayarlar. Yaz [StyleType](../styletype/). |
| virtual void [set_Type](./set_type/)([ChartType](../charttype/)) | Grafik tipini ayarlar. Yaz [ChartType](../charttype/). |
| virtual void [set_Width](../../aspose.slides/ishape/set_width/)(**float**) | Şeklin genişliğini puan cinsinden ayarlar. Yaz **float**. |
| virtual void [set_X](../../aspose.slides/ishape/set_x/)(**float**) | Şeklin sol üst köşesinin x koordinatını puan cinsinden ayarlar. Yaz **float**. |
| virtual void [set_Y](../../aspose.slides/ishape/set_y/)(**float**) | Şeklin sol üst köşesinin y koordinatını puan cinsinden ayarlar. Yaz **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını paylaşılan yerine zayıf bir gösterici olarak ayarlar. Kapsayıcılardaki göstericilerin zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun benzeri. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidi açmasını uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual void [ValidateChartLayout](./validatechartlayout/)() | Grafik öğelerinin gerçek değerlerini hesaplar. Gerçek değerler, [IActualLayout](../iactuallayout/) arayüzünü ([IActualLayout::get_ActualX](../iactuallayout/get_actualx/), [IActualLayout::get_ActualY](../iactuallayout/get_actualy/), [IActualLayout::get_ActualWidth](../iactuallayout/get_actualwidth/), [IActualLayout::get_ActualHeight](../iactuallayout/get_actualheight/)) uygulayan öğelerin konumlarını ve gerçek eksen değerlerini ([IAxis::get_ActualMaxValue](../iaxis/get_actualmaxvalue/), [IAxis::get_ActualMinValue](../iaxis/get_actualminvalue/), [IAxis::get_ActualMajorUnit](../iaxis/get_actualmajorunit/), [IAxis::get_ActualMinorUnit](../iaxis/get_actualminorunit/), [IAxis::get_ActualMajorUnitScale](../iaxis/get_actualmajorunitscale/), [IAxis::get_ActualMinorUnitScale](../iaxis/get_actualminorunitscale/)) içerir. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | [Shape](../../aspose.slides/shape/) içeriğini SVG dosyası olarak kaydeder. |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | [Shape](../../aspose.slides/shape/) içeriğini SVG dosyası olarak kaydeder. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [IGraphicalObject](../../aspose.slides/igraphicalobject/)
* Sınıf [IFormattedTextContainer](../iformattedtextcontainer/)
* Sınıf [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable/)
* Ad alanı [Aspose::Slides::Charts](../)
* Kütüphane [Aspose.Slides](../../)