---
title: IChartParagraphFormat
second_title: Dokumentacja API Aspose.Slides dla C++
description: Reprezentuje właściwości formatowania akapitu wykresu.
type: docs
weight: 781
url: /pl/aspose.slides.charts/ichartparagraphformat/
---
## IChartParagraphFormat klasa

Represents a paragraph formatting properties of a chart.

```cpp
class IChartParagraphFormat : public virtual System::Object
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartości w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| virtual [TextAlignment](../../aspose.slides/textalignment/) [get_Alignment](./get_alignment/)() | Zwraca wyrównanie tekstu w akapicie. Czytaj [TextAlignment](../../aspose.slides/textalignment/). |
| virtual **float** [get_DefaultTabSize](./get_defaulttabsize/)() | Zwraca domyślny rozmiar tabulacji. Czytaj **float**. |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() | Określa, czy w akapicie używane jest łamanie linii w stylu wschodnioazjatyckim. Czytaj [NullableBool](../../aspose.slides/nullablebool/). |
| virtual [Aspose::Slides::FontAlignment](../../aspose.slides/fontalignment/) [get_FontAlignment](./get_fontalignment/)() | Zwraca wyrównanie czcionki w akapicie. Czytaj [Slides::FontAlignment](../../aspose.slides/fontalignment/). |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() | Określa, czy w akapicie używana jest wieszająca interpunkcja. Czytaj [NullableBool](../../aspose.slides/nullablebool/). |
| virtual **float** [get_Indent](./get_indent/)() | Zwraca wcięcie pierwszej linii/ wieszające wcięcie akapitu. Wieszające wcięcie może być określone wartościami ujemnymi. Czytaj **float**. |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() | Określa, czy w akapicie używane jest łamanie linii łacińskie. Czytaj [NullableBool](../../aspose.slides/nullablebool/). |
| virtual **float** [get_MarginLeft](./get_marginleft/)() | Zwraca lewy margines w akapicie. Czytaj **float**. |
| virtual **float** [get_MarginRight](./get_marginright/)() | Zwraca prawy margines w akapicie. Czytaj **float**. |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_RightToLeft](./get_righttoleft/)() | Określa, czy w akapicie używany jest zapis od prawej do lewej. Czytaj [NullableBool](../../aspose.slides/nullablebool/). |
| virtual **float** [get_SpaceAfter](./get_spaceafter/)() | Zwraca ilość odstępu po ostatniej linii w akapicie. Czytaj **float**. |
| virtual **float** [get_SpaceBefore](./get_spacebefore/)() | Zwraca ilość odstępu przed pierwszą linią w akapicie. Czytaj **float**. |
| virtual **float** [get_SpaceWithin](./get_spacewithin/)() | Zwraca ilość odstępu między liniami bazowymi w akapicie. Czytaj **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITab](../../aspose.slides/itab/)\> [get_Tab](./get_tab/)(**int32_t**) | Zwraca tabulację akapitu podanym indeksie. Tylko do odczytu [Aspose::Slides::ITab](../../aspose.slides/itab/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../../aspose.slides/itabcollection/)\> [get_Tabs](./get_tabs/)() | Zwraca tabulacje akapitu. Tylko do odczytu [ITabCollection](../../aspose.slides/itabcollection/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. W rzeczywistości nic nie kopiuje, jedynie inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. W rzeczywistości nic nie kopiuje, jedynie inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartości z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku stringów. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| virtual void [set_Alignment](./set_alignment/)([TextAlignment](../../aspose.slides/textalignment/)) | Ustawia wyrównanie tekstu w akapicie. Zapisz [TextAlignment](../../aspose.slides/textalignment/). |
| virtual void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) | Ustawia domyślny rozmiar tabulacji. Zapisz **float**. |
| virtual void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../../aspose.slides/nullablebool/)) | Określa, czy w akapicie używane jest łamanie linii w stylu wschodnioazjatyckim. Zapisz [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../../aspose.slides/fontalignment/)) | Ustawia wyrównanie czcionki w akapicie. Zapisz [Slides::FontAlignment](../../aspose.slides/fontalignment/). |
| virtual void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../../aspose.slides/nullablebool/)) | Określa, czy w akapicie używana jest wieszająca interpunkcja. Zapisz [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_Indent](./set_indent/)(**float**) | Ustawia wcięcie pierwszej linii/wieszające wcięcie akapitu. Wieszające wcięcie może być określone wartościami ujemnymi. Zapisz **float**. |
| virtual void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../../aspose.slides/nullablebool/)) | Określa, czy w akapicie używane jest łamanie linii łacińskie. Zapisz [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_MarginLeft](./set_marginleft/)(**float**) | Ustawia lewy margines w akapicie. Zapisz **float**. |
| virtual void [set_MarginRight](./set_marginright/)(**float**) | Ustawia prawy margines w akapicie. Zapisz **float**. |
| virtual void [set_RightToLeft](./set_righttoleft/)([NullableBool](../../aspose.slides/nullablebool/)) | Określa, czy w akapicie używany jest zapis od prawej do lewej. Zapisz [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_SpaceAfter](./set_spaceafter/)(**float**) | Ustawia ilość odstępu po ostatniej linii w akapicie. Zapisz **float**. |
| virtual void [set_SpaceBefore](./set_spacebefore/)(**float**) | Ustawia ilość odstępu przed pierwszą linią w akapicie. Zapisz **float**. |
| virtual void [set_SpaceWithin](./set_spacewithin/)(**float**) | Ustawia ilość odstępu między liniami bazowymi w akapicie. Zapisz **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustaw n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala zmienić wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera aktualną wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów do string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [Object](../../system/object/)
* Przestrzeń nazw [Aspose::Slides::Charts](../)
* Biblioteka [Aspose.Slides](../../)