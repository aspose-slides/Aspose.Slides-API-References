---
title: ParagraphFormat
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Ta klasa zawiera właściwości formatowania akapitu. W przeciwieństwie do IParagraphFormatEffectiveData, wszystkie właściwości tej klasy są zapisywalne.
type: docs
weight: 4668
url: /pl/aspose.slides/paragraphformat/
---
## ParagraphFormat klasa


Ta klasa zawiera właściwości formatowania akapitu. W przeciwieństwie do [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/), wszystkie właściwości tej klasy są zapisywalne.

```cpp
class ParagraphFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::IParagraphFormat,
                        public Aspose::Slides::Charts::IChartParagraphFormat
```

## Metody

| Metoda | Opis |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Porównuje z podanym obiektem. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() override | Zwraca wyrównanie tekstu w akapicie bez dziedziczenia. Czytaj [TextAlignment](../textalignment/). |
| **float** [get_DefaultTabSize](./get_defaulttabsize/)() override | Zwraca domyślny rozmiar tabulacji bez dziedziczenia. Czytaj **float**. |
| [NullableBool](../nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() override | Określa, czy w akapicie używany jest przełamanie linii wschodnioazjatyckie. Nie zastosowano dziedziczenia. Czytaj [NullableBool](../nullablebool/). |
| [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() override | Zwraca wyrównanie czcionki w akapicie bez dziedziczenia. Czytaj [Slides::FontAlignment](../fontalignment/). |
| [NullableBool](../nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() override | Określa, czy w akapicie używana jest wieszająca interpunkcja. Nie zastosowano dziedziczenia. Czytaj [NullableBool](../nullablebool/). |
| **float** [get_Indent](./get_indent/)() override | Zwraca wcięcie pierwszej linii/wcięcie wiszące akapitu bez dziedziczenia. Wcięcie wiszące może być określone wartością ujemną. Czytaj **float**. |
| [NullableBool](../nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() override | Określa, czy w akapicie używany jest przełamanie linii łacińskiej. Nie zastosowano dziedziczenia. Czytaj [NullableBool](../nullablebool/). |
| **float** [get_MarginLeft](./get_marginleft/)() override | Zwraca lewy margines w akapicie bez dziedziczenia. Czytaj **float**. |
| **float** [get_MarginRight](./get_marginright/)() override | Zwraca prawy margines w akapicie bez dziedziczenia. Czytaj **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Zwraca obiekt Parent_Immediate. Tylko do odczytu [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Zwraca rodzica [IPresentationComponent](../ipresentationcomponent/). Tylko do odczytu [IPresentationComponent](../ipresentationcomponent/). |
| [NullableBool](../nullablebool/) [get_RightToLeft](./get_righttoleft/)() override | Określa, czy w akapicie używany jest zapis od prawej do lewej. Nie zastosowano dziedziczenia. Czytaj [NullableBool](../nullablebool/). |
| **float** [get_SpaceAfter](./get_spaceafter/)() override | Zwraca ilość odstępu po ostatniej linii w akapicie bez dziedziczenia. Wartość dodatnia określa procent rozmiaru czcionki, jaki ma zajmować biały odstęp. Wartość ujemna określa rozmiar białego odstępu w punktach. Czytaj **float**. |
| **float** [get_SpaceBefore](./get_spacebefore/)() override | Zwraca ilość odstępu przed pierwszą linią w akapicie bez dziedziczenia. Wartość dodatnia określa procent rozmiaru czcionki, jaki ma zajmować biały odstęp. Wartość ujemna określa rozmiar białego odstępu w punktach. Czytaj **float**. |
| **float** [get_SpaceWithin](./get_spacewithin/)() override | Zwraca ilość odstępu pomiędzy liniami bazowymi w akapicie. Wartość dodatnia oznacza procent, ujemna - rozmiar w punktach. Nie zastosowano dziedziczenia. Czytaj **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\> [get_Tab](./get_tab/)(**int32_t**) override | Zwraca tabulację akapitu o podanym indeksie. Nie zastosowano dziedziczenia. Tylko do odczytu [Aspose::Slides::ITab](../itab/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../itabcollection/)\> [get_Tabs](./get_tabs/)() override | Zwraca tabulacje akapitu. Nie zastosowano dziedziczenia. Tylko do odczytu [ITabCollection](../itabcollection/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę licznika referencji powiązaną z obiektem. |
| [System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)\> [GetEffective](./geteffective/)() override | Pobiera skuteczne dane formatowania akapitu z zastosowanym dziedziczeniem. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Zwraca kod skrótu. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analogiczny do wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analogiczny do operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogiczny do metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie typów niestandardowych. |
| [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie konstruktorów klas pochodnych. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie konstruktorów klas pochodnych. |
| [ParagraphFormat](./paragraphformat/)() | Inicjalizuje nową instancję klasy [ParagraphFormat](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o określoną wartość. |
| void [set_Alignment](./set_alignment/)([TextAlignment](../textalignment/)) override | Ustawia wyrównanie tekstu w akapicie bez dziedziczenia. Zapisz [TextAlignment](../textalignment/). |
| void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) override | Ustawia domyślny rozmiar tabulacji bez dziedziczenia. Zapisz **float**. |
| void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../nullablebool/)) override | Określa, czy w akapicie używany jest przełamanie linii wschodnioazjatyckie. Nie zastosowano dziedziczenia. Zapisz [NullableBool](../nullablebool/). |
| void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../fontalignment/)) override | Ustawia wyrównanie czcionki w akapicie bez dziedziczenia. Zapisz [Slides::FontAlignment](../fontalignment/). |
| void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../nullablebool/)) override | Określa, czy w akapicie używana jest wieszająca interpunkcja. Nie zastosowano dziedziczenia. Zapisz [NullableBool](../nullablebool/). |
| void [set_Indent](./set_indent/)(**float**) override | Ustawia wcięcie pierwszej linii/wcięcie wiszące akapitu bez dziedziczenia. Wcięcie wiszące może być określone wartością ujemną. Zapisz **float**. |
| void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../nullablebool/)) override | Określa, czy w akapicie używany jest przełamanie linii łacińskiej. Nie zastosowano dziedziczenia. Zapisz [NullableBool](../nullablebool/). |
| void [set_MarginLeft](./set_marginleft/)(**float**) override | Ustawia lewy margines w akapicie bez dziedziczenia. Zapisz **float**. |
| void [set_MarginRight](./set_marginright/)(**float**) override | Ustawia prawy margines w akapicie bez dziedziczenia. Zapisz **float**. |
| void [set_RightToLeft](./set_righttoleft/)([NullableBool](../nullablebool/)) override | Określa, czy w akapicie używany jest zapis od prawej do lewej. Nie zastosowano dziedziczenia. Zapisz [NullableBool](../nullablebool/). |
| void [set_SpaceAfter](./set_spaceafter/)(**float**) override | Ustawia ilość odstępu po ostatniej linii w akapicie bez dziedziczenia. Wartość dodatnia określa procent rozmiaru czcionki, jaki ma zajmować biały odstęp. Wartość ujemna określa rozmiar białego odstępu w punktach. Zapisz **float**. |
| void [set_SpaceBefore](./set_spacebefore/)(**float**) override | Ustawia ilość odstępu przed pierwszą linią w akapicie bez dziedziczenia. Wartość dodatnia określa procent rozmiaru czcionki, jaki ma zajmować biały odstęp. Wartość ujemna określa rozmiar białego odstępu w punktach. Zapisz **float**. |
| void [set_SpaceWithin](./set_spacewithin/)(**float**) override | Ustawia ilość odstępu między liniami bazowymi w akapicie. Wartość dodatnia oznacza procent, ujemna - rozmiar w punktach. Nie zastosowano dziedziczenia. Zapisz **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego używaj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego używaj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogiczny do metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję obiektów niestandardowych na ciąg znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego używaj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego używaj inteligentnych wskaźników lub ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |
## Uwagi


Ta klasa jest używana do zwracania i manipulowania właściwościami formatowania akapitu zdefiniowanymi dla konkretnego akapitu. Oznacza to, że przy pobieraniu wartości nie jest stosowane dziedziczenie, więc w większości przypadków otrzymasz wartości oznaczające „niezdefiniowane”.

Aby uzyskać efektywne wartości parametrów formatowania, włącznie z dziedziczonymi, należy użyć metody [ParagraphFormat::GetEffective](./geteffective/), która zwraca instancję [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/).
## Zobacz także

* Klasa [PVIObject](../pviobject/)
* Klasa [IParagraphFormat](../iparagraphformat/)
* Klasa [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat/)
* Przestrzeń nazw [Aspose::Slides](../)
* Biblioteka [Aspose.Slides](../../)