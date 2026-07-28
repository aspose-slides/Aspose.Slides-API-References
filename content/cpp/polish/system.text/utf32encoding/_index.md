---
title: UTF32Encoding
second_title: Aspose.Slides dla C++ – referencja API
description: "Kodowanie UTF-32. Obiekty tej klasy powinny być tworzone wyłącznie przy użyciu funkcji System::MakeObject(). Nigdy nie twórz instancji tego typu na stosie ani nie używaj operatora new, ponieważ może to spowodować błędy czasu wykonywania i/lub awarie asercji. Zawsze opakowuj tę klasę w wskaźnik System::SmartPtr i używaj tego wskaźnika do przekazywania jej jako argumentu do funkcji."
type: docs
weight: 352
url: /pl/system.text/utf32encoding/
---
## UTF32Encoding klasa

UTF-32 encoding. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class UTF32Encoding : public System::Text::ICUEncoding
```

## Metody

| Metoda | Opis |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Klonuje obiekt kodowania. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Konwertuje bajty pomiędzy dwoma kodowaniami. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | Konwertuje bajty pomiędzy dwoma kodowaniami. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Porównuje z obiektem. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](../encoding/get_ascii/)() | Pobiera kodowanie ASCII. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](../encoding/get_bigendianunicode/)() | Pobiera standardowy obiekt kodowania Unicode w porządku big-endian. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](../encoding/get_bigendianutf32/)() | Pobiera standardowy obiekt kodowania UTF-32 w porządku big-endian. |
| virtual [String](../../system/string/) [get_BodyName](../encoding/get_bodyname/)() | Pobiera nazwę kodowania zgodną z treścią agenta pocztowego. |
| virtual int [get_CodePage](../encoding/get_codepage/)() | Pobiera identyfikator strony kodowej [Windows](../../system.windows/). |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](../encoding/get_decoderfallback/)() const | Pobiera zastępnik dekodera. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](../encoding/get_default/)() | Pobiera domyślne kodowanie. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](../encoding/get_encoderfallback/)() const | Pobiera zastępnik enkodera. |
| virtual [String](../../system/string/) [get_EncodingName](../encoding/get_encodingname/)() | Pobiera czytelną nazwę kodowania. |
| virtual [String](../../system/string/) [get_HeaderName](../encoding/get_headername/)() | Pobiera nazwę kodowania zgodną z nagłówkiem agenta pocztowego. |
| virtual **bool** [get_IsBrowserDisplay](../encoding/get_isbrowserdisplay/)() | Sprawdza, czy kodowanie może być użyte w przeglądarce do wyświetlania treści. |
| virtual **bool** [get_IsBrowserSave](../encoding/get_isbrowsersave/)() | Sprawdza, czy kodowanie może być użyte w przeglądarce do zapisywania treści. |
| virtual **bool** [get_IsMailNewsDisplay](../encoding/get_ismailnewsdisplay/)() | Sprawdza, czy kodowanie może być użyte w kliencie pocztowym do wyświetlania treści. |
| virtual **bool** [get_IsMailNewsSave](../encoding/get_ismailnewssave/)() | Sprawdza, czy kodowanie może być użyte w kliencie pocztowym do zapisywania treści. |
| **bool** [get_IsReadOnly](../encoding/get_isreadonly/)() | Sprawdza, czy kodowanie jest tylko do odczytu. |
| virtual **bool** [get_IsSingleByte](../encoding/get_issinglebyte/)() | Sprawdza, czy kodowanie jest jednobajtowe. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](../encoding/get_latin1/)() | Pobiera kodowanie Latin1. DO WEWNĘTRZNEGO UŻYTKU. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](../encoding/get_unicode/)() | Pobiera standardowy obiekt kodowania Unicode. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](../encoding/get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](../encoding/get_utf7/)() | Pobiera standardowy obiekt kodowania UTF-7. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](../encoding/get_utf8/)() | Pobiera standardowy obiekt kodowania UTF-8. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](../encoding/get_utf8unmarked/)() | Tylko wewnętrzne, przeznaczone do użytku przez biblioteki klas: Nieoznaczone i nie walidujące wejścia. |
| virtual [String](../../system/string/) [get_WebName](../encoding/get_webname/)() | Pobiera nazwę kodowania zgodną z IANA. |
| virtual int [get_WindowsCodePage](../encoding/get_windowscodepage/)() | Pobiera identyfikator strony kodowej [Windows](../../system.windows/). |
| int [GetByteCount](../icuencoding/getbytecount/)(const char_t *, int) override | Pobiera liczbę znaków potrzebnych do zakodowania bufora znaków. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | RTTI. |
| int [GetByteCount](../icuencoding/getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(const [String](../../system/string/)\&) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(const char_t *, int) | RTTI. |
| int [GetBytes](../icuencoding/getbytes/)(const char_t *, int, **uint8_t** *, int) override | Pobiera bajty wynikające z kodowania bufora znaków. |
| virtual int [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Pobiera bajty wynikające z kodowania bufora znaków. |
| virtual int [GetBytes](../icuencoding/getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | Pobiera bajty wynikające z kodowania bufora znaków. |
| int [GetBytes](../icuencoding/getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | Pobiera bajty wynikające z kodowania bufora znaków. |
| virtual int [GetBytes](../icuencoding/getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Pobiera bajty wynikające z kodowania bufora znaków. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const [String](../../system/string/)\&) | Pobiera bajty wynikające z kodowania bufora znaków. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Pobiera bajty wynikające z kodowania bufora znaków. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | Pobiera bajty wynikające z kodowania bufora znaków. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Pobiera bajty wynikające z kodowania bufora znaków. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Pobiera bajty wynikające z kodowania bufora znaków. |
| virtual int [GetBytes](../icuencoding/getbytes/)(const char_t *, int, **uint8_t** *, int) | Pobiera bajty wynikające z kodowania bufora znaków. |
| int [GetCharCount](../icuencoding/getcharcount/)(const **uint8_t** *, int) override | Pobiera liczbę znaków potrzebnych do dekodowania bufora bajtów. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Pobiera liczbę znaków potrzebnych do dekodowania bufora bajtów. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Pobiera liczbę znaków potrzebnych do dekodowania bufora bajtów. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)(const **uint8_t** *, int) | Pobiera liczbę znaków potrzebnych do dekodowania bufora bajtów. |
| int [GetChars](../icuencoding/getchars/)(const **uint8_t** *, int, char_t *, int) override | Pobiera znaki wynikające z dekodowania bufora bajtów. |
| virtual int [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | Pobiera znaki wynikające z dekodowania bufora bajtów. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Pobiera znaki wynikające z dekodowania bufora bajtów. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Pobiera znaki wynikające z dekodowania bufora bajtów. |
| virtual int [GetChars](../icuencoding/getchars/)(const **uint8_t** *, int, char_t *, int) | Pobiera znaki wynikające z dekodowania bufora bajtów. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę licznika referencji powiązaną z obiektem. |
| [DecoderPtr](../../system/decoderptr/) [GetDecoder](../icuencoding/getdecoder/)() override | Pobiera dekoder, który przekazuje żądania do tego obiektu. |
| [EncoderPtr](../../system/encoderptr/) [GetEncoder](../icuencoding/getencoder/)() override | Pobiera enkoder, który przekazuje żądania do tego obiektu. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&) | Pobiera kodowanie według nazwy. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int) | Pobiera kodowanie według strony kodowej. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Pobiera kodowanie według strony kodowej. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Pobiera kodowanie według nazwy. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](../encoding/getencodings/)() | Pobiera listę znanych kodowań. |
| int [GetHashCode](./gethashcode/)() const override | Pobiera kod hash kodowania. |
| int [GetMaxByteCount](../icuencoding/getmaxbytecount/)(int) override | Pobiera maksymalną liczbę bajtów potrzebnych do zakodowania określonej liczby znaków. |
| int [GetMaxCharCount](../icuencoding/getmaxcharcount/)(int) override | Pobiera maksymalną liczbę znaków potrzebnych do dekodowania określonej liczby bajtów. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](./getpreamble/)() override | Pobiera nagłówek strony kodowej. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(**uint8_t** *, int) | Dekoduje bufor bajtów do łańcucha. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Dekoduje bufor bajtów do łańcucha. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Dekoduje bufor bajtów do łańcucha. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Dekoduje bufor bajtów do łańcucha. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | Dekoduje bufor bajtów do łańcucha. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Dekoduje bufor bajtów do łańcucha. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | Dekoduje bufor bajtów do łańcucha. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | Dekoduje bufor bajtów do łańcucha. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
|  [ICUEncoding](../icuencoding/icuencoding/)(const Details::EncodingInfoInternal *) | Konstruktor. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt reprezentuje instancję typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie typów niestandardowych. |
|   [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|   [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| **bool** [operator==](./operator_equal_equal/)(const [UTF32Encoding](./)\&) const | Porównuje parametry kodowań. |
| **bool** [operator==](../icuencoding/operator_equal_equal/)(const [ICUEncoding](../icuencoding/)\&) const | Porównuje kodowania przy użyciu stron kodowych. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartości z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągu znaków i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o określoną wartość. |
| void [set_DecoderFallback](../encoding/set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Ustawia zastępnik dekodera. |
| void [set_EncoderFallback](../encoding/set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | Ustawia zastępnik enkodera. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustaw n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję obiektów niestandardowych do łańcucha. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
|   [UTF32Encoding](./utf32encoding/)() | Konstruktor. |
|   [UTF32Encoding](./utf32encoding/)(**bool**, **bool**) | Konstruktor. |
|   [UTF32Encoding](./utf32encoding/)(**bool**, **bool**, **bool**) | Konstruktor. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa słaby licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza słaby licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Pola

| Pole | Opis |
| --- | --- |
| static constexpr [BIG_UTF32_CODE_PAGE](./big_utf32_code_page/) | Liczba magiczna używana przez [Windows](../../system.windows/) dla identyfikatora kodowej big endian UTF-32. |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | Domyślna wartość strony kodowej. |
| static constexpr [UTF32_CODE_PAGE](./utf32_code_page/) | Liczba magiczna używana przez [Windows](../../system.windows/) dla identyfikatora kodowej little endian UTF-32. |

## Zobacz także

* Klasa [ICUEncoding](../icuencoding/)
* Przestrzeń nazw [System::Text](../)
* Biblioteka [Aspose.Slides](../../)