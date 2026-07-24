---
title: Chart
second_title: Aspose.Slides için C++ API Referansı
description: Bir slayttaki grafik tabloyu temsil eder.
type: docs
weight: 53
url: /tr/aspose.slides.charts/chart/
---
## Chart sınıfı

Represents an graphic chart on a slide.

```cpp
class Chart : public Aspose::Slides::GraphicalObject,
              public Aspose::Slides::Charts::IChart
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) override | Eger yoksa yeni bir yer tutucu ekler ve yer tutucu özelliklerini belirtilen bir yere ayarlar. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Theme::IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](./createthemeeffective/)() override | Bu grafik için etkili bir temayı döndürür. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objeleri C# [Object.Equals](../../system/object/equals/) semantiği kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipindeki nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer tipindeki nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | İki NaN'ın eşit kabul edildiği, IEC 60559:1989’a göre NaN’ın herhangi bir değer, NaN dahil, eşit olmadığına rağmen, C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | İki NaN'ın eşit kabul edildiği, IEC 60559:1989’a göre NaN’ın herhangi bir değer, NaN dahil, eşit olmadığına rağmen, C# tarzı çift hassasiyetli kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/shape/get_alternativetext/)() override | Bir şekille ilişkili alternatif metni döndürür. Oku [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/shape/get_alternativetexttitle/)() override | Bir şekille ilişkili alternatif metnin başlığını döndürür. Oku [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAxesManager](../iaxesmanager/)\> [get_Axes](./get_axes/)() override | Grafik eksenlerine erişim sağlar. Yalnızca okunabilir [IAxesManager](../iaxesmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_BackWall](./get_backwall/)() override | 3D grafiğin arka duvarının biçimini değiştirmeye izin veren bir nesneyi döndürür. Yalnızca okunabilir [IChartWall](../ichartwall/). |
| [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/shape/get_blackwhitemode/)() override | Özellik, bir şeklin siyah-beyaz görüntü modunda nasıl gösterileceğini belirler. Oku [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartData](../ichartdata/)\> [get_ChartData](./get_chartdata/)() override | Bir grafik ile ilişkili bağlantılı ya da gömülü veri hakkında bilgileri döndürür. Yalnızca okunabilir [IChartData](../ichartdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDataTable](../idatatable/)\> [get_ChartDataTable](./get_chartdatatable/)() override | Grafiğin veri tablosunu döndürür. Yalnızca okunabilir [IDataTable](../idatatable/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_ChartTitle](./get_charttitle/)() override | Grafik başlığını döndürür. Yalnızca okunabilir [IChartTitle](../icharttitle/). |
| **int32_t** [get_ConnectionSiteCount](../../aspose.slides/shape/get_connectionsitecount/)() override | Şeklin bağlama noktalarının sayısını döndürür. Yalnızca okunabilir **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/shape/get_customdata/)() override | Şeklin özel verisini döndürür. Yalnızca okunabilir [ICustomData](../../aspose.slides/icustomdata/). |
| [DisplayBlanksAsType](../displayblanksastype/) [get_DisplayBlanksAs](./get_displayblanksas/)() override | Grafikte boş hücrelerin nasıl çizileceğini döndürür. Oku [DisplayBlanksAsType](../displayblanksastype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/shape/get_effectformat/)() override | Bir şekle uygulanan piksel efektlerini içeren [EffectFormat](../../aspose.slides/effectformat/) nesnesini döndürür. Not: Etki özellikleri olmayan belirli şekil tipleri için null döndürebilir. Yalnızca okunabilir [IEffectFormat](../../aspose.slides/ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/shape/get_fillformat/)() override | [FillFormat](../../aspose.slides/fillformat/) nesnesini döndürür, bu nesne bir şeklin dolgu biçimlendirme özelliklerini içerir. Not: Dolgu özellikleri olmayan belirli şekil tipleri için null döndürebilir. Yalnızca okunabilir [IFillFormat](../../aspose.slides/ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_Floor](./get_floor/)() override | 3D grafiğin zemininin biçimini değiştirmeye izin veren bir nesneyi döndürür. Yalnızca okunabilir [IChartWall](../ichartwall/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/shape/get_frame/)() override | Şekil çerçevesinin özelliklerini döndürür. Oku [IShapeFrame](../../aspose.slides/ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)\> [get_GraphicalObjectLock](../../aspose.slides/graphicalobject/get_graphicalobjectlock/)() override | Şeklin kilitlerini döndürür. Yalnızca okunabilir [IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/). |
| **bool** [get_HasDataTable](./get_hasdatatable/)() override | Bir grafiğin veri tablosu olup olmadığını belirler. Oku **bool**. |
| **bool** [get_HasLegend](./get_haslegend/)() override | Bir grafiğin lejandı olup olmadığını belirler. Oku **bool**. |
| **bool** [get_HasRoundedCorners](./get_hasroundedcorners/)() override | Grafik alanının yuvarlatılmış köşelere sahip olmasını belirler. Oku **bool**. |
| **bool** [get_HasTitle](./get_hastitle/)() override | Bir grafiğin görünür başlığı olup olmadığını belirler. Oku **bool**. |
| **float** [get_Height](../../aspose.slides/shape/get_height/)() override | Şeklin yüksekliğini, puan cinsinden alır. Oku **float**. |
| **bool** [get_Hidden](../../aspose.slides/shape/get_hidden/)() override | Şeklin gizli olup olmadığını belirler. Oku **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/shape/get_hyperlinkclick/)() override | Fare tıklaması için tanımlanan hiperlinki döndürür. Oku [IHyperlink](../../aspose.slides/ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/shape/get_hyperlinkmanager/)() override | Hiperlink yöneticisini döndürür. Yalnızca okunabilir [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/shape/get_hyperlinkmouseover/)() override | Fare üzerine gelindiğinde tanımlanan hiperlinki döndürür. Oku [IHyperlink](../../aspose.slides/ihyperlink/). |
| **bool** [get_IsDecorative](../../aspose.slides/shape/get_isdecorative/)() override | ‘Dekoratif olarak işaretle’ seçeneğini alır. Oku/yaz **bool**. |
| **bool** [get_IsGrouped](../../aspose.slides/shape/get_isgrouped/)() override | Şeklin gruplanmış olup olmadığını belirler. Yalnızca okunabilir **bool**. |
| **bool** [get_IsTextHolder](../../aspose.slides/shape/get_istextholder/)() override | Şeklin TextHolder_PPT olup olmadığını belirler. Yalnızca okunabilir **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegend](../ilegend/)\> [get_Legend](./get_legend/)() override | Bir grafik için lejandı döndürür. Yalnızca okunabilir [ILegend](../ilegend/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/shape/get_lineformat/)() override | [LineFormat](../../aspose.slides/lineformat/) nesnesini döndürür, bu nesne bir şeklin çizgi biçimlendirme özelliklerini içerir. Not: Çizgi özellikleri olmayan belirli şekil tipleri için null döndürebilir. Yalnızca okunabilir [ILineFormat](../../aspose.slides/ilineformat/). |
| [System::String](../../system/string/) [get_Name](../../aspose.slides/shape/get_name/)() override | Bir şeklin adını döndürür. Null olmamalıdır. Gerekirse boş string değeri kullanın. Oku [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/)() override | Şeklin ömrü boyunca sabit kalan ve PowerPoint ya da interop kodunun şekle belge içinde her yerden güvenilir şekilde referans vermesini sağlayan, slayt kapsamlı benzersiz bir tanımlayıcı döndürür. Yalnızca okunabilir **uint32_t**. Ayrıca bkz [Shape::get_UniqueId](../../aspose.slides/shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/shape/get_parentgroup/)() override | Şekil gruplanmışsa üst [GroupShape](../../aspose.slides/groupshape/) nesnesini döndürür. Aksi takdirde null döndürür. Yalnızca okunabilir [IGroupShape](../../aspose.slides/igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/shape/get_placeholder/)() override | Bir şeklin yer tutucusunu döndürür. Şeklin yer tutucusu yoksa null döndürür. Yalnızca okunabilir [IPlaceholder](../../aspose.slides/iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartPlotArea](../ichartplotarea/)\> [get_PlotArea](./get_plotarea/)() override | Bir grafiğin çizim alanını temsil eder. Yalnızca okunabilir [IChartPlotArea](../ichartplotarea/). |
| **bool** [get_PlotVisibleCellsOnly](./get_plotvisiblecellsonly/)() override | Yalnızca görünür hücrelerin çizilip çizilmeyeceğini belirler. Her iki görünür ve gizli hücreyi çizmek için false. Oku **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/shape/get_presentation/)() override | Bir slaytın üst sunumunu döndürür. Yalnızca okunabilir [IPresentation](../../aspose.slides/ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/shape/get_rawframe/)() override | Ham şekil çerçevesinin özelliklerini döndürür. Oku [IShapeFrame](../../aspose.slides/ishapeframe/). |
| **float** [get_Rotation](../../aspose.slides/shape/get_rotation/)() override | Belirtilen şeklin z ekseni etrafında döndürülmüş olduğu derece sayısını döndürür. Pozitif değer saat yönünde; negatif değer saat yönünün tersinde döndürmeyi gösterir. Oku **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IRotation3D](../irotation3d/)\> [get_Rotation3D](./get_rotation3d/)() override | Bir grafiğin 3D döndürülmesini döndürür. Yalnızca okunabilir [IRotation3D](../irotation3d/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/shape/get_shapelock/)() override | Şeklin kilitlerini döndürür. Yalnızca okunabilir [IBaseShapeLock](../../aspose.slides/ibaseshapelock/). |
| **bool** [get_ShowDataLabelsOverMaximum](./get_showdatalabelsovermaximum/)() override | Grafiğin maksimum değerinin üzerindeki veri etiketlerinin gösterilmesini belirtir. Oku **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_SideWall](./get_sidewall/)() override | 3D grafiğin yan duvarının biçimini değiştirmeye izin veren bir nesneyi döndürür. Yalnızca okunabilir [IChartWall](../ichartwall/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/shape/get_slide/)() override | Bir şeklin üst slaytını döndürür. Yalnızca okunabilir [IBaseSlide](../../aspose.slides/ibaseslide/). |
| [StyleType](../styletype/) [get_Style](./get_style/)() override | Grafik stilini döndürür. Oku [StyleType](../styletype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Grafik metin biçimini döndürür. Özellik aşağıdaki tipler için geçerli değildir: [ChartType::Treemap](../charttype/), [ChartType::Sunburst](../charttype/), [ChartType::Waterfall](../charttype/), [ChartType::Histogram](../charttype/), [ChartType::Funnel](../charttype/),[ChartType::BoxAndWhisker](../charttype/). Yalnızca okunabilir [IChartTextFormat](../icharttextformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Theme::IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/)\> [get_ThemeManager](./get_thememanager/)() override | Tema yöneticisini döndürür. Yalnızca okunabilir [Aspose::Slides::Theme::IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/shape/get_threedformat/)() override | [ThreeDFormat](../../aspose.slides/threedformat/) nesnesini döndürür; bu nesne bir şeklin 3D efekt özelliklerini içerir. Not: 3D özellikleri olmayan belirli şekil tipleri için null döndürebilir. Yalnızca okunabilir [IThreeDFormat](../../aspose.slides/ithreedformat/). |
| [ChartType](../charttype/) [get_Type](./get_type/)() override | Grafik tipini döndürür. Oku [ChartType](../charttype/). |
| **uint32_t** [get_UniqueId](../../aspose.slides/shape/get_uniqueid/)() override | Eklentiler veya diğer kodlar tarafından kullanılmak üzere, sunum kapsamlı iç bir tanımlayıcı döndürür. Bu değer kullanıcı ya da program tarafından yeniden atanabileceği için kalıcı benzersiz bir anahtar olarak ele alınmamalıdır. Yalnızca okunabilir **uint32_t**. Ayrıca bkz [Shape::get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_UserShapes](./get_usershapes/)() override | Grafiğin üstünde çizilen şekilleri belirtir. Yalnızca okunabilir [IGroupShape](../../aspose.slides/igroupshape/). |
| **float** [get_Width](../../aspose.slides/shape/get_width/)() override | Şeklin genişliğini, puan cinsinden alır. Oku **float**. |
| **float** [get_X](../../aspose.slides/shape/get_x/)() override | Şeklin sol üst köşesinin x koordinatını, puan cinsinden alır. Oku **float**. |
| **float** [get_Y](../../aspose.slides/shape/get_y/)() override | Şeklin sol üst köşesinin y koordinatını, puan cinsinden alır. Oku **float**. |
| **int32_t** [get_ZOrderPosition](../../aspose.slides/shape/get_zorderposition/)() override | Bir şeklin z-sırasındaki konumunu döndürür. Shapes[0] z-sırasının arkasındaki şekli, Shapes[Shapes.Count - 1] ise önündeki şekli döndürür. Yalnızca okunabilir **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder/)() override | Temel bir yer tutucu şekli döndürür (geçerli şeklin devralındığı düzen ve/veya ana slayttan gelen şekil). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun benzeri. Özel nesnelerin hashlenmesini sağlar. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)() override | Şekil küçük resmini döndürür. [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) şekil küçük resim sınırları tipi varsayılan olarak kullanılır. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) override | Şekil küçük resmini döndürür. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının benzeri. |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../../aspose.slides/shape/getvisualbounds/)() | Şeklin render edilmiş içeriğinden hesaplanan görsel sınırlarını alır. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün benzeri. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlemci nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun benzeri. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapıları başlatılır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapıcısını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapıcısını etkinleştirir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referansla değer tipindeki nesneyi nullptr ile karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'ın dize ve nullptr durumu için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'ın dize durumu için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder/)() override | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| void [set_AlternativeText](../../aspose.slides/shape/set_alternativetext/)([System::String](../../system/string/)) override | Bir şekille ilişkili alternatif metni ayarlar. Yaz [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../../aspose.slides/shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Bir şekille ilişkili alternatif metnin başlığını ayarlar. Yaz [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../../aspose.slides/shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) override | Özellik, bir şeklin siyah-beyaz görüntü modunda nasıl render edileceğini belirler. Yaz [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| void [set_DisplayBlanksAs](./set_displayblanksas/)([DisplayBlanksAsType](../displayblanksastype/)) override | Grafikte boş hücrelerin nasıl çizileceğini ayarlar. Yaz [DisplayBlanksAsType](../displayblanksastype/). |
| void [set_Frame](../../aspose.slides/shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | Şekil çerçevesinin özelliklerini ayarlar. Yaz [IShapeFrame](../../aspose.slides/ishapeframe/). |
| void [set_HasDataTable](./set_hasdatatable/)(**bool**) override | Bir grafiğin veri tablosu olup olmadığını belirler. Yaz **bool**. |
| void [set_HasLegend](./set_haslegend/)(**bool**) override | Bir grafiğin lejandı olup olmadığını belirler. Yaz **bool**. |
| void [set_HasRoundedCorners](./set_hasroundedcorners/)(**bool**) override | Grafik alanının yuvarlatılmış köşelere sahip olmasını belirler. Yaz **bool**. |
| void [set_HasTitle](./set_hastitle/)(**bool**) override | Bir grafiğin görünür başlığı olup olmadığını belirler. Yaz **bool**. |
| void [set_Height](../../aspose.slides/shape/set_height/)(**float**) override | Şeklin yüksekliğini, puan cinsinden ayarlar. Yaz **float**. |
| void [set_Hidden](../../aspose.slides/shape/set_hidden/)(**bool**) override | Şeklin gizli olup olmadığını belirler. Yaz **bool**. |
| void [set_HyperlinkClick](../../aspose.slides/shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | Fare tıklaması için tanımlanan hiperlinki ayarlar. Yaz [IHyperlink](../../aspose.slides/ihyperlink/). |
| void [set_HyperlinkMouseOver](../../aspose.slides/shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | Fare üzerine gelindiğinde tanımlanan hiperlinki ayarlar. Yaz [IHyperlink](../../aspose.slides/ihyperlink/). |
| void [set_IsDecorative](../../aspose.slides/shape/set_isdecorative/)(**bool**) override | 'Dekoratif olarak işaretle' seçeneğini ayarlar. Oku/yaz **bool**. |
| void [set_Name](../../aspose.slides/shape/set_name/)([System::String](../../system/string/)) override | Bir şeklin adını ayarlar. Null olmamalıdır. Gerekirse boş string değeri kullanın. Yaz [System::String](../../system/string/). |
| void [set_PlotVisibleCellsOnly](./set_plotvisiblecellsonly/)(**bool**) override | Yalnızca görünür hücrelerin çizilip çizilmeyeceğini belirler. Her iki görünür ve gizli hücreyi çizmek için false. Yaz **bool**. |
| void [set_RawFrame](../../aspose.slides/shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | Ham şekil çerçevesinin özelliklerini ayarlar. Yaz [IShapeFrame](../../aspose.slides/ishapeframe/). |
| void [set_Rotation](../../aspose.slides/shape/set_rotation/)(**float**) override | Belirtilen şeklin z ekseni etrafında döndürülmüş olduğu derece sayısını ayarlar. Pozitif değer saat yönünde; negatif değer saat yönünün tersinde döndürmeyi gösterir. Yaz **float**. |
| void [set_ShowDataLabelsOverMaximum](./set_showdatalabelsovermaximum/)(**bool**) override | Grafiğin maksimum değerinin üzerindeki veri etiketlerinin gösterilmesini belirler. Yaz **bool**. |
| void [set_Style](./set_style/)([StyleType](../styletype/)) override | Grafik stilini ayarlar. Yaz [StyleType](../styletype/). |
| void [set_Type](./set_type/)([ChartType](../charttype/)) override | Grafik tipini ayarlar. Yaz [ChartType](../charttype/). |
| void [set_Width](../../aspose.slides/shape/set_width/)(**float**) override | Şeklin genişliğini, puan cinsinden ayarlar. Yaz **float**. |
| void [set_X](../../aspose.slides/shape/set_x/)(**float**) override | Şeklin sol üst köşesinin x koordinatını, puan cinsinden ayarlar. Yaz **float**. |
| void [set_Y](../../aspose.slides/shape/set_y/)(**float**) override | Şeklin sol üst köşesinin y koordinatını, puan cinsinden ayarlar. Yaz **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını paylaşımlı yerine zayıf bir işaretçi olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun benzeri. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açar. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlemci nesnesini kullanın. |
| void [ValidateChartLayout](./validatechartlayout/)() override | Grafik öğelerinin gerçek değerlerini hesaplar. Gerçek değerler, [IActualLayout](../iactuallayout/) arayüzünü uygulayan öğelerin konumlarını ([IActualLayout::get_ActualX](../iactuallayout/get_actualx/), [IActualLayout::get_ActualY](../iactuallayout/get_actualy/), [IActualLayout::get_ActualWidth](../iactuallayout/get_actualwidth/), [IActualLayout::get_ActualHeight](../iactuallayout/get_actualheight/)) ve gerçek eksen değerlerini ([IAxis::get_ActualMaxValue](../iaxis/get_actualmaxvalue/), [IAxis::get_ActualMinValue](../iaxis/get_actualminvalue/), [IAxis::get_ActualMajorUnit](../iaxis/get_actualmajorunit/), [IAxis::get_ActualMinorUnit](../iaxis/get_actualminorunit/), [IAxis::get_ActualMajorUnitScale](../iaxis/get_actualmajorunitscale/), [IAxis::get_ActualMinorUnitScale](../iaxis/get_actualminorunitscale/)) içerir. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | [Shape](../../aspose.slides/shape/) içeriğini SVG dosyası olarak kaydeder. |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | [Shape](../../aspose.slides/shape/) içeriğini SVG dosyası olarak kaydeder. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Ayrıca bakınız

* Sınıf [GraphicalObject](../../aspose.slides/graphicalobject/)
* Sınıf [IChart](../ichart/)
* İsim alanı [Aspose::Slides::Charts](../)
* Kütüphane [Aspose.Slides](../../)