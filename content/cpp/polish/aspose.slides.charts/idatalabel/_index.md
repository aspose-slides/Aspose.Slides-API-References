---
title: IDataLabel
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Reprezentuje etykiety serii.
type: docs
weight: 937
url: /pl/aspose.slides.charts/idatalabel/
---
## IDataLabel klasa

Reprezentuje etykiety serii.

```cpp
class IDataLabel : public Aspose::Slides::Charts::ILayoutable,
                   public Aspose::Slides::Charts::IOverridableText,
                   public Aspose::Slides::Charts::IActualLayout
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | Inicjalizuje TextFrameForOverriding tekstem przekazanym w parametrze "text". Jeśli TextFrameForOverriding jest już zainicjowany, po prostu zmienia jego tekst. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, gdzie dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, gdzie dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | Określa rzeczywistą wysokość elementu wykresu. Wywołaj metodę [IChart::ValidateChartLayout](../ichart/validatechartlayout/) przed, aby uzyskać rzeczywiste wartości. Odczyt **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | Określa rzeczywistą szerokość elementu wykresu. Wywołaj metodę [IChart::ValidateChartLayout](../ichart/validatechartlayout/) przed, aby uzyskać rzeczywiste wartości. Odczyt **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | Określa rzeczywistą pozycję x (lewy) elementu wykresu względem lewego górnego rogu wykresu. Wywołaj metodę [IChart::ValidateChartLayout](../ichart/validatechartlayout/) przed, aby uzyskać rzeczywiste wartości. Odczyt **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | Określa rzeczywistą górną krawędź elementu wykresu względem lewego górnego rogu wykresu. Wywołaj metodę [IChart::ValidateChartLayout](../ichart/validatechartlayout/) przed, aby uzyskać rzeczywiste wartości. Odczyt **float**. |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | Pobiera górę elementu wykresu jako ułamek wysokości wykresu. Tylko do odczytu **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Zwraca wykres. Tylko do odczytu [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataLabelFormat](../idatalabelformat/)\> [get_DataLabelFormat](./get_datalabelformat/)() | Zwraca format etykiety danych. Tylko do odczytu [IDataLabelFormat](../idatalabelformat/). |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | Określa wysokość elementu wykresu jako ułamek wysokości wykresu. Odczyt **float**. |
| virtual **bool** [get_IsVisible](./get_isvisible/)() | False oznacza, że etykieta danych nie jest widoczna (a więc wszystkie flagi Show* (ShowValue, ...) są false). Tylko do odczytu **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Zwraca prezentację. Tylko do odczytu [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | Pobiera prawą krawędź elementu wykresu jako ułamek szerokości wykresu. Tylko do odczytu **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Zwraca podstawowy slajd. Tylko do odczytu [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Zwraca format tekstu wykresu. Tylko do odczytu [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | Może zawierać sformatowany tekst. Jeśli ta właściwość nie jest nullem, wartość tego sformatowanego tekstu zastępuje automatycznie generowany tekst. Automatycznie generowany tekst jest implicytną właściwością etykiety danych, etykiety jednostki wyświetlania osi wartości, tytułu osi, tytułu wykresu, etykiety linii trendu. Automatycznie generowany tekst jest formatowany przy użyciu właściwości [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/). Tylko do odczytu [ITextFrame](../../aspose.slides/itextframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [get_ValueFromCell](./get_valuefromcell/)() | Pobiera komórkę danych skoroszytu. Stosowane, jeśli właściwość IDataLabelFormat::get(set)_ShowLabelValueFromCell ma wartość true. |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | Określa szerokość elementu wykresu jako ułamek szerokości wykresu. Odczyt **float**. |
| virtual **float** [get_X](../ilayoutable/get_x/)() | Określa pozycję x (lewo) elementu wykresu jako ułamek szerokości wykresu. Odczyt **float**. |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | Określa górę elementu wykresu jako ułamek wysokości wykresu. Odczyt **float**. |
| virtual [System::String](../../system/string/) [GetActualLabelText](./getactuallabeltext/)() | Zwraca rzeczywisty tekst etykiety na podstawie [DataLabelFormat](../datalabelformat/) ustawień lub wartości TextFrameForOverriding.Text. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogiczna metoda C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analogiczna wywołanie C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual void [Hide](./hide/)() | Ukrywa etykietę danych, ustawiając wszystkie flagi Show* (ShowValue, ...) na stan false. IsVisible będzie false po tej operacji. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę statementu C# lock(). Wywołaj bezpośrednio lub użyj obiektu ochronnego [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogiczna metoda C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku stringów. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | Określa wysokość elementu wykresu jako ułamek wysokości wykresu. Zapis **float**. |
| virtual void [set_ValueFromCell](./set_valuefromcell/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\>) | Ustawia komórkę danych skoroszytu. Stosowane, jeśli właściwość IDataLabelFormat::get(set)_ShowLabelValueFromCell ma wartość true. |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | Określa szerokość elementu wykresu jako ułamek szerokości wykresu. Zapis **float**. |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | Określa pozycję x (lewo) elementu wykresu jako ułamek szerokości wykresu. Zapis **float**. |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | Określa górę elementu wykresu jako ułamek wysokości wykresu. Zapis **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogiczna metoda C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów na string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie statementu C# lock(). Wywołaj bezpośrednio lub użyj obiektu ochronnego [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [ILayoutable](../ilayoutable/)
* Klasa [IOverridableText](../ioverridabletext/)
* Klasa [IActualLayout](../iactuallayout/)
* Przestrzeń nazw [Aspose::Slides::Charts](../)
* Biblioteka [Aspose.Slides](../../)