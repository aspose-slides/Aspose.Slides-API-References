---
title: DataLabelFormat
second_title: Aspose.Slides dla C++ – referencja API
description: Reprezentuje opcje formatowania etykiety danych.
type: docs
weight: 391
url: /pl/aspose.slides.charts/datalabelformat/
---
## DataLabelFormat klasa


Reprezentuje opcje formatowania dla [DataLabel](../datalabel/).

```cpp
class DataLabelFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::Charts::IDataLabelFormat
```

## Metody

| Method | Description |
| --- | --- |
| **bool** [Equals](../../aspose.slides/pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Porównuje z określonym obiektem. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Zwraca wykres. Tylko do odczytu [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Reprezentuje format etykiety danych. Tylko do odczytu [IFormat](../iformat/). |
| **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() override | Odczyt **bool**. |
| [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() override | Reprezentuje ciąg formatu dla obiektu DataLabels. Odczyt [System::String](../../system/string/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../../aspose.slides/idomobject/)\> [get_Parent_Immediate](../../aspose.slides/idomobject/get_parent_immediate/)() | Zwraca obiekt Parent_Immediate. Tylko do odczytu [IDOMObject](../../aspose.slides/idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | Zwraca rodzica [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). Tylko do odczytu [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [LegendDataLabelPosition](../legenddatalabelposition/) [get_Position](./get_position/)() override | Reprezentuje pozycję etykiety danych. Odczyt [LegendDataLabelPosition](../legenddatalabelposition/). |
| [System::String](../../system/string/) [get_Separator](./get_separator/)() override | Ustawia lub zwraca Variant reprezentujący separator używany w etykietach danych na wykresie. Odczyt [System::String](../../system/string/). |
| **bool** [get_ShowBubbleSize](./get_showbubblesize/)() override | Reprezentuje zachowanie wyświetlania wartości rozmiaru bąbelka etykiety danych określonego wykresu. True wyświetla wartość rozmiaru bąbelka. False ukrywa. Odczyt **bool**. |
| **bool** [get_ShowCategoryName](./get_showcategoryname/)() override | Reprezentuje zachowanie wyświetlania nazwy kategorii etykiety danych określonego wykresu. True wyświetla nazwę kategorii dla etykiet danych na wykresie. False ukrywa. Odczyt **bool**. |
| **bool** [get_ShowLabelAsDataCallout](./get_showlabelasdatacallout/)() override | Określa, czy etykieta danych określonego wykresu będzie wyświetlana jako odwołanie danych czy jako etykieta danych. |
| **bool** [get_ShowLabelValueFromCell](./get_showlabelvaluefromcell/)() override | Reprezentuje zachowanie wyświetlania wartości komórki etykiety danych określonego wykresu. True wyświetla wartość komórki. False ukrywa. Odczyt **bool**. |
| **bool** [get_ShowLeaderLines](./get_showleaderlines/)() override | Reprezentuje zachowanie wyświetlania linii prowadzących etykiety danych określonego wykresu. True wyświetla linie prowadzące. False ukrywa. Odczyt **bool**. |
| **bool** [get_ShowLegendKey](./get_showlegendkey/)() override | Reprezentuje zachowanie wyświetlania klucza legendy etykiety danych określonego wykresu. True, jeśli klucz legendy etykiety danych jest widoczny. Odczyt **bool**. |
| **bool** [get_ShowPercentage](./get_showpercentage/)() override | Reprezentuje zachowanie wyświetlania wartości procentowej etykiety danych określonego wykresu. True wyświetla wartość procentową. False ukrywa. Odczyt **bool**. |
| **bool** [get_ShowSeriesName](./get_showseriesname/)() override | Zwraca wartość Boolean wskazującą zachowanie wyświetlania nazwy serii dla etykiet danych na wykresie. True wyświetla nazwę serii. False ukrywa. Odczyt **bool**. |
| **bool** [get_ShowValue](./get_showvalue/)() override | Reprezentuje zachowanie wyświetlania wartości procentowej etykiety danych określonego wykresu. True wyświetla wartość procentową. False ukrywa. Odczyt **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Zwraca format tekstu wykresu. Tylko do odczytu [IChartTextFormat](../icharttextformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| **int32_t** [GetHashCode](../../aspose.slides/pviobject/gethashcode/)() const override | Zwraca kod skrótu. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt reprezentuje instancję typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie typów niestandardowych. |
| [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartości z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
| void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) override | Zapis **bool**. |
| void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) override | Reprezentuje ciąg formatu dla obiektu DataLabels. Zapis [System::String](../../system/string/). |
| void [set_Position](./set_position/)([LegendDataLabelPosition](../legenddatalabelposition/)) override | Reprezentuje pozycję etykiety danych. Zapis [LegendDataLabelPosition](../legenddatalabelposition/). |
| void [set_Separator](./set_separator/)([System::String](../../system/string/)) override | Ustawia lub zwraca Variant reprezentujący separator używany w etykietach danych na wykresie. Zapis [System::String](../../system/string/). |
| void [set_ShowBubbleSize](./set_showbubblesize/)(**bool**) override | Reprezentuje zachowanie wyświetlania wartości rozmiaru bąbelka etykiety danych określonego wykresu. True wyświetla wartość rozmiaru bąbelka. False ukrywa. Zapis **bool**. |
| void [set_ShowCategoryName](./set_showcategoryname/)(**bool**) override | Reprezentuje zachowanie wyświetlania nazwy kategorii etykiety danych określonego wykresu. True wyświetla nazwę kategorii dla etykiet danych na wykresie. False ukrywa. Zapis **bool**. |
| void [set_ShowLabelAsDataCallout](./set_showlabelasdatacallout/)(**bool**) override | Określa, czy etykieta danych określonego wykresu będzie wyświetlana jako odwołanie danych czy jako etykieta danych. |
| void [set_ShowLabelValueFromCell](./set_showlabelvaluefromcell/)(**bool**) override | Reprezentuje zachowanie wyświetlania wartości komórki etykiety danych określonego wykresu. True wyświetla wartość komórki. False ukrywa. Zapis **bool**. |
| void [set_ShowLeaderLines](./set_showleaderlines/)(**bool**) override | Reprezentuje zachowanie wyświetlania linii prowadzących etykiety danych określonego wykresu. True wyświetla linie prowadzące. False ukrywa. Zapis **bool**. |
| void [set_ShowLegendKey](./set_showlegendkey/)(**bool**) override | Reprezentuje zachowanie wyświetlania klucza legendy etykiety danych określonego wykresu. True, jeśli klucz legendy etykiety danych jest widoczny. Zapis **bool**. |
| void [set_ShowPercentage](./set_showpercentage/)(**bool**) override | Reprezentuje zachowanie wyświetlania wartości procentowej etykiety danych określonego wykresu. True wyświetla wartość procentową. False ukrywa. Zapis **bool**. |
| void [set_ShowSeriesName](./set_showseriesname/)(**bool**) override | Ustawia wartość Boolean wskazującą zachowanie wyświetlania nazwy serii dla etykiet danych na wykresie. True wyświetla nazwę serii. False ukrywa. Zapis **bool**. |
| void [set_ShowValue](./set_showvalue/)(**bool**) override | Reprezentuje zachowanie wyświetlania wartości procentowej etykiety danych określonego wykresu. True wyświetla wartość procentową. False ukrywa. Zapis **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwertowanie obiektów niestandardowych na ciąg znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa słaby licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza słaby licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../../aspose.slides/pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Usuwa obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |
## Zobacz także

* Klasa [PVIObject](../../aspose.slides/pviobject/)
* Klasa [IDataLabelFormat](../idatalabelformat/)
* Przestrzeń nazw [Aspose::Slides::Charts](../)
* Biblioteka [Aspose.Slides](../../)