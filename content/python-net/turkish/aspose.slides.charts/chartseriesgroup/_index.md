---
title: ChartSeriesGroup class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup sınıf

Seri grubunu temsil eder.

ChartSeriesGroup türü aşağıdaki üyeleri ortaya çıkar:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`type`](/slides/python-net/tr/aspose.slides.charts/chartseriesgroup/type/) | Bu seri grubunun tipini döndürür.<br/>            Salt Okunur [`CombinableSeriesTypesGroup`](/slides/python-net/tr/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/tr/aspose.slides.charts/chartseriesgroup/plot_on_second_axis/) | Bu grubun serilerinin ikincil eksende çizilip çizilmediğini gösterir.<br/>            Salt Okunur **bool**. |
| [`series`](/slides/python-net/tr/aspose.slides.charts/chartseriesgroup/series/) | Seri koleksiyonunu döndürür.<br/>            Salt Okunur [`IChartSeriesReadonlyCollection`](/slides/python-net/tr/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/tr/aspose.slides.charts/chartseriesgroup/up_down_bars/) | Line veya Stok grafiğinin yukarı/aşağı çubuklarına erişim sağlar.<br/>            Salt Okunur [`IUpDownBarsManager`](/slides/python-net/tr/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/tr/aspose.slides.charts/chartseriesgroup/gap_width/) | Çubuk veya sütun kümeleri arasındaki boşluğu, çubuk veya sütun genişliğinin yüzde olarak alır veya ayarlar.<br/>            Değer 0 ile 500 arasında olmalıdır.<br/>            Okunur/Yazılabilir **int**. |
| [`gap_depth`](/slides/python-net/tr/aspose.slides.charts/chartseriesgroup/gap_depth/) | 3B grafikte veri serileri arasındaki mesafeyi, işaretçi genişliğinin yüzde olarak alır veya ayarlar.<br/>            Değer 0 ile 500 arasında olmalıdır.<br/>            Okunur/Yazılabilir **int**. |
| [`first_slice_angle`](/slides/python-net/tr/aspose.slides.charts/chartseriesgroup/first_slice_angle/) | İlk pasta veya donut grafiği diliminin açısını alır veya ayarlar, <br/>            derece cinsinden (yukarıdan saat yönünde, 0 ile 360 derece arasında).<br/>            Okunur/Yazılabilir **int**. |
| [`doughnut_hole_size`](/slides/python-net/tr/aspose.slides.charts/chartseriesgroup/doughnut_hole_size/) | Donut grafiğindeki deliğin boyutunu belirtir (çizim alanı boyutunun %0 ile %90 arasında olabilir).<br/>            Okunur/Yazılabilir **int**. |
| [`overlap`](/slides/python-net/tr/aspose.slides.charts/chartseriesgroup/overlap/) | Çubuk ve sütunların 2-D grafiklerde ne kadar üst üste geleceğini yüzde olarak belirtir (-100% ile 100% arasında).<br/>             - -100%: Azami boşluk (çubuklar tamamen ayrılmıştır).<br/>             - 0%: Çubuklar yan yana, üst üste gelmeden yer alır.<br/>             - 100%: Azami üst üste gelme (çubuklar tamamen birbirinin üstüne gelir).<br/>             Bu özellik Okunur/Yazılabilir **int**. |
| [`second_pie_size`](/slides/python-net/tr/aspose.slides.charts/chartseriesgroup/second_pie_size/) | Pie-of-pie veya bar-of-pie grafiğinin ikinci pasta veya çubuğunun boyutunu, ilk pastanın boyutunun yüzde olarak belirtir ( %5 ile %200 arasında olabilir).<br/>            Okunur/Yazılabilir **int**. |
| [`bubble_size_representation`](/slides/python-net/tr/aspose.slides.charts/chartseriesgroup/bubble_size_representation/) | Balon grafiğinde balon boyutu değerlerinin nasıl temsil edileceğini belirtir.<br/>            Okunur/Yazılabilir [`BubbleSizeRepresentationType`](/slides/python-net/tr/aspose.slides.charts/bubblesizerepresentationtype). |
| [`pie_split_position`](/slides/python-net/tr/aspose.slides.charts/chartseriesgroup/pie_split_position/) | Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta veya çubukta hangi veri noktalarının olacağını belirlemek için kullanılacak bir değeri belirtir. <br/>            PieSplitBy özelliği ile birlikte kullanılır.<br/>            Okunur/Yazılabilir **float**. |
| [`pie_split_by`](/slides/python-net/tr/aspose.slides.charts/chartseriesgroup/pie_split_by/) | Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta veya çubukta hangi veri noktalarının olacağını belirleme yöntemini belirtir.<br/>            Okunur/Yazılabilir [`PieSplitType`](/slides/python-net/tr/aspose.slides.charts/piesplittype). |
| [`is_color_varied`](/slides/python-net/tr/aspose.slides.charts/chartseriesgroup/is_color_varied/) | Serideki her veri işaretçisinin farklı bir renge sahip olmasını belirtir.<br/>            Okunur/Yazılabilir **bool**. |
| [`has_series_lines`](/slides/python-net/tr/aspose.slides.charts/chartseriesgroup/has_series_lines/) | True ise grafik seri çizgilerine sahiptir. Yığılı çubuk ve OfPie grafiklerine uygulanır.<br/>            Okunur/Yazılabilir **bool**. |
| [`hi_low_lines_format`](/slides/python-net/tr/aspose.slides.charts/chartseriesgroup/hi_low_lines_format/) | HiLowLines biçimini belirtir. <br/>            HiLowLines, HiLowClose, OpenHiLowClose, VolumeHiLowClose ve VolumeOpenHiLowClose grafik türleriyle uygulanır. |
| [`bubble_size_scale`](/slides/python-net/tr/aspose.slides.charts/chartseriesgroup/bubble_size_scale/) | Balon grafiği için ölçek faktörünü belirtir (varsayılan boyutun %0 ile %300 arasında olabilir).<br/>            Okunur/Yazılabilir **int**. |
| [`pie_split_custom_points`](/slides/python-net/tr/aspose.slides.charts/chartseriesgroup/pie_split_custom_points/) | Özel bölünmüş bir pie-of-pie veya bar-of-pie grafiği için özel bölünme bilgisi.<br/>            İkinci pasta veya çubukta çizilecek veri noktalarını içerir.<br/>            Salt Okunur [`PieSplitCustomPointCollection`](/slides/python-net/tr/aspose.slides.charts/piesplitcustompointcollection). |
| [`chart`](/slides/python-net/tr/aspose.slides.charts/chartseriesgroup/chart/) | Üst grafiği döndürür.<br/>            Salt Okunur [`IChart`](/slides/python-net/tr/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/tr/aspose.slides.charts/chartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/tr/aspose.slides.charts/chartseriesgroup/presentation/) |  |

Belirtilen dizindeki öğeyi alır.

## İndeksleyici

| Ad | Açıklama |
| :- | :- |
| [`[index]`](/slides/python-net/tr/aspose.slides.charts/chartseriesgroup/__getitem__/) |  |


### Açıklamalar

1) ChartSeriesGroupCollection sınıfı ve CombinableSeriesTypesGroup enumu için özet ve açıklamalara bakınız.  
2) Seri grubu, grup içindeki her seri için ortak olan bazı seri özellikleri içerir ("series group properties").  
   "Series group properties" ChartSeriesGroup sınıfında Okunur/Yazılabilir'dir.  
   Her "series group properties" özelliği, ChartSeries sınıfında salt okunur bir yansıtma alabilir.

### Diğer Bağlantılar
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)