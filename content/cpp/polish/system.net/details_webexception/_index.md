---
title: Details_WebException
second_title: Aspose.Slides dla C++ - Referencja API
description: "Reprezentuje wyjątek, który jest zgłaszany przez WebRequest, gdy wystąpi błąd. Nigdy nie twórz ręcznie instancji tej klasy. Użyj klasy WebException zamiast tego. Nigdy nie owijaj instancji klasy WebException w System::SmartPtr."
type: docs
weight: 92
url: /pl/system.net/details_webexception/
---
## Details_WebException klasa

Reprezentuje wyjątek, który jest zgłaszany przez [WebRequest](../webrequest/) gdy wystąpi błąd. Nigdy nie twórz ręcznie instancji tej klasy. Użyj klasy WebException zamiast tego. Nigdy nie owijaj instancji klasy WebException w [System::SmartPtr](../../system/smartptr/).

```cpp
class Details_WebException : public System::Details_InvalidOperationException
```

## Metody

| Metoda | Opis |
| --- | --- |
| static [Exception](../../system/exception/) [CreateCompatibleException](./createcompatibleexception/)([Exception](../../system/exception/)) | Nie jest zaimplementowane. |
|  [Details_WebException](./details_webexception/)() | Tworzy nową instancję. |
|  [Details_WebException](./details_webexception/)([String](../../system/string/)) | Tworzy nową instancję. |
|  [Details_WebException](./details_webexception/)([String](../../system/string/), [Exception](../../system/exception/)) | Tworzy nową instancję. |
|  [Details_WebException](./details_webexception/)([String](../../system/string/), [WebExceptionStatus](../webexceptionstatus/)) | Tworzy nową instancję. |
|  [Details_WebException](./details_webexception/)([String](../../system/string/), [Exception](../../system/exception/), [WebExceptionStatus](../webexceptionstatus/), [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\>) | Tworzy nową instancję. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\> [get_Data](../../system/details_exception/get_data/)() | Zwraca słownik z danymi niestandardowego wyjątku. |
| **int32_t** [get_HResult](../../system/details_exception/get_hresult/)() const | Zwraca 32-bitową wartość całkowitą, będącą kodem HRESULT powiązanym z wyjątkiem reprezentowanym przez bieżący obiekt. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [get_InnerException](../../system/details_exception/get_innerexception/)() const | Zwraca referencję do obiektu reprezentującego wewnętrzny wyjątek. |
| virtual [String](../../system/string/) [get_Message](../../system/details_exception/get_message/)() const | Zwraca łańcuch zawierający opis błędu. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [get_Response](./get_response/)() | Zwraca odpowiedź sieciową, z którą powiązany jest bieżący wyjątek. |
| virtual [String](../../system/string/) [get_StackTrace](../../system/details_exception/get_stacktrace/)() const | Zwraca łańcuch zawierający ślad stosu. |
| [WebExceptionStatus](../webexceptionstatus/) [get_Status](./get_status/)() | Zwraca kod statusu. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [GetBaseException](../../system/details_exception/getbaseexception/)() const | Zwraca kopię obiektu Exception reprezentującego najgłębiej zagnieżdżony wyjątek. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogia do metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie niestandardowych obiektów. |
| const [System::TypeInfo](../../system/typeinfo/)\& [GetType](../../system/details_invalidoperationexception/gettype/)() const override | Pobiera rzeczywisty typ obiektu. Analogia do wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| **bool** [Is](../../system/details_invalidoperationexception/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const override |  |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu nadzorczego [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogia do metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie niestandardowych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. W rzeczywistości nic nie kopiuje, jedynie inicjalizuje nowy obiekt i umożliwia kopiowanie przy konstruowaniu podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. W rzeczywistości nic nie kopiuje, jedynie inicjalizuje nowy obiekt i umożliwia kopiowanie przy konstruowaniu podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| void [set_HResult](../../system/details_exception/set_hresult/)(**int32_t**) | Ustawia HRESULT, zakodowaną wartość numeryczną przypisaną do konkretnego wyjątku. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| [String](../../system/string/) [ToString](../../system/details_exception/tostring/)() const override | Zwraca reprezentację łańcuchową bieżącego obiektu. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/details_invalidoperationexception/type/)() |  |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowywanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu nadzorczego [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual const char * [what](../../system/details_exception/what/)() const | Implementuje metodę [what()](../../system/details_exception/what/), wywoływaną przez klasę [ExceptionWrapper](../../system/exceptionwrapper/). Pomimo że ta klasa nie dziedziczy po std::exception, klasy pochodne mogą używać chronionych/prywatnych członków do implementacji swojej logiki. Przeniesienie implementacji tej metody do [ExceptionWrapper](../../system/exceptionwrapper/) może zepsuć tę logikę. |
| virtual  [~Details_WebException](./~details_webexception/)() | Niszczy bieżącą instancję. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [Details_InvalidOperationException](../../system/details_invalidoperationexception/)
* Przestrzeń nazw [System::Net](../)
* Biblioteka [Aspose.Slides](../../)