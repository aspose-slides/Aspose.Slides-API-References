---
title: ChartSeriesGroup class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup sınıf

Seri grubunu temsil eder.

ChartSeriesGroup türü aşağıdaki üyeleri sunar:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`type`](/slides/python-net/tr/aspose.slides.charts/chartseriesgroup/type/) | Bu seri grubunun tipini döndürür.<br/>            Salt okunur [`CombinableSeriesTypesGroup`](/slides/python-net/tr/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/tr/aspose.slides.charts/chartseriesgroup/plot_on_second_axis/) | Bu grubun serilerinin ikincil eksende çizilip çizilmediğini gösterir.<br/>            Salt okunur **bool**. |
| [`series`](/slides/python-net/tr/aspose.slides.charts/chartseriesgroup/series/) | Seri koleksiyonunu döndürür.<br/>            Salt okunur [`IChartSeriesReadonlyCollection`](/slides/python-net/tr/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/tr/aspose.slides.charts/chartseriesgroup/up_down_bars/) | Çizgi veya Hisse senedi grafiğinin yukarı/aşağı çubuklarına erişim sağlar.<br/>            Salt okunur [`IUpDownBarsManager`](/slides/python-net/tr/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/tr/aspose.slides.charts/chartseriesgroup/gap_width/) | Çubuk veya sütun kümeleri arasındaki boşluğu, çubuk veya sütun genişliğinin yüzdesi olarak belirtir.<br/>            Okunabilir/yazılabilir **int**. |
| [`gap_depth`](/slides/python-net/tr/aspose.slides.charts/chartseriesgroup/gap_depth/) | 3B grafikte veri serileri arasındaki mesafeyi, işaretçi genişliğinin yüzdesi olarak döndürür veya ayarlar.<br/>            Okunabilir/yazılabilir **int**. |
| [`first_slice_angle`](/slides/python-net/tr/aspose.slides.charts/chartseriesgroup/first_slice_angle/) | İlk pasta veya halka grafiği diliminin açısını alır veya ayarlar, <br/>            derece cinsinden (yukarıdan saat yönünde, 0 ile 360 derece arası).<br/>            Okunabilir/yazılabilir **int**. |
| [`doughnut_hole_size`](/slides/python-net/tr/aspose.slides.charts/chartseriesgroup/doughnut_hole_size/) | Halka grafiğindeki boşluğun boyutunu belirtir (çizim alanının boyutunun %0 ile %90 arasında olabilir).<br/>            Okunabilir/yazılabilir **int**. |
| [`overlap`](/slides/python-net/tr/aspose.slides.charts/chartseriesgroup/overlap/) | 2D grafiklerde çubuk ve sütunların ne kadar üst üste geleceğini yüzde olarak ( -%100 ile %100 arasında) belirtir.<br/>             - -%100: En fazla boşluk (çubuklar tamamen ayrılmıştır).<br/>             - %0: Çubuklar yan yana, üst üste gelmeden veya boşluk olmadan yerleştirilir.<br/>             - %100: En fazla üst üste binme (çubuklar tamamen üst üste gelir).<br/>             Bu özellik okunabilir/yazılabilir **int**. |
| [`second_pie_size`](/slides/python-net/tr/aspose.slides.charts/chartseriesgroup/second_pie_size/) | Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta veya çubuğun boyutunu, ilk pastanın boyutunun %5 ile %200 arasında olabilir.<br/>            Okunabilir/yazılabilir **int**. |
| [`bubble_size_representation`](/slides/python-net/tr/aspose.slides.charts/chartseriesgroup/bubble_size_representation/) | Baloncuk grafiğinde baloncuk boyutu değerlerinin nasıl temsil edildiğini belirtir.<br/>            Okunabilir/yazılabilir [`BubbleSizeRepresentationType`](/slides/python-net/tr/aspose.slides.charts/bubblesizerepresentationtype). |
| [`pie_split_position`](/slides/python-net/tr/aspose.slides.charts/chartseriesgroup/pie_split_position/) | Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta veya çubuğa hangi veri noktalarının dahil edileceğini belirlemek için kullanılacak bir değeri belirtir. <br/>            PieSplitBy özelliği ile birlikte kullanılır.<br/>            Okunabilir/yazılabilir **float**. |
| [`pie_split_by`](/slides/python-net/tr/aspose.slides.charts/chartseriesgroup/pie_split_by/) | Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta veya çubuğa hangi veri noktalarının dahil edileceğini belirleme şeklini belirtir.<br/>            Okunabilir/yazılabilir [`PieSplitType`](/slides/python-net/tr/aspose.slides.charts/piesplittype). |
| [`is_color_varied`](/slides/python-net/tr/aspose.slides.charts/chartseriesgroup/is_color_varied/) | Serideki her veri işaretçisinin farklı bir renge sahip olmasını belirtir.<br/>            Okunabilir/yazılabilir **bool**. |
| [`has_series_lines`](/slides/python-net/tr/aspose.slides.charts/chartseriesgroup/has_series_lines/) | Grafik serileri çizgileri varsa doğru. Yığılmış çubuk ve OfPie grafikleri için uygulanır.<br/>            Okunabilir/yazılabilir **bool**. |
| [`hi_low_lines_format`](/slides/python-net/tr/aspose.slides.charts/chartseriesgroup/hi_low_lines_format/) | HiLowLines biçimini belirtir. <br/>            HiLowLines, HiLowClose, OpenHiLowClose, VolumeHiLowClose ve VolumeOpenHiLowClose grafik türleriyle uygulanır. |
| [`bubble_size_scale`](/slides/python-net/tr/aspose.slides.charts/chartseriesgroup/bubble_size_scale/) | Baloncuk grafiği için ölçek faktörünü belirtir (varsayılan boyutun %0 ile %300 arasında olabilir).<br/>            Okunabilir/yazılabilir **int**. |
| [`pie_split_custom_points`](/slides/python-net/tr/aspose.slides.charts/chartseriesgroup/pie_split_custom_points/) | Özel bir bölme ile bir pie-of-pie veya bar-of-pie grafiği için özel bölme bilgilerini içerir.<br/>            Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta veya çubukta çizilecek veri noktalarını içerir.<br/>            Salt okunur [`PieSplitCustomPointCollection`](/slides/python-net/tr/aspose.slides.charts/piesplitcustompointcollection). |
| [`chart`](/slides/python-net/tr/aspose.slides.charts/chartseriesgroup/chart/) | Üst grafiği döndürür.<br/>            Salt okunur [`IChart`](/slides/python-net/tr/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/tr/aspose.slides.charts/chartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/tr/aspose.slides.charts/chartseriesgroup/presentation/) |  |

Belirtilen indeksdeki elementi alır.

## Dizinleyici

| Ad | Açıklama |
| :- | :- |
| [`[index]`](/slides/python-net/tr/aspose.slides.charts/chartseriesgroup/__getitem__/) |  |


### Açıklamalar

1) ChartSeriesGroupCollection sınıfı ve CombinableSeriesTypesGroup enum için özet ve açıklamalara bakın.  
2) Seri grubu, grup içindeki her seri için ortak olan bazı seri özelliklerini içerir ("series group properties"). "series group properties" ChartSeriesGroup sınıfında okunabilir/yazılabilir özelliktedir. "series group properties" öğelerinin her biri ChartSeries sınıfında salt okunur bir projeksiyona sahip olabilir.

### Bakınız
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)