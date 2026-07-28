---
title: StringWriter
second_title: Aspose.Slides dla C++ – Referencja API
description: "Implementuje TextWriter, który zapisuje informacje do łańcucha znaków. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji System::MakeObject() . Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ może to powodować błędy w czasie wykonywania i/lub naruszenia asercji. Zawsze owiń tę klasę wskaźnikiem System::SmartPtr i używaj tego wskaźnika do przekazywania jej funkcjom jako argument."
type: docs
weight: 417
url: /pl/system.io/stringwriter/
---
## StringWriter klasa

Implementuje [TextWriter](../textwriter/) który zapisuje informacje do ciągu znaków. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie wykonania i/lub naruszenia asercji. Zawsze opakowuj tę klasę w wskaźnik [System::SmartPtr](../../system/smartptr/) i używaj tego wskaźnika do przekazywania jej funkcjom jako argumentu.

```cpp
class StringWriter : public System::IO::TextWriter
```

## Metody

| Method | Description |
| --- | --- |
| virtual void [Close](../textwriter/close/)() | Zamyka strumień i zwalnia pozyskane zasoby. |
| void [Dispose](../textwriter/dispose/)() override | Zwalnia wszystkie zasoby używane przez bieżący obiekt i zamyka podstawowy strumień. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartości w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| virtual void [Flush](../textwriter/flush/)() | Zrzuca zawartość bufora do podstawowego strumienia. |
| [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() override | Zwraca aktualnie używane kodowanie. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](../textwriter/get_formatprovider/)() const | Zwraca aktualnie używany obiekt [IFormatProvider](../../system/iformatprovider/). |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](../textwriter/get_formatprovider/)() | Zwraca aktualnie używany obiekt [IFormatProvider](../../system/iformatprovider/). |
| virtual [System::String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() const | Zwraca ciąg znaków kończący wiersz. |
| [String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() | Zwraca ciąg znaków kończący wiersz. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\> [GetStringBuilder](./getstringbuilder/)() | Zwraca aktualnie używany StringBuilder. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę statementu C# lock(). Wywołaj bezpośrednio lub użyj obiektu stróżującego [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartości z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku łańcucha znaków i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku łańcuchów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
| virtual void [set_NewLine](../textwriter/set_newline/)(const [System::String](../../system/string/)\&) | Ustawia ciąg znaków kończący wiersz. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
|  [StringWriter](./stringwriter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | Tworzy nową instancję [StringWriter](./) używając podanego StringBuilder i [IFormatProvider](../../system/iformatprovider/). |
|  [StringWriter](./stringwriter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | Tworzy nową instancję [StringWriter](./) używając podanego StringBuilder i [IFormatProvider](../../system/iformatprovider/) z bieżącej kultury. |
|  [StringWriter](./stringwriter/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | Tworzy nową instancję [StringWriter](./) używając podanego [IFormatProvider](../../system/iformatprovider/). |
|  [StringWriter](./stringwriter/)() | Tworzy nową instancję [StringWriter](./) używając [IFormatProvider](../../system/iformatprovider/) z bieżącej kultury. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Zwraca podstawowy ciąg znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie statementu C# lock(). Wywołaj bezpośrednio lub użyj obiektu stróżującego [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [Write](./write/)(char_t) override | Zapisuje określony znak do strumienia. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Zapisuje określony podzakres znaków z podanej tablicy znaków do strumienia. |
| void [Write](./write/)(const [String](../../system/string/)\&) override | Zapisuje określony ciąg znaków do strumienia. |
| virtual void [Write](../textwriter/write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Zapisuje reprezentację tekstową podanego obiektu do strumienia. |
| virtual void [Write](../textwriter/write/)(**bool**) | Zapisuje reprezentację tekstową podanej wartości logicznej do strumienia. |
| virtual void [Write](../textwriter/write/)([Decimal](../../system/decimal/)) | Zapisuje reprezentację tekstową podanego obiektu [Decimal](../../system/decimal/) do strumienia. |
| virtual void [Write](../textwriter/write/)(**double**) | Zapisuje reprezentację tekstową podanej podwójnej precyzji liczby zmiennoprzecinkowej do strumienia. |
| virtual void [Write](../textwriter/write/)(int) | Zapisuje reprezentację tekstową podanej 32-bitowej wartości całkowitej do strumienia. |
| virtual void [Write](../textwriter/write/)(**int64_t**) | Zapisuje reprezentację tekstową podanej 64-bitowej wartości całkowitej do strumienia. |
| virtual void [Write](../textwriter/write/)(**float**) | Zapisuje reprezentację tekstową podanej jednokrotnej precyzji liczby zmiennoprzecinkowej do strumienia. |
| virtual void [Write](../textwriter/write/)(**uint32_t**) | Zapisuje reprezentację tekstową podanej nieujemnej 32-bitowej wartości całkowitej do strumienia. |
| virtual void [Write](../textwriter/write/)(**uint64_t**) | Zapisuje reprezentację tekstową podanej nieujemnej 64-bitowej wartości całkowitej do strumienia. |
| virtual void [Write](../textwriter/write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Zapisuje wszystkie znaki z podanej tablicy do strumienia. |
| virtual void [Write](../textwriter/write/)(const char_t *) | Zapisuje podany łańcuch c do strumienia. |
| virtual void [Write](../textwriter/write/)(const [TypeInfo](../../system/typeinfo/)\&) | Zapisuje reprezentację tekstową podanego obiektu [TypeInfo](../../system/typeinfo/) do strumienia. |
| void [Write](../textwriter/write/)(const [String](../../system/string/)\&, const TArgs\&...) | Zapisuje podane wartości sformatowane według określonego formatu do strumienia. |
| virtual void [WriteLine](../textwriter/writeline/)() | Zapisuje znaki kończące wiersz do strumienia. |
| virtual void [WriteLine](../textwriter/writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Zapisuje reprezentację tekstową podanego obiektu, a następnie znaki kończące wiersz, do strumienia. |
| virtual void [WriteLine](../textwriter/writeline/)(**bool**) | Zapisuje reprezentację tekstową podanej wartości logicznej, a następnie znaki kończące wiersz, do strumienia. |
| virtual void [WriteLine](../textwriter/writeline/)(char_t) | Zapisuje określony znak, a następnie znaki kończące wiersz, do strumienia. |
| virtual void [WriteLine](../textwriter/writeline/)([Decimal](../../system/decimal/)) | Zapisuje reprezentację tekstową podanego obiektu [Decimal](../../system/decimal/), a następnie znaki kończące wiersz, do strumienia. |
| virtual void [WriteLine](../textwriter/writeline/)(**double**) | Zapisuje reprezentację tekstową podanej podwójnej precyzji liczby zmiennoprzecinkowej, a następnie znaki kończące wiersz, do strumienia. |
| virtual void [WriteLine](../textwriter/writeline/)(int) | Zapisuje reprezentację tekstową podanej 32-bitowej wartości całkowitej, a następnie znaki kończące wiersz, do strumienia. |
| virtual void [WriteLine](../textwriter/writeline/)(**int64_t**) | Zapisuje reprezentację tekstową podanej 64-bitowej wartości całkowitej, a następnie znaki kończące wiersz, do strumienia. |
| virtual void [WriteLine](../textwriter/writeline/)(**float**) | Zapisuje reprezentację tekstową podanej jednokrotnej precyzji liczby zmiennoprzecinkowej, a następnie znaki kończące wiersz, do strumienia. |
| virtual void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&) | Zapisuje podany ciąg znaków, a następnie znaki kończące wiersz, do strumienia. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint32_t**) | Zapisuje reprezentację tekstową podanej nieujemnej 32-bitowej wartości całkowitej, a następnie znaki kończące wiersz, do strumienia. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint64_t**) | Zapisuje reprezentację tekstową podanej nieujemnej 64-bitowej wartości całkowitej, a następnie znaki kończące wiersz, do strumienia. |
| virtual void [WriteLine](../textwriter/writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Zapisuje wszystkie znaki z podanej tablicy, a następnie znaki kończące wiersz, do strumienia. |
| virtual void [WriteLine](../textwriter/writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Zapisuje określony podzakres znaków UTF-16 z podanej tablicy znaków, a następnie znaki kończące wiersz, do strumienia. |
| virtual void [WriteLine](../textwriter/writeline/)(const char_t *) | Zapisuje podany łańcuch c, a następnie znaki kończące wiersz, do strumienia. |
| virtual void [WriteLine](../textwriter/writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | Zapisuje reprezentację tekstową podanego obiektu [TypeInfo](../../system/typeinfo/), a następnie znaki kończące wiersz, do strumienia. |
| void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | Zapisuje podane wartości sformatowane według określonego formatu, a następnie znaki kończące wiersz, do strumienia. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |
| virtual  [~TextWriter](../textwriter/~textwriter/)() | Destruktor. |

## Zobacz także

* Klasa [TextWriter](../textwriter/)
* Przestrzeń nazw [System::IO](../)
* Biblioteka [Aspose.Slides](../../)