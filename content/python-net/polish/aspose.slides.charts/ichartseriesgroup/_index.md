---
title: IChartSeriesGroup class
second_title: Aspose.Slides dla Pythona poprzez .NET Referencja API
description: 
type: docs
url: /pl/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup klasa

Represents group of series.

The IChartSeriesGroup type exposes the following members:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`type`](/slides/python-net/pl/aspose.slides.charts/ichartseriesgroup/type/) | Zwraca typ tej grupy serii.<br/>            Tylko do odczytu [`CombinableSeriesTypesGroup`](/slides/python-net/pl/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/pl/aspose.slides.charts/ichartseriesgroup/plot_on_second_axis/) | Wskazuje, czy serie tej grupy są rysowane na osi pomocniczej.<br/>            Tylko do odczytu **bool**. |
| [`series`](/slides/python-net/pl/aspose.slides.charts/ichartseriesgroup/series/) | Zwraca kolekcję serii wykresu tylko do odczytu.<br/>            Tylko do odczytu [`IChartSeriesReadonlyCollection`](/slides/python-net/pl/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/pl/aspose.slides.charts/ichartseriesgroup/up_down_bars/) | Zapewnia dostęp do pasków góra/dół wykresu liniowego lub giełdowego.<br/>            Tylko do odczytu [`IUpDownBarsManager`](/slides/python-net/pl/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/pl/aspose.slides.charts/ichartseriesgroup/gap_width/) | Pobiera lub ustawia odstęp między grupami słupków lub kolumn, wyrażony jako procent szerokości słupka lub kolumny.<br/>            Wartość musi mieścić się w przedziale od 0 do 500.<br/>            Odczyt/zapis **int**. |
| [`gap_depth`](/slides/python-net/pl/aspose.slides.charts/ichartseriesgroup/gap_depth/) | Pobiera lub ustawia odległość między seriami danych w wykresie 3D, wyrażoną jako procent szerokości znacznika.<br/>            Wartość musi mieścić się w przedziale od 0 do 500.<br/>            Odczyt/zapis **int**. |
| [`first_slice_angle`](/slides/python-net/pl/aspose.slides.charts/ichartseriesgroup/first_slice_angle/) | Pobiera lub ustawia kąt pierwszego wycinka wykresu kołowego lub pierścieniowego,<br/>            w stopniach (zgodnie z ruchem wskazówek zegara od góry, od 0 do 360 stopni).<br/>            Odczyt/zapis **int**. |
| [`is_color_varied`](/slides/python-net/pl/aspose.slides.charts/ichartseriesgroup/is_color_varied/) | Określa, że każdy znacznik danych w serii ma inny kolor.<br/>            Odczyt/zapis **bool**. |
| [`has_series_lines`](/slides/python-net/pl/aspose.slides.charts/ichartseriesgroup/has_series_lines/) | Prawda, jeśli wykres zawiera linie serii. Stosowane w wykresach słupkowych skumulowanych i OfPie.<br/>            Odczyt/zapis **bool**. |
| [`overlap`](/slides/python-net/pl/aspose.slides.charts/ichartseriesgroup/overlap/) | Określa, o ile słupki i kolumny mają nakładać się na wykresach 2-D, wyrażone jako procent (od -100% do 100%).<br/>            - -100%: Maksymalny odstęp (słupki są całkowicie rozdzielone).<br/>            - 0%: Słupki są ustawione obok siebie bez nakładania się i bez odstępu.<br/>            - 100%: Maksymalne nakładanie (słupki całkowicie na siebie nachodzą).<br/>            Ta właściwość jest odczyt/zapis **int**. |
| [`second_pie_size`](/slides/python-net/pl/aspose.slides.charts/ichartseriesgroup/second_pie_size/) | Określa rozmiar drugiego koła lub słupka wykresu koło-w-kolach lub słupek-w-kołach, wyrażony jako procent rozmiaru pierwszego koła (może wynosić od 5 do 200 procent).<br/>            Odczyt/zapis **int**. |
| [`pie_split_position`](/slides/python-net/pl/aspose.slides.charts/ichartseriesgroup/pie_split_position/) | Określa wartość używaną do określenia, które punkty danych znajdują się w drugim kole lub słupku wykresu koło-w-kolach lub słupek-w-kołach.<br/>            Stosowane razem z właściwością PieSplitBy.<br/>            Odczyt/zapis **float**. |
| [`pie_split_by`](/slides/python-net/pl/aspose.slides.charts/ichartseriesgroup/pie_split_by/) | Określa sposób określania, które punkty danych znajdują się w drugim kole lub słupku wykresu koło-w-kolach lub słupek-w-kołach.<br/>            Odczyt/zapis [`PieSplitType`](/slides/python-net/pl/aspose.slides.charts/piesplittype). |
| [`pie_split_custom_points`](/slides/python-net/pl/aspose.slides.charts/ichartseriesgroup/pie_split_custom_points/) | Niestandardowe informacje o podziale dla wykresu koło-w-kolach lub słupek-w-kołach z niestandardowym podziałem.<br/>            Zawiera punkty danych, które mają być rysowane w drugim kole lub słupku w wykresie koło-w-kolach lub słupek-w-kołach.<br/>            Tylko do odczytu [`IPieSplitCustomPointCollection`](/slides/python-net/pl/aspose.slides.charts/ipiesplitcustompointcollection). |
| [`doughnut_hole_size`](/slides/python-net/pl/aspose.slides.charts/ichartseriesgroup/doughnut_hole_size/) | Określa rozmiar otworu w wykresie pierścieniowym (może wynosić od 10 do 90 procent rozmiaru obszaru wykresu).<br/>            Odczyt/zapis **int**. |
| [`bubble_size_scale`](/slides/python-net/pl/aspose.slides.charts/ichartseriesgroup/bubble_size_scale/) | Określa współczynnik skalowania wykresu bąbelkowego (może wynosić od 0 do 300 procent domyślnego rozmiaru).<br/>            Odczyt/zapis **int**. |
| [`hi_low_lines_format`](/slides/python-net/pl/aspose.slides.charts/ichartseriesgroup/hi_low_lines_format/) | Określa format HiLowLines.<br/>            HiLowLines stosowane z typami wykresów HiLowClose, OpenHiLowClose, VolumeHiLowClose oraz VolumeOpenHiLowClose. |
| [`bubble_size_representation`](/slides/python-net/pl/aspose.slides.charts/ichartseriesgroup/bubble_size_representation/) | Określa sposób reprezentacji wartości rozmiaru bąbelka na wykresie bąbelkowym.<br/>            Odczyt/zapis [`BubbleSizeRepresentationType`](/slides/python-net/pl/aspose.slides.charts/bubblesizerepresentationtype). |
| [`chart`](/slides/python-net/pl/aspose.slides.charts/ichartseriesgroup/chart/) |  |
| [`slide`](/slides/python-net/pl/aspose.slides.charts/ichartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/pl/aspose.slides.charts/ichartseriesgroup/presentation/) |  |

Pobiera element pod wskazanym indeksem.

## Indeksator

| Nazwa | Opis |
| :- | :- |
| [`[index]`](/slides/python-net/pl/aspose.slides.charts/ichartseriesgroup/__getitem__/) |  |

### Uwagi

1) Zobacz podsumowanie i uwagi dla klasy ChartSeriesGroupCollection oraz wyliczenia CombinableSeriesTypesGroup.
            2) Grupa serii zawiera niektóre właściwości serii, które są wspólne dla każdej serii w grupie („właściwości grupy serii”).
            „Właściwości grupy serii” w klasie ChartSeriesGroup są odczyt/zapis.
            Każda z „właściwości grupy serii” może mieć projekcję tylko do odczytu w klasie ChartSeries.

### Zobacz także
* modul [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)