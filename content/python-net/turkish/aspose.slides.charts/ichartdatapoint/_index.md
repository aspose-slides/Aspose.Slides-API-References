---
title: IChartDataPoint class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint sınıf

Seri veri noktasını temsil eder.

IChartDataPoint türü aşağıdaki üyeleri sunar:

## Özellikler

| Ö

zellik | Açıklama |
| :- | :- |
| [`x_value`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/x_value/) | Grafi

k veri noktasının x değerini döndürür.<br/>            Yalnızca okuma [`IStringOrDoubleChartValue`](/slides/python-net/tr/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/y_value/) | Grafik veri noktasının y değerini döndürür.<br/>            Yalnızca okuma [`IDoubleChartValue`](/slides/python-net/tr/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/bubble_size/) | Grafik veri noktasının baloncuk boyutunu döndürür.<br/>            Yalnızca okuma [`IDoubleChartValue`](/slides/python-net/tr/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/value/) | Grafik veri noktasının değerini döndürür.<br/>            Yalnızca okuma [`IDoubleChartValue`](/slides/python-net/tr/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/size_value/) | Grafik veri noktasının boyut değerini döndürür.<br/>            Treemap ve Sunburst grafiklerinde kullanılır.<br/>            Yalnızca okuma [`IDoubleChartValue`](/slides/python-net/tr/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/color_value/) | Grafik veri noktasının renk değerini döndürür.<br/>            Harita grafiklerinde kullanılır.<br/>            Yalnızca okuma [`IDoubleChartValue`](/slides/python-net/tr/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/error_bars_custom_values/) | Özel değer türünde seri hata çubukları değerlerini temsil eder.<br/>            Yalnızca okuma [`IErrorBarsCustomValues`](/slides/python-net/tr/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/label/) | Grafik veri noktasının etiketini temsil eder.<br/>            Yalnızca okuma [`IDataLabel`](/slides/python-net/tr/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/is_bubble_3d/) | Baloncukların 3D etkisine sahip olacağını belirtir.<br/>            Okuma/Yazma **bool**. |
| [`explosion`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/explosion/) | Veri noktasının pasta grafiğinin merkezinden ne kadar taşınacağını belirtir.<br/>            Okuma/Yazma **int**. |
| [`format`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/format/) | Biçimlendirme özelliklerini temsil eder.<br/>            Okuma/Yazma [`IFormat`](/slides/python-net/tr/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/marker/) | Bir veri işaretleyicisi belirtir.<br/>            Yalnızca okuma [`IMarker`](/slides/python-net/tr/aspose.slides.charts/imarker). |
| [`related_legend_entry`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/related_legend_entry/) | Bu listedeki grafik türlerinden biri için ilgili lejand girdisinin özellikleri:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPi e3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            Yalnızca okuma [`ILegendEntryProperties`](/slides/python-net/tr/aspose.slides.charts/ilegendentryproperties). |
| [`set_as_total`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/set_as_total/) | Veri noktasını toplam olarak ayarlar. Yalnızca Waterfall seri türünde uygulanır. |
| [`invert_if_negative`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/invert_if_negative/) | Değer negatif olduğunda veri noktasının renklerini tersine çevireceğini belirtir.<br/>            Okuma/Yazma **bool**. |
| [`data_point_levels`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/data_point_levels/) | Veri noktası seviyelerinin kapsayıcısını döndürür. Treeamp ve Sunburst serileri için uygulanır.<br/>            Veri noktası seviyesi indekslemesi sıfır tabanlıdır. |
| [`index`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/index/) | Bu veri noktasının ebeveynin çocuk koleksiyonunun hangisine uygulanacağını belirler.<br/>            Okuma **int**. |
| [`actual_x`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/actual_x/) |  |
| [`actual_y`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/actual_y/) |  |
| [`actual_width`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/actual_width/) |  |
| [`actual_height`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/actual_height/) |  |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`remove(self)`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/remove/#) | Grafik serisinden DataPoint'i kaldırır. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/get_automatic_data_point_color/#) | Seri indeksi, veri noktası indeksi, ParentSeriesGroup.IsColorVaried özelliği ve grafik stiline göre veri noktasının otomatik rengini döndürür.<br/>            FillType NotDefined ise bu renk varsayılan olarak kullanılır. |

### İlgili
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)