---
title: StringFormat
second_title: Aspose.Slides dla C++ – dokumentacja API
description: "Enkapsuluje informacje o układzie tekstu, manipulacje wyświetlaniem oraz funkcje OpenType. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji System::MakeObject(). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ może to skutkować błędami czasu wykonywania i/lub awariami asercji. Zawsze otaczaj tę klasę wskaźnikiem System::SmartPtr i używaj tego wskaźnika do przekazywania go jako argumentu do funkcji."
type: docs
weight: 313
url: /pl/system.drawing/stringformat/
---
## StringFormat klasa

Enkapsuluje informacje o układzie tekstu, manipulacje wyświetlaniem oraz funkcje OpenType. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ może to skutkować błędami czasu wykonania i/lub awariami asercji. Zawsze otaczaj tę klasę wskaźnikiem [System::SmartPtr](../../system/smartptr/) i używaj tego wskaźnika do przekazywania jej jako argumentu do funkcji.

```cpp
class StringFormat : public System::Object
```

## Metody

| Metoda | Opis |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[StringFormat](./)\> [Clone](./clone/)() | Zwraca dokładną kopię bieżącego obiektu. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| [StringAlignment](../stringalignment/) [get_Alignment](./get_alignment/)() const | Zwraca wartość określającą wyrównanie poziome ciągu. |
| **int32_t** [get_DigitSubstitutionLanguage](./get_digitsubstitutionlanguage/)() const | Zwraca wartość określającą język używany, gdy lokalne cyfry są zastępowane cyframi zachodnimi. |
| [StringDigitSubstitute](../stringdigitsubstitute/) [get_DigitSubstitutionMethod](./get_digitsubstitutionmethod/)() const | Zwraca metodę zamiany cyfr. |
| [StringFormatFlags](../stringformatflags/) [get_FormatFlags](./get_formatflags/)() const | Zwraca kombinację bitową StringFormatFlags określającą format ciągu reprezentowany przez bieżący obiekt. |
| static [SharedPtr](../../system/sharedptr/)\<[StringFormat](./)\> [get_GenericDefault](./get_genericdefault/)() | Zwraca obiekt [StringFormat](./) reprezentujący domyślny format generyczny. |
| static [SharedPtr](../../system/sharedptr/)\<[StringFormat](./)\> [get_GenericTypographic](./get_generictypographic/)() | Zwraca obiekt [StringFormat](./) reprezentujący generyczny format typograficzny. |
| [Text::HotkeyPrefix](../../system.drawing.text/hotkeyprefix/) [get_HotkeyPrefix](./get_hotkeyprefix/)() const | Zwraca wartość określającą sposób wyświetlania prefiksu klawisza skrótu. |
| [StringAlignment](../stringalignment/) [get_LineAlignment](./get_linealignment/)() const | Zwraca wartość określającą wyrównanie pionowe ciągu. |
| [StringTrimming](../stringtrimming/) [get_Trimming](./get_trimming/)() const | Zwraca wartość określającą sposób przycinania ciągu. |
| int [GetCharacterRangesCount](./getcharacterrangescount/)() const | Zwraca rozmiar tablicy [CharacterRange](../characterrange/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Zwraca strukturę danych licznika referencji związaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Odpowiednik metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| [ArrayPtr](../../system/arrayptr/)\<**float**\> [GetTabStops](./gettabstops/)(**float**\&) const | Zwraca tabulatory dla bieżącego [StringFormat](./) obiektu. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Zwraca rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Odpowiednik operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. W rzeczywistości nic nie kopiuje, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. W rzeczywistości nic nie kopiuje, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
| void [set_Alignment](./set_alignment/)([StringAlignment](../stringalignment/)) | Ustawia wyrównanie poziome ciągu. |
| void [set_FormatFlags](./set_formatflags/)([StringFormatFlags](../stringformatflags/)) | Ustawia flagi formatu ciągu. |
| void [set_HotkeyPrefix](./set_hotkeyprefix/)([Text::HotkeyPrefix](../../system.drawing.text/hotkeyprefix/)) | Ustawia wartość określającą sposób wyświetlania prefiksu klawisza skrótu. |
| void [set_LineAlignment](./set_linealignment/)([StringAlignment](../stringalignment/)) | Ustawia wyrównanie pionowe ciągu. |
| void [set_Trimming](./set_trimming/)([StringTrimming](../stringtrimming/)) | Ustawia wartość określającą sposób przycinania ciągu. |
| void [SetDigitSubstitution](./setdigitsubstitution/)(**int32_t**, [StringDigitSubstitute](../stringdigitsubstitute/)) | Ustawia język i metodę zamiany cyfr. |
| void [SetMeasurableCharacterRanges](./setmeasurablecharacterranges/)(const [ArrayPtr](../../system/arrayptr/)\<[CharacterRange](../characterrange/)\>\&) | Ustawia tablicę obiektów [CharacterRange](../characterrange/) reprezentujących zakresy znaków mierzone wywołaniem metody MeasureCharacterRanges(). |
| void [SetTabStops](./settabstops/)(**float**, const [ArrayPtr](../../system/arrayptr/)\<**float**\>\&) | Ustawia tabulatory dla bieżącego [StringFormat](./) obiektu. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach do trybu słabego. |
| int [SharedCount](../../system/object/sharedcount/)() const | Zwraca bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
|  [StringFormat](./stringformat/)() | Tworzy nową instancję klasy [StringFormat](./). |
|  [StringFormat](./stringformat/)([StringFormatFlags](../stringformatflags/), **int32_t**) | Tworzy nową instancję klasy [StringFormat](./) z podanymi flagami formatu i językiem. |
|  [StringFormat](./stringformat/)(const [SharedPtr](../../system/sharedptr/)\<[StringFormat](./)\>\&) | Konstruktor kopiujący. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Odpowiednik metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów do string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Usuwa obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [Object](../../system/object/)
* Przestrzeń nazw [System::Drawing](../)
* Biblioteka [Aspose.Slides](../../)