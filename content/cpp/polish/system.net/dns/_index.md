---
title: Dns
second_title: Referencja API Aspose.Slides dla C++
description: Udostępnia metody do pracy z DNS.
type: docs
weight: 105
url: /pl/system.net/dns/
---
## Dns klasa


Udostępnia metody do pracy z DNS.

```cpp
class Dns : public System::Object
```

## Metody

| Metoda | Opis |
| --- | --- |
| static [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetHostAddresses](./begingethostaddresses/)([String](../../system/string/), [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Inicjuje operację asynchroniczną tworzącą nową instancję IPHostEntry-class przy użyciu określonego ciągu znaków zawierającego nazwę hosta lub adres IP. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetHostByName](./begingethostbyname/)([String](../../system/string/), [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Inicjuje operację asynchroniczną tworzącą nową instancję IPHostEntry-class przy użyciu określonej nazwy hosta. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetHostEntry](./begingethostentry/)([String](../../system/string/), [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Inicjuje operację asynchroniczną tworzącą nową instancję IPHostEntry-class przy użyciu określonego ciągu znaków zawierającego nazwę hosta lub adres IP. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetHostEntry](./begingethostentry/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../ipaddress/)\>, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Inicjuje operację asynchroniczną tworzącą nową instancję IPHostEntry-class przy użyciu określonego adresu IP. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginResolve](./beginresolve/)([String](../../system/string/), [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Inicjuje operację asynchroniczną tworzącą nową instancję IPHostEntry-class przy użyciu określonej nazwy hosta. |
|  [Dns](./dns/)() | Usunięty domyślny konstruktor. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../ipaddress/)\>\> [EndGetHostAddresses](./endgethostaddresses/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | Czeka, aż określona operacja asynchroniczna tworząca nową instancję IPHostEntry-class zakończy się. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPHostEntry](../iphostentry/)\> [EndGetHostByName](./endgethostbyname/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | Czeka, aż określona operacja asynchroniczna tworząca nową instancję IPHostEntry-class zakończy się. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPHostEntry](../iphostentry/)\> [EndGetHostEntry](./endgethostentry/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | Czeka, aż określona operacja asynchroniczna tworząca nową instancję IPHostEntry-class zakończy się. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPHostEntry](../iphostentry/)\> [EndResolve](./endresolve/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | Czeka, aż określona operacja asynchroniczna tworząca nową instancję IPHostEntry-class zakończy się. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../ipaddress/)\>\> [GetHostAddresses](./gethostaddresses/)([String](../../system/string/)) | Zwraca kolekcję adresów IP określonej nazwy hosta lub adresu IP. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPHostEntry](../iphostentry/)\> [GetHostByAddress](./gethostbyaddress/)([String](../../system/string/)) | Tworzy nową instancję IPHostEntry-class przy użyciu określonej reprezentacji ciągu znaków adresu IP. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPHostEntry](../iphostentry/)\> [GetHostByAddress](./gethostbyaddress/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../ipaddress/)\>) | Tworzy nową instancję IPHostEntry-class przy użyciu określonego adresu IP. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPHostEntry](../iphostentry/)\> [GetHostByName](./gethostbyname/)([String](../../system/string/)) | Tworzy nową instancję IPHostEntry-class przy użyciu określonej nazwy hosta. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPHostEntry](../iphostentry/)\> [GetHostEntry](./gethostentry/)([String](../../system/string/)) | Tworzy nową instancję IPHostEntry-class przy użyciu określonego ciągu znaków zawierającego nazwę hosta lub adres IP. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPHostEntry](../iphostentry/)\> [GetHostEntry](./gethostentry/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../ipaddress/)\>) | Tworzy nową instancję IPHostEntry-class przy użyciu określonego adresu IP. |
| static [String](../../system/string/) [GetHostName](./gethostname/)() | Zwraca nazwę hosta lokalnego komputera. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt reprezentuje instancję typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku łańcucha znaków i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku łańcuchów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o określoną wartość. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPHostEntry](../iphostentry/)\> [Resolve](./resolve/)([String](../../system/string/)) | Tworzy nową instancję IPHostEntry-class przy użyciu określonej nazwy hosta. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów na string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |
## Zobacz także

* Klasa [Object](../../system/object/)
* Przestrzeń nazw [System::Net](../)
* Biblioteka [Aspose.Slides](../../)