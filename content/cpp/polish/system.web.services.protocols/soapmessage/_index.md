---
title: SoapMessage
second_title: Aspose.Slides dla C++ – odniesienie do API
description: "Reprezentuje wiadomość SOAP. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji System::MakeObject(). Nigdy nie twórz instancji tego typu na stosie ani nie używaj operatora new, ponieważ spowoduje to błędy w czasie wykonania i/lub awarie asercji. Zawsze otaczaj tę klasę wskaźnikiem System::SmartPtr i używaj tego wskaźnika do przekazywania jej jako argumentu do funkcji."
type: docs
weight: 131
url: /pl/system.web.services.protocols/soapmessage/
---
## SoapMessage klasa

Reprezentuje wiadomość SOAP. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani nie używaj operatora new, ponieważ spowoduje to błędy w czasie wykonania i/lub awarie asercji. Zawsze otaczaj tę klasę wskaźnikiem [System::SmartPtr](../../system/smartptr/) i używaj tego wskaźnika do przekazywania jej jako argumentu do funkcji.

```cpp
class SoapMessage : public System::Object
```

## Metody

| Metoda | Opis |
| --- | --- |
| void [CollectHeaders](./collectheaders/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<SoapHeaderMapping\>\>, [SoapHeaderDirection](../soapheaderdirection/)) | Ustawia wewnętrzną kolekcję nagłówków SOAP. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że według IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że według IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| [System::SharedPtr](../../system/sharedptr/)\<SoapHeaderMapping\> [FindHeader](./findheader/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<SoapHeaderMapping\>\>, const [TypeInfo](../../system/typeinfo/)\&) | Znajduje mapowanie nagłówka według określonego typu nagłówka. |
| virtual [String](../../system/string/) [get_Action](./get_action/)() | Zwraca wartość atrybutu 'SOAPAction'. |
| [String](../../system/string/) [get_ContentEncoding](./get_contentencoding/)() | Pobiera wartość nagłówka 'Content-Encoding'. |
| [String](../../system/string/) [get_ContentType](./get_contenttype/)() | Pobiera wartość nagłówka 'Content-Type'. |
| [SoapException](../soapexception/) [get_Exception](./get_exception/)() | Pobiera wyjątek rzucany przez metodę serwisową XML [Web](../../system.web/). |
| [System::SharedPtr](../../system/sharedptr/)\<[SoapHeaderCollection](../soapheadercollection/)\> [get_Headers](./get_headers/)() | Zwraca kolekcję nagłówków SOAP. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\> [get_InParameters](./get_inparameters/)() | Pobiera parametry przekazywane do metody serwisowej XML [Web](../../system.web/). |
| **bool** [get_IsSoap12](./get_issoap12/)() | Zwraca wartość wskazującą, czy używana jest wersja SOAP 1.2. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\> [get_OutParameters](./get_outparameters/)() | Pobiera parametry wyjściowe przekazywane do metody serwisowej XML [Web](../../system.web/). |
| virtual [SoapProtocolVersion](../soapprotocolversion/) [get_SoapVersion](./get_soapversion/)() | Zwraca wersję SOAP używaną. |
| [SoapMessageStage](../soapmessagestage/) [get_Stage](./get_stage/)() | Pobiera etap przetwarzania wiadomości SOAP. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\> [get_Stream](./get_stream/)() | Pobiera strumień zawierający dane wiadomości SOAP. |
| virtual [String](../../system/string/) [get_Url](./get_url/)() | Zwraca URL serwisu XML [Web](../../system.web/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetInParameterValue](./getinparametervalue/)(**int32_t**) | Pobiera wartość parametru wejściowego pod podanym indeksem. |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetOutParameterValue](./getoutparametervalue/)(**int32_t**) | Pobiera wartość parametru wyjściowego pod podanym indeksem. |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetReturnValue](./getreturnvalue/)() | Pobiera wartość zwracaną przez metodę serwisową XML [Web](../../system.web/). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę statementa C# lock(). Wywołaj bezpośrednio lub użyj obiektu wartownika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku stringów. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| void [set_ContentEncoding](./set_contentencoding/)([String](../../system/string/)) | Ustawia wartość nagłówka 'Content-Encoding'. |
| void [set_ContentType](./set_contenttype/)([String](../../system/string/)) | Ustawia wartość nagłówka 'Content-Type'. |
| void [set_InParameters](./set_inparameters/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>) | Ustawia parametry przekazywane do metody serwisowej XML [Web](../../system.web/). |
| void [set_InternalStream](./set_internalstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Ustawia strumień zawierający dane wiadomości SOAP. |
| void [set_OutParameters](./set_outparameters/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>) | Ustawia parametry wyjściowe przekazywane do metody serwisowej XML [Web](../../system.web/). |
| void [SetException](./setexception/)([SoapException](../soapexception/)) | Ustawia wyjątek rzucany przez metodę serwisową XML [Web](../../system.web/). |
| void [SetHeaders](./setheaders/)([System::SharedPtr](../../system/sharedptr/)\<[SoapHeaderCollection](../soapheadercollection/)\>) | Ustawia kolekcję nagłówków SOAP. |
| void [SetStage](./setstage/)([SoapMessageStage](../soapmessagestage/)) | Ustawia etap przetwarzania wiadomości SOAP. |
| void [SetStream](./setstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Ustawia strumień zawierający dane wiadomości SOAP. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu na słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
|  [SoapMessage](./soapmessage/)() | Tworzy nową instancję. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwertowanie własnych obiektów na ciąg znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie statementa C# lock(). Wywołaj bezpośrednio lub użyj obiektu wartownika [LockContext](../../system/lockcontext/). |
| void [UpdateHeaderValues](./updateheadervalues/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<SoapHeaderMapping\>\>) | Aktualizuje wewnętrzną kolekcję nagłówków SOAP. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwolnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [Object](../../system/object/)
* Przestrzeń nazw [System::Web::Services::Protocols](../)
* Biblioteka [Aspose.Slides](../../)