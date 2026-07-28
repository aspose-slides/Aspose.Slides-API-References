---
title: ChartPlotArea
second_title: Aspose.Slides dla C++ – odniesienie API
description: Reprezentuje prostokąt, w którym powinien być rysowany wykres.
type: docs
weight: 248
url: /pl/aspose.slides.charts/chartplotarea/
---
## ChartPlotArea klasa


Reprezentuje prostokąt, w którym powinien być rysowany wykres.

```cpp
class ChartPlotArea : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::Chart>>,
                      public Aspose::Slides::Charts::IChartPlotArea
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartości w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| **float** [get_ActualHeight](./get_actualheight/)() override | Określa rzeczywistą wysokość elementu wykresu. Wywołaj metodę [IChart::ValidateChartLayout](../ichart/validatechartlayout/) wcześniej, aby uzyskać rzeczywiste wartości. Odczytaj **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | Określa rzeczywistą szerokość elementu wykresu. Wywołaj metodę [IChart::ValidateChartLayout](../ichart/validatechartlayout/) wcześniej, aby uzyskać rzeczywiste wartości. Odczytaj **float**. |
| **float** [get_ActualX](./get_actualx/)() override | Określa rzeczywistą pozycję x (lewo) elementu wykresu względem lewego górnego rogu wykresu. Wywołaj metodę [IChart::ValidateChartLayout](../ichart/validatechartlayout/) wcześniej, aby uzyskać rzeczywiste wartości. Odczytaj **float**. |
| **float** [get_ActualY](./get_actualy/)() override | Określa rzeczywistą górę elementu wykresu względem lewego górnego rogu wykresu. Wywołaj metodę [IChart::ValidateChartLayout](../ichart/validatechartlayout/) wcześniej, aby uzyskać rzeczywiste wartości. Odczytaj **float**. |
| **float** [get_Bottom](./get_bottom/)() override | Dół. Tylko do odczytu **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | [Chart](../chart/). Tylko do odczytu [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Zwraca format obszaru wykresu. Tylko do odczytu [IFormat](../iformat/). |
| **float** [get_Height](./get_height/)() override | Zwraca wysokość ramki ograniczającej obszar wykresu jako ułamek wysokości wykresu (od 0 do 1). Odczytaj **float**. |
| **bool** [get_IsLocationAutocalculated](./get_islocationautocalculated/)() | Definiuje sposób obliczania położenia: true – obliczane automatycznie; określone przez własności X, Y, Width, Height. Tylko do odczytu **bool**. |
| [Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/) [get_LayoutTargetType](./get_layouttargettype/)() override | Jeśli układ obszaru wykresu jest definiowany ręcznie, własność ta określa, czy układać obszar wykresu wewnątrz (bez osi i etykiet osi) czy na zewnątrz (z osiami i etykietami). Odczytaj [LayoutTargetType](../layouttargettype/). |
| **float** [get_Right](./get_right/)() override | Prawa strona. Tylko do odczytu **float**. |
| **float** [get_Width](./get_width/)() override | Zwraca szerokość ramki ograniczającej obszar wykresu jako ułamek szerokości wykresu (od 0 do 1). Odczytaj **float**. |
| **float** [get_X](./get_x/)() override | Zwraca współrzędną x lewego górnego rogu ramki ograniczającej obszar wykresu jako ułamek szerokości wykresu (od 0 do 1). Odczytaj **float**. |
| **float** [get_Y](./get_y/)() override | Zwraca współrzędną y lewego górnego rogu ramki ograniczającej obszar wykresu jako ułamek wysokości wykresu (od 0 do 1). Odczytaj **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji skojarzoną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje niczego, właściwie, tylko inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje niczego, właściwie, tylko inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartości z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| void [set_Height](./set_height/)(**float**) override | Ustawia wysokość ramki ograniczającej obszar wykresu jako ułamek wysokości wykresu (od 0 do 1). Zapisz **float**. |
| void [set_LayoutTargetType](./set_layouttargettype/)([Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/)) override | Jeśli układ obszaru wykresu jest definiowany ręcznie, własność ta określa, czy układać obszar wykresu wewnątrz (bez osi i etykiet osi) czy na zewnątrz (z osiami i etykietami). Zapisz [LayoutTargetType](../layouttargettype/). |
| void [set_Width](./set_width/)(**float**) override | Ustawia szerokość ramki ograniczającej obszar wykresu jako ułamek szerokości wykresu (od 0 do 1). Zapisz **float**. |
| void [set_X](./set_x/)(**float**) override | Ustawia współrzędną x lewego górnego rogu ramki ograniczającej obszar wykresu jako ułamek szerokości wykresu (od 0 do 1). Zapisz **float**. |
| void [set_Y](./set_y/)(**float**) override | Ustawia współrzędną y lewego górnego rogu ramki ograniczającej obszar wykresu jako ułamek wysokości wykresu (od 0 do 1). Zapisz **float**. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów na ciąg znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [DomObject](../../aspose.slides/domobject/)
* Klasa [IChartPlotArea](../ichartplotarea/)
* Przestrzeń nazw [Aspose::Slides::Charts](../)
* Biblioteka [Aspose.Slides](../../)