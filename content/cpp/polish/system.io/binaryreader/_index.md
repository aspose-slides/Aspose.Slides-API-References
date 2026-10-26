---
title: BinaryReader
second_title: Aspose.Slides dla C++ - odwołanie do API
description: "Reprezentuje odczytywacz, który odczytuje typy prymitywne jako dane binarne w określonym kodowaniu. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji System::MakeObject(). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ może to skutkować błędami czasu wykonania i/lub błędami asercji. Zawsze opakowuj tę klasę w wskaźnik System::SmartPtr i używaj tego wskaźnika do przekazywania go jako argumentu do funkcji."
type: docs
weight: 92
url: /pl/system.io/binaryreader/
---
## BinaryReader klasa

Represents a reader that reads primitive data types as binary data in particular encoding. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class BinaryReader : public System::IDisposable
```

## Metody

| Metoda | Opis |
| --- | --- |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Tworzy instancję klasy [BinaryReader](./), która odczytuje dane ze wskazanego strumienia przy użyciu kodowania UTF-8. |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Tworzy instancję klasy [BinaryReader](./), która odczytuje dane ze wskazanego strumienia przy użyciu określonego kodowania. |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&, **bool**) | Tworzy instancję klasy [BinaryReader](./), która odczytuje dane ze wskazanego strumienia przy użyciu określonego kodowania. |
| virtual void [Close](./close/)() | Zamyka bieżący obiekt [BinaryReader](./) oraz podstawowy strumień wejściowy. |
| void [Dispose](./dispose/)() override | Zwalnia wszystkie zasoby używane przez bieżący obiekt i zamyka podstawowy strumień. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartości w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() | Zwraca strumień wejściowy. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Odpowiednik metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Odpowiednik operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. W rzeczywistości nic nie kopiuje, jedynie inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. W rzeczywistości nic nie kopiuje, jedynie inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| virtual int [PeekChar](./peekchar/)() | Odczytuje pojedynczy znak ze strumienia wejściowego bez zmiany kursora odczytu strumienia. |
| virtual int [Read](./read/)() | Odczytuje pojedynczy znak ze strumienia wejściowego. |
| virtual int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Odczytuje określoną liczbę bajtów ze strumienia wejściowego i zapisuje je do określonej tablicy bajtów. |
| virtual int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Odczytuje określoną liczbę znaków ze strumienia wejściowego, konwertuje je na kodowanie UTF-16 i zapisuje powstałe znaki UTF-16 do określonej tablicy znaków, zaczynając od wskazanej pozycji. |
| virtual **bool** [ReadBoolean](./readboolean/)() | Odczytuje pojedynczy bajt ze strumienia wejściowego i zwraca jego reprezentację logiczną. |
| virtual **uint8_t** [ReadByte](./readbyte/)() | Odczytuje pojedynczy bajt ze strumienia wejściowego. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ReadBytes](./readbytes/)(int) | Odczytuje określoną liczbę bajtów ze strumienia wejściowego. |
| virtual char_t [ReadChar](./readchar/)() | Odczytuje pojedynczy znak ze strumienia wejściowego. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [ReadChars](./readchars/)(int) | Odczytuje określoną liczbę znaków ze strumienia wejściowego i zwraca je w kodowaniu UTF-16. |
| virtual [Decimal](../../system/decimal/) [ReadDecimal](./readdecimal/)() | NIE ZIMPLEMENTOWANO. |
| virtual **double** [ReadDouble](./readdouble/)() | Odczytuje 8 bajtów ze strumienia wejściowego i zwraca je jako liczbę zmiennoprzecinkową podwójnej precyzji. |
| virtual **int16_t** [ReadInt16](./readint16/)() | Odczytuje 2 bajty ze strumienia wejściowego i zwraca je jako 16-bitową wartość całkowitą. |
| virtual int [ReadInt32](./readint32/)() | Odczytuje 4 bajty ze strumienia wejściowego i zwraca je jako 32-bitową wartość całkowitą. |
| virtual **int64_t** [ReadInt64](./readint64/)() | Odczytuje 8 bajtów ze strumienia wejściowego i zwraca je jako 64-bitową wartość całkowitą. |
| virtual **int8_t** [ReadSByte](./readsbyte/)() | Odczytuje pojedynczy bajt ze strumienia wejściowego i zwraca go jako signed 8-bitową wartość całkowitą. |
| virtual **float** [ReadSingle](./readsingle/)() | Odczytuje 4 bajty ze strumienia wejściowego i zwraca je jako liczbę zmiennoprzecinkową pojedynczej precyzji. |
| virtual [String](../../system/string/) [ReadString](./readstring/)() | Odczytuje łańcuch znaków z bieżącego strumienia. Łańcuch jest poprzedzony długością, zakodowaną jako liczba całkowita w siedmiobitowych fragmentach. |
| virtual **uint16_t** [ReadUInt16](./readuint16/)() | Odczytuje 2 bajty ze strumienia wejściowego i zwraca je jako nieznakowaną 16-bitową wartość całkowitą. |
| virtual **uint32_t** [ReadUInt32](./readuint32/)() | Odczytuje 4 bajty ze strumienia wejściowego i zwraca je jako nieznakowaną 32-bitową wartość całkowitą. |
| virtual **uint64_t** [ReadUInt64](./readuint64/)() | Odczytuje 8 bajtów ze strumienia wejściowego i zwraca je jako nieznakowaną 64-bitową wartość całkowitą. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty według referencji. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty według referencji. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartości z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku łańcuchów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia zmianę wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Odpowiednik metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów na łańcuch znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~BinaryReader](./~binaryreader/)() | Destruktor. |
| virtual  [~Object](../../system/object/~object/)() | Usuwa obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [IDisposable](../../system/idisposable/)
* Przestrzeń nazw [System::IO](../)
* Biblioteka [Aspose.Slides](../../)