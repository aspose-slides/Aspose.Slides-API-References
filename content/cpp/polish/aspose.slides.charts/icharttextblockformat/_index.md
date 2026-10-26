---
title: IChartTextBlockFormat
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Reprezentuje właściwości formatowania elementów tekstu wykresu.
type: docs
weight: 885
url: /pl/aspose.slides.charts/icharttextblockformat/
---
## IChartTextBlockFormat klasa


Reprezentuje właściwości formatowania elementów tekstu wykresu.

```cpp
class IChartTextBlockFormat : public virtual System::Object
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typów referencyjnych w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typów wartościowych w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| virtual [TextAnchorType](../../aspose.slides/textanchortype/) [get_AnchoringType](./get_anchoringtype/)() | Zwraca pionowy tekst kotwicy w [TextFrame](../../aspose.slides/textframe/). Przeczytaj [TextAnchorType](../../aspose.slides/textanchortype/). |
| virtual [TextAutofitType](../../aspose.slides/textautofittype/) [get_AutofitType](./get_autofittype/)() | Zwraca tryb automatycznego dopasowania tekstu. Zmiana tej właściwości może mieć określony wpływ tylko na następujące części wykresu: [DataLabel](../datalabel/) i [DataLabelFormat](../datalabelformat/) (pełne wsparcie w PowerPoint 2013; w PowerPoint 2007 nie ma wpływu na renderowanie). Przeczytaj [TextAutofitType](../../aspose.slides/textautofittype/). |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_CenterText](./get_centertext/)() | Jeśli [NullableBool::True](../../aspose.slides/nullablebool/), tekst powinien być wyśrodkowany w poziomie w ramce. Przeczytaj [NullableBool](../../aspose.slides/nullablebool/). |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | Zwraca dolny margines (punkty) w [TextFrame](../../aspose.slides/textframe/). Zmiana tej właściwości może mieć określony wpływ tylko na następujące części wykresu: [DataLabel](../datalabel/) i [DataLabelFormat](../datalabelformat/) (pełne wsparcie w PowerPoint 2013; w PowerPoint 2007 nie ma wpływu na renderowanie). Przeczytaj **double**. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | Zwraca lewy margines (punkty) w [TextFrame](../../aspose.slides/textframe/). Zmiana tej właściwości może mieć określony wpływ tylko na następujące części wykresu: [DataLabel](../datalabel/) i [DataLabelFormat](../datalabelformat/) (pełne wsparcie w PowerPoint 2013; w PowerPoint 2007 nie ma wpływu na renderowanie). Przeczytaj **double**. |
| virtual **double** [get_MarginRight](./get_marginright/)() | Zwraca prawy margines (punkty) w [TextFrame](../../aspose.slides/textframe/). Zmiana tej właściwości może mieć określony wpływ tylko na następujące części wykresu: [DataLabel](../datalabel/) i [DataLabelFormat](../datalabelformat/) (pełne wsparcie w PowerPoint 2013; w PowerPoint 2007 nie ma wpływu na renderowanie). Przeczytaj **double**. |
| virtual **double** [get_MarginTop](./get_margintop/)() | Zwraca górny margines (punkty) w [TextFrame](../../aspose.slides/textframe/). Zmiana tej właściwości może mieć określony wpływ tylko na następujące części wykresu: [DataLabel](../datalabel/) i [DataLabelFormat](../datalabelformat/) (pełne wsparcie w PowerPoint 2013; w PowerPoint 2007 nie ma wpływu na renderowanie). Przeczytaj **double**. |
| virtual **float** [get_RotationAngle](./get_rotationangle/)() | Określa niestandardowy obrót stosowany do tekstu w obrębie ramki. Jeśli nie jest określony, używany jest obrót towarzyszącego kształtu. Jeśli jest określony, zostaje zastosowany niezależnie od kształtu. To znaczy, że kształt może mieć zastosowany obrót oprócz obrotu samego tekstu. Uzyskana wartość wizualnego obrotu tekstu podsumowana z tej właściwości i predefiniowanego typu pionowego w właściwości TextVerticalType. Przeczytaj **float**. |
| virtual [Aspose::Slides::TextVerticalType](../../aspose.slides/textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | Określa orientację tekstu. Uzyskana wartość wizualnego obrotu tekstu podsumowana z tej właściwości i własnego kąta w właściwości RotationAngle. Przeczytaj [Slides::TextVerticalType](../../aspose.slides/textverticaltype/). |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_WrapText](./get_wraptext/)() | **True** jeśli tekst jest zawijany przy marginesach [TextFrame](../../aspose.slides/textframe/). Zmiana tej właściwości może mieć określony wpływ tylko na następujące części wykresu: [DataLabel](../datalabel/) i [DataLabelFormat](../datalabelformat/) (pełne wsparcie w PowerPoint 2007/2013). Przeczytaj [NullableBool](../../aspose.slides/nullablebool/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie niestandardowych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie niestandardowych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. W rzeczywistości nic nie kopiuje, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. W rzeczywistości nic nie kopiuje, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku łańcucha znaków i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku łańcuchów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
| virtual void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../../aspose.slides/textanchortype/)) | Ustawia pionowy tekst kotwicy w [TextFrame](../../aspose.slides/textframe/). Zapisz [TextAnchorType](../../aspose.slides/textanchortype/). |
| virtual void [set_AutofitType](./set_autofittype/)([TextAutofitType](../../aspose.slides/textautofittype/)) | Ustawia tryb automatycznego dopasowania tekstu. Zmiana tej właściwości może mieć określony wpływ tylko na następujące części wykresu: [DataLabel](../datalabel/) i [DataLabelFormat](../datalabelformat/) (pełne wsparcie w PowerPoint 2013; w PowerPoint 2007 nie ma wpływu na renderowanie). Zapisz [TextAutofitType](../../aspose.slides/textautofittype/). |
| virtual void [set_CenterText](./set_centertext/)([NullableBool](../../aspose.slides/nullablebool/)) | Jeśli [NullableBool::True](../../aspose.slides/nullablebool/), tekst powinien być wyśrodkowany w poziomie w ramce. Zapisz [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | Ustawia dolny margines (punkty) w [TextFrame](../../aspose.slides/textframe/). Zmiana tej właściwości może mieć określony wpływ tylko na następujące części wykresu: [DataLabel](../datalabel/) i [DataLabelFormat](../datalabelformat/) (pełne wsparcie w PowerPoint 2013; w PowerPoint 2007 nie ma wpływu na renderowanie). Zapisz **double**. |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | Ustawia lewy margines (punkty) w [TextFrame](../../aspose.slides/textframe/). Zmiana tej właściwości może mieć określony wpływ tylko na następujące części wykresu: [DataLabel](../datalabel/) i [DataLabelFormat](../datalabelformat/) (pełne wsparcie w PowerPoint 2013; w PowerPoint 2007 nie ma wpływu na renderowanie). Zapisz **double**. |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | Ustawia prawy margines (punkty) w [TextFrame](../../aspose.slides/textframe/). Zmiana tej właściwości może mieć określony wpływ tylko na następujące części wykresu: [DataLabel](../datalabel/) i [DataLabelFormat](../datalabelformat/) (pełne wsparcie w PowerPoint 2013; w PowerPoint 2007 nie ma wpływu na renderowanie). Zapisz **double**. |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | Ustawia górny margines (punkty) w [TextFrame](../../aspose.slides/textframe/). Zmiana tej właściwości może mieć określony wpływ tylko na następujące części wykresu: [DataLabel](../datalabel/) i [DataLabelFormat](../datalabelformat/) (pełne wsparcie w PowerPoint 2013; w PowerPoint 2007 nie ma wpływu na renderowanie). Zapisz **double**. |
| virtual void [set_RotationAngle](./set_rotationangle/)(**float**) | Określa niestandardowy obrót stosowany do tekstu w obrębie ramki. Jeśli nie jest określony, używany jest obrót towarzyszącego kształtu. Jeśli jest określony, zostaje zastosowany niezależnie od kształtu. To znaczy, że kształt może mieć zastosowany obrót oprócz obrotu samego tekstu. Uzyskana wartość wizualnego obrotu tekstu podsumowana z tej właściwości i własnego kąta w właściwości RotationAngle. Zapisz **float**. |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../../aspose.slides/textverticaltype/)) | Określa orientację tekstu. Uzyskana wartość wizualnego obrotu tekstu podsumowana z tej właściwości i własnego kąta w właściwości RotationAngle. Zapisz [Slides::TextVerticalType](../../aspose.slides/textverticaltype/). |
| virtual void [set_WrapText](./set_wraptext/)([NullableBool](../../aspose.slides/nullablebool/)) | **True** jeśli tekst jest zawijany przy marginesach [TextFrame](../../aspose.slides/textframe/). Zmiana tej właściwości może mieć określony wpływ tylko na następujące części wykresu: [DataLabel](../datalabel/) i [DataLabelFormat](../datalabelformat/) (pełne wsparcie w PowerPoint 2007/2013). Zapisz [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwertowanie niestandardowych obiektów na łańcuch znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa słaby licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza słaby licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [Object](../../system/object/)
* Przestrzeń nazw [Aspose::Slides::Charts](../)
* Biblioteka [Aspose.Slides](../../)