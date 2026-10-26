---
title: StreamWriter
second_title: Aspose.Slides dla C++ - referencja API
description: "Reprezentuje obiekt zapisujący znaki do strumienia bajtowego. Obiekty tej klasy powinny być tworzone wyłącznie przy użyciu funkcji System::MakeObject(). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ może to spowodować błędy czasu wykonywania i/lub naruszenia asercji. Zawsze opakowuj tę klasę w wskaźnik System::SmartPtr i używaj tego wskaźnika do przekazywania go funkcjom jako argument."
type: docs
weight: 391
url: /pl/system.io/streamwriter/
---
## Klasa StreamWriter

Reprezentuje obiekt zapisujący znaki do strumienia bajtowego. Obiekty tej klasy powinny być tworzone wyłącznie za pomocą funkcji [System::MakeObject()](../../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ może to spowodować błędy w czasie wykonywania i/lub naruszenia asercji. Zawsze opakowuj tę klasę w wskaźnik [System::SmartPtr](../../system/smartptr/) i używaj tego wskaźnika do przekazywania jej funkcjom jako argument.

```cpp
class StreamWriter : public System::IO::TextWriter
```

## Metody

| Method | Description |
| --- | --- |
| void [Close](./close/)() override | Zamyka strumień i zwalnia pozyskane zasoby. |
| void [Dispose](./dispose/)() override | Zwalnia wszystkie zasoby używane przez bieżący obiekt i zamyka podstawowy strumień. |
| virtual void [Dispose](./dispose/)(**bool**) | Zwalnia wszystkie zasoby używane przez bieżący obiekt i zamyka podstawowy strumień. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| void [Flush](./flush/)() override | Opróżnia zawartość bufora do podstawowego strumienia, a następnie opróżnia podstawowy strumień. |
| **bool** [get_AutoFlush](./get_autoflush/)() const | Zwraca wartość wskazującą, czy [StreamWriter](./) będzie opróżniał dane do podstawowego strumienia przy każdym wywołaniu metody [StreamWriter::Write](./write/). |
| [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() const | Zwraca współdzielony wskaźnik do obiektu reprezentującego podstawowy strumień. |
| [EncodingPtr](../../system/encodingptr/) [get_Encoding](./get_encoding/)() override | Zwraca obecnie używane kodowanie. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](../textwriter/get_formatprovider/)() const | Zwraca obecnie używany obiekt [IFormatProvider](../../system/iformatprovider/). |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](../textwriter/get_formatprovider/)() | Zwraca obecnie używany obiekt [IFormatProvider](../../system/iformatprovider/). |
| virtual [System::String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() const | Zwraca ciąg znaków końca wiersza. |
| [String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() | Zwraca ciąg znaków końca wiersza. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Odpowiednik metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Odpowiednik operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu stróża [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. W rzeczywistości nic nie kopiuje, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. W rzeczywistości nic nie kopiuje, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągu znaków i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
| void [set_AutoFlush](./set_autoflush/)(**bool**) | Zwraca wartość określającą, czy [StreamWriter](./) powinien opróżniać dane do podstawowego strumienia przy każdym wywołaniu metody [StreamWriter::Write](./write/). |
| virtual void [set_NewLine](../textwriter/set_newline/)(const [System::String](../../system/string/)\&) | Ustawia ciąg znaków końca wiersza. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączyć wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Tworzy instancję obiektu [StreamWriter](./), który zapisuje znaki do określonego podstawowego strumienia używając kodowania UTF-8 i bufora o domyślnym rozmiarze 1024 bajtów. |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Tworzy instancję obiektu [StreamWriter](./), który zapisuje znaki do określonego podstawowego strumienia używając podanego kodowania i bufora o domyślnym rozmiarze 1024 bajtów. |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, int, **bool**) | Tworzy instancję obiektu [StreamWriter](./), który zapisuje znaki do określonego podstawowego strumienia używając podanego kodowania i bufora o określonym rozmiarze. Parametr określa, czy podstawowy strumień powinien być zamknięty po zlikwidowaniu obiektu [StreamWriter](./). |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&) | Tworzy instancję obiektu [StreamWriter](./), który zapisuje znaki do określonego pliku używając kodowania UTF-8 i bufora o domyślnym rozmiarze 1024 bajtów. |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&, **bool**, const [EncodingPtr](../../system/encodingptr/)\&) | Tworzy instancję obiektu [StreamWriter](./), który zapisuje znaki do określonego pliku używając podanego kodowania i bufora o domyślnym rozmiarze 1024 bajtów. Parametr określa, czy dane mają być dołączane do pliku, czy plik ma być nadpisany. |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&, **bool**, const [EncodingPtr](../../system/encodingptr/)\&, int) | Tworzy instancję obiektu [StreamWriter](./), który zapisuje znaki do określonego pliku używając podanego kodowania i rozmiaru bufora. Parametr określa, czy dane mają być dołączane do pliku, czy plik ma być nadpisany. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Odpowiednik metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów do ciągu znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu stróża [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa słaby licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza słaby licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [Write](./write/)(char_t) override | Zapisuje podany znak do strumienia. |
| void [Write](./write/)(const [String](../../system/string/)\&) override | Zapisuje podany ciąg znaków do strumienia. |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) override | Zapisuje reprezentację tekstową podanego obiektu do strumienia. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) override | Zapisuje wszystkie znaki z podanej tablicy do strumienia. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Zapisuje podany podzakres znaków UTF-16 z podanej tablicy znaków do strumienia. |
| void [Write](./write/)(const char_t *) override | Zapisuje podany ciąg C (c-string) do strumienia. |
| void [Write](./write/)(const [System::SharedPtr](../../system/sharedptr/)\<T\>\&) | Zapisuje reprezentację tekstową podanego obiektu do strumienia. |
| virtual void [Write](../textwriter/write/)(**bool**) | Zapisuje reprezentację tekstową podanej wartości logicznej do strumienia. |
| virtual void [Write](../textwriter/write/)([Decimal](../../system/decimal/)) | Zapisuje reprezentację tekstową podanego obiektu [Decimal](../../system/decimal/) do strumienia. |
| virtual void [Write](../textwriter/write/)(**double**) | Zapisuje reprezentację tekstową podanej wartości double do strumienia. |
| virtual void [Write](../textwriter/write/)(int) | Zapisuje reprezentację tekstową podanej 32-bitowej wartości całkowitej do strumienia. |
| virtual void [Write](../textwriter/write/)(**int64_t**) | Zapisuje reprezentację tekstową podanej 64-bitowej wartości całkowitej do strumienia. |
| virtual void [Write](../textwriter/write/)(**float**) | Zapisuje reprezentację tekstową podanej wartości float do strumienia. |
| virtual void [Write](../textwriter/write/)(**uint32_t**) | Zapisuje reprezentację tekstową podanej nieujemnej 32-bitowej wartości całkowitej do strumienia. |
| virtual void [Write](../textwriter/write/)(**uint64_t**) | Zapisuje reprezentację tekstową podanej nieujemnej 64-bitowej wartości całkowitej do strumienia. |
| virtual void [Write](../textwriter/write/)(const [TypeInfo](../../system/typeinfo/)\&) | Zapisuje reprezentację tekstową podanego obiektu [TypeInfo](../../system/typeinfo/) do strumienia. |
| void [Write](../textwriter/write/)(const [String](../../system/string/)\&, const TArgs\&...) | Zapisuje podane wartości sformatowane zgodnie z podanym formatem do strumienia. |
| void [WriteLine](./writeline/)() override | Zapisuje znaki końca wiersza do strumienia. |
| void [WriteLine](./writeline/)(const [String](../../system/string/)\&) override | Zapisuje podany ciąg znaków, a następnie znaki końca wiersza do strumienia. |
| void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) override | Zapisuje reprezentację tekstową podanego obiektu, a następnie znaki końca wiersza do strumienia. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) override | Zapisuje wszystkie znaki z podanej tablicy, a następnie znaki końca wiersza do strumienia. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Zapisuje podany podzakres znaków UTF-16 z podanej tablicy znaków, a następnie znaki końca wiersza do strumienia. |
| void [WriteLine](./writeline/)(const char_t *) override | Zapisuje podany ciąg C, a następnie znaki końca wiersza do strumienia. |
| void [WriteLine](./writeline/)(const [System::SharedPtr](../../system/sharedptr/)\<T\>\&) | Zapisuje reprezentację tekstową podanego obiektu, a następnie znaki końca wiersza do strumienia. |
| virtual void [WriteLine](../textwriter/writeline/)(**bool**) | Zapisuje reprezentację tekstową podanej wartości logicznej, a następnie znaki końca wiersza do strumienia. |
| virtual void [WriteLine](../textwriter/writeline/)(char_t) | Zapisuje podany znak, a następnie znaki końca wiersza do strumienia. |
| virtual void [WriteLine](../textwriter/writeline/)([Decimal](../../system/decimal/)) | Zapisuje reprezentację tekstową podanego obiektu [Decimal](../../system/decimal/), a następnie znaki końca wiersza do strumienia. |
| virtual void [WriteLine](../textwriter/writeline/)(**double**) | Zapisuje reprezentację tekstową podanej wartości double, a następnie znaki końca wiersza do strumienia. |
| virtual void [WriteLine](../textwriter/writeline/)(int) | Zapisuje reprezentację tekstową podanej 32-bitowej wartości całkowitej, a następnie znaki końca wiersza do strumienia. |
| virtual void [WriteLine](../textwriter/writeline/)(**int64_t**) | Zapisuje reprezentację tekstową podanej 64-bitowej wartości całkowitej, a następnie znaki końca wiersza do strumienia. |
| virtual void [WriteLine](../textwriter/writeline/)(**float**) | Zapisuje reprezentację tekstową podanej wartości float, a następnie znaki końca wiersza do strumienia. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint32_t**) | Zapisuje reprezentację tekstową podanej nieujemnej 32-bitowej wartości całkowitej, a następnie znaki końca wiersza do strumienia. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint64_t**) | Zapisuje reprezentację tekstową podanej nieujemnej 64-bitowej wartości całkowitej, a następnie znaki końca wiersza do strumienia. |
| virtual void [WriteLine](../textwriter/writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | Zapisuje reprezentację tekstową podanego obiektu [TypeInfo](../../system/typeinfo/), a następnie znaki końca wiersza do strumienia. |
| void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | Zapisuje podane wartości sformatowane zgodnie z podanym formatem, a następnie znaki końca wiersza do strumienia. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |
|  [~StreamWriter](./~streamwriter/)() | Destruktor. |
| virtual  [~TextWriter](../textwriter/~textwriter/)() | Destruktor. |

## Zobacz także

* Klasa [TextWriter](../textwriter/)
* Przestrzeń nazw [System::IO](../)
* Biblioteka [Aspose.Slides](../../)