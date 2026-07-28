---
title: UnmanagedMemoryStream
second_title: Aspose.Slides dla C++ – dokumentacja API
description: "Zapewnia dostęp do niezarządzanej pamięci. Obiekty tej klasy powinny być przydzielane wyłącznie przy użyciu funkcji System::MakeObject(). Nigdy nie twórz instancji tego typu na stosie ani za pomocą operatora new, ponieważ może to spowodować błędy w czasie wykonywania i/lub awarie asercji. Zawsze opakowuj tę klasę we wskaźnik System::SmartPtr i używaj tego wskaźnika do przekazywania go jako argument do funkcji."
type: docs
weight: 456
url: /pl/system.io/unmanagedmemorystream/
---
## UnmanagedMemoryStream klasa


Zapewnia dostęp do niezarządzanej pamięci. Obiekty tej klasy powinny być przydzielane wyłącznie przy użyciu funkcji [System::MakeObject()](../../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani za pomocą operatora new, ponieważ spowoduje to błędy w czasie wykonania i/lub błędy asercji. Zawsze opakowuj tę klasę w wskaźnik [System::SmartPtr](../../system/smartptr/) i używaj tego wskaźnika do przekazywania go jako argument do funkcji.

```cpp
class UnmanagedMemoryStream : public System::IO::Stream
```

## Metody

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Inicjuje asynchroniczną operację odczytu. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Inicjuje asynchroniczną operację zapisu. |
| virtual void [Close](../stream/close/)() | Zamyka strumień. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Kopiuje bajty do określonego strumienia. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | Kopiuje bajty do określonego strumienia, używając określonego rozmiaru bufora. |
| void [Dispose](../stream/dispose/)() override | Zwalnia wszystkie zasoby używane przez bieżący obiekt i zamyka strumień. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Czeka, aż określona asynchroniczna operacja odczytu zostanie zakończona. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Zakańcza asynchroniczną operację zapisu. Czeka, aż określona asynchroniczna operacja zapisu zostanie zakończona. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartości w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwie wartości NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równe żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwie wartości NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równe żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| void [Flush](./flush/)() override | Nie robi nic. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Asynchronicznie czyści wszystkie bufory tego strumienia, powoduje zapisanie wszelkich danych buforowanych do urządzenia bazowego i monitoruje żądania anulowania. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | Asynchronicznie czyści wszystkie bufory tego strumienia, powoduje zapisanie wszelkich danych buforowanych do urządzenia bazowego i monitoruje żądania anulowania. |
| **bool** [get_CanRead](./get_canread/)() const override | Określa, czy strumień jest odczytywalny. |
| **bool** [get_CanSeek](./get_canseek/)() const override | Określa, czy strumień obsługuje pozycjonowanie. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | Zwraca wartość określającą, czy bieżący strumień może wygasnąć. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | Określa, czy strumień jest zapisywalny. |
| virtual **int64_t** [get_Capacity](./get_capacity/)() const | Zwraca bieżącą pojemność podstawowego bufora pamięci. |
| **int64_t** [get_Length](./get_length/)() const override | Zwraca długość strumienia w bajtach. |
| **int64_t** [get_Position](./get_position/)() const override | Zwraca bieżącą pozycję strumienia. |
| **uint8_t** * [get_PositionPointer](./get_positionpointer/)() | NIE ZAIMPLEMENTOWANO. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | Zwraca wartość w milisekundach określającą, jak długo strumień będzie próbował odczytać przed przekroczeniem limitu czasu. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | Zwraca wartość w milisekundach określającą, jak długo strumień będzie próbował zapisać przed przekroczeniem limitu czasu. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Zwraca strukturę licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie niestandardowych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Zwraca rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu ochronnego [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie niestandardowych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie konstruktorów podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie konstruktorów podklas. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Odczytuje określoną liczbę bajtów ze strumienia i zapisuje je do określonej tablicy bajtów. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Odczytuje określoną liczbę bajtów ze strumienia i zapisuje je do określonej tablicy bajtów. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Odczytuje określoną liczbę bajtów ze strumienia i zapisuje je do określonej tablicy bajtów. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Odczytuje określoną liczbę bajtów ze strumienia i zapisuje je do określonego przedziału bajtów. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Asynchronicznie odczytuje sekwencję bajtów z bieżącego strumienia, przesuwa pozycję w strumieniu o liczbę odczytanych bajtów i monitoruje żądania anulowania. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Asynchronicznie odczytuje sekwencję bajtów z bieżącego strumienia, przesuwa pozycję w strumieniu o liczbę odczytanych bajtów i monitoruje żądania anulowania. |
| virtual int [ReadByte](../stream/readbyte/)() | Odczytuje pojedynczy bajt ze strumienia i zwraca 32-bitową wartość całkowitą równą wartości odczytanego bajtu. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje obiekt typu wartości z nullptr poprzez referencję. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o określoną wartość. |
| **int64_t** [Seek](./seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | Ustawia pozycję strumienia reprezentowaną przez bieżący obiekt. |
| void [set_Position](./set_position/)(**int64_t**) override | Ustawia pozycję strumienia. |
| void [set_PositionPointer](./set_positionpointer/)(**uint8_t** *) | NIE ZAIMPLEMENTOWANO. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | Ustawia wartość określającą, czy bieżący strumień może wygasnąć. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | Ustawia wartość w milisekundach określającą, jak długo strumień będzie próbował odczytać przed przekroczeniem limitu czasu. |
| void [SetLength](./setlength/)(**int64_t**) override | NIE ZAIMPLEMENTOWANO. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Zwraca bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję niestandardowych obiektów do string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu ochronnego [LockContext](../../system/lockcontext/). |
|  [UnmanagedMemoryStream](./unmanagedmemorystream/)(**uint8_t** *, **int64_t**) | Tworzy nową instancję [UnmanagedMemoryStream](./). |
|  [UnmanagedMemoryStream](./unmanagedmemorystream/)(**uint8_t** *, **int64_t**, **int64_t**, [FileAccess](../fileaccess/)) | Tworzy nową instancję [UnmanagedMemoryStream](./). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | NIE ZAIMPLEMENTOWANO. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | NIE ZAIMPLEMENTOWANO. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Zapisuje określony podzakres bajtów z określonej tablicy bajtów do strumienia. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Zapisuje określony podzakres bajtów z określonego przedziału bajtów do strumienia. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Asynchronicznie zapisuje sekwencję bajtów do bieżącego strumienia, przesuwa bieżącą pozycję w tym strumieniu o liczbę zapisanych bajtów i monitoruje żądania anulowania. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Asynchronicznie zapisuje sekwencję bajtów do bieżącego strumienia, przesuwa bieżącą pozycję w tym strumieniu o liczbę zapisanych bajtów i monitoruje żądania anulowania. |
| virtual void [WriteByte](../stream/writebyte/)(**uint8_t**) | Zapisuje określoną bez znaku 8-bitową wartość całkowitą do strumienia. |
| virtual  [~Object](../../system/object/~object/)() | Usuwa obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Pola

| Field | Description |
| --- | --- |
| static [Null](../stream/null/) | Strumień bez podstawowego magazynu. |

## Zobacz także

* Klasa [Stream](../stream/)
* Przestrzeń nazw [System::IO](../)
* Biblioteka [Aspose.Slides](../../)