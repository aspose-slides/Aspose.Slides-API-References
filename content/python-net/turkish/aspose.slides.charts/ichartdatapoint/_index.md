---
title: IChartDataPoint class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint sınıfı

Seri veri noktasını temsil eder.

IChartDataPoint türü aşağıdaki üyeleri gösterir.

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`x_value`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/x_value/) | Grafik veri noktasının x değerini alır.<br/>            Yalnızca okuma [`IStringOrDoubleChartValue`](/slides/python-net/tr/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/y_value/) | Grafik veri noktasının y değerini alır.<br/>            Yalnızca okuma [`IDoubleChartValue`](/slides/python-net/tr/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/bubble_size/) | Grafik veri noktasının balon boyutunu alır.<br/>            Yalnızca okuma [`IDoubleChartValue`](/slides/python-net/tr/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/value/) | Grafik veri noktasının değerini alır.<br/>            Yalnızca okuma [`IDoubleChartValue`](/slides/python-net/tr/aspose.slides.charts/idoublechartvalue). |
| [`cached_x_value`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/cached_x_value/) | Grafik veri noktasının önbelleğe alınmış X değerini alır.<br/>            Yalnızca okuma [`ICachedChartValue`](/slides/python-net/tr/aspose.slides.charts/icachedchartvalue). |
| [`cached_y_value`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/cached_y_value/) | Grafik veri noktasının önbelleğe alınmış Y değerini alır.<br/>            Yalnızca okuma [`ICachedChartValue`](/slides/python-net/tr/aspose.slides.charts/icachedchartvalue). |
| [`cached_value`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/cached_value/) | Grafik veri noktasının önbelleğe alınmış değerini alır.<br/>            Yalnızca okuma [`ICachedChartValue`](/slides/python-net/tr/aspose.slides.charts/icachedchartvalue). |
| [`cached_bubble_size`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/cached_bubble_size/) | Grafik veri noktasının önbelleğe alınmış balon boyutunu alır.<br/>            Yalnızca okuma [`ICachedChartValue`](/slides/python-net/tr/aspose.slides.charts/icachedchartvalue). |
| [`size_value`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/size_value/) | Grafik veri noktasının boyut değerini alır.<br/>            Treemap ve Sunburst grafiklerinde kullanılır. <br/>            Yalnızca okuma [`IDoubleChartValue`](/slides/python-net/tr/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/color_value/) | Grafik veri noktasının renk değerini alır.<br/>            Harita grafiklerinde kullanılır. <br/>            Yalnızca okuma [`IDoubleChartValue`](/slides/python-net/tr/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/error_bars_custom_values/) | Sıra hat çubukları değerlerini Özel değer tipi durumunda temsil eder.<br/>            Yalnızca okuma [`IErrorBarsCustomValues`](/slides/python-net/tr/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/label/) | Grafik veri noktasının etiketini temsil eder.<br/>            Yalnızca okuma [`IDataLabel`](/slides/python-net/tr/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/is_bubble_3d/) | Balonların 3D etkisine sahip olacağını belirtir.<br/>            Okuma/yazma **bool**. |
| [`explosion`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/explosion/) | Veri noktasının pasta grafiğinin merkezinden ne kadar kaydırılacağını belirtir.<br/>            Okuma/yazma **int**. |
| [`format`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/format/) | Biçimlendirme özelliklerini temsil eder.<br/>            Okuma/yazma [`IFormat`](/slides/python-net/tr/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/marker/) | Veri işaretleyicisini belirtir.<br/>            Yalnızca okuma [`IMarker`](/slides/python-net/tr/aspose.slides.charts/imarker). |
| [`related_legend_entry`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/related_legend_entry/) | Bu listedeki grafik türlerinden birine ait ilgili lejand girdisinin özellikleri:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            Yalnızca okuma [`ILegendEntryProperties`](/slides/python-net/tr/aspose.slides.charts/ilegendentryproperties). |
| [`set_as_total`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/set_as_total/) | Veri noktasını toplam olarak ayarlar. Yalnızca Waterfall serisi türü için uygulanır. |
| [`invert_if_negative`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/invert_if_negative/) | Veri noktasının değeri negatifse renklerini tersine çevireceğini belirtir.<br/>            Okuma/yazma **bool**. |
| [`data_point_levels`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/data_point_levels/) | Veri noktası seviyelerinin kapsayıcısını döndürür. Treeamp ve Sunburst serileri için uygulanır.<br/>            Veri noktası seviyeleri indekslemesi sıfır tabanlıdır. |
| [`index`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/index/) | Ebeveynin çocuk koleksiyonundan hangisine bu veri noktasının uygulanacağını belirler.<br/>            Okuma **int**. |
| [`actual_x`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/actual_x/) |  |
| [`actual_y`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/actual_y/) |  |
| [`actual_width`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/actual_width/) |  |
| [`actual_height`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/actual_height/) |  |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`remove(self)`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/remove/#) | Veri noktasını grafik serisinden kaldırır. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/get_automatic_data_point_color/#) | Seri indeksi, veri noktası indeksi, ParentSeriesGroup.IsColorVaried özelliği ve grafik stiline dayanarak veri noktasının otomatik rengini döndürür.<br/>            Bu renk, FillType NotDefined olduğunda varsayılan olarak kullanılır. |

### Diğer
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)