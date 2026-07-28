---
title: Details_DivideByZeroException
second_title: Aspose.Slides for C++ Dokumentacja API
description: "DivideByZeroException jest rzucany, gdy w operacji arytmetycznej próbuje się dzielić przez 0. Nigdy nie twórz ręcznie instancji tej klasy. Użyj klasy DivideByZeroException. Nigdy nie osadzaj instancji klasy DivideByZeroException w System::SmartPtr."
type: docs
weight: 404
url: /pl/system/details_dividebyzeroexception/
---
## Details_DivideByZeroException klasa

DivideByZeroException jest rzucany, gdy w operacji arytmetycznej próbuje się podzielić przez 0. Nigdy nie twórz ręcznie instancji tej klasy. Użyj klasy DivideByZeroException. Nigdy nie osadzaj instancji klasy DivideByZeroException w [System::SmartPtr](../smartptr/).

```cpp
class Details_DivideByZeroException : public System::Details_ArithmeticException
```

## Metody

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że według IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że według IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do celów wewnętrznych. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | Zwraca słownik z danymi niestandardowego wyjątku. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | Zwraca 32-bitową wartość całkowitą będącą kodem HRESULT powiązanym z wyjątkiem reprezentowanym przez bieżący obiekt. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | Zwraca referencję do obiektu reprezentującego wewnętrzny wyjątek. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | Zwraca ciąg znaków zawierający opis błędu. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | Zwraca ciąg znaków zawierający ślad stosu. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | Zwraca kopię obiektu Exception reprezentującego najgłębszy wewnętrzny wyjątek. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Odpowiednik metody C# [Object.GetHashCode()](../object/gethashcode/). Umożliwia haszowanie niestandardowych obiektów. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | Pobiera rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](../object/gettype/). |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | Implementuje zachowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../object/memberwiseclone/). Umożliwia klonowanie niestandardowych typów. |
|  [Object](../object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../object/object/)([Object](../object/) const\&) | Konstruktor kopiujący. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operator przypisania. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje obiekt typu wartościowego ze wskaźnikiem nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specjalizacja [Object::ReferenceEquals](../object/referenceequals/) dla przypadku stringów. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | Ustawia HRESULT, zakodowaną wartość liczbową przypisaną konkretnemu wyjątkowi. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słabe odniesienie (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie należy wywoływać bezpośrednio; używaj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie należy wywoływać bezpośrednio; używaj inteligentnych wskaźników lub ThisProtector. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | Zwraca reprezentację łańcuchową bieżącego obiektu. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | Implementuje zwolnienie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie należy wywoływać bezpośrednio; używaj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie należy wywoływać bezpośrednio; używaj inteligentnych wskaźników lub ThisProtector. |
| virtual const char * [what](../details_exception/what/)() const | Implementuje metodę [what()](../details_exception/what/), którą wywołuje klasa [ExceptionWrapper](../exceptionwrapper/). Mimo że klasa ta nie dziedziczy po std::exception, klasy pochodne mogą używać chronionych/prywatnych członków do realizacji logiki. Przeniesienie implementacji tej metody do [ExceptionWrapper](../exceptionwrapper/) może zepsuć tę logikę. |
| virtual  [~Object](../object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Uwagi

OutOfMemoryException jest rzucany, gdy aplikacja nie ma dostępnej pamięci. Nigdy nie twórz ręcznie instancji tej klasy. Użyj klasy OutOfMemoryException. Nigdy nie osadzaj instancji klasy OutOfMemoryException w [System::SmartPtr](../smartptr/).

## Zobacz także

* Klasa [Details_ArithmeticException](../details_arithmeticexception/)
* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)