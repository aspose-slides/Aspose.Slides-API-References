---
title: ChartTitle
second_title: Dokumentacja API Aspose.Slides dla C++
description: Reprezentuje właściwości tytułu wykresu.
type: docs
weight: 326
url: /pl/aspose.slides.charts/charttitle/
---
## ChartTitle klasa

Represents chart title properties.

```cpp
class ChartTitle : public Aspose::Slides::Charts::IChartTitle,
                   public Aspose::Slides::IDOMObject
```

## Metody

| Metoda | Opis |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | Inicjalizuje TextFrameForOverriding tekstem przekazanym w parametrze \"text\". Jeśli TextFrameForOverriding jest już zainicjalizowany, po prostu zmienia jego tekst. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| **float** [get_ActualHeight](./get_actualheight/)() override | Określa rzeczywistą wysokość elementu wykresu. Wywołaj metodę [IChart::ValidateChartLayout](../ichart/validatechartlayout/) przed uzyskaniem rzeczywistych wartości. Odczyt **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | Określa rzeczywistą szerokość elementu wykresu. Wywołaj metodę [IChart::ValidateChartLayout](../ichart/validatechartlayout/) przed uzyskaniem rzeczywistych wartości. Odczyt **float**. |
| **float** [get_ActualX](./get_actualx/)() override | Określa rzeczywistą pozycję x (lewy) elementu wykresu względem lewego górnego rogu wykresu. Wywołaj metodę [IChart::ValidateChartLayout](../ichart/validatechartlayout/) przed uzyskaniem rzeczywistych wartości. Odczyt **float**. |
| **float** [get_ActualY](./get_actualy/)() override | Określa rzeczywistą górną krawędź elementu wykresu względem lewego górnego rogu wykresu. Wywołaj metodę [IChart::ValidateChartLayout](../ichart/validatechartlayout/) przed uzyskaniem rzeczywistych wartości. Odczyt **float**. |
| **float** [get_Bottom](./get_bottom/)() override | Dół. Tylko do odczytu **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Zwraca nadrzędny wykres. Tylko do odczytu [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Zwraca style wypełnienia, linii i efektów tytułu. Tylko do odczytu [IFormat](../iformat/). |
| **float** [get_Height](./get_height/)() override | Zwraca wysokość tytułu jako ułamek wysokości wykresu. Odczyt **float**. |
| **bool** [get_Overlay](./get_overlay/)() override | Określa, czy inne elementy wykresu mogą nakładać się na tytuł. Odczyt **bool**. |
| **float** [get_Right](./get_right/)() override | Prawo. Tylko do odczytu **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Zwraca format tekstu. Tylko do odczytu [IChartTextFormat](../icharttextformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | Może zawierać tekst sformatowany bogatym formatowaniem. Jeśli ta właściwość nie jest nullem, wartość tego sformatowanego tekstu zastępuje automatycznie generowany tekst. Automatycznie generowany tekst jest domyślną właściwością etykiety danych, etykiety jednostki wyświetlania osi wartości, tytułu osi, tytułu wykresu, etykiety linii trendu. Automatycznie generowany tekst jest formatowany przy użyciu właściwości [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/). Tylko do odczytu [ITextFrame](../../aspose.slides/itextframe/). |
| **float** [get_Width](./get_width/)() override | Zwraca szerokość tytułu jako ułamek szerokości wykresu. Odczyt **float**. |
| **float** [get_X](./get_x/)() override | Zwraca współrzędną x tytułu jako ułamek szerokości wykresu. Odczyt **float**. |
| **float** [get_Y](./get_y/)() override | Zwraca współrzędną y tytułu jako ułamek wysokości wykresu. Odczyt **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogiczna metoda do C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analogiczny wywołaniu C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analogiczny operator 'is' w C#. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie statementu C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnicy [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogiczna metoda do C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. W rzeczywistości nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. W rzeczywistości nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartości z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku łańcuchów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| void [set_Height](./set_height/)(**float**) override | Ustawia wysokość tytułu jako ułamek wysokości wykresu. Zapis **float**. |
| void [set_Overlay](./set_overlay/)(**bool**) override | Określa, czy inne elementy wykresu mogą nakładać się na tytuł. Zapis **bool**. |
| void [set_Width](./set_width/)(**float**) override | Ustawia szerokość tytułu jako ułamek szerokości wykresu. Zapis **float**. |
| void [set_X](./set_x/)(**float**) override | Ustawia współrzędną x tytułu jako ułamek szerokości wykresu. Zapis **float**. |
| void [set_Y](./set_y/)(**float**) override | Ustawia współrzędną y tytułu jako ułamek wysokości wykresu. Zapis **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj smart pointerów lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj smart pointerów lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogiczna metoda do C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów do łańcucha. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie statementu C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnicy [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj smart pointerów lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj smart pointerów lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [IChartTitle](../icharttitle/)
* Klasa [IDOMObject](../../aspose.slides/idomobject/)
* Przestrzeń nazw [Aspose::Slides::Charts](../)
* Biblioteka [Aspose.Slides](../../)