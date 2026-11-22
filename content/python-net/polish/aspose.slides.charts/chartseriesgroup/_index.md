---
title: ChartSeriesGroup class
second_title: Aspose.Slides dla Pythona poprzez .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup klasa

Reprezentuje grupę serii.

Typ ChartSeriesGroup udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`type`](/slides/python-net/pl/aspose.slides.charts/chartseriesgroup/type/) | Zwraca typ tej grupy serii.<br/>            Tylko do odczytu [`CombinableSeriesTypesGroup`](/slides/python-net/pl/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/pl/aspose.slides.charts/chartseriesgroup/plot_on_second_axis/) | Wskazuje, czy seria tej grupy jest rysowana na drugiej osi.<br/>            Tylko do odczytu **bool**. |
| [`series`](/slides/python-net/pl/aspose.slides.charts/chartseriesgroup/series/) | Zwraca kolekcję serii.<br/>            Tylko do odczytu [`IChartSeriesReadonlyCollection`](/slides/python-net/pl/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/pl/aspose.slides.charts/chartseriesgroup/up_down_bars/) | Umożliwia dostęp do słupków góra/dół wykresu liniowego lub giełdowego.<br/>            Tylko do odczytu [`IUpDownBarsManager`](/slides/python-net/pl/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/pl/aspose.slides.charts/chartseriesgroup/gap_width/) | Pobiera lub ustawia odstęp między grupami słupków lub kolumn, wyrażony jako procent szerokości słupka lub kolumny.<br/>            Wartość musi mieścić się w przedziale od 0 do 500.<br/>            Odczyt/zapis **int**. |
| [`gap_depth`](/slides/python-net/pl/aspose.slides.charts/chartseriesgroup/gap_depth/) | Pobiera lub ustawia odległość między seriami danych w wykresie 3D, wyrażoną jako procent szerokości znacznika.<br/>            Wartość musi mieścić się w przedziale od 0 do 500.<br/>            Odczyt/zapis **int**. |
| [`first_slice_angle`](/slides/python-net/pl/aspose.slides.charts/chartseriesgroup/first_slice_angle/) | Pobiera lub ustawia kąt pierwszego wycinka wykresu kołowego lub pierścieniowego,<br/>            w stopniach (zgodnie z ruchem wskazówek zegara od góry, od 0 do 360 stopni).<br/>            Odczyt/zapis **int**. |
| [`doughnut_hole_size`](/slides/python-net/pl/aspose.slides.charts/chartseriesgroup/doughnut_hole_size/) | Określa rozmiar otworu w wykresie pierścieniowym (może wynosić od 0 do 90 procent<br/>            rozmiaru obszaru wykresu).<br/>            Odczyt/zapis **int**. |
| [`overlap`](/slides/python-net/pl/aspose.slides.charts/chartseriesgroup/overlap/) | Określa, jak bardzo słupki i kolumny mają nachodzić na siebie w wykresach 2-D, wyrażone jako procent (od -100% do 100%).<br/>             - -100%: Maksymalny odstęp (słupki są całkowicie rozdzielone).<br/>             - 0%: Słupki są umieszczone obok siebie bez nachodzenia ani odstępu.<br/>             - 100%: Maksymalne nachodzenie (słupki całkowicie na siebie nachodzą).<br/>             Ta właściwość jest odczyt/zapis **int**. |
| [`second_pie_size`](/slides/python-net/pl/aspose.slides.charts/chartseriesgroup/second_pie_size/) | Określa rozmiar drugiego koła lub słupka w wykresie koło-w-kółku lub słupek-w-kółku, wyrażony jako procent rozmiaru pierwszego koła (może wynosić od 5 do 200 procent).<br/>            Odczyt/zapis **int**. |
| [`bubble_size_representation`](/slides/python-net/pl/aspose.slides.charts/chartseriesgroup/bubble_size_representation/) | Określa sposób reprezentacji wartości rozmiaru bąbelka na wykresie bąbelkowym.<br/>            Odczyt/zapis [`BubbleSizeRepresentationType`](/slides/python-net/pl/aspose.slides.charts/bubblesizerepresentationtype). |
| [`pie_split_position`](/slides/python-net/pl/aspose.slides.charts/chartseriesgroup/pie_split_position/) | Określa wartość używaną do określenia, które punkty danych znajdują się w drugim kole lub słupku na wykresie koło-w-kółku lub słupek-w-kółku.<br/>            Jest używana razem z właściwością PieSplitBy.<br/>            Odczyt/zapis **float**. |
| [`pie_split_by`](/slides/python-net/pl/aspose.slides.charts/chartseriesgroup/pie_split_by/) | Określa sposób określania, które punkty danych znajdują się w drugim kole lub słupku na wykresie koło-w-kółku lub słupek-w-kółku.<br/>            Odczyt/zapis [`PieSplitType`](/slides/python-net/pl/aspose.slides.charts/piesplittype). |
| [`is_color_varied`](/slides/python-net/pl/aspose.slides.charts/chartseriesgroup/is_color_varied/) | Określa, że każdy znacznik danych w serii ma inny kolor.<br/>            Odczyt/zapis **bool**. |
| [`has_series_lines`](/slides/python-net/pl/aspose.slides.charts/chartseriesgroup/has_series_lines/) | Prawda, jeśli wykres ma linie serii. Stosowane do wykresów słupkowych skumulowanych i OfPie.<br/>            Odczyt/zapis **bool**. |
| [`hi_low_lines_format`](/slides/python-net/pl/aspose.slides.charts/chartseriesgroup/hi_low_lines_format/) | Określa format HiLowLines.<br/>            HiLowLines stosowane wraz z typami wykresów HiLowClose, OpenHiLowClose, VolumeHiLowClose i VolumeOpenHiLowClose. |
| [`bubble_size_scale`](/slides/python-net/pl/aspose.slides.charts/chartseriesgroup/bubble_size_scale/) | Określa współczynnik skali dla wykresu bąbelkowego (może wynosić od 0 do 300 procent domyślnego rozmiaru).<br/>            Odczyt/zapis **int**. |
| [`pie_split_custom_points`](/slides/python-net/pl/aspose.slides.charts/chartseriesgroup/pie_split_custom_points/) | Niestandardowe informacje o podziale dla wykresu koło-w-kółku lub słupek-w-kółku z niestandardowym podziałem.<br/>            Zawiera punkty danych, które mają być rysowane w drugim kole lub słupku w wykresie koło-w-kółku lub słupek-w-kółku.<br/>            Tylko do odczytu [`PieSplitCustomPointCollection`](/slides/python-net/pl/aspose.slides.charts/piesplitcustompointcollection). |
| [`chart`](/slides/python-net/pl/aspose.slides.charts/chartseriesgroup/chart/) | Zwraca wykres nadrzędny.<br/>            Tylko do odczytu [`IChart`](/slides/python-net/pl/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/pl/aspose.slides.charts/chartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/pl/aspose.slides.charts/chartseriesgroup/presentation/) |  |

Pobiera element o określonym indeksie.

## Indeksator

| Nazwa | Opis |
| :- | :- |
| [`[index]`](/slides/python-net/pl/aspose.slides.charts/chartseriesgroup/__getitem__/) |  |

### Uwagi

1) Zobacz podsumowanie i uwagi dla klasy ChartSeriesGroupCollection i wyliczenia CombinableSeriesTypesGroup.  
2) Grupa serii zawiera pewne właściwości serii, które są wspólne dla każdej serii w grupie („właściwości grupy serii”).  
„Właściwości grupy serii” w klasie ChartSeriesGroup są odczyt/zapis.  
Każda z „właściwości grupy serii” może mieć projekcję tylko do odczytu w klasie ChartSeries.

### Zobacz także
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)