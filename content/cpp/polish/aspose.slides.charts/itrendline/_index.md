---
title: ITrendline
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Klasa reprezentuje linię trendu serii wykresu
type: docs
weight: 1223
url: /pl/aspose.slides.charts/itrendline/
---
## ITrendline class

Klasa reprezentuje linię trendu serii wykresu

```cpp
class ITrendline : public Aspose::Slides::Charts::IOverridableText
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | Inicjalizuje TextFrameForOverriding tekstem w parametrze "text". Jeśli TextFrameForOverriding jest już zainicjalizowany, po prostu zmienia jego tekst. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartości w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| virtual **double** [get_Backward](./get_backward/)() | Określa liczbę kategorii (lub jednostek na wykresie punktowym), o które linia trendu rozciąga się przed danymi serii będącej trendowaną. Na wykresach punktowych i niepunktowych wartość może być dowolną nieujemną wartością. Odczyt **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Zwraca wykres. Tylko do odczytu [IChart](../ichart/). |
| virtual **bool** [get_DisplayEquation](./get_displayequation/)() | Określa, że równanie linii trendu jest wyświetlane na wykresie (w tej samej etykiecie co wartość Rsquared). Odczyt **bool**. |
| virtual **bool** [get_DisplayRSquaredValue](./get_displayrsquaredvalue/)() | Określa, że wartość R-kwadrat linii trendu jest wyświetlana na wykresie (w tej samej etykiecie co równanie). Odczyt **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Reprezentuje format linii trendu. Odczyt [IFormat](../iformat/). |
| virtual **double** [get_Forward](./get_forward/)() | Określa liczbę kategorii (lub jednostek na wykresie punktowym), o które linia trendu rozciąga się po danych serii będącej trendowaną. Na wykresach punktowych i niepunktowych wartość może być dowolną nieujemną wartością. Odczyt **double**. |
| virtual **double** [get_Intercept](./get_intercept/)() | Określa wartość, w której linia trendu przecina oś Y. Właściwość jest obsługiwana tylko gdy typ linii trendu to exp, linear lub poly. Odczyt **double**. |
| virtual **uint8_t** [get_Order](./get_order/)() | Określa stopień wielomianowej linii trendu. Jest ignorowane dla innych typów linii trendu. Wartość musi mieścić się w przedziale od 2 do 6. Odczyt **uint8_t**. |
| virtual **uint8_t** [get_Period](./get_period/)() | Określa okres linii trendu dla linii trendu średniej kroczącej. Jest ignorowane dla innych wariantów linii trendu. Wartość musi być pomiędzy 2 a 255. Odczyt **uint8_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Zwraca prezentację. Tylko do odczytu [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() | Reprezentuje pozycję legendy powiązaną z tą linią trendu. Tylko do odczytu [ILegendEntryProperties](../ilegendentryproperties/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Zwraca slajd bazowy. Tylko do odczytu [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Zwraca format tekstu wykresu. Tylko do odczytu [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | Może zawierać sformatowany tekst. Jeśli ta właściwość nie jest równa null, wartość tego sformatowanego tekstu nadpisuje tekst generowany automatycznie. Tekst generowany automatycznie jest implicytną właściwością etykiety danych, etykiety jednostki wyświetlania osi wartości, tytułu osi, tytułu wykresu, etykiety linii trendu. Tekst generowany automatycznie jest formatowany przy użyciu właściwości [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/). Tylko do odczytu [ITextFrame](../../aspose.slides/itextframe/). |
| virtual [System::String](../../system/string/) [get_TrendlineName](./get_trendlinename/)() | Pobiera nazwę linii trendu. Odczyt [System::String](../../system/string/). |
| virtual [Aspose::Slides::Charts::TrendlineType](../trendlinetype/) [get_TrendlineType](./get_trendlinetype/)() | Pobiera typ linii trendu. Odczyt [TrendlineType](../trendlinetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie obiektów niestandardowych. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu stróżującego [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie typów niestandardowych. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartości z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągu znaków i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| virtual void [set_Backward](./set_backward/)(**double**) | Określa liczbę kategorii (lub jednostek na wykresie punktowym), o które linia trendu rozciąga się przed danymi serii będącej trendowaną. Na wykresach punktowych i niepunktowych wartość może być dowolną nieujemną wartością. Zapis **double**. |
| virtual void [set_DisplayEquation](./set_displayequation/)(**bool**) | Określa, że równanie linii trendu jest wyświetlane na wykresie (w tej samej etykiecie co wartość Rsquared). Zapis **bool**. |
| virtual void [set_DisplayRSquaredValue](./set_displayrsquaredvalue/)(**bool**) | Określa, że wartość R-kwadrat linii trendu jest wyświetlana na wykresie (w tej samej etykiecie co równanie). Zapis **bool**. |
| virtual void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) | Reprezentuje format linii trendu. Zapis [IFormat](../iformat/). |
| virtual void [set_Forward](./set_forward/)(**double**) | Określa liczbę kategorii (lub jednostek na wykresie punktowym), o które linia trendu rozciąga się po danych serii będącej trendowaną. Na wykresach punktowych i niepunktowych wartość może być dowolną nieujemną wartością. Zapis **double**. |
| virtual void [set_Intercept](./set_intercept/)(**double**) | Określa wartość, w której linia trendu przecina oś Y. Właściwość jest obsługiwana tylko gdy typ linii trendu to exp, linear lub poly. Zapis **double**. |
| virtual void [set_Order](./set_order/)(**uint8_t**) | Określa stopień wielomianowej linii trendu. Jest ignorowane dla innych typów linii trendu. Wartość musi mieścić się w przedziale od 2 do 6. Zapis **uint8_t**. |
| virtual void [set_Period](./set_period/)(**uint8_t**) | Określa okres linii trendu dla linii trendu średniej kroczącej. Jest ignorowane dla innych wariantów linii trendu. Wartość musi być pomiędzy 2 a 255. Zapis **uint8_t**. |
| virtual void [set_TrendlineName](./set_trendlinename/)([System::String](../../system/string/)) | Ustawia nazwę linii trendu. Zapis [System::String](../../system/string/). |
| virtual void [set_TrendlineType](./set_trendlinetype/)([Aspose::Slides::Charts::TrendlineType](../trendlinetype/)) | Ustawia typ linii trendu. Zapis [TrendlineType](../trendlinetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera aktualną wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję obiektów niestandardowych na łańcuch znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu stróżującego [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [IOverridableText](../ioverridabletext/)
* Przestrzeń nazw [Aspose::Slides::Charts](../)
* Biblioteka [Aspose.Slides](../../)