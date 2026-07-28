---
title: Legend
second_title: Aspose.Slides dla C++ – referencja API
description: Reprezentuje właściwości legendy wykresu.
type: docs
weight: 1262
url: /pl/aspose.slides.charts/legend/
---
## Klasa Legend


Reprezentuje właściwości legendy wykresu.

```cpp
class Legend : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::Chart>>,
               public Aspose::Slides::Charts::ILegend
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równe żadnej wartości, włączając NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równe żadnej wartości, włączając NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| **float** [get_ActualHeight](./get_actualheight/)() override | Określa rzeczywistą wysokość elementu wykresu. Wywołaj metodę [IChart::ValidateChartLayout](../ichart/validatechartlayout/) przed uzyskaniem rzeczywistych wartości. Odczyt **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | Określa rzeczywistą szerokość elementu wykresu. Wywołaj metodę [IChart::ValidateChartLayout](../ichart/validatechartlayout/) przed uzyskaniem rzeczywistych wartości. Odczyt **float**. |
| **float** [get_ActualX](./get_actualx/)() override | Określa rzeczywistą pozycję x (lewy) elementu wykresu względem lewego górnego rogu wykresu. Wywołaj metodę [IChart::ValidateChartLayout](../ichart/validatechartlayout/) przed uzyskaniem rzeczywistych wartości. Odczyt **float**. |
| **float** [get_ActualY](./get_actualy/)() override | Określa rzeczywistą górną pozycję elementu wykresu względem lewego górnego rogu wykresu. Wywołaj metodę [IChart::ValidateChartLayout](../ichart/validatechartlayout/) przed uzyskaniem rzeczywistych wartości. Odczyt **float**. |
| **float** [get_Bottom](./get_bottom/)() override | Dół. Tylko do odczytu **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Zwraca wykres. Tylko do odczytu [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryCollection](../ilegendentrycollection/)\> [get_Entries](./get_entries/)() override | Pobiera wpisy legendy. Tylko do odczytu [ILegendEntryCollection](../ilegendentrycollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_Entry](./get_entry/)(**int32_t**) override | Pobiera właściwości wpisu legendy odpowiadającego punktowi danych w wykresie pod określonym indeksem. W przypadku typów wykresów: bar-of-pie, exploded pie, exploded pie 3D, pie, pie 3D, pie-of-pie, punkt danych jest pobierany z pierwszej serii. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Zwraca format legendy. Tylko do odczytu [IFormat](../iformat/). |
| **float** [get_Height](./get_height/)() override | Zwraca wysokość legendy jako ułamek wysokości wykresu. Odczyt **float**. |
| **bool** [get_Overlay](./get_overlay/)() override | Określa, czy inne elementy wykresu mogą nakładać się na legendę. Odczyt **bool**. |
| [LegendPositionType](../legendpositiontype/) [get_Position](./get_position/)() override | Określa pozycję legendy na wykresie. Wartości nie-NaN właściwości X, Y, Width, Heigt nadpisują efekt tej właściwości. Odczyt [LegendPositionType](../legendpositiontype/). |
| **float** [get_Right](./get_right/)() override | Prawa. Tylko do odczytu **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Format tekstu. Tylko do odczytu [IChartTextFormat](../icharttextformat/). |
| **float** [get_Width](./get_width/)() override | Zwraca szerokość legendy jako ułamek szerokości wykresu. Odczyt **float**. |
| **float** [get_X](./get_x/)() override | Zwraca współrzędną x legendy jako ułamek szerokości wykresu. Odczyt **float**. |
| **float** [get_Y](./get_y/)() override | Zwraca współrzędną y legendy jako ułamek wysokości wykresu. Odczyt **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
| void [set_Height](./set_height/)(**float**) override | Ustawia wysokość legendy jako ułamek wysokości wykresu. Zapis **float**. |
| void [set_Overlay](./set_overlay/)(**bool**) override | Określa, czy inne elementy wykresu mogą nakładać się na legendę. Zapis **bool**. |
| void [set_Position](./set_position/)([LegendPositionType](../legendpositiontype/)) override | Określa pozycję legendy na wykresie. Wartości nie-NaN właściwości X, Y, Width, Heigt nadpisują efekt tej właściwości. Zapis [LegendPositionType](../legendpositiontype/). |
| void [set_Width](./set_width/)(**float**) override | Ustawia szerokość legendy jako ułamek szerokości wykresu. Zapis **float**. |
| void [set_X](./set_x/)(**float**) override | Ustawia współrzędną x legendy jako ułamek szerokości wykresu. Zapis **float**. |
| void [set_Y](./set_y/)(**float**) override | Ustawia współrzędną y legendy jako ułamek wysokości wykresu. Zapis **float**. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala na przełączanie wskaźników w kontenerach do trybu słabego. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Inkrementuje współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Dekrementuje i zwraca współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów do stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Inkrementuje słaby licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Dekrementuje słaby licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zniszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [DomObject](../../aspose.slides/domobject/)
* Klasa [ILegend](../ilegend/)
* Przestrzeń nazw [Aspose::Slides::Charts](../)
* Biblioteka [Aspose.Slides](../../)