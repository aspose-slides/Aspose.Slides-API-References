---
title: StreamReader
second_title: Aspose.Slides dla C++ – odwołanie API
description: "Reprezentuje czytnik, który odczytuje znaki z strumienia bajtów. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji System::MakeObject(). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonania i/lub naruszenia asercji. Zawsze owijaj tę klasę w wskaźnik System::SmartPtr i używaj tego wskaźnika do przekazywania go jako argumentu do funkcji."
type: docs
weight: 378
url: /pl/system.io/streamreader/
---
## StreamReader klasa


Reprezentuje czytnik, który odczytuje znaki z strumienia bajtów. Obiekty tej klasy powinny być alokowane wyłącznie za pomocą funkcji [System::MakeObject()](../../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonania i/lub naruszenia asercji. Zawsze owijaj tę klasę w wskaźnik [System::SmartPtr](../../system/smartptr/) i używaj tego wskaźnika do przekazywania go jako argumentu do funkcji.

```cpp
class StreamReader : public System::IO::TextReader
```

## Metody

| Method | Description |
| --- | --- |
| void [Close](./close/)() override | Zamyka bieżący i podstawowy strumień. |
| virtual void [Dispose](./dispose/)(**bool**) | Zwalnia wszystkie zasoby używane przez bieżący obiekt i zamyka podstawowy strumień. |
| void [Dispose](./dispose/)() override | Zwalnia wszystkie zasoby używane przez bieżący obiekt i zamyka podstawowy strumień. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, nawet jeśli zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, nawet jeśli zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() const | Zwraca wspólny wskaźnik do obiektu reprezentującego podstawowy strumień. |
| [EncodingPtr](../../system/encodingptr/) [get_CurrentEncoding](./get_currentencoding/)() | Zwraca aktualnie używane kodowanie. |
| **bool** [get_EndOfStream](./get_endofstream/)() | Zwraca wartość wskazującą, czy koniec strumienia został osiągnięty. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Odpowiednik metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie obiektów niestandardowych. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Odpowiednik operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie typów niestandardowych. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. W rzeczywistości nic nie kopiuje, tylko inicjalizuje nowy obiekt i umożliwia kopiowanie konstruktorów podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. W rzeczywistości nic nie kopiuje, tylko inicjalizuje nowy obiekt i umożliwia kopiowanie konstruktorów podklas. |
| int [Peek](./peek/)() override | Odczytuje pojedynczy znak ze strumienia bez zmian kursora odczytu strumienia. |
| int [Read](./read/)() override | Odczytuje pojedynczy znak ze strumienia. |
| int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) override | Odczytuje określoną liczbę znaków ze strumienia, konwertuje je na kodowanie UTF-16 i zapisuje powstałe znaki UTF-16 do określonej tablicy znaków począwszy od wskazanej pozycji. |
| virtual int [ReadBlock](../textreader/readblock/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Odczytuje maksymalną określoną liczbę znaków z bieżącego czytnika tekstu i zapisuje dane do bufora, zaczynając od podanego indeksu. |
| [String](../../system/string/) [ReadLine](./readline/)() override | Odczytuje znaki ze strumienia aż do końca bieżącej linii. |
| [String](../../system/string/) [ReadToEnd](./readtoend/)() override | Odczytuje znaki ze strumienia aż do końca strumienia. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Inkremenuje licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementuje i zwraca licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Tworzy instancję obiektu [StreamReader](./), który odczytuje znaki z określonego podstawowego strumienia przy użyciu kodowania UTF-8 i bufora o domyślnym rozmiarze 1024 bajtów. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **bool**) | Tworzy instancję obiektu [StreamReader](./), który odczytuje znaki z określonego podstawowego strumienia przy użyciu kodowania UTF-8 i bufora o domyślnym rozmiarze 1024 bajtów. Parametr określa, czy wykrywanie znacznika kolejności bajtów ma być włączone. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Tworzy instancję obiektu [StreamReader](./), który odczytuje znaki z określonego podstawowego strumienia przy użyciu podanego kodowania i bufora o domyślnym rozmiarze 1024 bajtów. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**) | Tworzy instancję obiektu [StreamReader](./), który odczytuje znaki z określonego podstawowego strumienia przy użyciu podanego kodowania i bufora o domyślnym rozmiarze 1024 bajtów. Parametr określa, czy wykrywanie znacznika kolejności bajtów ma być włączone. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**, int) | Tworzy instancję obiektu [StreamReader](./), który odczytuje znaki z określonego podstawowego strumienia przy użyciu podanego kodowania i bufora o podanym rozmiarze. Parametr określa, czy wykrywanie znacznika kolejności bajtów ma być włączone. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&) | Tworzy instancję obiektu [StreamReader](./), który odczytuje znaki z określonego pliku przy użyciu kodowania UTF-8 i bufora o domyślnym rozmiarze 4096 bajtów. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, **bool**) | Tworzy instancję obiektu [StreamReader](./), który odczytuje znaki z określonego pliku przy użyciu kodowania UTF-8 i bufora o domyślnym rozmiarze 4096 bajtów. Parametr określa, czy wykrywanie znacznika kolejności bajtów ma być włączone. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Tworzy instancję obiektu [StreamReader](./), który odczytuje znaki z określonego pliku przy użyciu podanego kodowania i bufora o domyślnym rozmiarze 4096 bajtów. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**) | Tworzy instancję obiektu [StreamReader](./), który odczytuje znaki z określonego podstawowego strumienia przy użyciu podanego kodowania i bufora o domyślnym rozmiarze 4096 bajtów. Parametr określa, czy wykrywanie znacznika kolejności bajtów ma być włączone. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**, int) | Tworzy instancję obiektu [StreamReader](./), który odczytuje znaki z określonego pliku przy użyciu podanego kodowania i bufora o podanym rozmiarze. Parametr określa, czy wykrywanie znacznika kolejności bajtów ma być włączone. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Odpowiednik metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję obiektów niestandardowych do ciągu znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Inkremenuje licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementuje licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |
|  [~StreamReader](./~streamreader/)() | Destruktor. |
## Zobacz także

* Klasa [TextReader](../textreader/)
* Przestrzeń nazw [System::IO](../)
* Biblioteka [Aspose.Slides](../../)