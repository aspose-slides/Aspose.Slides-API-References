---
title: Axis class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/axis/
---
## Axis sınıfı

chart'ın eksenini temsil eden nesneyi kapsüller.

Axis tipi aşağıdaki üyelere erişim sağlar:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`chart`](/slides/python-net/tr/aspose.slides.charts/axis/chart/) | Üst chart'ı döndürür.<br/>            Salt okunur [`IChart`](/slides/python-net/tr/aspose.slides.charts/ichart). |
| [`axis_between_categories`](/slides/python-net/tr/aspose.slides.charts/axis/axis_between_categories/) | Değer ekseninin kategori eksenini kategoriler arasında kesip kesmediğini temsil eder.<br/>             Bu özellik yalnızca kategori eksenlerine uygulanır ve 3-D chart'lara uygulanmaz.<br/>             Okunur/yazılabilir **bool**. |
| [`category_axis_type`](/slides/python-net/tr/aspose.slides.charts/axis/category_axis_type/) | Kategori ekseninin tipini belirtir.<br/>            Okunur/yazılabilir [`CategoryAxisType`](/slides/python-net/tr/aspose.slides.charts/categoryaxistype). |
| [`cross_at`](/slides/python-net/tr/aspose.slides.charts/axis/cross_at/) | Eksenin, dik eksenin onu kestiği noktayı temsil eder.<br/>            Okunur/yazılabilir **float**. |
| [`display_unit`](/slides/python-net/tr/aspose.slides.charts/axis/display_unit/) | Değer ekseni için görüntü birimlerinin ölçekleme değerini belirtir.<br/>            Okunur/yazılabilir [`DisplayUnitType`](/slides/python-net/tr/aspose.slides.charts/displayunittype). |
| [`actual_max_value`](/slides/python-net/tr/aspose.slides.charts/axis/actual_max_value/) | Eksen üzerindeki gerçek maksimum değeri belirtir. Gerçek değeri almak için daha önce IChart.ValidateChartLayout() metodunu çağırın. |
| [`actual_min_value`](/slides/python-net/tr/aspose.slides.charts/axis/actual_min_value/) | Eksen üzerindeki gerçek minimum değeri belirtir. Gerçek değeri almak için daha önce IChart.ValidateChartLayout() metodunu çağırın. |
| [`actual_major_unit`](/slides/python-net/tr/aspose.slides.charts/axis/actual_major_unit/) | Eksenin gerçek temel birimini belirtir. Gerçek değeri almak için daha önce IChart.ValidateChartLayout() metodunu çağırın. |
| [`actual_minor_unit`](/slides/python-net/tr/aspose.slides.charts/axis/actual_minor_unit/) | Eksenin gerçek yan birimini (minor unit) belirtir. Gerçek değeri almak için daha önce IChart.ValidateChartLayout() metodunu çağırın. |
| [`actual_major_unit_scale`](/slides/python-net/tr/aspose.slides.charts/axis/actual_major_unit_scale/) | Eksenin gerçek temel birim ölçeğini belirtir. Gerçek değeri almak için daha önce IChart.ValidateChartLayout() metodunu çağırın. |
| [`actual_minor_unit_scale`](/slides/python-net/tr/aspose.slides.charts/axis/actual_minor_unit_scale/) | Eksenin gerçek yan birim ölçeğini belirtir. Gerçek değeri almak için daha önce IChart.ValidateChartLayout() metodunu çağırın. |
| [`is_automatic_max_value`](/slides/python-net/tr/aspose.slides.charts/axis/is_automatic_max_value/) | Maksimum değerin otomatik olarak atanıp atanmadığını gösterir.<br/>            Okunur/yazılabilir **bool**. |
| [`max_value`](/slides/python-net/tr/aspose.slides.charts/axis/max_value/) | Değer eksenindeki maksimum değeri temsil eder.<br/>            Okunur/yazılabilir **float**. |
| [`minor_unit`](/slides/python-net/tr/aspose.slides.charts/axis/minor_unit/) | Tarih veya değer ekseni için yan birimleri (minor units) temsil eder.<br/>            Okunur/yazılabilir **float**. |
| [`is_automatic_minor_unit`](/slides/python-net/tr/aspose.slides.charts/axis/is_automatic_minor_unit/) | Eksenin yan biriminin otomatik olarak atanıp atanmadığını gösterir.<br/>            Okunur/yazılabilir **bool**. |
| [`major_unit`](/slides/python-net/tr/aspose.slides.charts/axis/major_unit/) | Tarih veya değer ekseni için temel birimleri temsil eder.<br/>            Okunur/yazılabilir **float**. |
| [`is_automatic_major_unit`](/slides/python-net/tr/aspose.slides.charts/axis/is_automatic_major_unit/) | Eksenin temel biriminin otomatik olarak atanıp atanmadığını gösterir.<br/>            Okunur/yazılabilir **bool**. |
| [`is_automatic_min_value`](/slides/python-net/tr/aspose.slides.charts/axis/is_automatic_min_value/) | Minimum değerin otomatik olarak atanıp atanmadığını gösterir.<br/>            Okunur/yazılabilir **bool**. |
| [`min_value`](/slides/python-net/tr/aspose.slides.charts/axis/min_value/) | Değer eksenindeki minimum değeri temsil eder.<br/>            Okunur/yazılabilir **float**. |
| [`is_logarithmic`](/slides/python-net/tr/aspose.slides.charts/axis/is_logarithmic/) | Değer ekseninin ölçek tipinin logaritmik olup olmadığını temsil eder.<br/>            Okunur/yazılabilir **bool**. |
| [`log_base`](/slides/python-net/tr/aspose.slides.charts/axis/log_base/) | Logaritmik tabanı temsil eder. Varsayılan değer 10'dur.<br/>            Okunur/yazılabilir **float**. |
| [`is_plot_order_reversed`](/slides/python-net/tr/aspose.slides.charts/axis/is_plot_order_reversed/) | MS PowerPoint'in veri noktalarını sondan ilkine çizep çizmediğini temsil eder.<br/>            Okunur/yazılabilir **bool**. |
| [`is_visible`](/slides/python-net/tr/aspose.slides.charts/axis/is_visible/) | Eksenin görünür olup olmadığını temsil eder.<br/>            Okunur/yazılabilir **bool**. |
| [`major_tick_mark`](/slides/python-net/tr/aspose.slides.charts/axis/major_tick_mark/) | Belirtilen eksen için temel işaret (major tick mark) tipini temsil eder.<br/>            Okunur/yazılabilir [`TickMarkType`](/slides/python-net/tr/aspose.slides.charts/tickmarktype). |
| [`minor_tick_mark`](/slides/python-net/tr/aspose.slides.charts/axis/minor_tick_mark/) | Belirtilen eksen için yan işaret (minor tick mark) tipini temsil eder.<br/>            Okunur/yazılabilir [`TickMarkType`](/slides/python-net/tr/aspose.slides.charts/tickmarktype). |
| [`tick_label_position`](/slides/python-net/tr/aspose.slides.charts/axis/tick_label_position/) | Belirtilen eksende işaret etiketi konumunu temsil eder.<br/>            Okunur/yazılabilir [`TickLabelPositionType`](/slides/python-net/tr/aspose.slides.charts/ticklabelpositiontype). |
| [`major_unit_scale`](/slides/python-net/tr/aspose.slides.charts/axis/major_unit_scale/) | Tarih ekseni için temel birim ölçeğini temsil eder.<br/>            Okunur/yazılabilir [`TimeUnitType`](/slides/python-net/tr/aspose.slides.charts/timeunittype). |
| [`minor_unit_scale`](/slides/python-net/tr/aspose.slides.charts/axis/minor_unit_scale/) | Tarih ekseni için temel birim ölçeğini temsil eder.<br/>            Okunur/yazılabilir [`TimeUnitType`](/slides/python-net/tr/aspose.slides.charts/timeunittype). |
| [`base_unit_scale`](/slides/python-net/tr/aspose.slides.charts/axis/base_unit_scale/) | Tarih ekseninde temsil edilen en küçük zaman birimini belirtir.<br/>            Okunur/yazılabilir [`TimeUnitType`](/slides/python-net/tr/aspose.slides.charts/timeunittype). |
| [`minor_grid_lines_format`](/slides/python-net/tr/aspose.slides.charts/axis/minor_grid_lines_format/) | Chart eksenindeki yan ızgara çizgileri biçimini temsil eder.<br/>            Salt okunur [`IChartLinesFormat`](/slides/python-net/tr/aspose.slides.charts/ichartlinesformat). |
| [`major_grid_lines_format`](/slides/python-net/tr/aspose.slides.charts/axis/major_grid_lines_format/) | Chart eksenindeki temel ızgara çizgileri biçimini temsil eder.<br/>            Salt okunur [`IChartLinesFormat`](/slides/python-net/tr/aspose.slides.charts/ichartlinesformat). |
| [`show_minor_grid_lines`](/slides/python-net/tr/aspose.slides.charts/axis/show_minor_grid_lines/) | Yan ızgara çizgisini gizlemek için MinorGridLinesFormat.Line.FillFormat.FillType'ı FillType.NoFill olarak ayarlayın.<br/>            Salt okunur **bool**. |
| [`show_major_grid_lines`](/slides/python-net/tr/aspose.slides.charts/axis/show_major_grid_lines/) | Temel ızgara çizgisini gizlemek için MajorGridLinesFormat.Line.FillFormat.FillType'ı FillType.NoFill olarak ayarlayın.<br/>            Salt okunur **bool**. |
| [`format`](/slides/python-net/tr/aspose.slides.charts/axis/format/) | Eksenin biçimini temsil eder.<br/>            Salt okunur [`IAxisFormat`](/slides/python-net/tr/aspose.slides.charts/iaxisformat). |
| [`text_format`](/slides/python-net/tr/aspose.slides.charts/axis/text_format/) | Metnin biçimini temsil eder.<br/>            Salt okunur [`IChartTextFormat`](/slides/python-net/tr/aspose.slides.charts/icharttextformat). |
| [`title`](/slides/python-net/tr/aspose.slides.charts/axis/title/) | Eksenin başlığını alır.<br/>            Salt okunur [`IChartTitle`](/slides/python-net/tr/aspose.slides.charts/icharttitle). |
| [`cross_type`](/slides/python-net/tr/aspose.slides.charts/axis/cross_type/) | Belirtilen eksende diğer eksenin kesiştiği noktadaki CrossType'ı temsil eder.<br/>            Okunur/yazılabilir [`CrossesType`](/slides/python-net/tr/aspose.slides.charts/crossestype). |
| [`position`](/slides/python-net/tr/aspose.slides.charts/axis/position/) | Eksenin konumunu temsil eder.<br/>            Okunur/yazılabilir [`AxisPositionType`](/slides/python-net/tr/aspose.slides.charts/axispositiontype). |
| [`has_title`](/slides/python-net/tr/aspose.slides.charts/axis/has_title/) | Bir eksenin görünür başlığı olup olmadığını belirler.<br/>            Okunur/yazılabilir **bool**. |
| [`number_format`](/slides/python-net/tr/aspose.slides.charts/axis/number_format/) | Axis Labels için biçim dizesini temsil eder.<br/>            Okunur/yazılabilir **str**. |
| [`is_number_format_linked_to_source`](/slides/python-net/tr/aspose.slides.charts/axis/is_number_format_linked_to_source/) | Biçimin bağlanmış kaynak veri olup olmadığını gösterir.<br/>            Okunur/yazılabilir **bool**. |
| [`tick_label_rotation_angle`](/slides/python-net/tr/aspose.slides.charts/axis/tick_label_rotation_angle/) | İşaret etiketlerinin döndürme açısını temsil eder.<br/>            Okunur/yazılabilir **float**. |
| [`tick_label_spacing`](/slides/python-net/tr/aspose.slides.charts/axis/tick_label_spacing/) | Çizilen etiketler arasında atlanacak işaret etiketi sayısını belirtir. Kategori veya seri eksenlerine uygulanır.<br/>            Okunur/yazılabilir **int**. |
| [`is_automatic_tick_label_spacing`](/slides/python-net/tr/aspose.slides.charts/axis/is_automatic_tick_label_spacing/) | Otomatik işaret etiketi aralığı değerini belirtir. false ise: TickLabelSpacing özelliğini kullanın.<br/>            Okunur/yazılabilir **bool**. |
| [`tick_marks_spacing`](/slides/python-net/tr/aspose.slides.charts/axis/tick_marks_spacing/) | Bir sonraki işaret çizilmeden önce kaç işaret atlanacağını belirtir.<br/>            Kategori veya seri eksenlerine uygulanır.<br/>            Okunur/yazılabilir **int**. |
| [`is_automatic_tick_marks_spacing`](/slides/python-net/tr/aspose.slides.charts/axis/is_automatic_tick_marks_spacing/) | Otomatik işaret aralığı değerini belirtir. false ise: TickMarksSpacing özelliğini kullanın.<br/>            Okunur/yazılabilir **bool**. |
| [`label_offset`](/slides/python-net/tr/aspose.slides.charts/axis/label_offset/) | Etiketlerin eksene olan mesafesini belirtir. Kategori veya tarih eksenlerine uygulanır. Değer 0% ile 1000% arasında olmalıdır.<br/>            Okunur/yazılabilir **int**. |
| [`aggregation_type`](/slides/python-net/tr/aspose.slides.charts/axis/aggregation_type/) | Kategori ekseninin toplama tipini (binning) temsil eder. Kategorilere uygulanır. Yalnızca Histogram veya HistogramPareto serileriyle kullanılır. |
| [`bin_width`](/slides/python-net/tr/aspose.slides.charts/axis/bin_width/) | AggregationType özelliği AxisAggregationType.ByBinWidth olarak ayarlandığında kutu genişliğini belirtir.<br/>            Kategori eksenlerine uygulanır. Yalnızca Histogram veya HistogramPareto serileriyle kullanılır. |
| [`number_of_bins`](/slides/python-net/tr/aspose.slides.charts/axis/number_of_bins/) | AggregationType özelliği AxisAggregationType.ByNumberOfBins olarak ayarlandığında kutu sayısını belirtir.<br/>            Kategori eksenlerine uygulanır. Yalnızca Histogram veya HistogramPareto serileriyle kullanılır. |
| [`is_overflow_bin`](/slides/python-net/tr/aspose.slides.charts/axis/is_overflow_bin/) | Taşma kutusunun uygulanıp uygulanmadığını belirtir. Taşma kutusu değerini ayarlamak için IsAutomaticOverflowBin ve OverflowBin kullanın. |
| [`is_automatic_overflow_bin`](/slides/python-net/tr/aspose.slides.charts/axis/is_automatic_overflow_bin/) | Otomatik taşma kutusu değerini belirtir. false ise: OverflowBin özelliğini kullanın. |
| [`overflow_bin`](/slides/python-net/tr/aspose.slides.charts/axis/overflow_bin/) | Taşma kutusu özel değerini belirtir. IsAutomaticOverflowBin özelliği false ve IsOverflowBin özelliği true olduğunda uygulanır. |
| [`is_underflow_bin`](/slides/python-net/tr/aspose.slides.charts/axis/is_underflow_bin/) | Alt taşma kutusunun uygulanıp uygulanmadığını belirtir. Alt taşma kutusu değerini ayarlamak için IsAutomaticUnderflowBin ve UnderflowBin kullanın. |
| [`is_automatic_underflow_bin`](/slides/python-net/tr/aspose.slides.charts/axis/is_automatic_underflow_bin/) | Otomatik alt taşma kutusu değerini belirtir. false ise: UnderflowBin özelliğini kullanın. |
| [`underflow_bin`](/slides/python-net/tr/aspose.slides.charts/axis/underflow_bin/) | Alt taşma kutusu özel değerini belirtir. IsAutomaticUnderflowBin özelliği false ve IsUnderflowBin özelliği true olduğunda uygulanır. |
| [`slide`](/slides/python-net/tr/aspose.slides.charts/axis/slide/) |  |
| [`presentation`](/slides/python-net/tr/aspose.slides.charts/axis/presentation/) |  |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`set_category_axis_type_automatically(self)`](/slides/python-net/tr/aspose.slides.charts/axis/set_category_axis_type_automatically/#) | IAxis.CategoryAxisType özelliğini eksen verilerine dayalı otomatik olarak belirlenen bir değerle ayarlar. |

### Ayrıca Bakınız
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)