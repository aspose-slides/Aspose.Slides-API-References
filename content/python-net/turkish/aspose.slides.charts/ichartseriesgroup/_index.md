---
title: IChartSeriesGroup class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup sınıfı

Seri grubunu temsil eder.

IChartSeriesGroup türü aşağıdaki üyelere sahiptir:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`type`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroup/type/) | Bu seri grubunun tipini döndürür.<br/>            Yalnızca okuma [`CombinableSeriesTypesGroup`](/slides/python-net/tr/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroup/plot_on_second_axis/) | Bu grubun serilerinin ikincil eksende çizilip çizilmediğini gösterir.<br/>            Yalnızca okuma **bool**. |
| [`series`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroup/series/) | Grafik serilerinin yalnızca okunabilir bir koleksiyonunu döndürür.<br/>            Yalnızca okuma [`IChartSeriesReadonlyCollection`](/slides/python-net/tr/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroup/up_down_bars/) | Line veya Stock grafiğinin yukarı/aşağı çubuklarına erişim sağlar.<br/>            Yalnızca okuma [`IUpDownBarsManager`](/slides/python-net/tr/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroup/gap_width/) | Çubuk veya sütun kümeleri arasındaki boşluğu, çubuk veya sütun genişliğinin yüzde cinsinden alır ya da ayarlar.<br/>            Değer 0 ile 500 arasında olmalıdır.<br/>            Okuma/yazma **int**. |
| [`gap_depth`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroup/gap_depth/) | 3B grafikte veri serileri arasındaki mesafeyi, işaretçi genişliğinin yüzde cinsinden alır ya da ayarlar.<br/>            Değer 0 ile 500 arasında olmalıdır.<br/>            Okuma/yazma **int**. |
| [`first_slice_angle`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroup/first_slice_angle/) | İlk pasta ya da donut grafik diliminin açısını alır ya da ayarlar, <br/>            derece cinsinden (yukarıdan saat yönünde, 0'dan 360 dereceye).<br/>            Okuma/yazma **int**. |
| [`is_color_varied`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroup/is_color_varied/) | Serideki her veri işaretleyicisinin farklı bir renge sahip olacağını belirtir.<br/>            Okuma/yazma **bool**. |
| [`has_series_lines`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroup/has_series_lines/) | Grafiğin seri çizgileri varsa doğru (true). Yığılmış çubuk ve OfPie grafiklerine uygulanır.<br/>            Okuma/yazma **bool**. |
| [`overlap`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroup/overlap/) | 2B grafiklerde çubuk ve sütunların ne kadar üst üste geleceğini yüzde olarak belirtir ( -%100 ile %100 arasında).<br/>             - -100%: Azami boşluk (çubuklar tamamen ayrılmıştır).<br/>             - 0%: Çubuklar üst üste gelmeden yan yana yer alır.<br/>             - 100%: Azami üst üste gelme (çubuklar tamamen birbirinin üzerine gelir).<br/>             Bu özellik okuma/yazma **int**. |
| [`second_pie_size`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroup/second_pie_size/) | Pie-of-pie grafiği veya bar-of-pie grafiğinde ikinci pasta ya da çubuğun boyutunu, ilk pastanın boyutunun yüzde cinsinden belirtir ( %5 ile %200 arasında olabilir).<br/>            Okuma/yazma **int**. |
| [`pie_split_position`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroup/pie_split_position/) | Pie-of-pie ya da bar-of-pie grafiğinde ikinci pasta veya çubukta hangi veri noktalarının olacağını belirlemek için kullanılacak bir değeri belirtir.<br/>            PieSplitBy özelliği ile birlikte kullanılır.<br/>            Okuma/yazma **float**. |
| [`pie_split_by`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroup/pie_split_by/) | Pie-of-pie ya da bar-of-pie grafiğinde ikinci pasta veya çubukta hangi veri noktalarının olacağını belirleme yöntemini belirtir.<br/>            Okuma/yazma [`PieSplitType`](/slides/python-net/tr/aspose.slides.charts/piesplittype). |
| [`pie_split_custom_points`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroup/pie_split_custom_points/) | Özel bölme bilgisi, özel bir bölme içeren pie-of-pie ya da bar-of-pie grafiği için.<br/>            İkinci pasta veya çubukta çizilecek veri noktalarını içerir.<br/>            Yalnızca okuma [`IPieSplitCustomPointCollection`](/slides/python-net/tr/aspose.slides.charts/ipiesplitcustompointcollection). |
| [`doughnut_hole_size`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroup/doughnut_hole_size/) | Donut grafiğindeki deliğin boyutunu belirtir (çizim alanının boyutunun %10 ile %90 arasında olabilir).<br/>            Okuma/yazma **int**. |
| [`bubble_size_scale`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroup/bubble_size_scale/) | Balon grafiği için ölçek faktörünü belirtir (varsayılan boyutun %0 ile %300 arasında olabilir).<br/>            Okuma/yazma **int**. |
| [`hi_low_lines_format`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroup/hi_low_lines_format/) | HiLowLines biçimini belirtir. <br/>            HiLowLines, HiLowClose, OpenHiLowClose, VolumeHiLowClose ve VolumeOpenHiLowClose grafik tipleriyle uygulanır. |
| [`bubble_size_representation`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroup/bubble_size_representation/) | Balon grafiğinde balon boyutu değerlerinin nasıl temsil edileceğini belirtir.<br/>            Okuma/yazma [`BubbleSizeRepresentationType`](/slides/python-net/tr/aspose.slides.charts/bubblesizerepresentationtype). |
| [`chart`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroup/chart/) |  |
| [`slide`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroup/presentation/) |  |

Belirtilen indeksteki öğeyi alır.

## Dizinleyici

| Ad | Açıklama |
| :- | :- |
| [`[index]`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroup/__getitem__/) |  |


### Açıklamalar

1) ChartSeriesGroupCollection sınıfı ve CombinableSeriesTypesGroup enum'ı için özet ve açıklamalara bakın.  
2) Seri grubu, grup içindeki her seri için ortak bazı seri özellikleri içerir ("series group properties").  
"Series group properties" ChartSeriesGroup sınıfında okuma/yazma özelliğindedir.  
Her "series group properties" öğesi, ChartSeries sınıfında yalnızca okuma projeksiyonuna sahip olabilir.

### Ayrıca Bakınız
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)