---
title: ServicePoint
second_title: Aspose.Slides dla C++ – referencja API
description: "Zapewnia zarządzanie połączeniami HTTP. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji System::MakeObject(). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ może to spowodować błędy czasu wykonywania i/lub błędy asercji. Zawsze opakowuj tę klasę w wskaźnik System::SmartPtr i używaj tego wskaźnika jako argumentu w funkcjach."
type: docs
weight: 417
url: /pl/system.net/servicepoint/
---
## ServicePoint klasa

Zapewnia zarządzanie połączeniami HTTP. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonania i/lub błędy asercji. Zawsze opakowuj tę klasę w wskaźnik [System::SmartPtr](../../system/smartptr/) i używaj tego wskaźnika, aby przekazać ją do funkcji jako argument.

```cpp
class ServicePoint : public System::Object
```

## Metody

| Metoda | Opis |
| --- | --- |
| **bool** [CloseConnectionGroup](./closeconnectiongroup/)([String](../../system/string/)) | Zamyka i usuwa połączenia, które należą do określonej grupy połączeń. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartości w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_Address](./get_address/)() | Zwraca URI serwera, z którym łączy się bieżąca instancja. |
| [BindIPEndPoint](../bindipendpoint/) [get_BindIPEndPointDelegate](./get_bindipendpointdelegate/)() | Pobiera delegata używanego do powiązania lokalnego [IPEndPoint](../ipendpoint/) z bieżącą instancją. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_Certificate](./get_certificate/)() | Zwraca certyfikat używany przez bieżącą instancję. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_ClientCertificate](./get_clientcertificate/)() | Zwraca ostatni certyfikat klienta. |
| **int32_t** [get_ConnectionLeaseTimeout](./get_connectionleasetimeout/)() | Pobiera limit czasu w milisekundach, po którym aktywne [ServicePoint](./) zostaną zamknięte. |
| **int32_t** [get_ConnectionLimit](./get_connectionlimit/)() | Pobiera maksymalną liczbę połączeń dozwoloną dla bieżącej instancji. |
| [String](../../system/string/) [get_ConnectionName](./get_connectionname/)() | Zwraca nazwę połączenia. |
| **int32_t** [get_CurrentConnections](./get_currentconnections/)() | Zwraca liczbę otwartych połączeń. |
| **bool** [get_Expect100Continue](./get_expect100continue/)() | Pobiera wartość określającą, czy zachowanie 100-Continue jest używane. |
| [DateTime](../../system/datetime/) [get_IdleSince](./get_idlesince/)() | Zwraca datę i godzinę ostatniego połączenia z hostem. |
| **int32_t** [get_MaxIdleTime](./get_maxidletime/)() | Pobiera okres czasu w milisekundach, po którym bezczynne połączenie zostanie zamknięte. |
| virtual [Version](../../system/version/) [get_ProtocolVersion](./get_protocolversion/)() | Zwraca wersję HTTP. |
| **int32_t** [get_ReceiveBufferSize](./get_receivebuffersize/)() | Pobiera rozmiar bufora odbiorczego. |
| **bool** [get_SupportsPipelining](./get_supportspipelining/)() | Zwraca wartość określającą, czy bieżąca instancja obsługuje połączenia pipeline. |
| **bool** [get_UseNagleAlgorithm](./get_usenaglealgorithm/)() | Pobiera wartość określającą, czy algorytm Nagle jest używany przez połączenia zarządzane przez bieżącą instancję. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogiczna metoda do C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analogiczna metoda do wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analogiczne do operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie w instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażniczego [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogiczna metoda do C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
| [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez odniesienie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez odniesienie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartości z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągu znaków i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza wspólny licznik referencji o podaną wartość. |
| void [set_BindIPEndPointDelegate](./set_bindipendpointdelegate/)([BindIPEndPoint](../bindipendpoint/)) | Ustawia delegata używanego do powiązania lokalnego [IPEndPoint](../ipendpoint/) z bieżącą instancją. |
| void [set_ConnectionLeaseTimeout](./set_connectionleasetimeout/)(**int32_t**) | Ustawia limit czasu w milisekundach, po którym aktywne [ServicePoint](./) zostaną zamknięte. |
| void [set_ConnectionLimit](./set_connectionlimit/)(**int32_t**) | Ustawia maksymalną liczbę połączeń dozwoloną dla bieżącej instancji. |
| void [set_Expect100Continue](./set_expect100continue/)(**bool**) | Ustawia wartość określającą, czy zachowanie 100-Continue jest używane. |
| void [set_MaxIdleTime](./set_maxidletime/)(**int32_t**) | Ustawia okres czasu w milisekundach, po którym bezczynne połączenie zostanie zamknięte. |
| void [set_ReceiveBufferSize](./set_receivebuffersize/)(**int32_t**) | Ustawia rozmiar bufora odbiorczego. |
| void [set_UseNagleAlgorithm](./set_usenaglealgorithm/)(**bool**) | Ustawia wartość określającą, czy algorytm Nagle jest używany przez połączenia zarządzane przez bieżącą instancję. |
| void [SetTcpKeepAlive](./settcpkeepalive/)(**bool**, **int32_t**, **int32_t**) | Ustawia wartość określającą, czy opcja 'Keep-Alive' jest włączona. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość wspólnego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa wspólny licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca wspólny licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogiczna metoda do C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów na string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie w instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażniczego [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa słaby licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza słaby licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [Object](../../system/object/)
* Przestrzeń nazw [System::Net](../)
* Biblioteka [Aspose.Slides](../../)