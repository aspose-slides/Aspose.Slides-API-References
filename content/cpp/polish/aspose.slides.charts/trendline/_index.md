---
title: Trendline
second_title: Aspose.Slides for C++ – referencja API
description: Klasa reprezentuje linię trendu serii wykresu
type: docs
weight: 1366
url: /pl/aspose.slides.charts/trendline/
---
## Trendline klasa

Klasa reprezentuje linię trendu serii wykresu

```cpp
class Trendline : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::TrendlineCollection>>,
                  public Aspose::Slides::Charts::ITrendline
```

## Metody

| Metoda | Opis |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | Inicjalizuje TextFrameForOverriding tekstem w parametrze "text". Jeśli TextFrameForOverriding jest już zainicjowany, po prostu zmienia jego tekst. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN-y są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN-y są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| **double** [get_Backward](./get_backward/)() override | Określa liczbę kategorii (lub jednostek na wykresie punktowym), o które linia trendu rozciąga się przed danymi serii będącej trendowaną. Na wykresach punktowych i niepunktowych wartość musi być nieujemna. Odczyt **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Zwraca wykres nadrzędny. Tylko do odczytu [IChart](../ichart/). |
| **bool** [get_DisplayEquation](./get_displayequation/)() override | Określa, że równanie linii trendu jest wyświetlane na wykresie (w tej samej etykiecie co Rsquaredvalue). Odczyt **bool**. |
| **bool** [get_DisplayRSquaredValue](./get_displayrsquaredvalue/)() override | Określa, że wartość R-kwadrat linii trendu jest wyświetlana na wykresie (w tej samej etykiecie co równanie). Odczyt **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Reprezentuje format linii trendu. Odczyt [IFormat](../iformat/). |
| **double** [get_Forward](./get_forward/)() override | Określa liczbę kategorii (lub jednostek na wykresie punktowym), o które linia trendu rozciąga się po danych serii będącej trendowaną. Na wykresach punktowych i niepunktowych wartość musi być nieujemna. Odczyt **double**. |
| **double** [get_Intercept](./get_intercept/)() override | Określa wartość, w której linia trendu przecina oś y. Ta właściwość jest obsługiwana tylko gdy typ linii trendu to exp, linear lub poly. Odczyt **double**. |
| **uint8_t** [get_Order](./get_order/)() override | Określa stopień wielomianowej linii trendu. Jest ignorowane dla innych typów linii trendu. Wartość musi być w przedziale od 2 do 6. Odczyt **uint8_t**. |
| **uint8_t** [get_Period](./get_period/)() override | Określa okres linii trendu dla średniej kroczącej. Jest ignorowane dla innych wariantów linii trendu. Wartość musi być w przedziale od 2 do 255. Odczyt **uint8_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() override | Reprezentuje pozycję legendy związaną z tą linią trendu. Tylko do odczytu [ILegendEntryProperties](../ilegendentryproperties/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Zwraca format tekstu. Tylko do odczytu [IChartTextFormat](../icharttextformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | Może zawierać sformatowany tekst. Jeśli ta właściwość nie jest null, wtedy wartość tego sformatowanego tekstu nadpisuje automatycznie generowany tekst etykiety danych. Automatycznie generowany tekst etykiety danych oznacza tekst zarządzany przez właściwości ShowSeriesName, ShowValue, ... i formatowany przy użyciu właściwości TextFormatManager.TextFormat. Tylko do odczytu [ITextFrame](../../aspose.slides/itextframe/). |
| [System::String](../../system/string/) [get_TrendlineName](./get_trendlinename/)() override | Pobiera nazwę linii trendu. Odczyt [System::String](../../system/string/). |
| [Aspose::Slides::Charts::TrendlineType](../trendlinetype/) [get_TrendlineType](./get_trendlinetype/)() override | Pobiera typ linii trendu. Odczyt [Charts::TrendlineType](../trendlinetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt reprezentuje instancję typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie konstruktorów podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie konstruktorów podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
| void [set_Backward](./set_backward/)(**double**) override | Określa liczbę kategorii (lub jednostek na wykresie punktowym), o które linia trendu rozciąga się przed danymi serii będącej trendowaną. Na wykresach punktowych i niepunktowych wartość musi być nieujemna. Zapis **double**. |
| void [set_DisplayEquation](./set_displayequation/)(**bool**) override | Określa, że równanie linii trendu jest wyświetlane na wykresie (w tej samej etykiecie co Rsquaredvalue). Zapis **bool**. |
| void [set_DisplayRSquaredValue](./set_displayrsquaredvalue/)(**bool**) override | Określa, że wartość R-kwadrat linii trendu jest wyświetlana na wykresie (w tej samej etykiecie co równanie). Zapis **bool**. |
| void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) override | Reprezentuje format linii trendu. Zapis [IFormat](../iformat/). |
| void [set_Forward](./set_forward/)(**double**) override | Określa liczbę kategorii (lub jednostek na wykresie punktowym), o które linia trendu rozciąga się po danych serii będącej trendowaną. Na wykresach punktowych i niepunktowych wartość musi być nieujemna. Zapis **double**. |
| void [set_Intercept](./set_intercept/)(**double**) override | Określa wartość, w której linia trendu przecina oś y. Ta właściwość jest obsługiwana tylko gdy typ linii trendu to exp, linear lub poly. Zapis **double**. |
| void [set_Order](./set_order/)(**uint8_t**) override | Określa stopień wielomianowej linii trendu. Jest ignorowane dla innych typów linii trendu. Wartość musi być w przedziale 2-6. Zapis **uint8_t**. |
| void [set_Period](./set_period/)(**uint8_t**) override | Określa okres linii trendu dla średniej kroczącej. Jest ignorowane dla innych wariantów linii trendu. Wartość musi być w przedziale 2-255. Zapis **uint8_t**. |
| void [set_TrendlineName](./set_trendlinename/)([System::String](../../system/string/)) override | Ustawia nazwę linii trendu. Zapis [System::String](../../system/string/). |
| void [set_TrendlineType](./set_trendlinetype/)([Aspose::Slides::Charts::TrendlineType](../trendlinetype/)) override | Ustawia typ linii trendu. Zapis [Charts::TrendlineType](../trendlinetype/). |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala zmienić wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie należy wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie należy wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów na string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie należy wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie należy wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Usuwa obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [DomObject](../../aspose.slides/domobject/)
* Klasa [ITrendline](../itrendline/)
* Przestrzeń nazw [Aspose::Slides::Charts](../)
* Biblioteka [Aspose.Slides](../../)