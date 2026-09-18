---
title: IAxis class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/iaxis/
---
## IAxis sınıfı

Grafik eksenini temsil eden nesneyi kapsüller.

IAxis türü aşağıdaki üyeleri ortaya koyar:

## Özellikler

| Property | Description |
| :- | :- |
| [`axis_between_categories`](/slides/python-net/tr/aspose.slides.charts/iaxis/axis_between_categories/) | Değer ekseninin kategori eksenini kategoriler arasında kesip kesmediğini temsil eder.<br/>            Bu özellik yalnızca kategori eksenlerine uygulanır ve 3-B eksenlerine uygulanmaz.<br/>            Okunur/yazılır **bool**. |
| [`cross_at`](/slides/python-net/tr/aspose.slides.charts/iaxis/cross_at/) | Eksen üzerindeki, dik eksenin onu kestiği noktayı temsil eder.<br/>            Okunur/yazılır **float**. |
| [`display_unit`](/slides/python-net/tr/aspose.slides.charts/iaxis/display_unit/) | Değer ekseni için gösterim birimlerinin ölçekleme değerini belirtir.<br/>            Okunur/yazılır [`DisplayUnitType`](/slides/python-net/tr/aspose.slides.charts/displayunittype). |
| [`actual_max_value`](/slides/python-net/tr/aspose.slides.charts/iaxis/actual_max_value/) | Eksen üzerindeki gerçek maksimum değeri belirtir. Gerçek değeri elde etmek için önceden IChart.ValidateChartLayout() yöntemini çağırın. |
| [`actual_min_value`](/slides/python-net/tr/aspose.slides.charts/iaxis/actual_min_value/) | Eksen üzerindeki gerçek minimum değeri belirtir. Gerçek değeri elde etmek için önceden IChart.ValidateChartLayout() yöntemini çağırın. |
| [`actual_major_unit`](/slides/python-net/tr/aspose.slides.charts/iaxis/actual_major_unit/) | Eksenin gerçek büyük birimini belirtir. Gerçek değeri elde etmek için önceden IChart.ValidateChartLayout() yöntemini çağırın. |
| [`actual_minor_unit`](/slides/python-net/tr/aspose.slides.charts/iaxis/actual_minor_unit/) | Eksenin gerçek küçük birimini belirtir. Gerçek değeri elde etmek için önceden IChart.ValidateChartLayout() yöntemini çağırın. |
| [`actual_major_unit_scale`](/slides/python-net/tr/aspose.slides.charts/iaxis/actual_major_unit_scale/) | Eksenin gerçek büyük birim ölçeğini belirtir. Gerçek değeri elde etmek için önceden IChart.ValidateChartLayout() yöntemini çağırın. |
| [`actual_minor_unit_scale`](/slides/python-net/tr/aspose.slides.charts/iaxis/actual_minor_unit_scale/) | Eksenin gerçek küçük birim ölçeğini belirtir. Gerçek değeri elde etmek için önceden IChart.ValidateChartLayout() yöntemini çağırın. |
| [`is_automatic_max_value`](/slides/python-net/tr/aspose.slides.charts/iaxis/is_automatic_max_value/) | Maksimum değerin otomatik olarak atanıp atanmadığını gösterir.<br/>             Okunur/yazılır **bool**. |
| [`max_value`](/slides/python-net/tr/aspose.slides.charts/iaxis/max_value/) | Değer eksenindeki maksimum değeri temsil eder.<br/>             Okunur/yazılır **float**. |
| [`minor_unit`](/slides/python-net/tr/aspose.slides.charts/iaxis/minor_unit/) | Tarih veya değer ekseni için küçük birimleri temsil eder.<br/>             Okunur/yazılır **float**. |
| [`is_automatic_minor_unit`](/slides/python-net/tr/aspose.slides.charts/iaxis/is_automatic_minor_unit/) | Eksenin küçük biriminin otomatik olarak atanıp atanmadığını gösterir.<br/>             Okunur/yazılır **bool**. |
| [`major_unit`](/slides/python-net/tr/aspose.slides.charts/iaxis/major_unit/) | Tarih veya değer ekseni için büyük birimleri temsil eder.<br/>             Okunur/yazılır **float**. |
| [`is_automatic_major_unit`](/slides/python-net/tr/aspose.slides.charts/iaxis/is_automatic_major_unit/) | Eksenin büyük biriminin otomatik olarak atanıp atanmadığını gösterir.<br/>            Okunur/yazılır **bool**. |
| [`is_automatic_min_value`](/slides/python-net/tr/aspose.slides.charts/iaxis/is_automatic_min_value/) | Minimum değerin otomatik olarak atanıp atanmadığını gösterir.<br/>             Okunur/yazılır **bool**. |
| [`min_value`](/slides/python-net/tr/aspose.slides.charts/iaxis/min_value/) | Değer eksenindeki minimum değeri temsil eder.<br/>             Okunur/yazılır **float**. |
| [`is_logarithmic`](/slides/python-net/tr/aspose.slides.charts/iaxis/is_logarithmic/) | Değer ekseni ölçek tipinin logaritmik olup olmadığını gösterir.<br/>             Okunur/yazılır **bool**. |
| [`log_base`](/slides/python-net/tr/aspose.slides.charts/iaxis/log_base/) | Logaritmik tabanı temsil eder. Varsayılan değer 10'dur.<br/>             Okunur/yazılır **float**. |
| [`is_plot_order_reversed`](/slides/python-net/tr/aspose.slides.charts/iaxis/is_plot_order_reversed/) | MS PowerPoint'in veri noktalarını sonuncudan birincine çizecek olup olmadığını gösterir.<br/>             Okunur/yazılır **bool**. |
| [`is_visible`](/slides/python-net/tr/aspose.slides.charts/iaxis/is_visible/) | Eksenin görünür olup olmadığını gösterir.<br/>             Okunur/yazılır **bool**. |
| [`major_tick_mark`](/slides/python-net/tr/aspose.slides.charts/iaxis/major_tick_mark/) | Belirtilen eksen için büyük tik işaretinin tipini temsil eder.<br/>             Okunur/yazılır [`TickMarkType`](/slides/python-net/tr/aspose.slides.charts/tickmarktype). |
| [`minor_tick_mark`](/slides/python-net/tr/aspose.slides.charts/iaxis/minor_tick_mark/) | Belirtilen eksen için küçük tik işaretinin tipini temsil eder.<br/>             Okunur/yazılır [`TickMarkType`](/slides/python-net/tr/aspose.slides.charts/tickmarktype). |
| [`tick_label_position`](/slides/python-net/tr/aspose.slides.charts/iaxis/tick_label_position/) | Belirtilen eksende tik etiketi konumunu temsil eder.<br/>             Okunur/yazılır [`TickLabelPositionType`](/slides/python-net/tr/aspose.slides.charts/ticklabelpositiontype). |
| [`major_unit_scale`](/slides/python-net/tr/aspose.slides.charts/iaxis/major_unit_scale/) | Tarih ekseni için büyük birim ölçeğini temsil eder.<br/>             Okunur/yazılır [`TimeUnitType`](/slides/python-net/tr/aspose.slides.charts/timeunittype). |
| [`minor_unit_scale`](/slides/python-net/tr/aspose.slides.charts/iaxis/minor_unit_scale/) | Tarih ekseni için büyük birim ölçeğini temsil eder.<br/>             Okunur/yazılır [`TimeUnitType`](/slides/python-net/tr/aspose.slides.charts/timeunittype). |
| [`base_unit_scale`](/slides/python-net/tr/aspose.slides.charts/iaxis/base_unit_scale/) | Tarih ekseninde temsil edilen en küçük zaman birimini belirtir.<br/>            Okunur/yazılır [`TimeUnitType`](/slides/python-net/tr/aspose.slides.charts/timeunittype). |
| [`minor_grid_lines_format`](/slides/python-net/tr/aspose.slides.charts/iaxis/minor_grid_lines_format/) | Bir grafik eksenindeki küçük ızgara çizgileri biçimini temsil eder.<br/>             Sadece okunur [`IChartLinesFormat`](/slides/python-net/tr/aspose.slides.charts/ichartlinesformat). |
| [`major_grid_lines_format`](/slides/python-net/tr/aspose.slides.charts/iaxis/major_grid_lines_format/) | Bir grafik eksenindeki büyük ızgara çizgileri biçimini temsil eder.<br/>             Sadece okunur [`IChartLinesFormat`](/slides/python-net/tr/aspose.slides.charts/ichartlinesformat). |
| [`show_minor_grid_lines`](/slides/python-net/tr/aspose.slides.charts/iaxis/show_minor_grid_lines/) | Küçük ızgara çizgilerinin gösterilip gösterilmediğini temsil eder.<br/>             Sadece okunur **bool**. |
| [`show_major_grid_lines`](/slides/python-net/tr/aspose.slides.charts/iaxis/show_major_grid_lines/) | Büyük ızgara çizgilerinin gösterilip gösterilmediğini temsil eder.<br/>             Sadece okunur **bool**. |
| [`format`](/slides/python-net/tr/aspose.slides.charts/iaxis/format/) | Eksenin biçimini temsil eder.<br/>             Sadece okunur [`IAxisFormat`](/slides/python-net/tr/aspose.slides.charts/iaxisformat). |
| [`title`](/slides/python-net/tr/aspose.slides.charts/iaxis/title/) | Eksenin başlığını alır.<br/>             Sadece okunur [`IChartTitle`](/slides/python-net/tr/aspose.slides.charts/icharttitle). |
| [`cross_type`](/slides/python-net/tr/aspose.slides.charts/iaxis/cross_type/) | Diğer eksenin kesiştiği belirtilen eksendeki CrossType'ı temsil eder.<br/>             Okunur/yazılır [`CrossesType`](/slides/python-net/tr/aspose.slides.charts/crossestype). |
| [`position`](/slides/python-net/tr/aspose.slides.charts/iaxis/position/) | Eksenin konumunu temsil eder.<br/>             Okunur/yazılır [`AxisPositionType`](/slides/python-net/tr/aspose.slides.charts/axispositiontype). |
| [`has_title`](/slides/python-net/tr/aspose.slides.charts/iaxis/has_title/) | Bir eksenin görünür bir başlığı olup olmadığını belirler.<br/>            Okunur/yazılır **bool**. |
| [`number_format`](/slides/python-net/tr/aspose.slides.charts/iaxis/number_format/) | Eksen Etiketleri için format dizesini temsil eder.<br/>            Okunur/yazılır **str**. |
| [`is_number_format_linked_to_source`](/slides/python-net/tr/aspose.slides.charts/iaxis/is_number_format_linked_to_source/) | Formatın bağlantılı kaynak verilere ait olup olmadığını gösterir.<br/>            Okunur/yazılır **bool**. |
| [`tick_label_rotation_angle`](/slides/python-net/tr/aspose.slides.charts/iaxis/tick_label_rotation_angle/) | Tik etiketlerinin döndürme açısını temsil eder<br/>            Okunur/yazılır **float**. |
| [`tick_label_spacing`](/slides/python-net/tr/aspose.slides.charts/iaxis/tick_label_spacing/) | Çizilen etiketler arasındaki atlanacak tik etiketi sayısını belirtir.<br/>            Okunur/yazılır **int**. |
| [`is_automatic_tick_label_spacing`](/slides/python-net/tr/aspose.slides.charts/iaxis/is_automatic_tick_label_spacing/) | Otomatik tik etiketi aralığı değerini belirtir. False ise: TickLabelSpacing özelliğini kullanın.<br/>            Okunur/yazılır **bool**. |
| [`tick_marks_spacing`](/slides/python-net/tr/aspose.slides.charts/iaxis/tick_marks_spacing/) | Bir sonraki tik işaretinin çizilmeden önce kaç tane atlanacağını belirtir.<br/>            Kategori veya seriler eksenine uygulanır.<br/>            Okunur/yazılır **int**. |
| [`is_automatic_tick_marks_spacing`](/slides/python-net/tr/aspose.slides.charts/iaxis/is_automatic_tick_marks_spacing/) | Otomatik tik işareti aralığını belirtir. False ise: TickMarksSpacing özelliğini kullanın.<br/>            Okunur/yazılır **bool**. |
| [`label_offset`](/slides/python-net/tr/aspose.slides.charts/iaxis/label_offset/) | Etiketlerin eksenden uzaklığını belirtir. Kategori veya tarih eksenine uygulanır. Değer 0% ile 1000% arasında olmalıdır.<br/>            Okunur/yazılır **int**. |
| [`category_axis_type`](/slides/python-net/tr/aspose.slides.charts/iaxis/category_axis_type/) | Kategori ekseninin tipini belirtir.<br/>            Okunur/yazılır [`IAxis.category_axis_type`](/slides/python-net/tr/aspose.slides.charts/iaxis/category_axis_type). |
| [`aggregation_type`](/slides/python-net/tr/aspose.slides.charts/iaxis/aggregation_type/) | Kategori ekseninin toplama tipini (binleme) temsil eder. Kategoriye uygulanır. Yalnızca Histogram veya HistogramPareto serileriyle kullanılır. |
| [`bin_width`](/slides/python-net/tr/aspose.slides.charts/iaxis/bin_width/) | AggregationType özelliği AxisAggregationType.ByBinWidth olarak ayarlandığında bin genişliğini belirtir.<br/>            Kategori eksenlerine uygulanır. Yalnızca Histogram veya HistogramPareto serileriyle kullanılır. |
| [`number_of_bins`](/slides/python-net/tr/aspose.slides.charts/iaxis/number_of_bins/) | AggregationType özelliği AxisAggregationType.ByNumberOfBins olarak ayarlandığında bin sayılarını belirtir.<br/>            Kategori eksenlerine uygulanır. Yalnızca Histogram veya HistogramPareto serileriyle kullanılır. |
| [`is_overflow_bin`](/slides/python-net/tr/aspose.slides.charts/iaxis/is_overflow_bin/) | Taşma bininin uygulanıp uygulanmadığını belirtir. Taşma bin değeri ayarlamak için IsAutomaticOverflowBin ve OverflowBin kullanın. |
| [`is_automatic_overflow_bin`](/slides/python-net/tr/aspose.slides.charts/iaxis/is_automatic_overflow_bin/) | Otomatik taşma bin değerini belirtir. False ise: OverflowBin özelliğini kullanın. |
| [`overflow_bin`](/slides/python-net/tr/aspose.slides.charts/iaxis/overflow_bin/) | Taşma bin özelleştirilmiş değerini belirtir. IsAutomaticOverflowBin özelliği false ve IsOverflowBin özelliği true olduğunda uygulanır. |
| [`is_underflow_bin`](/slides/python-net/tr/aspose.slides.charts/iaxis/is_underflow_bin/) | Azalma bininin uygulanıp uygulanmadığını belirtir. Azalma bin değerini ayarlamak için IsAutomaticUnderflowBin ve UnderflowBin kullanın. |
| [`is_automatic_underflow_bin`](/slides/python-net/tr/aspose.slides.charts/iaxis/is_automatic_underflow_bin/) | Otomatik azalma bin değerini belirtir. False ise: UnderflowBin özelliğini kullanın. |
| [`underflow_bin`](/slides/python-net/tr/aspose.slides.charts/iaxis/underflow_bin/) | Azalma bin özelleştirilmiş değerini belirtir. IsAutomaticUnderflowBin özelliği false ve IsUnderflowBin özelliği true olduğunda uygulanır. |
| [`text_format`](/slides/python-net/tr/aspose.slides.charts/iaxis/text_format/) |  |
| [`chart`](/slides/python-net/tr/aspose.slides.charts/iaxis/chart/) |  |
| [`slide`](/slides/python-net/tr/aspose.slides.charts/iaxis/slide/) |  |
| [`presentation`](/slides/python-net/tr/aspose.slides.charts/iaxis/presentation/) |  |

## Yöntemler

| Method | Description |
| :- | :- |
| [`set_category_axis_type_automatically(self)`](/slides/python-net/tr/aspose.slides.charts/iaxis/set_category_axis_type_automatically/#) | Eksen verilerine dayanarak otomatik olarak belirlenen bir değerle IAxis.CategoryAxisType özelliğini ayarlar. |


### Ayrıca Bakınız
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)