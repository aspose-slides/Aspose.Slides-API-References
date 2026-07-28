---
title: IChartData
second_title: Aspose.Slides dla C++ Referencja API
description: Reprezentuje dane używane do rysowania wykresu.
type: docs
weight: 651
url: /pl/aspose.slides.charts/ichartdata/
---
## IChartData klasa

Reprezentuje dane używane do rysowania wykresu.

```cpp
class IChartData : public virtual System::Object
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych podwójnej precyzji w stylu C#, w którym dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategoryCollection](../ichartcategorycollection/)\> [get_Categories](./get_categories/)() | Pobiera główne kategorie (lub zarówno główne jak i podrzędne, jeśli [IChartData::set_UseSecondaryCategories](./set_usesecondarycategories/) jest ustawione na false). Tylko do odczytu [IChartCategoryCollection](../ichartcategorycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategory](../ichartcategory/)\> [get_Category](./get_category/)(**int32_t**) | Zwraca główną kategorię pod podanym indeksem. Jeśli [get_UseSecondaryCategories](./get_usesecondarycategories/) jest false, pobiera spośród wszystkich kategorii. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataWorkbook](../ichartdataworkbook/)\> [get_ChartDataWorkbook](./get_chartdataworkbook/)() | Pobiera fabrykę komórek służącą do tworzenia komórek używanych w seriach wykresu lub kategoriach. Tylko do odczytu [IChartDataWorkbook](../ichartdataworkbook/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) | Zwraca serię pod podanym indeksem. |
| virtual [ChartDataSourceType](../chartdatasourcetype/) [get_DataSourceType](./get_datasourcetype/)() | Reprezentuje źródło danych wykresu |
| virtual [WorkbookType](../workbooktype/) [get_EmbeddedWorkbookType](./get_embeddedworkbooktype/)() | Pobiera typ wbudowanego skoroszytu. Zwraca [WorkbookType::NotDefined](../workbooktype/), jeśli [IChartData::get_DataSourceType](./get_datasourcetype/) jest [ChartDataSourceType::ExternalWorkbook](../chartdatasourcetype/). Tylko do odczytu [WorkbookType](../workbooktype/). |
| virtual [System::String](../../system/string/) [get_ExternalWorkbookPath](./get_externalworkbookpath/)() | Reprezentuje ścieżkę do zewnętrznego skoroszytu, jeśli źródło danych jest zewnętrzne, w przeciwnym razie null |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategoryCollection](../ichartcategorycollection/)\> [get_SecondaryCategories](./get_secondarycategories/)() | Pobiera podrzędne kategorie, jeśli [IChartData::get_UseSecondaryCategories](./get_usesecondarycategories/) jest true. Tylko do odczytu [IChartCategoryCollection](../ichartcategorycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategory](../ichartcategory/)\> [get_SecondaryCategory](./get_secondarycategory/)(**int32_t**) | Zwraca podrzędną kategorię pod podanym indeksem. Jeśli [get_UseSecondaryCategories](./get_usesecondarycategories/) jest false, wtedy [IChartData::get_SecondaryCategories](./get_secondarycategories/) jest null. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesCollection](../ichartseriescollection/)\> [get_Series](./get_series/)() | Pobiera serie. Tylko do odczytu [IChartSeriesCollection](../ichartseriescollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_SeriesGroup](./get_seriesgroup/)([System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\>) |  |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_SeriesGroup](./get_seriesgroup/)(**int32_t**) | Zwraca grupę serii pod podanym indeksem. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroupCollection](../ichartseriesgroupcollection/)\> [get_SeriesGroups](./get_seriesgroups/)() | Pobiera grupy serii. Tylko do odczytu [IChartSeriesGroupCollection](../ichartseriesgroupcollection/). |
| virtual **bool** [get_UseSecondaryCategories](./get_usesecondarycategories/)() | Jeśli ustawione na false, [IChartData::get_SecondaryCategories](./get_secondarycategories/) zwraca null i dane w [IChartData::get_Categories](./get_categories/) są używane zarówno dla serii głównej jak i podrzędnej. Jeśli ustawione na true, dane w [IChartData::get_SecondaryCategories](./get_secondarycategories/) są używane dla serii podrzędnej, a dane w [IChartData::get_Categories](./get_categories/) są używane dla serii głównej. Odczyt **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual [System::String](../../system/string/) [GetRange](./getrange/)() | Pobiera zakres danych wykresu. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IO::MemoryStream](../../system.io/memorystream/)\> [ReadWorkbookStream](./readworkbookstream/)() | Zapisuje wewnętrznie zawarty skoroszyt [Excel](../../aspose.slides.excel/) do strumienia w pamięci. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
| virtual void [set_UseSecondaryCategories](./set_usesecondarycategories/)(**bool**) | Jeśli ustawione na false, [IChartData::get_SecondaryCategories](./get_secondarycategories/) zwraca null i dane w [IChartData::get_Categories](./get_categories/) są używane zarówno dla serii głównej jak i podrzędnej. Jeśli ustawione na true, dane w [IChartData::get_SecondaryCategories](./get_secondarycategories/) są używane dla serii podrzędnej, a dane w [IChartData::get_Categories](./get_categories/) są używane dla serii głównej. Zapis **bool**. |
| virtual void [SetExternalWorkbook](./setexternalworkbook/)([System::String](../../system/string/)) | Ustawia zewnętrzny skoroszyt jako źródło danych wykresu. Dane [Chart](../chart/) zostaną zaktualizowane z docelowego skoroszytu. |
| virtual void [SetExternalWorkbook](./setexternalworkbook/)([System::String](../../system/string/), **bool**) | Ustawia zewnętrzny skoroszyt jako źródło danych wykresu. |
| virtual void [SetRange](./setrange/)([System::String](../../system/string/)) | Ustawia zakres danych wykresu. Serie i kategorie zostaną zaktualizowane na podstawie nowego zakresu danych. Jeśli liczba serii w zakresie danych jest większa niż liczba serii w danych wykresu, dodatkowe serie z tym samym typem co ostatnia seria w bieżącej kolekcji zostaną dodane na koniec kolekcji. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączyć wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie należy wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie należy wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual void [SwitchRowColumn](./switchrowcolumn/)() | Zamienia dane względem osi. Dane wykreślane na osi X zostaną przeniesione na oś Y i odwrotnie. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów na string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowywanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa słaby licznik referencji. Nie należy wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza słaby licznik referencji. Nie należy wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual void [WriteWorkbookStream](./writeworkbookstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::MemoryStream](../../system.io/memorystream/)\>) | Inicjalizuje wewnętrznie zawarty skoroszyt [Excel](../../aspose.slides.excel/) wartością określoną przez użytkownika. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [Object](../../system/object/)
* Przestrzeń nazw [Aspose::Slides::Charts](../)
* Biblioteka [Aspose.Slides](../../)