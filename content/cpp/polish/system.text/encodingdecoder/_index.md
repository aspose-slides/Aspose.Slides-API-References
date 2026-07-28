---
title: EncodingDecoder
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: "Dekoder wykorzystujący obiekt kodowania do dekodowania. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji System::MakeObject(). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ może to spowodować błędy w czasie wykonywania i/lub awarie asercji. Zawsze owiń tę klasę wskaźnikiem System::SmartPtr i używaj tego wskaźnika do przekazywania go funkcjom jako argument."
type: docs
weight: 235
url: /pl/system.text/encodingdecoder/
---
## EncodingDecoder klasa

[Decoder](../decoder/) wykorzystuje obiekt kodowania do dekodowania. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie wykonywania i/lub awarie asercji. Zawsze owiń tę klasę w wskaźnik [System::SmartPtr](../../system/smartptr/) i używaj tego wskaźnika do przekazywania go jako argumentu do funkcji.

```cpp
class EncodingDecoder : public System::Text::Decoder
```

## Metody

| Metoda | Opis |
| --- | --- |
| void [Convert](./convert/)(const **uint8_t** *, int, char_t *, int, **bool**, int&, int&, **bool**&) override | Konwertuje bajty na znaki. |
| void [Convert](./convert/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, **bool**, int&, int&, **bool**\&) override | Konwertuje bajty na znaki. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const&, **float** const&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const&, **double** const&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase&, void **) const | Wyłącznie do użytku wewnętrznego. |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_Fallback](../decoder/get_fallback/)() const | Zwraca domyślne zachowanie obsługi błędów. |
| [DecoderFallbackBufferPtr](../../system/decoderfallbackbufferptr/) [get_FallbackBuffer](../decoder/get_fallbackbuffer/)() const | Zwraca bufor rezerwowy. |
| virtual int [GetCharCount](../decoder/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Zwraca liczbę znaków potrzebnych do dekodowania bufora. |
| virtual int [GetCharCount](../decoder/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, **bool**) | Zwraca liczbę znaków potrzebnych do dekodowania bufora. |
| virtual int [GetCharCount](../decoder/getcharcount/)(const **uint8_t** *, int, **bool**) | Zwraca liczbę znaków potrzebnych do dekodowania bufora. |
| virtual int [GetChars](../decoder/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | Pobiera znaki uzyskane po dekodowaniu bufora. |
| virtual int [GetChars](../decoder/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int, **bool**) | Pobiera znaki uzyskane po dekodowaniu bufora. |
| virtual int [GetChars](../decoder/getchars/)(const **uint8_t** *, int, char_t *, int, **bool**) | Pobiera znaki uzyskane po dekodowaniu bufora. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Zwraca strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Zwraca rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
| [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
| [Object](../../system/object/object/)([Object](../../system/object/) const&) | Konstruktor kopiujący. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const&) | Operator przypisania. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const&, [ptr](../../system/object/ptr/) const&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, T const&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, [String](../../system/string/) const&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku stringów. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| virtual void [Reset](../decoder/reset/)() | Czyści wewnętrzny stan dekodera. |
| void [set_Fallback](../decoder/set_fallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Ustawia domyślne zachowanie obsługi błędów. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Zwraca bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Inkrementuje licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego używać inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementuje i zwraca licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego używać inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów na string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Inkrementuje licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego używać inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementuje licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego używać inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [Decoder](../decoder/)
* Przestrzeń nazw [System::Text](../)
* Biblioteka [Aspose.Slides](../../)