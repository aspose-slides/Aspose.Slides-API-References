---
title: TextWriter
second_title: Aspose.Slides dla C++ – dokumentacja API
description: "Podstawowa klasa dla klas reprezentujących pisarze, które zapisują sekwencje znaków do różnych miejsc docelowych. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji System::MakeObject(). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonania i/lub błędy asercji. Zawsze otaczaj tę klasę wskaźnikiem System::SmartPtr i używaj tego wskaźnika do przekazywania go jako argumentu do funkcji."
type: docs
weight: 443
url: /pl/system.io/textwriter/
---
## Klasa TextWriter

Podstawowa klasa dla klas, które reprezentują pisarze zapisujące sekwencje znaków do różnych miejsc docelowych. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonania i/lub błędy asercji. Zawsze otaczaj tę klasę wskaźnikiem [System::SmartPtr](../../system/smartptr/) i używaj tego wskaźnika do przekazywania jej jako argumentu do funkcji.

```cpp
class TextWriter : public System::IDisposable
```

## Metody

| Method | Description |
| --- | --- |
| virtual void [Close](./close/)() | Zamyka strumień i zwalnia pozyskane zasoby. |
| void [Dispose](./dispose/)() override | Zwalnia wszystkie zasoby używane przez bieżący obiekt i zamyka leżący pod spodem strumień. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, w którym dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, w którym dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| virtual void [Flush](./flush/)() | Opróżnia zawartość bufora do leżącego pod spodem strumienia. |
| virtual [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Zwraca aktualnie używane kodowanie. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](./get_formatprovider/)() const | Zwraca aktualnie używany obiekt [IFormatProvider](../../system/iformatprovider/). |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](./get_formatprovider/)() | Zwraca aktualnie używany obiekt [IFormatProvider](../../system/iformatprovider/). |
| virtual [System::String](../../system/string/) [get_NewLine](./get_newline/)() const | Zwraca łańcuch znaków zakończenia wiersza. |
| [String](../../system/string/) [get_NewLine](./get_newline/)() | Zwraca łańcuch znaków zakończenia wiersza. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Odpowiednik metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt reprezentuje instancję typu opisanego przez targetType. Odpowiednik operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
| [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągu znaków i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
| virtual void [set_NewLine](./set_newline/)(const [System::String](../../system/string/)\&) | Ustawia łańcuch znaków zakończenia wiersza. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Odpowiednik metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów na łańcuch. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa słaby licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza słaby licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Zapisuje łańcuch znakowy reprezentacji podanego obiektu do strumienia. |
| virtual void [Write](./write/)(**bool**) | Zapisuje łańcuch znakowy reprezentacji podanej wartości boolowskiej do strumienia. |
| virtual void [Write](./write/)(char_t) | Zapisuje podany znak do strumienia. |
| virtual void [Write](./write/)([Decimal](../../system/decimal/)) | Zapisuje łańcuch znakowy reprezentacji podanego obiektu [Decimal](../../system/decimal/) do strumienia. |
| virtual void [Write](./write/)(**double**) | Zapisuje łańcuch znakowy reprezentacji podanej wartości zmiennoprzecinkowej podwójnej precyzji do strumienia. |
| virtual void [Write](./write/)(int) | Zapisuje łańcuch znakowy reprezentacji podanej 32-bitowej wartości całkowitej do strumienia. |
| virtual void [Write](./write/)(**int64_t**) | Zapisuje łańcuch znakowy reprezentacji podanej 64-bitowej wartości całkowitej do strumienia. |
| virtual void [Write](./write/)(**float**) | Zapisuje łańcuch znakowy reprezentacji podanej wartości zmiennoprzecinkowej pojedynczej precyzji do strumienia. |
| virtual void [Write](./write/)(const [String](../../system/string/)\&) | Zapisuje podany łańcuch do strumienia. |
| virtual void [Write](./write/)(**uint32_t**) | Zapisuje łańcuch znakowy reprezentacji podanej 32-bitowej wartości bez znaku do strumienia. |
| virtual void [Write](./write/)(**uint64_t**) | Zapisuje łańcuch znakowy reprezentacji podanej 64-bitowej wartości bez znaku do strumienia. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Zapisuje wszystkie znaki z podanej tablicy do strumienia. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Zapisuje określony podzakres znaków UTF-16 z podanej tablicy znaków do strumienia. |
| virtual void [Write](./write/)(const char_t *) | Zapisuje podany ciąg C do strumienia. |
| virtual void [Write](./write/)(const [TypeInfo](../../system/typeinfo/)\&) | Zapisuje łańcuch znakowy reprezentacji podanego obiektu [TypeInfo](../../system/typeinfo/) do strumienia. |
| void [Write](./write/)(const [String](../../system/string/)\&, const TArgs\&...) | Zapisuje podane wartości sformatowane według określonego formatu do strumienia. |
| virtual void [WriteLine](./writeline/)() | Zapisuje znaki zakończenia wiersza do strumienia. |
| virtual void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Zapisuje łańcuch znakowy reprezentacji podanego obiektu, a następnie znaki zakończenia wiersza, do strumienia. |
| virtual void [WriteLine](./writeline/)(**bool**) | Zapisuje łańcuch znakowy reprezentacji podanej wartości bool, a następnie znaki zakończenia wiersza, do strumienia. |
| virtual void [WriteLine](./writeline/)(char_t) | Zapisuje podany znak, a następnie znaki zakończenia wiersza, do strumienia. |
| virtual void [WriteLine](./writeline/)([Decimal](../../system/decimal/)) | Zapisuje łańcuch znakowy reprezentacji podanego obiektu [Decimal](../../system/decimal/), a następnie znaki zakończenia wiersza, do strumienia. |
| virtual void [WriteLine](./writeline/)(**double**) | Zapisuje łańcuch znakowy reprezentacji podanej wartości podwójnej precyzji, a następnie znaki zakończenia wiersza, do strumienia. |
| virtual void [WriteLine](./writeline/)(int) | Zapisuje łańcuch znakowy reprezentacji podanej 32-bitowej wartości całkowitej, a następnie znaki zakończenia wiersza, do strumienia. |
| virtual void [WriteLine](./writeline/)(**int64_t**) | Zapisuje łańcuch znakowy reprezentacji podanej 64-bitowej wartości całkowitej, a następnie znaki zakończenia wiersza, do strumienia. |
| virtual void [WriteLine](./writeline/)(**float**) | Zapisuje łańcuch znakowy reprezentacji podanej wartości pojedynczej precyzji, a następnie znaki zakończenia wiersza, do strumienia. |
| virtual void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | Zapisuje podany łańcuch, a następnie znaki zakończenia wiersza, do strumienia. |
| virtual void [WriteLine](./writeline/)(**uint32_t**) | Zapisuje łańcuch znakowy reprezentacji podanej 32-bitowej wartości bez znaku, a następnie znaki zakończenia wiersza, do strumienia. |
| virtual void [WriteLine](./writeline/)(**uint64_t**) | Zapisuje łańcuch znakowy reprezentacji podanej 64-bitowej wartości bez znaku, a następnie znaki zakończenia wiersza, do strumienia. |
| virtual void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Zapisuje wszystkie znaki z podanej tablicy, a następnie znaki zakończenia wiersza, do strumienia. |
| virtual void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Zapisuje określony podzakres znaków UTF-16 z podanej tablicy znaków, a następnie znaki zakończenia wiersza, do strumienia. |
| virtual void [WriteLine](./writeline/)(const char_t *) | Zapisuje podany ciąg C, a następnie znaki zakończenia wiersza, do strumienia. |
| virtual void [WriteLine](./writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | Zapisuje łańcuch znakowy reprezentacji podanego obiektu [TypeInfo](../../system/typeinfo/), a następnie znaki zakończenia wiersza, do strumienia. |
| void [WriteLine](./writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | Zapisuje podane wartości sformatowane według określonego formatu, a następnie znaki zakończenia wiersza, do strumienia. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |
| virtual  [~TextWriter](./~textwriter/)() | Destruktor. |

## Typedefy

| Typedef | Opis |
| --- | --- |
| [Ptr](./ptr/) | Alias dla wskaźnika współdzielonego do tej klasy. |

## Zobacz także

* Klasa [IDisposable](../../system/idisposable/)
* Przestrzeń nazw [System::IO](../)
* Biblioteka [Aspose.Slides](../../)