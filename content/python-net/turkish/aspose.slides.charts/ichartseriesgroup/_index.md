---
title: IChartSeriesGroup class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup sınıf

Seri grubunu temsil eder.

IChartSeriesGroup türü aşağıdaki üyeleri gösterir:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`type`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroup/type/) | Bu seri grubunun tipini döndürür.<br/>            Salt okunur [`CombinableSeriesTypesGroup`](/slides/python-net/tr/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroup/plot_on_second_axis/) | Bu grubun serisinin ikincil eksende çizilip çizilmediğini gösterir.<br/>            Salt okunur **bool**. |
| [`series`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroup/series/) | Grafik serilerinin yalnızca okunabilir bir koleksiyonunu döndürür.<br/>            Salt okunur [`IChartSeriesReadonlyCollection`](/slides/python-net/tr/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroup/up_down_bars/) | Çizgi veya Stok grafiğinin yukarı/aşağı çubuklarına erişim sağlar.<br/>            Salt okunur [`IUpDownBarsManager`](/slides/python-net/tr/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroup/gap_width/) | Çubuk veya sütun kümeleri arasındaki boşluğu, çubuk veya sütun genişliğinin yüzdesi olarak belirtir.<br/>            Okunur/yazılabilir **int**. |
| [`gap_depth`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroup/gap_depth/) | 3B bir grafikte veri serileri arasındaki mesafeyi, işaretleyici genişliğinin yüzdesi olarak döndürür veya ayarlar.<br/>            Okunur/yazılabilir **int**. |
| [`first_slice_angle`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroup/first_slice_angle/) | İlk pasta veya halka grafik diliminin açısını alır veya ayarlar, <br/>            derece cinsinden (yukarıdan saat yönünde, 0 ila 360 derece).<br/>            Okunur/yazılabilir **int**. |
| [`is_color_varied`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroup/is_color_varied/) | Serideki her veri işaretleyicisinin farklı bir renge sahip olacağını belirtir.<br/>            Okunur/yazılabilir **bool**. |
| [`has_series_lines`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroup/has_series_lines/) | Grafik serileri çizgileri varsa true olur. Yığılmış çubuk ve OfPie grafiklerine uygulanır.<br/>            Okunur/yazılabilir **bool**. |
| [`overlap`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroup/overlap/) | 2D grafiklerde çubuk ve sütunların ne kadar üst üste geleceğini yüzde olarak belirtir ( -%100 ile %100 arasında).<br/>             - -%100: Azami boşluk (çubuklar tamamen ayrılmıştır).<br/>             - %0: Çubuklar üst üste gelmeden yan yana yerleştirilir.<br/>             - %100: Azami üst üste gelme (çubuklar birbirinin tamamen üstüne gelir).<br/>             Bu özellik Okunur/yazılabilir **int**. |
| [`second_pie_size`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroup/second_pie_size/) | Pie-of-pie grafiğinin veya bar-of-pie grafiğinin ikinci pasta ya da çubuğunun boyutunu, ilk pastanın boyutunun yüzdesi olarak belirtir (5 ile 200 yüzde arasında olabilir).<br/>            Okunur/yazılabilir **int**. |
| [`pie_split_position`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroup/pie_split_position/) | Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta ya da çubukta yer alacak veri noktalarını belirlemek için kullanılacak bir değeri belirtir. <br/>            PieSplitBy özelliğiyle birlikte kullanılır.<br/>            Okunur/yazılabilir **float**. |
| [`pie_split_by`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroup/pie_split_by/) | Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta ya da çubukta yer alacak veri noktalarının nasıl belirleneceğini belirtir.<br/>            Okunur/yazılabilir [`PieSplitType`](/slides/python-net/tr/aspose.slides.charts/piesplittype). |
| [`pie_split_custom_points`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroup/pie_split_custom_points/) | Özel bölme bilgisi, özel bölmesi olan bir pie-of-pie veya bar-of-pie grafiği için.<br/>            Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta ya da çubukta çizilecek veri noktalarını içerir.<br/>            Salt okunur [`IPieSplitCustomPointCollection`](/slides/python-net/tr/aspose.slides.charts/ipiesplitcustompointcollection). |
| [`doughnut_hole_size`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroup/doughnut_hole_size/) | Donut grafiğindeki deliğin boyutunu belirtir (çizim alanının boyutunun %10 ile %90 arasında olabilir).<br/>            Okunur/yazılabilir **int**. |
| [`bubble_size_scale`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroup/bubble_size_scale/) | Balon grafiği için ölçek faktörünü belirtir (varsayılan boyutun %0 ile %300 arasında olabilir).<br/>            Okunur/yazılabilir **int**. |
| [`hi_low_lines_format`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroup/hi_low_lines_format/) | HiLowLines biçimini belirtir. <br/>            HiLowLines, HiLowClose, OpenHiLowClose, VolumeHiLowClose ve VolumeOpenHiLowClose grafik tipleriyle uygulanır. |
| [`bubble_size_representation`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroup/bubble_size_representation/) | Balon grafiğinde balon boyutu değerlerinin nasıl temsil edileceğini belirtir.<br/>            Okunur/yazılabilir [`BubbleSizeRepresentationType`](/slides/python-net/tr/aspose.slides.charts/bubblesizerepresentationtype). |
| [`chart`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroup/chart/) |  |
| [`slide`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroup/presentation/) |  |

Belirtilen indeksteki öğeyi alır.

## Dizinleyici

| Ad | Açıklama |
| :- | :- |
| [`[index]`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroup/__getitem__/) |  |

### Açıklamalar

1) ChartSeriesGroupCollection sınıfı ve CombinableSeriesTypesGroup enumu için özet ve açıklamalara bakınız.  
2) Seri grubu, grup içindeki her seri için ortak olan bazı seri özelliklerini içerir ("seri grup özellikleri"). "Seri grup özellikleri" ChartSeriesGroup sınıfında Okunur/yazılabilir. "Seri grup özellikleri"nin her biri ChartSeries sınıfında salt okunur bir projeksiyona sahip olabilir.

### Ayrıca Bakınız
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)