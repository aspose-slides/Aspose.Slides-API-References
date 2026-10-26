---
title: IParagraphFormat
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Ta klasa zawiera właściwości formatowania akapitu. W przeciwieństwie do IParagraphFormatEffectiveData, wszystkie właściwości tej klasy są zapisywalne.
type: docs
weight: 3147
url: /pl/aspose.slides/iparagraphformat/
---
## IParagraphFormat klasa


Ta klasa zawiera właściwości formatowania akapitu. W przeciwieństwie do [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/), wszystkie właściwości tej klasy są zapisywalne.

```cpp
class IParagraphFormat : public virtual System::Object
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równe żadnej wartości, włączając NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równe żadnej wartości, włączając NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| virtual [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() | Zwraca wyrównanie tekstu w akapicie bez dziedziczenia. Odczytaj [TextAlignment](../textalignment/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormat](../ibulletformat/)\> [get_Bullet](./get_bullet/)() | Zwraca format wypunktowania akapitu. Tylko do odczytu [IBulletFormat](../ibulletformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../iportionformat/)\> [get_DefaultPortionFormat](./get_defaultportionformat/)() | Zwraca domyślny format części akapitu. Nie zastosowano dziedziczenia. Tylko do odczytu [IPortionFormat](../iportionformat/). |
| virtual **float** [get_DefaultTabSize](./get_defaulttabsize/)() | Zwraca domyślny rozmiar tabulacji bez dziedziczenia. Odczyt **float**. |
| virtual **int16_t** [get_Depth](./get_depth/)() | Zwraca głębokość akapitu. Wartość 0 oznacza nieokreśloną wartość. Odczyt **int16_t**. |
| virtual [NullableBool](../nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() | Określa, czy w akapicie używany jest podział linii w stylu wschodnioazjatyckim. Nie zastosowano dziedziczenia. Odczyt [NullableBool](../nullablebool/). |
| virtual [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() | Zwraca wyrównanie czcionki w akapicie bez dziedziczenia. Odczyt [Slides::FontAlignment](../fontalignment/). |
| virtual [NullableBool](../nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() | Określa, czy w akapicie używany jest wiszący znak interpunkcyjny. Nie zastosowano dziedziczenia. Odczyt [NullableBool](../nullablebool/). |
| virtual **float** [get_Indent](./get_indent/)() | Zwraca wcięcie pierwszej linii/wcięcie wiszące akapitu bez dziedziczenia. Wcięcie wiszące może być określone wartościami ujemnymi. Odczyt **float**. |
| virtual [NullableBool](../nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() | Określa, czy w akapicie używany jest podział linii łacińskiej. Nie zastosowano dziedziczenia. Odczyt [NullableBool](../nullablebool/). |
| virtual **float** [get_MarginLeft](./get_marginleft/)() | Zwraca lewy margines w akapicie bez dziedziczenia. Odczyt **float**. |
| virtual **float** [get_MarginRight](./get_marginright/)() | Zwraca prawy margines w akapicie bez dziedziczenia. Odczyt **float**. |
| virtual [NullableBool](../nullablebool/) [get_RightToLeft](./get_righttoleft/)() | Określa, czy w akapicie używany jest zapis od prawej do lewej. Nie zastosowano dziedziczenia. Odczyt [NullableBool](../nullablebool/). |
| virtual **float** [get_SpaceAfter](./get_spaceafter/)() | Zwraca ilość odstępu po ostatniej linii w akapicie bez dziedziczenia. Wartość dodatnia określa procent rozmiaru czcionki, jaki ma zajmować biały odstęp. Wartość ujemna określa rozmiar białego odstępu w punktach. Odczyt **float**. |
| virtual **float** [get_SpaceBefore](./get_spacebefore/)() | Zwraca ilość odstępu przed pierwszą linią w akapicie bez dziedziczenia. Wartość dodatnia określa procent rozmiaru czcionki, jaki ma zajmować biały odstęp. Wartość ujemna określa rozmiar białego odstępu w punktach. Odczyt **float**. |
| virtual **float** [get_SpaceWithin](./get_spacewithin/)() | Zwraca ilość odstępu między liniami bazowymi w akapicie. Wartość dodatnia oznacza procent, ujemna – rozmiar w punktach. Nie zastosowano dziedziczenia. Odczyt **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\> [get_Tab](./get_tab/)(**int32_t**) | Zwraca tabulację akapitu o podanym indeksie. Nie zastosowano dziedziczenia. Tylko do odczytu [Aspose::Slides::ITab](../itab/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../itabcollection/)\> [get_Tabs](./get_tabs/)() | Zwraca tabulacje akapitu. Nie zastosowano dziedziczenia. Tylko do odczytu [ITabCollection](../itabcollection/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)\> [GetEffective](./geteffective/)() | Pobiera skuteczne dane formatowania akapitu z zastosowanym dziedziczeniem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Odpowiednik metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Odpowiednik operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu wartownika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. W rzeczywistości nic nie kopiuje, tylko inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. W rzeczywistości nic nie kopiuje, tylko inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadków string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadków stringów. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
| virtual void [set_Alignment](./set_alignment/)([TextAlignment](../textalignment/)) | Ustawia wyrównanie tekstu w akapicie bez dziedziczenia. Zapis [TextAlignment](../textalignment/). |
| virtual void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) | Ustawia domyślny rozmiar tabulacji bez dziedziczenia. Zapis **float**. |
| virtual void [set_Depth](./set_depth/)(**int16_t**) | Ustawia głębokość akapitu. Wartość 0 oznacza nieokreśloną wartość. Zapis **int16_t**. |
| virtual void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../nullablebool/)) | Określa, czy w akapicie używany jest podział linii w stylu wschodnioazjatyckim. Nie zastosowano dziedziczenia. Zapis [NullableBool](../nullablebool/). |
| virtual void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../fontalignment/)) | Ustawia wyrównanie czcionki w akapicie bez dziedziczenia. Zapis [Slides::FontAlignment](../fontalignment/). |
| virtual void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../nullablebool/)) | Określa, czy w akapicie używany jest wiszący znak interpunkcyjny. Nie zastosowano dziedziczenia. Zapis [NullableBool](../nullablebool/). |
| virtual void [set_Indent](./set_indent/)(**float**) | Ustawia wcięcie pierwszej linii/wcięcie wiszące akapitu bez dziedziczenia. Wcięcie wiszące może być określone wartościami ujemnymi. Zapis **float**. |
| virtual void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../nullablebool/)) | Określa, czy w akapicie używany jest podział linii łacińskiej. Nie zastosowano dziedziczenia. Zapis [NullableBool](../nullablebool/). |
| virtual void [set_MarginLeft](./set_marginleft/)(**float**) | Ustawia lewy margines w akapicie bez dziedziczenia. Zapis **float**. |
| virtual void [set_MarginRight](./set_marginright/)(**float**) | Ustawia prawy margines w akapicie bez dziedziczenia. Zapis **float**. |
| virtual void [set_RightToLeft](./set_righttoleft/)([NullableBool](../nullablebool/)) | Określa, czy w akapicie używany jest zapis od prawej do lewej. Nie zastosowano dziedziczenia. Zapis [NullableBool](../nullablebool/). |
| virtual void [set_SpaceAfter](./set_spaceafter/)(**float**) | Ustawia ilość odstępu po ostatniej linii w akapicie bez dziedziczenia. Wartość dodatnia określa procent rozmiaru czcionki, jaki ma zajmować biały odstęp. Wartość ujemna określa rozmiar białego odstępu w punktach. Zapis **float**. |
| virtual void [set_SpaceBefore](./set_spacebefore/)(**float**) | Ustawia ilość odstępu przed pierwszą linią w akapicie bez dziedziczenia. Wartość dodatnia określa procent rozmiaru czcionki, jaki ma zajmować biały odstęp. Wartość ujemna określa rozmiar białego odstępu w punktach. Zapis **float**. |
| virtual void [set_SpaceWithin](./set_spacewithin/)(**float**) | Ustawia ilość odstępu między liniami bazowymi w akapicie. Wartość dodatnia oznacza procent, ujemna – rozmiar w punktach. Nie zastosowano dziedziczenia. Zapis **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala na przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Odpowiednik metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów do łańcucha znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu wartownika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Uwagi


Ta klasa jest używana do zwracania i modyfikowania właściwości formatowania akapitu zdefiniowanych dla konkretnego akapitu. Oznacza to, że przy pobieraniu wartości nie jest stosowane dziedziczenie, więc w większości przypadków otrzymasz wartości oznaczające „niezdefiniowane”.

Aby uzyskać skuteczne wartości parametrów formatowania, w tym dziedziczone, należy użyć metody [IParagraphFormat::GetEffective](./geteffective/), która zwraca instancję [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/).

## Zobacz także

* Klasa [Object](../../system/object/)
* Przestrzeń nazw [Aspose::Slides](../)
* Biblioteka [Aspose.Slides](../../)