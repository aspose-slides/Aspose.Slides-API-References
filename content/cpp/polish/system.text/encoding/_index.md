---
title: Encoding
second_title: Aspose.Slides dla C++ - referencja API
description: Usługi kodowania.
type: docs
weight: 222
url: /pl/system.text/encoding/
---
## Encoding klasa


[Encoding](./) usługi.

```cpp
class Encoding : public System::Object
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() | Klonuje obiekt kodowania. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](./convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Konwertuje bajty między dwoma kodowaniami. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](./convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | Konwertuje bajty między dwoma kodowaniami. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Porównuje kodowania. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](./get_ascii/)() | Pobiera kodowanie ASCII. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](./get_bigendianunicode/)() | Pobiera standardowy obiekt kodowania Unicode w big-endian. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](./get_bigendianutf32/)() | Pobiera standardowy obiekt kodowania UTF-32 w big-endian. |
| virtual [String](../../system/string/) [get_BodyName](./get_bodyname/)() | Pobiera nazwę kodowania zgodną z ciałem agenta pocztowego. |
| virtual int [get_CodePage](./get_codepage/)() | Pobiera [Windows](../../system.windows/) identyfikator strony kodowej. |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](./get_decoderfallback/)() const | Pobiera zastępczy dekoder. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](./get_default/)() | Pobiera domyślne kodowanie. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](./get_encoderfallback/)() const | Pobiera zastępczy enkoder. |
| virtual [String](../../system/string/) [get_EncodingName](./get_encodingname/)() | Pobiera nazwę kodowania czytelną dla człowieka. |
| virtual [String](../../system/string/) [get_HeaderName](./get_headername/)() | Pobiera nazwę kodowania zgodną z nagłówkiem agenta pocztowego. |
| virtual **bool** [get_IsBrowserDisplay](./get_isbrowserdisplay/)() | Sprawdza, czy kodowanie może być użyte w przeglądarce do wyświetlania treści. |
| virtual **bool** [get_IsBrowserSave](./get_isbrowsersave/)() | Sprawdza, czy kodowanie może być użyte w przeglądarce do zapisywania treści. |
| virtual **bool** [get_IsMailNewsDisplay](./get_ismailnewsdisplay/)() | Sprawdza, czy kodowanie może być użyte w kliencie poczty do wyświetlania treści. |
| virtual **bool** [get_IsMailNewsSave](./get_ismailnewssave/)() | Sprawdza, czy kodowanie może być użyte w kliencie poczty do zapisywania treści. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() | Sprawdza, czy kodowanie jest tylko do odczytu. |
| virtual **bool** [get_IsSingleByte](./get_issinglebyte/)() | Sprawdza, czy kodowanie jest jednobajtowe. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](./get_latin1/)() | Pobiera kodowanie Latin1. DO UŻYTKU WEWNĘTRZNEGO. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](./get_unicode/)() | Pobiera standardowy obiekt kodowania Unicode. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](./get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](./get_utf7/)() | Pobiera standardowy obiekt kodowania UTF-7. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](./get_utf8/)() | Pobiera standardowy obiekt kodowania UTF-8. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](./get_utf8unmarked/)() | Tylko wewnętrzne, do użycia przez biblioteki klas: Nieoznaczone i nie weryfikujące danych wejściowych. |
| virtual [String](../../system/string/) [get_WebName](./get_webname/)() | Pobiera nazwę kodowania zgodną z IANA. |
| virtual int [get_WindowsCodePage](./get_windowscodepage/)() | Pobiera [Windows](../../system.windows/) identyfikator strony kodowej. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Pobiera liczbę znaków potrzebnych do zakodowania bufora znaków. |
| virtual int [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | Pobiera liczbę znaków potrzebnych do zakodowania bufora znaków. |
| int [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Pobiera liczbę znaków potrzebnych do zakodowania bufora znaków. |
| virtual int [GetByteCount](./getbytecount/)(const [String](../../system/string/)\&) | Pobiera liczbę znaków potrzebnych do zakodowania łańcucha. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Pobiera liczbę znaków potrzebnych do zakodowania bufora znaków. |
| virtual int [GetByteCount](./getbytecount/)(const char_t *, int) | Pobiera liczbę znaków potrzebnych do zakodowania bufora znaków. |
| virtual int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Pobiera bajty powstałe w wyniku kodowania bufora znaków. |
| virtual int [GetBytes](./getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | Pobiera bajty powstałe w wyniku kodowania bufora znaków. |
| int [GetBytes](./getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | Pobiera bajty powstałe w wyniku kodowania bufora znaków. |
| virtual int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Pobiera bajty powstałe w wyniku kodowania bufora znaków. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const [String](../../system/string/)\&) | Pobiera bajty powstałe w wyniku kodowania bufora znaków. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Pobiera bajty powstałe w wyniku kodowania bufora znaków. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | Pobiera bajty powstałe w wyniku kodowania bufora znaków. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Pobiera bajty powstałe w wyniku kodowania bufora znaków. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Pobiera bajty powstałe w wyniku kodowania bufora znaków. |
| virtual int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) | Pobiera bajty powstałe w wyniku kodowania bufora znaków. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Pobiera liczbę znaków potrzebnych do dekodowania bufora bajtów. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Pobiera liczbę znaków potrzebnych do dekodowania bufora bajtów. |
| virtual int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) | Pobiera liczbę znaków potrzebnych do dekodowania bufora bajtów. |
| virtual int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | Pobiera znaki powstałe po dekodowaniu bufora bajtów. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Pobiera znaki powstałe po dekodowaniu bufora bajtów. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Pobiera znaki powstałe po dekodowaniu bufora bajtów. |
| virtual int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) | Pobiera znaki powstałe po dekodowaniu bufora bajtów. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual [DecoderPtr](../../system/decoderptr/) [GetDecoder](./getdecoder/)() | Pobiera dekoder, który przekazuje żądania do tego obiektu. |
| virtual [EncoderPtr](../../system/encoderptr/) [GetEncoder](./getencoder/)() | Pobiera enkoder, który przekazuje żądania do tego obiektu. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(const [String](../../system/string/)\&) | Pobiera kodowanie po nazwie. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(int) | Pobiera kodowanie po identyfikatorze strony kodowej. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Pobiera kodowanie po identyfikatorze strony kodowej. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Pobiera kodowanie po nazwie. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](./getencodings/)() | Pobiera listę znanych kodowań. |
| int [GetHashCode](./gethashcode/)() const override | Haszuje kodowanie. |
| virtual int [GetMaxByteCount](./getmaxbytecount/)(int) | Pobiera maksymalną liczbę bajtów potrzebną do zakodowania podanej liczby znaków. |
| virtual int [GetMaxCharCount](./getmaxcharcount/)(int) | Pobiera maksymalną liczbę znaków potrzebną do dekodowania podanej liczby bajtów. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](./getpreamble/)() | Zwraca sekwencję bajtów oznaczającą kodowanie (np. BOM). |
| virtual [String](../../system/string/) [GetString](./getstring/)(**uint8_t** *, int) | Dekoduje bufor bajtów do łańcucha. |
| [String](../../system/string/) [GetString](./getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Dekoduje bufor bajtów do łańcucha. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Dekoduje bufor bajtów do łańcucha. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Dekoduje bufor bajtów do łańcucha. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | Dekoduje bufor bajtów do łańcucha. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Dekoduje bufor bajtów do łańcucha. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | Dekoduje bufor bajtów do łańcucha. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | Dekoduje bufor bajtów do łańcucha. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę C# lock(). Wywołaj bezpośrednio lub użyj obiektu [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie typów własnych. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje obiekt typu wartości z nullptr przez referencję. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągu znaków i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
| void [set_DecoderFallback](./set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Ustawia zastępczy dekoder. |
| void [set_EncoderFallback](./set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | Ustawia zastępczy enkoder. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Inkrementuje współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; używaj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Dekrementuje i zwraca współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; używaj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów do łańcucha. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie C# lock(). Wywołaj bezpośrednio lub użyj obiektu [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Inkrementuje licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; używaj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Dekrementuje licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; używaj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Pola

| Pole | Opis |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](./default_code_page/) | Domyślna wartość strony kodowej. |

## Definicje typu

| Definicja typu | Opis |
| --- | --- |
| [Ptr](./ptr/) | RTTI. |

## Zobacz także

* Klasa [Object](../../system/object/)
* Przestrzeń nazw [System::Text](../)
* Biblioteka [Aspose.Slides](../../)