---
title: Chart class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/chart/
---
## Chart sınıfı

Represents an graphic chart on a slide.

**Inheritance:**[`Chart`](/slides/python-net/tr/aspose.slides.charts/chart) → [`GraphicalObject`](/slides/python-net/tr/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/tr/aspose.slides/shape)

The Chart type exposes the following members:

## Özellikler

| Property | Açıklama |
| :- | :- |
| [`is_text_holder`](/slides/python-net/tr/aspose.slides.charts/chart/is_text_holder/) | Şeklin TextHolder_PPT olup olmadığını belirler.<br/>            Yalnızca okuma **bool**. |
| [`placeholder`](/slides/python-net/tr/aspose.slides.charts/chart/placeholder/) | Şekil için yer tutucuyu döndürür. Şeklin yer tutucusu yoksa None döndürür.<br/>            Yalnızca okuma [`IPlaceholder`](/slides/python-net/tr/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/tr/aspose.slides.charts/chart/custom_data/) | Şeklin özel verisini döndürür.<br/>            Yalnızca okuma [`ICustomData`](/slides/python-net/tr/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/tr/aspose.slides.charts/chart/raw_frame/) | Ham şekil çerçevesinin özelliklerini döndürür veya ayarlar.<br/>            Okuma/yazma [`IShapeFrame`](/slides/python-net/tr/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/tr/aspose.slides.charts/chart/frame/) | Şekil çerçevesinin özelliklerini döndürür veya ayarlar.<br/>            Okuma/yazma [`IShapeFrame`](/slides/python-net/tr/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/tr/aspose.slides.charts/chart/line_format/) | Şekil için çizgi biçimlendirme özelliklerini içeren LineFormat nesnesini döndürür.<br/>            Not: çizgi özellikleri olmayan belirli şekil türleri için None döndürülebilir.<br/>            Yalnızca okuma [`ILineFormat`](/slides/python-net/tr/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/tr/aspose.slides.charts/chart/three_d_format/) | Şekil için 3D efekt özelliklerini içeren ThreeDFormat nesnesini döndürür.<br/>            Not: 3D özellikleri olmayan belirli şekil türleri için None döndürülebilir.<br/>            Yalnızca okuma [`IThreeDFormat`](/slides/python-net/tr/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/tr/aspose.slides.charts/chart/effect_format/) | Şekle uygulanmış piksel efektlerini içeren EffectFormat nesnesini döndürür.<br/>            Not: efekt özellikleri olmayan belirli şekil türleri için None döndürülebilir.<br/>            Yalnızca okuma [`IEffectFormat`](/slides/python-net/tr/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/tr/aspose.slides.charts/chart/fill_format/) | Şekil için dolgu biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür.<br/>            Not: dolgu özellikleri olmayan belirli şekil türleri için None döndürülebilir.<br/>            Yalnızca okuma [`IFillFormat`](/slides/python-net/tr/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/tr/aspose.slides.charts/chart/hyperlink_click/) | Fare tıklaması için tanımlanan köprüyi döndürür veya ayarlar.<br/>            Okuma/yazma [`IHyperlink`](/slides/python-net/tr/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/tr/aspose.slides.charts/chart/hyperlink_mouse_over/) | Fare üzerine gelindiğinde tanımlanan köprüyi döndürür veya ayarlar.<br/>            Okuma/yazma [`IHyperlink`](/slides/python-net/tr/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/tr/aspose.slides.charts/chart/hyperlink_manager/) | Köprü yöneticisini döndürür.<br/>            Yalnızca okuma [`IHyperlinkManager`](/slides/python-net/tr/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/tr/aspose.slides.charts/chart/hidden/) | Şeklin gizli olup olmadığını belirler.<br/>            Okuma/yazma **bool**. |
| [`z_order_position`](/slides/python-net/tr/aspose.slides.charts/chart/z_order_position/) | Bir şeklin z-sırasındaki konumunu döndürür.<br/>            Shapes[0] z-sırasının arkasındaki şekli döndürür,<br/>            Shapes[Shapes.Count - 1] ise z-sırasının önündeki şekli döndürür.<br/>            Yalnızca okuma **int**. |
| [`connection_site_count`](/slides/python-net/tr/aspose.slides.charts/chart/connection_site_count/) | Şeklin üzerindeki bağlantı noktalarının sayısını döndürür.<br/>            Yalnızca okuma **int**. |
| [`rotation`](/slides/python-net/tr/aspose.slides.charts/chart/rotation/) | Belirtilen şeklin z-ekseni etrafında döndürülmüş derece sayısını döndürür veya ayarlar.<br/>            Pozitif değer saat yönünde döndürmeyi, negatif değer ise saat yönünün tersine döndürmeyi gösterir.<br/>            Okuma/yazma **float**. |
| [`x`](/slides/python-net/tr/aspose.slides.charts/chart/x/) | Şeklin sol üst köşesinin x koordinatını, nokta cinsinden alır veya ayarlar.<br/>            Okuma/yazma **float**. |
| [`y`](/slides/python-net/tr/aspose.slides.charts/chart/y/) | Şeklin sol üst köşesinin y koordinatını, nokta cinsinden alır veya ayarlar.<br/>            Okuma/yazma **float**. |
| [`width`](/slides/python-net/tr/aspose.slides.charts/chart/width/) | Şeklin genişliğini, nokta cinsinden alır veya ayarlar.<br/>            Okuma/yazma **float**. |
| [`height`](/slides/python-net/tr/aspose.slides.charts/chart/height/) | Şeklin yüksekliğini, nokta cinsinden alır veya ayarlar.<br/>            Okuma/yazma **float**. |
| [`black_white_mode`](/slides/python-net/tr/aspose.slides.charts/chart/black_white_mode/) | Özellik, bir şeklin siyah-beyaz görüntüleme modunda nasıl render edileceğini belirler.<br/>            Okuma/yazma [`BlackWhiteMode`](/slides/python-net/tr/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/tr/aspose.slides.charts/chart/unique_id/) | Eklentiler veya diğer kodlar tarafından kullanılmak üzere, sunum kapsamlı bir iç tanımlayıcı döndürür.<br/>            Bu değer kullanıcı veya program tarafından yeniden atanabileceği için kalıcı benzersiz bir anahtar olarak ele alınmamalıdır.<br/>            Yalnızca okuma **int**.<br/>            Ayrıca bkz. [`Shape.office_interop_shape_id`](/slides/python-net/tr/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/tr/aspose.slides.charts/chart/office_interop_shape_id/) | Şeklin ömrü boyunca sabit kalan ve PowerPoint veya interop kodunun belge içinde herhangi bir yerden şekle güvenilir şekilde referans vermesini sağlayan, slayt kapsamlı benzersiz bir tanımlayıcı döndürür.<br/>            Yalnızca okuma **int**.<br/>            Ayrıca bkz. [`Shape.unique_id`](/slides/python-net/tr/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/tr/aspose.slides.charts/chart/alternative_text/) | Şekille ilişkili alternatif metni döndürür veya ayarlar.<br/>            Okuma/yazma **str**. |
| [`alternative_text_title`](/slides/python-net/tr/aspose.slides.charts/chart/alternative_text_title/) | Şekille ilişkili alternatif metnin başlığını döndürür veya ayarlar.<br/>            Okuma/yazma **str**. |
| [`name`](/slides/python-net/tr/aspose.slides.charts/chart/name/) | Bir şeklin adını döndürür veya ayarlar.<br/>            None olmamalıdır. Gerekirse boş string kullanılabilir.<br/>            Okuma/yazma **str**. |
| [`is_decorative`](/slides/python-net/tr/aspose.slides.charts/chart/is_decorative/) | 'Dekoratif olarak işaretle' seçeneğini alır veya ayarlar<br/>            Reed/write **bool**. |
| [`shape_lock`](/slides/python-net/tr/aspose.slides.charts/chart/shape_lock/) | Şeklin kilitlerini döndürür.<br/>            Yalnızca okuma [`IGraphicalObjectLock`](/slides/python-net/tr/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/tr/aspose.slides.charts/chart/is_grouped/) | Şeklin gruplanıp gruplanmadığını belirler.<br/>            Yalnızca okuma **bool**. |
| [`parent_group`](/slides/python-net/tr/aspose.slides.charts/chart/parent_group/) | Şekil gruplanmışsa üst GroupShape nesnesini döndürür. Aksi takdirde None döndürür.<br/>            Yalnızca okuma [`IGroupShape`](/slides/python-net/tr/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/tr/aspose.slides.charts/chart/slide/) | Bir şeklin üst slaytını döndürür.<br/>            Yalnızca okuma [`IBaseSlide`](/slides/python-net/tr/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/tr/aspose.slides.charts/chart/presentation/) | Bir slaytın üst sunumunu döndürür.<br/>            Yalnızca okuma [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/tr/aspose.slides.charts/chart/graphical_object_lock/) | Şeklin kilitlerini döndürür.<br/>            Yalnızca okuma [`IGraphicalObjectLock`](/slides/python-net/tr/aspose.slides/igraphicalobjectlock). |
| [`plot_visible_cells_only`](/slides/python-net/tr/aspose.slides.charts/chart/plot_visible_cells_only/) | Yalnızca görünür hücrelerin çizilip çizilmediğini belirler. Hem görünür hem gizli hücrelerin çizilmesi için False olur.<br/>            Okuma/yazma **bool**. |
| [`display_blanks_as`](/slides/python-net/tr/aspose.slides.charts/chart/display_blanks_as/) | Grafikte boş hücrelerin çizim yöntemini döndürür veya ayarlar.<br/>            Okuma/yazma [`DisplayBlanksAsType`](/slides/python-net/tr/aspose.slides.charts/displayblanksastype). |
| [`chart_data`](/slides/python-net/tr/aspose.slides.charts/chart/chart_data/) | Grafik ile ilişkili bağlantılı veya gömülü veri hakkında bilgi döndürür.<br/>            Yalnızca okuma [`IChartData`](/slides/python-net/tr/aspose.slides.charts/ichartdata). |
| [`has_title`](/slides/python-net/tr/aspose.slides.charts/chart/has_title/) | Bir grafiğin görünür başlığı olup olmadığını belirler.<br/>            Okuma/yazma **bool**. |
| [`chart_title`](/slides/python-net/tr/aspose.slides.charts/chart/chart_title/) | Grafik başlığını döndürür veya ayarlar.<br/>            Yalnızca okuma [`IChartTitle`](/slides/python-net/tr/aspose.slides.charts/icharttitle). |
| [`has_data_table`](/slides/python-net/tr/aspose.slides.charts/chart/has_data_table/) | Bir grafiğin veri tablosu olup olmadığını belirler.<br/>            Okuma/yazma **bool**. |
| [`has_legend`](/slides/python-net/tr/aspose.slides.charts/chart/has_legend/) | Bir grafiğin lejandı olup olmadığını belirler.<br/>            Okuma/yazma **bool**. |
| [`legend`](/slides/python-net/tr/aspose.slides.charts/chart/legend/) | Bir grafiğin lejandını döndürür veya ayarlar.<br/>            Yalnızca okuma [`ILegend`](/slides/python-net/tr/aspose.slides.charts/ilegend). |
| [`chart_data_table`](/slides/python-net/tr/aspose.slides.charts/chart/chart_data_table/) | Bir grafiğin veri tablosunu döndürür.<br/>            Yalnızca okuma [`IDataTable`](/slides/python-net/tr/aspose.slides.charts/idatatable). |
| [`style`](/slides/python-net/tr/aspose.slides.charts/chart/style/) | Grafik stilini döndürür veya ayarlar.<br/>            Okuma/yazma [`StyleType`](/slides/python-net/tr/aspose.slides.charts/styletype). |
| [`type`](/slides/python-net/tr/aspose.slides.charts/chart/type/) | Grafik tipini döndürür veya ayarlar.<br/>            Okuma/yazma [`ChartType`](/slides/python-net/tr/aspose.slides.charts/charttype). |
| [`plot_area`](/slides/python-net/tr/aspose.slides.charts/chart/plot_area/) | Bir grafiğin çizim alanını temsil eder.<br/>            Yalnızca okuma [`IChartPlotArea`](/slides/python-net/tr/aspose.slides.charts/ichartplotarea). |
| [`rotation_3d`](/slides/python-net/tr/aspose.slides.charts/chart/rotation_3d/) | Bir grafiğin 3D döndürmesini döndürür.<br/>            Yalnızca okuma [`IRotation3D`](/slides/python-net/tr/aspose.slides.charts/irotation3d). |
| [`back_wall`](/slides/python-net/tr/aspose.slides.charts/chart/back_wall/) | 3D grafiğin arka duvarının biçimini değiştirmeye izin veren bir nesneyi döndürür.<br/>            Yalnızca okuma [`IChartWall`](/slides/python-net/tr/aspose.slides.charts/ichartwall). |
| [`side_wall`](/slides/python-net/tr/aspose.slides.charts/chart/side_wall/) | 3D grafiğin yan duvarının biçimini değiştirmeye izin veren bir nesneyi döndürür.<br/>            Yalnızca okuma [`IChartWall`](/slides/python-net/tr/aspose.slides.charts/ichartwall). |
| [`floor`](/slides/python-net/tr/aspose.slides.charts/chart/floor/) | 3D grafiğin zemininin biçimini değiştirmeye izin veren bir nesneyi döndürür.<br/>            Yalnızca okuma [`IChartWall`](/slides/python-net/tr/aspose.slides.charts/ichartwall). |
| [`text_format`](/slides/python-net/tr/aspose.slides.charts/chart/text_format/) | Grafik metin biçimini döndürür.<br/>            Özellik aşağıdaki tipler için geçerli değildir: [`ChartType.TREEMAP`](/slides/python-net/tr/aspose.slides.charts/charttype/TREEMAP), [`ChartType.SUNBURST`](/slides/python-net/tr/aspose.slides.charts/charttype/SUNBURST),<br/>            [`ChartType.WATERFALL`](/slides/python-net/tr/aspose.slides.charts/charttype/WATERFALL), [`ChartType.HISTOGRAM`](/slides/python-net/tr/aspose.slides.charts/charttype/HISTOGRAM), [`ChartType.FUNNEL`](/slides/python-net/tr/aspose.slides.charts/charttype/FUNNEL),[`ChartType.BOX_AND_WHISKER`](/slides/python-net/tr/aspose.slides.charts/charttype/BOX_AND_WHISKER).<br/>            Yalnızca okuma [`IChartTextFormat`](/slides/python-net/tr/aspose.slides.charts/icharttextformat). |
| [`theme_manager`](/slides/python-net/tr/aspose.slides.charts/chart/theme_manager/) | Tema yöneticisini döndürür.<br/>            Yalnızca okuma [`IOverrideThemeManager`](/slides/python-net/tr/aspose.slides.theme/ioverridethememanager). |
| [`user_shapes`](/slides/python-net/tr/aspose.slides.charts/chart/user_shapes/) | Grafiğin üstünde çizilen şekilleri belirtir.<br/>            Yalnızca okuma [`IGroupShape`](/slides/python-net/tr/aspose.slides/igroupshape). |
| [`axes`](/slides/python-net/tr/aspose.slides.charts/chart/axes/) | Grafik eksenlerine erişim sağlar.<br/>            Yalnızca okuma [`IAxesManager`](/slides/python-net/tr/aspose.slides.charts/iaxesmanager). |
| [`show_data_labels_over_maximum`](/slides/python-net/tr/aspose.slides.charts/chart/show_data_labels_over_maximum/) | Grafik maksimumu üzerindeki veri etiketlerinin gösterilip gösterilmeyeceğini belirtir.<br/>            Okuma/yazma **bool**. |
| [`has_rounded_corners`](/slides/python-net/tr/aspose.slides.charts/chart/has_rounded_corners/) | Grafik alanının yuvarlatılmış köşelere sahip olup olmayacağını belirtir.<br/>            Okuma/yazma **bool**. |
| [`chart`](/slides/python-net/tr/aspose.slides.charts/chart/chart/) |  |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`get_image(self)`](/slides/python-net/tr/aspose.slides.charts/chart/get_image/#) | Şekil küçük resmini döndürür.<br/>            ShapeThumbnailBounds.Shape şekil küçük resim sınırları türü varsayılan olarak kullanılır. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/tr/aspose.slides.charts/chart/get_image/#shapethumbnailbounds-float-float) | Şekil küçük resmini döndürür. |
| [`write_as_svg(self, stream)`](/slides/python-net/tr/aspose.slides.charts/chart/write_as_svg/#iorawiobase) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/tr/aspose.slides.charts/chart/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [`remove_placeholder(self)`](/slides/python-net/tr/aspose.slides.charts/chart/remove_placeholder/#) | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/tr/aspose.slides.charts/chart/add_placeholder/#iplaceholder) | Yer tutucu yoksa yeni bir yer tutucu ekler ve yer tutucu özelliklerini belirtilen birine ayarlar. |
| [`get_base_placeholder(self)`](/slides/python-net/tr/aspose.slides.charts/chart/get_base_placeholder/#) | Temel bir yer tutucu şekli döndürür (geçerli şeklin devralındığı düzen ve/veya ana slayttan gelen şekil).<br/>            Geçerli şekil devralınmamışsa None döndürülür. |
| [`get_visual_bounds(self)`](/slides/python-net/tr/aspose.slides.charts/chart/get_visual_bounds/#) | Şeklin render edilmiş içeriğinden hesaplanan görsel sınırlarını alır. |
| [`validate_chart_layout(self)`](/slides/python-net/tr/aspose.slides.charts/chart/validate_chart_layout/#) | Grafik öğelerinin gerçek değerlerini hesaplar. Gerçek değerler, IActualLayout arayüzünü uygulayan öğelerin konumlarını içerir <br/>            (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight)<br/>            ve gerçek eksen değerlerini (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, <br/>            IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale). |
| [`create_theme_effective(self)`](/slides/python-net/tr/aspose.slides.charts/chart/create_theme_effective/#) | Bu grafik için etkili bir temayı döndürür. |

### Ayrıca Bakınız
* sınıf [`Chart`](/slides/python-net/tr/aspose.slides.charts/chart)
* sınıf [`GraphicalObject`](/slides/python-net/tr/aspose.slides/graphicalobject)
* sınıf [`Shape`](/slides/python-net/tr/aspose.slides/shape)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)