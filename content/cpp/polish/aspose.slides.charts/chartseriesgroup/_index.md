---
title: ChartSeriesGroup
second_title: Aspose.Slides dla C++ - Referencja API
description: Reprezentuje grupę serii.
type: docs
weight: 300
url: /pl/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup klasa

Reprezentuje grupę serii.

```cpp
class ChartSeriesGroup : public Aspose::Slides::Charts::IChartSeriesGroup,
                         public Aspose::Slides::IDOMObject
```

## Metody

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, łącznie z NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, łącznie z NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() override | Określa, jak wartości rozmiaru bąbelka są przedstawiane na wykresie bąbelkowym. Zobacz [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() override | Określa współczynnik skali dla wykresu bąbelkowego (może wynosić od 0 do 300 procent domyślnego rozmiaru). Odczytaj **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Zwraca wykres nadrzędny. Tylko do odczytu [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) override | Zwraca serię wykresu w grupie pod podanym indeksem. |
| **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() override | Określa rozmiar otworu w wykresie pierścieniowym (może wynosić od 0 do 90 procent rozmiaru obszaru rysowania). Odczytaj **uint8_t**. |
| **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() override | Pobiera kąt pierwszego segmentu wykresu kołowego lub pierścieniowego, w stopniach (zgodnie z ruchem wskazówek zegara od góry, od 0 do 360 stopni). Odczytaj **uint16_t**. |
| **uint16_t** [get_GapDepth](./get_gapdepth/)() override | Zwraca odległość, jako procent szerokości znacznika, pomiędzy seriami danych w wykresie 3D. Odczytaj **uint16_t**. |
| **uint16_t** [get_GapWidth](./get_gapwidth/)() override | Określa odstęp między grupami słupków lub kolumn, jako procent szerokości słupka lub kolumny. Odczytaj **uint16_t**. |
| **bool** [get_HasSeriesLines](./get_hasserieslines/)() override | Prawda, jeśli wykres ma linie serii. Dotyczy wykresów słupkowych skumulowanych i OfPie. Odczytaj **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_HiLowLinesFormat](./get_hilowlinesformat/)() override | Określa format HiLowLines. HiLowLines stosowane z typami wykresów HiLowClose, OpenHiLowClose, VolumeHiLowClose i VolumeOpenHiLowClose. |
| **bool** [get_IsColorVaried](./get_iscolorvaried/)() override | Określa, że każdy znacznik danych w serii ma inny kolor. Odczytaj **bool**. |
| **int8_t** [get_Overlap](./get_overlap/)() override | Określa, jak bardzo słupki i kolumny będą się nachodzić na wykresach 2D, jako procent (od -100% do 100%). |
| [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() override | Określa, jak określić, które punkty danych znajdują się w drugim kole lub słupku na wykresie pie-of-pie lub bar-of-pie. Zobacz [PieSplitType](../piesplittype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) override | Niestandardowe informacje o podziale dla wykresu pie-of-pie lub bar-of-pie z niestandardowym podziałem. Zwraca punkt danych, który ma być rysowany w drugim kole lub słupku na wykresie pie-of-pie lub bar-of-pie według indeksu. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() override | Niestandardowe informacje o podziale dla wykresu pie-of-pie lub bar-of-pie z niestandardowym podziałem. Zawiera punkty danych, które mają być rysowane w drugim kole lub słupku na wykresie pie-of-pie lub bar-of-pie. Tylko do odczytu [PieSplitCustomPointCollection](../piesplitcustompointcollection/). |
| **double** [get_PieSplitPosition](./get_piesplitposition/)() override | Określa wartość używaną do określenia, które punkty danych znajdują się w drugim kole lub słupku na wykresie pie-of-pie lub bar-of-pie. Używana razem z właściwością PieSplitBy. Odczytaj **double**. |
| **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() override | Wskazuje, czy seria tej grupy jest rysowana na drugiej osi. Tylko do odczytu **bool**. |
| **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() override | Określa rozmiar drugiego koła lub słupka wykresu pie-of-pie lub bar-of-pie, jako procent rozmiaru pierwszego koła (może wynosić od 5 do 200 procent). Odczytaj **uint16_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)\> [get_Series](./get_series/)() override | Zwraca kolekcję serii. Tylko do odczytu [IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/). |
| [CombinableSeriesTypesGroup](../combinableseriestypesgroup/) [get_Type](./get_type/)() override | Zwraca typ tej grupy serii. Tylko do odczytu [CombinableSeriesTypesGroup](../combinableseriestypesgroup/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IUpDownBarsManager](../iupdownbarsmanager/)\> [get_UpDownBars](./get_updownbars/)() override | Zapewnia dostęp do słupków górnych/dolnych wykresu liniowego lub giełdowego. Tylko do odczytu [IUpDownBarsManager](../iupdownbarsmanager/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [idx_get](./idx_get/)(**int32_t**) override | Pobiera element pod podanym indeksem. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt reprezentuje instancję typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
| [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| void [set_BubbleSizeRepresentation](./set_bubblesizerepresentation/)([BubbleSizeRepresentationType](../bubblesizerepresentationtype/)) override | Określa, jak wartości rozmiaru bąbelka są przedstawiane na wykresie bąbelkowym. Zapisz [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| void [set_BubbleSizeScale](./set_bubblesizescale/)(**int32_t**) override | Określa współczynnik skali dla wykresu bąbelkowego (może wynosić od 0 do 300 procent domyślnego rozmiaru). Zapisz **int32_t**. |
| void [set_DoughnutHoleSize](./set_doughnutholesize/)(**uint8_t**) override | Określa rozmiar otworu w wykresie pierścieniowym (może wynosić od 0 do 90 procent rozmiaru obszaru rysowania). Zapisz **uint8_t**. |
| void [set_FirstSliceAngle](./set_firstsliceangle/)(**uint16_t**) override | Ustawia kąt pierwszego segmentu wykresu kołowego lub pierścieniowego, w stopniach (zgodnie z ruchem wskazówek zegara od góry, od 0 do 360 stopni). Zapisz **uint16_t**. |
| void [set_GapDepth](./set_gapdepth/)(**uint16_t**) override | Ustawia odległość, jako procent szerokości znacznika, pomiędzy seriami danych w wykresie 3D. Zapisz **uint16_t**. |
| void [set_GapWidth](./set_gapwidth/)(**uint16_t**) override | Określa odstęp między grupami słupków lub kolumn, jako procent szerokości słupka lub kolumny. Zapisz **uint16_t**. |
| void [set_HasSeriesLines](./set_hasserieslines/)(**bool**) override | Prawda, jeśli wykres ma linie serii. Dotyczy wykresów słupkowych skumulowanych i OfPie. Zapisz **bool**. |
| void [set_IsColorVaried](./set_iscolorvaried/)(**bool**) override | Określa, że każdy znacznik danych w serii ma inny kolor. Zapisz **bool**. |
| void [set_Overlap](./set_overlap/)(**int8_t**) override | Określa, jak bardzo słupki i kolumny będą się nachodzić na wykresach 2D, jako procent (od -100% do 100%). |
| void [set_PieSplitBy](./set_piesplitby/)([PieSplitType](../piesplittype/)) override | Określa, jak określić, które punkty danych znajdują się w drugim kole lub słupku na wykresie pie-of-pie lub bar-of-pie. Zapisz [PieSplitType](../piesplittype/). |
| void [set_PieSplitPosition](./set_piesplitposition/)(**double**) override | Określa wartość, która ma być użyta do określenia, które punkty danych znajdują się w drugim kole lub słupku na wykresie pie-of-pie lub bar-of-pie. Używana razem z właściwością PieSplitBy. Zapisz **double**. |
| void [set_SecondPieSize](./set_secondpiesize/)(**uint16_t**) override | Określa rozmiar drugiego koła lub słupka wykresu pie-of-pie lub bar-of-pie, jako procent rozmiaru pierwszego koła (może wynosić od 5 do 200 procent). Zapisz **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustaw n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia zmianę wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów na string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Uwagi

1) Zobacz podsumowanie i uwagi dla klasy ChartSeriesGroupCollection oraz wyliczenia CombinableSeriesTypesGroup. 2) Grupa serii zawiera pewne właściwości serii, które są wspólne dla każdej serii w grupie ("series group properties"). "Series group properties" w klasie [ChartSeriesGroup](./) jest odczyt/zapis. Każda z "series group properties" może mieć projekcję tylko do odczytu w klasie [ChartSeries](../chartseries/).

## Zobacz także

* Klasa [IChartSeriesGroup](../ichartseriesgroup/)
* Klasa [IDOMObject](../../aspose.slides/idomobject/)
* Przestrzeń nazw [Aspose::Slides::Charts](../)
* Biblioteka [Aspose.Slides](../../)