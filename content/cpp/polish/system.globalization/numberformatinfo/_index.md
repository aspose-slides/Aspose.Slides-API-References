---
title: NumberFormatInfo
second_title: Aspose.Slides dla C++ Dokumentacja API
description: "Zawiera informacje o tym, jak formatować liczby. Operacje ustawiające są dostępne tylko dla obiektów nie-tylko-do-odczytu. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji System::MakeObject(). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie wykonywania i/lub naruszenia asercji. Zawsze otaczaj tę klasę wskaźnikiem System::SmartPtr i używaj tego wskaźnika do przekazywania jej jako argumentu do funkcji."
type: docs
weight: 248
url: /pl/system.globalization/numberformatinfo/
---
## NumberFormatInfo klasa

Zawiera informacje o tym, jak formatować liczby. Operacje ustawiające są dostępne tylko dla obiektów nie tylko do odczytu. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie wykonywania i/lub naruszenia asercji. Zawsze otaczaj tę klasę wskaźnikiem [System::SmartPtr](../../system/smartptr/) i używaj tego wskaźnika do przekazywania jej jako argumentu do funkcji.

```cpp
class NumberFormatInfo : public virtual System::Object,
                         public System::IFormatProvider,
                         public System::ICloneable
```

## Metody

| Metoda | Opis |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Tworzy kopię informacji o formacie. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| int [get_CurrencyDecimalDigits](./get_currencydecimaldigits/)() const | Zwraca liczbę cyfr dziesiętnych waluty. |
| [String](../../system/string/) [get_CurrencyDecimalSeparator](./get_currencydecimalseparator/)() const | Zwraca separator dziesiętny waluty. |
| [String](../../system/string/) [get_CurrencyGroupSeparator](./get_currencygroupseparator/)() const | Zwraca separator grupy waluty. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_CurrencyGroupSizes](./get_currencygroupsizes/)() const | Zwraca liczbę cyfr dziesiętnych waluty w grupie. |
| int [get_CurrencyNegativePattern](./get_currencynegativepattern/)() const | Zwraca negatywny wzorzec waluty. |
| int [get_CurrencyPositivePattern](./get_currencypositivepattern/)() const | Zwraca dodatni wzorzec waluty. |
| [String](../../system/string/) [get_CurrencySymbol](./get_currencysymbol/)() const | Zwraca symbol waluty. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [get_CurrentInfo](./get_currentinfo/)() | Zwraca informacje o formacie liczb zdefiniowane w bieżącej kulturze wątku. |
| [DigitShapes](../digitshapes/) [get_DigitSubstitution](./get_digitsubstitution/)() const | Zwraca wartość określającą, jak wyświetlać kształt cyfry. |
| static const [NumberFormatInfoPtr](../numberformatinfoptr/)\& [get_InvariantInfo](./get_invariantinfo/)() | Zwraca informacje o formacie liczb zdefiniowane w kulturze niezmiennej. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | Sprawdza, czy format jest tylko do odczytu. |
| [String](../../system/string/) [get_NaNSymbol](./get_nansymbol/)() const | Zwraca symbol Not-a-Number. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_NativeDigits](./get_nativedigits/)() const | Zwraca symbole cyfr (od 0 do 9). |
| [String](../../system/string/) [get_NegativeInfinitySymbol](./get_negativeinfinitysymbol/)() const | Zwraca symbol ujemnej nieskończoności. |
| [String](../../system/string/) [get_NegativeSign](./get_negativesign/)() const | Zwraca znak minus. |
| int [get_NumberDecimalDigits](./get_numberdecimaldigits/)() const | Zwraca liczbę cyfr dziesiętnych. |
| [String](../../system/string/) [get_NumberDecimalSeparator](./get_numberdecimalseparator/)() const | Zwraca separator dziesiętny. |
| [String](../../system/string/) [get_NumberGroupSeparator](./get_numbergroupseparator/)() const | Zwraca separator grupy liczb. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_NumberGroupSizes](./get_numbergroupsizes/)() const | Zwraca liczbę cyfr w grupie. |
| int [get_NumberNegativePattern](./get_numbernegativepattern/)() const | Zwraca negatywny wzorzec liczby. |
| int [get_PercentDecimalDigits](./get_percentdecimaldigits/)() const | Zwraca liczbę miejsc dziesiętnych w wartościach procentowych. |
| [String](../../system/string/) [get_PercentDecimalSeparator](./get_percentdecimalseparator/)() const | Zwraca separator dziesiętny w wartościach procentowych. |
| [String](../../system/string/) [get_PercentGroupSeparator](./get_percentgroupseparator/)() const | Zwraca separator grupy w wartościach procentowych. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_PercentGroupSizes](./get_percentgroupsizes/)() const | Zwraca liczbę cyfr w grupie wartości procentowych. |
| int [get_PercentNegativePattern](./get_percentnegativepattern/)() const | Zwraca negatywny wzorzec procentowy. |
| int [get_PercentPositivePattern](./get_percentpositivepattern/)() const | Zwraca dodatni wzorzec procentowy. |
| [String](../../system/string/) [get_PercentSymbol](./get_percentsymbol/)() const | Zwraca symbol procentu. |
| [String](../../system/string/) [get_PerMilleSymbol](./get_permillesymbol/)() const | Zwraca symbol promila. |
| [String](../../system/string/) [get_PositiveInfinitySymbol](./get_positiveinfinitysymbol/)() const | Zwraca symbol dodatniej nieskończoności. |
| [String](../../system/string/) [get_PositiveSign](./get_positivesign/)() const | Zwraca znak plus. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Zwraca strukturę danych licznika referencji powiązaną z obiektem. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetFormat](./getformat/)(const [TypeInfo](../../system/typeinfo/)\&) override | Zwraca formatowanie określonego typu. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Odpowiednik metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [GetInstance](./getinstance/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | Zwraca formatowanie powiązane z dostawcą formatu. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Zwraca rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Odpowiednik operatora C# 'is'. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [NumberFormatInfo](./numberformatinfo/)() | Konstruktor domyślny (niezmienny [NumberFormatInfo](./)). |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuj nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [NumberFormatInfo](./)\& [operator=](./operator_equal/)(const [NumberFormatInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuj nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [ReadOnly](./readonly/)([NumberFormatInfoPtr](../numberformatinfoptr/)) | Zwraca wersję tylko do odczytu formatowania. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| void [set_CurrencyDecimalDigits](./set_currencydecimaldigits/)(int) | Ustawia liczbę cyfr dziesiętnych waluty. |
| void [set_CurrencyDecimalSeparator](./set_currencydecimalseparator/)(const [String](../../system/string/)\&) | Ustawia separator dziesiętny waluty. |
| void [set_CurrencyGroupSeparator](./set_currencygroupseparator/)(const [String](../../system/string/)\&) | Ustawia separator grupy waluty. |
| void [set_CurrencyGroupSizes](./set_currencygroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | Ustawia liczbę cyfr dziesiętnych waluty w grupie. |
| void [set_CurrencyNegativePattern](./set_currencynegativepattern/)(int) | Ustawia negatywny wzorzec waluty. |
| void [set_CurrencyPositivePattern](./set_currencypositivepattern/)(int) | Ustawia dodatni wzorzec waluty. |
| void [set_CurrencySymbol](./set_currencysymbol/)(const [String](../../system/string/)\&) | Ustawia symbol waluty. |
| void [set_DigitSubstitution](./set_digitsubstitution/)([DigitShapes](../digitshapes/)) | Ustawia wartość określającą, jak wyświetlać kształt cyfry. |
| void [set_NaNSymbol](./set_nansymbol/)(const [String](../../system/string/)\&) | Ustawia symbol Not-a-Number. |
| void [set_NativeDigits](./set_nativedigits/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Ustawia symbole cyfr (od 0 do 9). |
| void [set_NegativeInfinitySymbol](./set_negativeinfinitysymbol/)(const [String](../../system/string/)\&) | Ustawia symbol ujemnej nieskończoności. |
| void [set_NegativeSign](./set_negativesign/)(const [String](../../system/string/)\&) | Ustawia znak minus. |
| void [set_NumberDecimalDigits](./set_numberdecimaldigits/)(int) | Ustawia liczbę cyfr dziesiętnych. |
| void [set_NumberDecimalSeparator](./set_numberdecimalseparator/)(const [String](../../system/string/)\&) | Ustawia separator dziesiętny. |
| void [set_NumberGroupSeparator](./set_numbergroupseparator/)(const [String](../../system/string/)\&) | Ustawia separator grupy liczb. |
| void [set_NumberGroupSizes](./set_numbergroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | Ustawia liczbę cyfr w grupie. |
| void [set_NumberNegativePattern](./set_numbernegativepattern/)(int) | Ustawia negatywny wzorzec liczby. |
| void [set_PercentDecimalDigits](./set_percentdecimaldigits/)(int) | Ustawia liczbę miejsc dziesiętnych w wartościach procentowych. |
| void [set_PercentDecimalSeparator](./set_percentdecimalseparator/)(const [String](../../system/string/)\&) | Ustawia separator dziesiętny w wartościach procentowych. |
| void [set_PercentGroupSeparator](./set_percentgroupseparator/)(const [String](../../system/string/)\&) | Ustawia separator grupy w wartościach procentowych. |
| void [set_PercentGroupSizes](./set_percentgroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | Ustawia liczbę cyfr w grupie wartości procentowych. |
| void [set_PercentNegativePattern](./set_percentnegativepattern/)(int) | Ustawia negatywny wzorzec procentowy. |
| void [set_PercentPositivePattern](./set_percentpositivepattern/)(int) | Ustawia dodatni wzorzec procentowy. |
| void [set_PercentSymbol](./set_percentsymbol/)(const [String](../../system/string/)\&) | Ustawia symbol procentu. |
| void [set_PerMilleSymbol](./set_permillesymbol/)(const [String](../../system/string/)\&) | Ustawia symbol promila. |
| void [set_PositiveInfinitySymbol](./set_positiveinfinitysymbol/)(const [String](../../system/string/)\&) | Ustawia symbol dodatniej nieskończoności. |
| void [set_PositiveSign](./set_positivesign/)(const [String](../../system/string/)\&) | Ustawia znak plus. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Zwraca bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Odpowiednik metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów na ciąg znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowywanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [Object](../../system/object/)
* Klasa [IFormatProvider](../../system/iformatprovider/)
* Klasa [ICloneable](../../system/icloneable/)
* Przestrzeń nazw [System::Globalization](../)
* Biblioteka [Aspose.Slides](../../)