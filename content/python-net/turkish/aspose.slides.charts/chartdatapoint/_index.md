---
title: ChartDataPoint class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint sınıfı

Seri veri noktasını temsil eder.

ChartDataPoint türü aşağıdaki üyeleri sunar:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`x_value`](/slides/python-net/tr/aspose.slides.charts/chartdatapoint/x_value/) | XValue.<br/>            Yalnızca okuma [`IStringOrDoubleChartValue`](/slides/python-net/tr/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/tr/aspose.slides.charts/chartdatapoint/y_value/) | YValue.<br/>            Yalnızca okuma [`IDoubleChartValue`](/slides/python-net/tr/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/tr/aspose.slides.charts/chartdatapoint/bubble_size/) | BubbleSize.<br/>            Yalnızca okuma [`IDoubleChartValue`](/slides/python-net/tr/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/tr/aspose.slides.charts/chartdatapoint/value/) | Value.<br/>            Yalnızca okuma [`IDoubleChartValue`](/slides/python-net/tr/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/tr/aspose.slides.charts/chartdatapoint/size_value/) | Grafiğin veri noktasının boyut değerini döndürür.<br/>            Treemap ve Sunburst grafiklerinde kullanılır. <br/>            Yalnızca okuma [`IDoubleChartValue`](/slides/python-net/tr/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/tr/aspose.slides.charts/chartdatapoint/color_value/) | Grafiğin veri noktasının renk değerini döndürür.<br/>            Harita grafiklerinde kullanılır. <br/>            Yalnızca okuma [`IDoubleChartValue`](/slides/python-net/tr/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/tr/aspose.slides.charts/chartdatapoint/error_bars_custom_values/) | Özel değer tipinde seri hata çubuğu değerlerini temsil eder.<br/>            Yalnızca okuma [`IErrorBarsCustomValues`](/slides/python-net/tr/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/tr/aspose.slides.charts/chartdatapoint/label/) | Label.<br/>            Yalnızca okuma [`IDataLabel`](/slides/python-net/tr/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/tr/aspose.slides.charts/chartdatapoint/is_bubble_3d/) | Balonların 3D etkisi uygulandığını belirtir.<br/>            Okuma/yazma **bool**. |
| [`explosion`](/slides/python-net/tr/aspose.slides.charts/chartdatapoint/explosion/) | Veri noktasının pasta grafiğinin merkezinden ne kadar taşınacağını belirtir.<br/>            Okuma/yazma **int**. |
| [`format`](/slides/python-net/tr/aspose.slides.charts/chartdatapoint/format/) | Biçimlendirme özelliklerini temsil eder.<br/>            Okuma/yazma [`IFormat`](/slides/python-net/tr/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/tr/aspose.slides.charts/chartdatapoint/marker/) | Bir veri işaretçisi belirtir.<br/>            Yalnızca okuma [`IMarker`](/slides/python-net/tr/aspose.slides.charts/imarker). |
| [`set_as_total`](/slides/python-net/tr/aspose.slides.charts/chartdatapoint/set_as_total/) | Veri noktasını toplam olarak ayarlar. Yalnızca Waterfall seri tipi için uygulanır. |
| [`related_legend_entry`](/slides/python-net/tr/aspose.slides.charts/chartdatapoint/related_legend_entry/) | Bu listedeki grafik tiplerinden birinde ilgili lejand girişinin özellikleri:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            Yalnızca okuma [`ILegendEntryProperties`](/slides/python-net/tr/aspose.slides.charts/ilegendentryproperties). |
| [`data_point_levels`](/slides/python-net/tr/aspose.slides.charts/chartdatapoint/data_point_levels/) | Veri noktası seviyelerinin kapsayıcısını döndürür. Treeamp ve Sunburst serileri için uygulanır.<br/>            Veri noktası seviyesi indekslemesi sıfır temellidir. |
| [`index`](/slides/python-net/tr/aspose.slides.charts/chartdatapoint/index/) |  |
| [`invert_if_negative`](/slides/python-net/tr/aspose.slides.charts/chartdatapoint/invert_if_negative/) | Veri noktasının değer negatif olduğunda renklerini tersine çevirmesini belirtir.<br/>            Okuma/yazma **bool**. |
| [`actual_x`](/slides/python-net/tr/aspose.slides.charts/chartdatapoint/actual_x/) | Grafik elemanının gerçek x konumunu (sol) grafik sol üst köşesine göre belirtir.<br/>            Gerçek değerleri almak için önce IChart.ValidateChartLayout() metodunu çağırın. <br/>            Okuma **float**. |
| [`actual_y`](/slides/python-net/tr/aspose.slides.charts/chartdatapoint/actual_y/) | Grafik elemanının gerçek üst konumunu grafik sol üst köşesine göre belirtir.<br/>            Gerçek değerleri almak için önce IChart.ValidateChartLayout() metodunu çağırın. <br/>            Okuma **float**. |
| [`actual_width`](/slides/python-net/tr/aspose.slides.charts/chartdatapoint/actual_width/) | Grafik elemanının gerçek genişliğini belirtir. Gerçek değerleri almak için önce IChart.ValidateChartLayout() metodunu çağırın. <br/>            Okuma **float**. |
| [`actual_height`](/slides/python-net/tr/aspose.slides.charts/chartdatapoint/actual_height/) | Grafik elemanının gerçek yüksekliğini belirtir. Gerçek değerleri almak için önce IChart.ValidateChartLayout() metodunu çağırın. <br/>            Okuma **float**. |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`remove(self)`](/slides/python-net/tr/aspose.slides.charts/chartdatapoint/remove/#) | DataPoint'i grafik serisinden kaldırır. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/tr/aspose.slides.charts/chartdatapoint/get_automatic_data_point_color/#) | Seri indeksi, veri noktası indeksi, ParentSeriesGroup.IsColorVaried özelliği ve grafik stili temelinde veri noktasının otomatik rengini döndürür.<br/>            FillType NotDefined olduğunda bu renk varsayılan olarak kullanılır. |

### Ayrıca Bakınız
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)