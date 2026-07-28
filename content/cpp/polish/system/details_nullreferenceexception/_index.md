---
title: Details_NullReferenceException
second_title: Aspose.Slides dla C++ dokumentacja API
description: "NullReferenceException jest rzucany, gdy próbuje się odwołać do referencji null. Nigdy nie twórz ręcznie instancji tej klasy. Użyj klasy NullReferenceException zamiast tego. Nigdy nie otaczaj instancji klasy NullReferenceException w System::SmartPtr."
type: docs
weight: 599
url: /pl/system/details_nullreferenceexception/
---
## Details_NullReferenceException klasa

NullReferenceException jest rzucany, gdy próbuje się odwołać do referencji null. Nigdy nie twórz ręcznie instancji tej klasy. Użyj klasy NullReferenceException zamiast tego. Nigdy nie otaczaj instancji klasy NullReferenceException w [System::SmartPtr](../smartptr/).

```cpp
class Details_NullReferenceException : public System::Details_SystemException
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | Zwraca słownik z niestandardowymi danymi wyjątku. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | Zwraca 32-bitową wartość całkowitą, będącą kodem HRESULT skojarzonym z wyjątkiem reprezentowanym przez bieżący obiekt. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | Zwraca referencję do obiektu reprezentującego wewnętrzny wyjątek. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | Zwraca ciąg znaków zawierający opis błędu. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | Zwraca ciąg znaków zawierający ślad stosu. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | Zwraca kopię obiektu Exception reprezentującego najgłębiej zagnieżdżony wyjątek. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Uzyskuje strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../object/gethashcode/). Umożliwia haszowanie niestandardowych obiektów. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | Uzyskuje rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../object/gettype/). |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | Implementuje blokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażniczego [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../object/memberwiseclone/). Umożliwia klonowanie niestandardowych typów. |
|  [Object](../object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../object/object/)([Object](../object/) const\&) | Konstruktor kopiujący. Nie kopiuje niczego, naprawdę, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operator przypisania. Nie kopiuje niczego, naprawdę, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Porównuje obiekty według referencji. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty według referencji. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../object/referenceequals/) dla przypadku łańcucha znaków i nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specjalizacja [Object::ReferenceEquals](../object/referenceequals/) dla przypadku łańcuchów znaków. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | Ustawia HRESULT, zakodowaną wartość liczbową przypisaną do konkretnego wyjątku. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../object/sharedcount/)() const | Uzyskuje bieżącą wartość licznika współdzielonych referencji. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | Zwraca łańcuch znaków będący reprezentacją bieżącego obiektu. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażniczego [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual const char * [what](../details_exception/what/)() const | Implementuje metodę [what()](../details_exception/what/), która jest wywoływana przez klasę [ExceptionWrapper](../exceptionwrapper/). Pomimo faktu, że ta klasa nie dziedziczy po std::exception, klasy pochodne mogą używać chronionych/prywatnych członków do implementacji ich logiki. Przeniesienie implementacji tej metody do [ExceptionWrapper](../exceptionwrapper/) może zepsuć tę logikę. |
| virtual  [~Object](../object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [Details_SystemException](../details_systemexception/)
* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)