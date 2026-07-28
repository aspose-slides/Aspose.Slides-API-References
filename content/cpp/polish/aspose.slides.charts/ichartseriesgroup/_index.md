---
title: IChartSeriesGroup
second_title: Referencja API Aspose.Slides dla C++
description: Reprezentuje grupę serii.
type: docs
weight: 846
url: /pl/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup klasa

Represents group of series.

```cpp
class IChartSeriesGroup : public Aspose::Slides::Charts::IChartComponent
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| virtual [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() | Określa, jak wartości rozmiaru bąbelka są reprezentowane na wykresie bąbelkowym. Czytaj [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| virtual **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() | Określa współczynnik skalowania wykresu bąbelkowego (może wynosić od 0 do 300 procent domyślnego rozmiaru). Czytaj **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Zwraca wykres. Tylko do odczytu [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) | Zwraca serię wykresu w grupie o podanym indeksie. |
| virtual **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() | Określa rozmiar otworu w wykresie pierścieniowym (może wynosić od 10 do 90 procent rozmiaru obszaru wykresu). Czytaj **uint8_t**. |
| virtual **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() | Pobiera kąt pierwszego wycinka wykresu kołowego lub pierścieniowego, w stopniach (zgodnie z ruchem wskazówek zegara od góry, od 0 do 360 stopni). Czytaj **uint16_t**. |
| virtual **uint16_t** [get_GapDepth](./get_gapdepth/)() | Zwraca odległość, jako procent szerokości znacznika, pomiędzy seriami danych w wykresie 3D. Czytaj **uint16_t**. |
| virtual **uint16_t** [get_GapWidth](./get_gapwidth/)() | Określa odstęp między grupami słupków lub kolumn, jako procent szerokości słupka lub kolumny. Czytaj **uint16_t**. |
| virtual **bool** [get_HasSeriesLines](./get_hasserieslines/)() | Prawda, jeśli wykres ma linie serii. Stosowane do wykresów słupkowych skumulowanych i OfPie. Czytaj **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_HiLowLinesFormat](./get_hilowlinesformat/)() | Określa format HiLowLines. HiLowLines stosowane wraz z typami wykresów HiLowClose, OpenHiLowClose, VolumeHiLowClose i VolumeOpenHiLowClose. |
| virtual **bool** [get_IsColorVaried](./get_iscolorvaried/)() | Określa, że każdy znacznik danych w serii ma inny kolor. Czytaj **bool**. |
| virtual **int8_t** [get_Overlap](./get_overlap/)() | Określa, o ile słupki i kolumny mają się zachodzić na wykresach 2D, jako procent (od -100% do 100%). |
| virtual [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() | Określa, jak ustalić, które punkty danych znajdują się w drugim wykresie kołowym lub słupkowym w wykresie pie-of-pie lub bar-of-pie. Czytaj [PieSplitType](../piesplittype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) | Informacje o niestandardowym podziale dla wykresu pie-of-pie lub bar-of-pie z niestandardowym podziałem. Zwraca punkt danych, który ma być rysowany w drugim wykresie kołowym lub słupkowym w wykresie pie-of-pie lub bar-of-pie według indeksu. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() | Informacje o niestandardowym podziale dla wykresu pie-of-pie lub bar-of-pie z niestandardowym podziałem. Zawiera punkty danych, które mają być rysowane w drugim wykresie kołowym lub słupkowym w wykresie pie-of-pie lub bar-of-pie. Tylko do odczytu [IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/). |
| virtual **double** [get_PieSplitPosition](./get_piesplitposition/)() | Określa wartość, która ma być użyta do ustalenia, które punkty danych znajdują się w drugim wykresie kołowym lub słupkowym w wykresie pie-of-pie lub bar-of-pie. Używana razem z własnością PieSplitBy. Czytaj **double**. |
| virtual **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() | Wskazuje, czy serie tej grupy są wykreślane na drugiej osi. Tylko do odczytu **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Zwraca prezentację. Tylko do odczytu [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() | Określa rozmiar drugiego wykresu kołowego lub słupkowego w wykresie pie-of-pie lub bar-of-pie, jako procent rozmiaru pierwszego wykresu (może wynosić od 5 do 200 procent). Czytaj **uint16_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)\> [get_Series](./get_series/)() | Zwraca kolekcję serii wykresu tylko do odczytu. Tylko do odczytu [IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Zwraca podstawowy slajd. Tylko do odczytu [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [CombinableSeriesTypesGroup](../combinableseriestypesgroup/) [get_Type](./get_type/)() | Zwraca typ tej grupy serii. Tylko do odczytu [CombinableSeriesTypesGroup](../combinableseriestypesgroup/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IUpDownBarsManager](../iupdownbarsmanager/)\> [get_UpDownBars](./get_updownbars/)() | Zapewnia dostęp do słupków w górę/w dół wykresu liniowego lub giełdowego. Tylko do odczytu [IUpDownBarsManager](../iupdownbarsmanager/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera faktyczny typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [idx_get](./idx_get/)(**int32_t**) | Pobiera element o podanym indeksie. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu czujnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. W rzeczywistości nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. W rzeczywistości nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku stringów. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
| virtual void [set_BubbleSizeRepresentation](./set_bubblesizerepresentation/)([BubbleSizeRepresentationType](../bubblesizerepresentationtype/)) | Określa, jak wartości rozmiaru bąbelka są reprezentowane na wykresie bąbelkowym. Zapisz [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| virtual void [set_BubbleSizeScale](./set_bubblesizescale/)(**int32_t**) | Określa współczynnik skalowania wykresu bąbelkowego (może wynosić od 0 do 300 procent domyślnego rozmiaru). Zapisz **int32_t**. |
| virtual void [set_DoughnutHoleSize](./set_doughnutholesize/)(**uint8_t**) | Określa rozmiar otworu w wykresie pierścieniowym (może wynosić od 10 do 90 procent rozmiaru obszaru wykresu). Zapisz **uint8_t**. |
| virtual void [set_FirstSliceAngle](./set_firstsliceangle/)(**uint16_t**) | Ustawia kąt pierwszego wycinka wykresu kołowego lub pierścieniowego, w stopniach (zgodnie z ruchem wskazówek zegara od góry, od 0 do 360 stopni). Zapisz **uint16_t**. |
| virtual void [set_GapDepth](./set_gapdepth/)(**uint16_t**) | Ustawia odległość, jako procent szerokości znacznika, pomiędzy seriami danych w wykresie 3D. Zapisz **uint16_t**. |
| virtual void [set_GapWidth](./set_gapwidth/)(**uint16_t**) | Określa odstęp między grupami słupków lub kolumn, jako procent szerokości słupka lub kolumny. Zapisz **uint16_t**. |
| virtual void [set_HasSeriesLines](./set_hasserieslines/)(**bool**) | Prawda, jeśli wykres ma linie serii. Stosowane do wykresów słupkowych skumulowanych i OfPie. Zapisz **bool**. |
| virtual void [set_IsColorVaried](./set_iscolorvaried/)(**bool**) | Określa, że każdy znacznik danych w serii ma inny kolor. Zapisz **bool**. |
| virtual void [set_Overlap](./set_overlap/)(**int8_t**) | Określa, o ile słupki i kolumny mają się zachodzić na wykresach 2D, jako procent (od -100% do 100%). |
| virtual void [set_PieSplitBy](./set_piesplitby/)([PieSplitType](../piesplittype/)) | Określa, jak ustalić, które punkty danych znajdują się w drugim wykresie kołowym lub słupkowym w wykresie pie-of-pie lub bar-of-pie. Zapisz [PieSplitType](../piesplittype/). |
| virtual void [set_PieSplitPosition](./set_piesplitposition/)(**double**) | Określa wartość, która ma być użyta do ustalenia, które punkty danych znajdują się w drugim wykresie kołowym lub słupkowym w wykresie pie-of-pie lub bar-of-pie. Używana razem z własnością PieSplitBy. Zapisz **double**. |
| virtual void [set_SecondPieSize](./set_secondpiesize/)(**uint16_t**) | Określa rozmiar drugiego wykresu kołowego lub słupkowego w wykresie pie-of-pie lub bar-of-pie, jako procent rozmiaru pierwszego wykresu (może wynosić od 5 do 200 procent). Zapisz **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów na ciąg znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu czujnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa słaby licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza słaby licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Uwagi

1) Zobacz podsumowanie i uwagi dla klasy ChartSeriesGroupCollection oraz wyliczenia CombinableSeriesTypesGroup. 2) Grupa serii zawiera niektóre właściwości serii, które są wspólne dla każdej serii w grupie ("series group properties"). "Series group properties" w klasie [ChartSeriesGroup](../chartseriesgroup/) jest odczyt/zapis. Każda z "series group properties" może mieć projekcję tylko do odczytu w klasie [ChartSeries](../chartseries/).

## Zobacz także

* Klasa [IChartComponent](../ichartcomponent/)
* Przestrzeń nazw [Aspose::Slides::Charts](../)
* Biblioteka [Aspose.Slides](../../)