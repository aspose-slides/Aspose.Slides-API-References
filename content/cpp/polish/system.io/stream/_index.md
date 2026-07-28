---
title: Stream
second_title: Aspose.Slides dla C++ – referencja API
description: "Podstawowa klasa dla różnych implementacji strumieni. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji System::MakeObject(). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie wykonywania i/lub błędy asercji. Zawsze opakuj tę klasę w wskaźnik System::SmartPtr i użyj tego wskaźnika do przekazywania go funkcjom jako argument."
type: docs
weight: 365
url: /pl/system.io/stream/
---
## Klasa Stream


Podstawowa klasa dla różnych implementacji strumieni. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie wykonywania i/lub błędy asercji. Zawsze opakuj tę klasę w wskaźnik [System::SmartPtr](../../system/smartptr/) i używaj tego wskaźnika do przekazywania jej funkcjom jako argument.

```cpp
class Stream : public System::IDisposable
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](./beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Inicjuje asynchroniczną operację odczytu. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](./beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Inicjuje asynchroniczną operację zapisu. |
| virtual void [Close](./close/)() | Zamyka strumień. |
| void [CopyTo](./copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](./)\>\&) | Kopiuje bajty do określonego strumienia. |
| void [CopyTo](./copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](./)\>\&, **int32_t**) | Kopiuje bajty do określonego strumienia, używając określonego rozmiaru bufora. |
| void [Dispose](./dispose/)() override | Zwalnia wszystkie zasoby używane przez bieżący obiekt i zamyka strumień. |
| virtual int [EndRead](./endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Czeka, aż określona asynchroniczna operacja odczytu zakończy się. |
| virtual void [EndWrite](./endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Kończy asynchroniczną operację zapisu. Czeka, aż określona asynchroniczna operacja zapisu zakończy się. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartości w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| virtual void [Flush](./flush/)() | Czyści bufory tego strumienia i zapisuje wszystkie buforowane dane do leżącego pod spodem magazynu. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](./flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Asynchronicznie czyści wszystkie bufory tego strumienia, powoduje zapisanie wszelkich buforowanych danych do leżącego pod spodem urządzenia i monitoruje żądania anulowania. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](./flushasync/)() | Asynchronicznie czyści wszystkie bufory tego strumienia, powoduje zapisanie wszelkich buforowanych danych do leżącego pod spodem urządzenia i monitoruje żądania anulowania. |
| virtual **bool** [get_CanRead](./get_canread/)() const | Określa, czy strumień jest czytelny. |
| virtual **bool** [get_CanSeek](./get_canseek/)() const | Określa, czy strumień obsługuje przeszukiwanie. |
| virtual **bool** [get_CanTimeout](./get_cantimeout/)() const | Pobiera wartość określającą, czy bieżący strumień może przekroczyć limit czasu. |
| virtual **bool** [get_CanWrite](./get_canwrite/)() const | Określa, czy strumień jest zapisywalny. |
| virtual **int64_t** [get_Length](./get_length/)() const | Zwraca długość strumienia w bajtach. |
| virtual **int64_t** [get_Position](./get_position/)() const | Zwraca bieżącą pozycję strumienia. |
| virtual int [get_ReadTimeout](./get_readtimeout/)() const | Pobiera wartość w milisekundach określającą, jak długo strumień będzie próbował odczytywać przed przekroczeniem limitu czasu. |
| virtual int [get_WriteTimeout](./get_writetimeout/)() const | Pobiera wartość w milisekundach określającą, jak długo strumień będzie próbował zapisywać przed przekroczeniem limitu czasu. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Odpowiednik metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Odpowiednik operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| virtual **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Odczytuje określoną liczbę bajtów ze strumienia i zapisuje je do określonej tablicy bajtów. |
| virtual **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Odczytuje określoną liczbę bajtów ze strumienia i zapisuje je do określonej tablicy bajtów. |
| **int32_t** [Read](./read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Odczytuje określoną liczbę bajtów ze strumienia i zapisuje je do określonej tablicy bajtów. |
| virtual **int32_t** [Read](./read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Odczytuje określoną liczbę bajtów ze strumienia i zapisuje je do określonego zakresu bajtów. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](./readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Asynchronicznie odczytuje sekwencję bajtów z bieżącego strumienia, przesuwa pozycję w strumieniu o liczbę odczytanych bajtów i monitoruje żądania anulowania. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](./readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Asynchronicznie odczytuje sekwencję bajtów z bieżącego strumienia, przesuwa pozycję w strumieniu o liczbę odczytanych bajtów i monitoruje żądania anulowania. |
| virtual int [ReadByte](./readbyte/)() | Odczytuje pojedynczy bajt ze strumienia i zwraca 32-bitową wartość całkowitą równą wartości odczytanego bajtu. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartości z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku stringów. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o określoną wartość. |
| virtual **int64_t** [Seek](./seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) | Ustawia pozycję strumienia reprezentowanego przez bieżący obiekt. |
| virtual void [set_Position](./set_position/)(**int64_t**) | Ustawia pozycję strumienia. |
| virtual void [set_ReadTimeout](./set_readtimeout/)(int) | Ustawia wartość określającą, czy bieżący strumień może przekroczyć limit czasu. |
| virtual void [set_WriteTimeout](./set_writetimeout/)(int) | Ustawia wartość w milisekundach określającą, jak długo strumień będzie próbował odczytywać przed przekroczeniem limitu czasu. |
| virtual void [SetLength](./setlength/)(**int64_t**) | Ustawia długość strumienia reprezentowanego przez bieżący obiekt. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Odpowiednik metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwertowanie własnych obiektów na string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Zapisuje określony podzakres bajtów z określonej tablicy bajtów do strumienia. |
| virtual void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Zapisuje określony podzakres bajtów z określonej tablicy bajtów do strumienia. |
| void [Write](./write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Zapisuje określony podzakres bajtów z określonej tablicy bajtów do strumienia. |
| virtual void [Write](./write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Zapisuje określony podzakres bajtów z określonego zakresu bajtów do strumienia. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](./writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Asynchronicznie zapisuje sekwencję bajtów do bieżącego strumienia, przesuwa bieżącą pozycję w tym strumieniu o liczbę zapisanych bajtów i monitoruje żądania anulowania. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](./writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Asynchronicznie zapisuje sekwencję bajtów do bieżącego strumienia, przesuwa bieżącą pozycję w tym strumieniu o liczbę zapisanych bajtów i monitoruje żądania anulowania. |
| virtual void [WriteByte](./writebyte/)(**uint8_t**) | Zapisuje określoną nieznakowaną 8-bitową wartość całkowitą do strumienia. |
| virtual  [~Object](../../system/object/~object/)() | Usuwa obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Pola

| Pole | Opis |
| --- | --- |
| static [Null](./null/) | Strumień bez leżącego pod spodem magazynu. |

## Definicje typów

| Definicja typu | Opis |
| --- | --- |
| [Ptr](./ptr/) | Alias dla współdzielonego wskaźnika do tej klasy. |

## Zobacz także

* Klasa [IDisposable](../../system/idisposable/)
* Przestrzeń nazw [System::IO](../)
* Biblioteka [Aspose.Slides](../../)