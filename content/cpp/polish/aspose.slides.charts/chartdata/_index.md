---
title: ChartData
second_title: Aspose.Slides dla C++ – odniesienie API
description: Reprezentuje dane używane do tworzenia wykresu.
type: docs
weight: 118
url: /pl/aspose.slides.charts/chartdata/
---
## ChartData klasa

Represents data used for a chart plotting.

```cpp
class ChartData : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::Chart>>,
                  public Aspose::Slides::Charts::IChartData
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartCategoryCollection](../ichartcategorycollection/)\> [get_Categories](./get_categories/)() override | Pobiera główne kategorie (lub zarówno główne, jak i podrzędne kategorie, jeśli [ChartData::set_UseSecondaryCategories](./set_usesecondarycategories/) jest ustawione na false). Tylko do odczytu [IChartCategoryCollection](../ichartcategorycollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartCategory](../ichartcategory/)\> [get_Category](./get_category/)(**int32_t**) override | Zwraca główną kategorię pod podanym indeksem. Jeśli [get_UseSecondaryCategories](./get_usesecondarycategories/) jest false, pobiera spośród wszystkich kategorii. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataWorkbook](../ichartdataworkbook/)\> [get_ChartDataWorkbook](./get_chartdataworkbook/)() override | Pobiera fabrykę komórek służącą do tworzenia komórek używanych w seriach wykresu lub kategoriach. Tylko do odczytu [IChartDataWorkbook](../ichartdataworkbook/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) override | Zwraca serię pod podanym indeksem. |
| [ChartDataSourceType](../chartdatasourcetype/) [get_DataSourceType](./get_datasourcetype/)() override | Reprezentuje ścieżkę do zewnętrznego skoroszytu, jeśli źródło danych jest zewnętrzne, w przeciwnym razie null |
| [WorkbookType](../workbooktype/) [get_EmbeddedWorkbookType](./get_embeddedworkbooktype/)() override | Pobiera typ osadzonego skoroszytu. Zwraca [WorkbookType::NotDefined](../workbooktype/), jeśli [ChartData::get_DataSourceType](./get_datasourcetype/) jest [ChartDataSourceType::ExternalWorkbook](../chartdatasourcetype/). Tylko do odczytu [WorkbookType](../workbooktype/). |
| [System::String](../../system/string/) [get_ExternalWorkbookPath](./get_externalworkbookpath/)() override | Reprezentuje źródło danych wykresu |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartCategoryCollection](../ichartcategorycollection/)\> [get_SecondaryCategories](./get_secondarycategories/)() override | Pobiera podrzędne kategorie, jeśli [ChartData::get_UseSecondaryCategories](./get_usesecondarycategories/) jest true. Tylko do odczytu [IChartCategoryCollection](../ichartcategorycollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartCategory](../ichartcategory/)\> [get_SecondaryCategory](./get_secondarycategory/)(**int32_t**) override | Zwraca podrzędną kategorię pod podanym indeksem. Jeśli [get_UseSecondaryCategories](./get_usesecondarycategories/) jest false, wtedy [ChartData::get_SecondaryCategories](./get_secondarycategories/) jest null. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesCollection](../ichartseriescollection/)\> [get_Series](./get_series/)() override | Pobiera serie. Tylko do odczytu [IChartSeriesCollection](../ichartseriescollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_SeriesGroup](./get_seriesgroup/)([System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\>) override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_SeriesGroup](./get_seriesgroup/)(**int32_t**) override | Zwraca grupę serii pod podanym indeksem. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroupCollection](../ichartseriesgroupcollection/)\> [get_SeriesGroups](./get_seriesgroups/)() override | Pobiera grupy serii. Tylko do odczytu [IChartSeriesGroupCollection](../ichartseriesgroupcollection/). |
| **bool** [get_UseSecondaryCategories](./get_usesecondarycategories/)() override | Jeśli ustawione na false, wtedy [ChartData::get_SecondaryCategories](./get_secondarycategories/) zwraca null i dane w [ChartData::get_Categories](./get_categories/) są używane zarówno dla serii głównych, jak i podrzędnych. Jeśli ustawione na true, wtedy dane w [ChartData::get_SecondaryCategories](./get_secondarycategories/) są używane dla serii podrzędnych, a dane w [ChartData::get_Categories](./get_categories/) są używane dla serii głównych. Odczyt **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| [System::String](../../system/string/) [GetRange](./getrange/)() override | Pobiera zakres danych wykresu. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt reprezentuje instancję typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu ochronnego [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. W rzeczywistości nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. W rzeczywistości nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::IO::MemoryStream](../../system.io/memorystream/)\> [ReadWorkbookStream](./readworkbookstream/)() override | Zapisuje wewnętrznie zawarty skoroszyt [Excel](../../aspose.slides.excel/) do strumienia w pamięci. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku stringów. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
| void [set_UseSecondaryCategories](./set_usesecondarycategories/)(**bool**) override | Jeśli ustawione na false, wtedy [ChartData::get_SecondaryCategories](./get_secondarycategories/) zwraca null i dane w [ChartData::get_Categories](./get_categories/) są używane zarówno dla serii głównych, jak i podrzędnych. Jeśli ustawione na true, wtedy dane w [ChartData::get_SecondaryCategories](./get_secondarycategories/) są używane dla serii podrzędnych, a dane w [ChartData::get_Categories](./get_categories/) są używane dla serii głównych. Zapis **bool**. |
| void [SetExternalWorkbook](./setexternalworkbook/)([System::String](../../system/string/)) override | Ustawia zewnętrzny skoroszyt jako źródło danych dla wykresu. [Chart](../chart/) dane będą aktualizowane z docelowego skoroszytu. |
| void [SetExternalWorkbook](./setexternalworkbook/)([System::String](../../system/string/), **bool**) override | Ustawia zewnętrzny skoroszyt jako źródło danych dla wykresu. |
| void [SetRange](./setrange/)([System::String](../../system/string/)) override | Ustaw zakres danych wykresu. Serie i kategorie zostaną zaktualizowane na podstawie nowego zakresu danych. Jeśli liczba serii w zakresie danych jest większa niż liczba serii w danych wykresu, dodatkowe serie o tym samym typie co ostatnia seria w bieżącej kolekcji zostaną dodane na koniec kolekcji. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Ustaw n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [SwitchRowColumn](./switchrowcolumn/)() override | Zamień dane na osi. Dane wykreślone na osi X zostaną przeniesione na oś Y i odwrotnie. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwertowanie własnych obiektów na string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu ochronnego [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WriteWorkbookStream](./writeworkbookstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::MemoryStream](../../system.io/memorystream/)\>) override | Inicjalizuje wewnętrznie zawarty skoroszyt [Excel](../../aspose.slides.excel/) wartością podaną przez użytkownika. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [DomObject](../../aspose.slides/domobject/)
* Klasa [IChartData](../ichartdata/)
* Przestrzeń nazw [Aspose::Slides::Charts](../)
* Biblioteka [Aspose.Slides](../../)