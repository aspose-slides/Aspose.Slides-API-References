---
title: DataLabelFormat
second_title: Aspose.Sildes dla .NET – dokumentacja API
description: Reprezentuje opcje formatowania dla DataLabel.
type: docs
weight: 1570
url: /pl/aspose.slides.charts/datalabelformat/
---
## DataLabelFormat klasa

Reprezentuje opcje formatowania dla DataLabel.

```csharp
public sealed class DataLabelFormat : PVIObject, IDataLabelFormat
```

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Umożliwia pobranie podstawowego interfejsu IPresentationComponent. Tylko do odczytu [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [Chart](../../aspose.slides.charts/datalabelformat/chart) { get; } | Zwraca wykres. Tylko do odczytu [`IChart`](../ichart). |
| [Format](../../aspose.slides.charts/datalabelformat/format) { get; } | Reprezentuje format etykiety danych. Tylko do odczytu [`IFormat`](../iformat). |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/datalabelformat/isnumberformatlinkedtosource) { get; set; } | Odczyt/zapis Boolean. |
| [NumberFormat](../../aspose.slides.charts/datalabelformat/numberformat) { get; set; } | Reprezentuje ciąg formatu dla obiektu DataLabels. Odczyt/zapis String. |
| [Position](../../aspose.slides.charts/datalabelformat/position) { get; set; } | Reprezentuje pozycję etykiety danych. Odczyt/zapis [`LegendDataLabelPosition`](../legenddatalabelposition). |
| [Separator](../../aspose.slides.charts/datalabelformat/separator) { get; set; } | Ustawia lub zwraca Variant reprezentujący separator używany dla etykiet danych na wykresie. Odczyt/zapis String. |
| [ShowBubbleSize](../../aspose.slides.charts/datalabelformat/showbubblesize) { get; set; } | Reprezentuje zachowanie wyświetlania wartości rozmiaru bąbelka etykiety danych określonego wykresu. True wyświetla wartość rozmiaru bąbelka. False ukrywa. Odczyt/zapis Boolean. |
| [ShowCategoryName](../../aspose.slides.charts/datalabelformat/showcategoryname) { get; set; } | Reprezentuje zachowanie wyświetlania nazwy kategorii etykiety danych określonego wykresu. True wyświetla nazwę kategorii. False ukrywa. Odczyt/zapis Boolean. |
| [ShowLabelAsDataCallout](../../aspose.slides.charts/datalabelformat/showlabelasdatacallout) { get; set; } | Określa, czy etykieta danych określonego wykresu będzie wyświetlana jako dymek danych czy jako etykieta danych. Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection etykiet danych, wówczas ta własność pobiera lub ustawia domyślną wartość właściwości ShowLabelAsDataCallout dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej własności powoduje również ustawienie tej samej wartości właściwości ShowLabelAsDataCallout dla wszystkich etykiet danych w kolekcji DataLabelCollection (np. "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" powoduje, że wszystkie DataLabels[i].ShowLabelAsDataCallout są równe val). |
| [ShowLabelValueFromCell](../../aspose.slides.charts/datalabelformat/showlabelvaluefromcell) { get; set; } | Reprezentuje zachowanie wyświetlania wartości komórki etykiety danych określonego wykresu. True wyświetla wartość komórki. False ukrywa. Odczyt/zapis Boolean. |
| [ShowLeaderLines](../../aspose.slides.charts/datalabelformat/showleaderlines) { get; set; } | Reprezentuje zachowanie wyświetlania linii prowadzących etykiety danych określonego wykresu. True wyświetla linie prowadzące. False ukrywa. Odczyt/zapis Boolean. |
| [ShowLegendKey](../../aspose.slides.charts/datalabelformat/showlegendkey) { get; set; } | Reprezentuje zachowanie wyświetlania klucza legendy etykiety danych określonego wykresu. True, jeśli klucz legendy etykiety danych jest widoczny. Odczyt/zapis Boolean. |
| [ShowPercentage](../../aspose.slides.charts/datalabelformat/showpercentage) { get; set; } | Reprezentuje zachowanie wyświetlania wartości procentowej etykiety danych określonego wykresu. True wyświetla wartość procentową. False ukrywa. Odczyt/zapis Boolean. |
| [ShowSeriesName](../../aspose.slides.charts/datalabelformat/showseriesname) { get; set; } | Zwraca lub ustawia Boolean określający zachowanie wyświetlania nazwy serii dla etykiet danych na wykresie. True pokazuje nazwę serii. False ukrywa. Odczyt/zapis Boolean. |
| [ShowValue](../../aspose.slides.charts/datalabelformat/showvalue) { get; set; } | Reprezentuje zachowanie wyświetlania wartości procentowej etykiety danych określonego wykresu. True wyświetla wartość procentową. False ukrywa. Odczyt/zapis Boolean. |
| [TextFormat](../../aspose.slides.charts/datalabelformat/textformat) { get; } | Zwraca format tekstu wykresu. Tylko do odczytu [`IChartTextFormat`](../icharttextformat). |

## Metody

| Nazwa | Opis |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Porównuje z określonym obiektem. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Zwraca kod skrótu. |

### Zobacz także

* klasa [PVIObject](../../aspose.slides/pviobject)
* interfejs [IDataLabelFormat](../idatalabelformat)
* przestrzeń nazw [Aspose.Slides.Charts](../../aspose.slides.charts)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->