---
title: IDataLabelFormat
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Reprezentuje opcje formatowania dla DataLabel.
type: docs
weight: 963
url: /pl/aspose.slides.charts/idatalabelformat/
---
## IDataLabelFormat klasa


Reprezentuje opcje formatowania dla [DataLabel](../datalabel/).

```cpp
class IDataLabelFormat : public Aspose::Slides::Charts::IFormattedTextContainer
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu C# [Object.Equals](../../system/object/equals/) semantyki. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Zwraca wykres. Tylko do odczytu [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Reprezentuje format etykiety danych. Tylko do odczytu [IFormat](../iformat/). |
| virtual **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() | Odczyt **bool**. |
| virtual [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() | Reprezentuje ciąg formatu dla obiektu DataLabels. Odczyt [System::String](../../system/string/). |
| virtual [LegendDataLabelPosition](../legenddatalabelposition/) [get_Position](./get_position/)() | Reprezentuje pozycję etykiety danych. Odczyt [LegendDataLabelPosition](../legenddatalabelposition/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Zwraca prezentację. Tylko do odczytu [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::String](../../system/string/) [get_Separator](./get_separator/)() | Ustawia lub zwraca Variant reprezentujący separator używany dla etykiet danych na wykresie. Odczyt [System::String](../../system/string/). |
| virtual **bool** [get_ShowBubbleSize](./get_showbubblesize/)() | Reprezentuje zachowanie wyświetlania wartości rozmiaru bąbelka etykiety danych określonego wykresu. Prawda wyświetla wartość rozmiaru bąbelka. Fałsz ukrywa. Odczyt **bool**. |
| virtual **bool** [get_ShowCategoryName](./get_showcategoryname/)() | Reprezentuje zachowanie wyświetlania nazwy kategorii etykiety danych określonego wykresu. Prawda wyświetla nazwę kategorii dla etykiet danych na wykresie. Fałsz ukrywa. Odczyt **bool**. |
| virtual **bool** [get_ShowLabelAsDataCallout](./get_showlabelasdatacallout/)() | Określa, czy etykieta danych określonego wykresu będzie wyświetlana jako dymek danych, czy jako etykieta danych. |
| virtual **bool** [get_ShowLabelValueFromCell](./get_showlabelvaluefromcell/)() | Reprezentuje zachowanie wyświetlania wartości komórki etykiety danych określonego wykresu. Prawda wyświetla wartość komórki. Fałsz ukrywa. Odczyt **bool**. |
| virtual **bool** [get_ShowLeaderLines](./get_showleaderlines/)() | Reprezentuje zachowanie wyświetlania linii prowadzących etykiety danych określonego wykresu. Prawda wyświetla linie prowadzące. Fałsz ukrywa. Odczyt **bool**. |
| virtual **bool** [get_ShowLegendKey](./get_showlegendkey/)() | Reprezentuje zachowanie wyświetlania klucza legendy etykiety danych określonego wykresu. Prawda, jeśli klucz legendy etykiety danych jest widoczny. Odczyt **bool**. |
| virtual **bool** [get_ShowPercentage](./get_showpercentage/)() | Reprezentuje zachowanie wyświetlania wartości procentowej etykiety danych określonego wykresu. Prawda wyświetla wartość procentową. Fałsz ukrywa. Odczyt **bool**. |
| virtual **bool** [get_ShowSeriesName](./get_showseriesname/)() | Zwraca wartość Boolean wskazującą zachowanie wyświetlania nazwy serii dla etykiet danych na wykresie. Prawda aby pokazać nazwę serii. Fałsz aby ukryć. Odczyt **bool**. |
| virtual **bool** [get_ShowValue](./get_showvalue/)() | Reprezentuje zachowanie wyświetlania wartości procentowej etykiety danych określonego wykresu. Prawda wyświetla wartość procentową. Fałsz ukrywa. Odczyt **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Zwraca podstawowy slajd. Tylko do odczytu [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Zwraca format tekstu wykresu. Tylko do odczytu [IChartTextFormat](../icharttextformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt reprezentuje instancję typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. W rzeczywistości nic nie kopiuje, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie przy konstruowaniu podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. W rzeczywistości nic nie kopiuje, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie przy konstruowaniu podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
| virtual void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) | Zapis **bool**. |
| virtual void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) | Reprezentuje ciąg formatu dla obiektu DataLabels. Zapis [System::String](../../system/string/). |
| virtual void [set_Position](./set_position/)([LegendDataLabelPosition](../legenddatalabelposition/)) | Reprezentuje pozycję etykiety danych. Zapis [LegendDataLabelPosition](../legenddatalabelposition/). |
| virtual void [set_Separator](./set_separator/)([System::String](../../system/string/)) | Ustawia lub zwraca Variant reprezentujący separator używany dla etykiet danych na wykresie. Zapis [System::String](../../system/string/). |
| virtual void [set_ShowBubbleSize](./set_showbubblesize/)(**bool**) | Reprezentuje zachowanie wyświetlania wartości rozmiaru bąbelka etykiety danych określonego wykresu. Prawda wyświetla wartość rozmiaru bąbelka. Fałsz ukrywa. Zapis **bool**. |
| virtual void [set_ShowCategoryName](./set_showcategoryname/)(**bool**) | Reprezentuje zachowanie wyświetlania nazwy kategorii etykiety danych określonego wykresu. Prawda wyświetla nazwę kategorii dla etykiet danych na wykresie. Fałsz ukrywa. Zapis **bool**. |
| virtual void [set_ShowLabelAsDataCallout](./set_showlabelasdatacallout/)(**bool**) | Określa, czy etykieta danych określonego wykresu będzie wyświetlana jako dymek danych, czy jako etykieta danych. |
| virtual void [set_ShowLabelValueFromCell](./set_showlabelvaluefromcell/)(**bool**) | Reprezentuje zachowanie wyświetlania wartości komórki etykiety danych określonego wykresu. Prawda wyświetla wartość komórki. Fałsz ukrywa. Zapis **bool**. |
| virtual void [set_ShowLeaderLines](./set_showleaderlines/)(**bool**) | Reprezentuje zachowanie wyświetlania linii prowadzących etykiety danych określonego wykresu. Prawda wyświetla linie prowadzące. Fałsz ukrywa. Zapis **bool**. |
| virtual void [set_ShowLegendKey](./set_showlegendkey/)(**bool**) | Reprezentuje zachowanie wyświetlania klucza legendy etykiety danych określonego wykresu. Prawda, jeśli klucz legendy etykiety danych jest widoczny. Zapis **bool**. |
| virtual void [set_ShowPercentage](./set_showpercentage/)(**bool**) | Reprezentuje zachowanie wyświetlania wartości procentowej etykiety danych określonego wykresu. Prawda wyświetla wartość procentową. Fałsz ukrywa. Zapis **bool**. |
| virtual void [set_ShowSeriesName](./set_showseriesname/)(**bool**) | Ustawia wartość Boolean wskazującą zachowanie wyświetlania nazwy serii dla etykiet danych na wykresie. Prawda aby pokazać nazwę serii. Fałsz aby ukryć. Zapis **bool**. |
| virtual void [set_ShowValue](./set_showvalue/)(**bool**) | Reprezentuje zachowanie wyświetlania wartości procentowej etykiety danych określonego wykresu. Prawda wyświetla wartość procentową. Fałsz ukrywa. Zapis **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala na przełączanie wskaźników w kontenerach do trybu słabego. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów na ciąg znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz też

* Klasa [IFormattedTextContainer](../iformattedtextcontainer/)
* Przestrzeń nazw [Aspose::Slides::Charts](../)
* Biblioteka [Aspose.Slides](../../)