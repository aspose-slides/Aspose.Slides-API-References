---
title: CacheControlHeaderValue
second_title: Aspose.Slides dla C++ - odniesienie API
description: "Reprezentuje wartość nagłówka 'Cache-Control'. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji System::MakeObject(). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonywania i/lub błędy asercji. Zawsze opakowuj tę klasę w wskaźnik System::SmartPtr i używaj tego wskaźnika do przekazywania go jako argumentu do funkcji."
type: docs
weight: 14
url: /pl/system.net.http.headers/cachecontrolheadervalue/
---
## CacheControlHeaderValue klasa


Reprezentuje wartość nagłówka 'Cache-Control'. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonywania i/lub błędy asercji. Zawsze opakowuj tę klasę w wskaźnik [System::SmartPtr](../../system/smartptr/) i używaj tego wskaźnika do przekazywania jej jako argumentu do funkcji.

```cpp
class CacheControlHeaderValue : public System::ICloneable
```

## Metody

| Metoda | Opis |
| --- | --- |
|  [CacheControlHeaderValue](./cachecontrolheadervalue/)() | Tworzy nową instancję. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, gdzie dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, gdzie dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\> [get_Extensions](./get_extensions/)() | Zwraca kolekcję tokenów rozszerzenia pamięci podręcznej. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MaxAge](./get_maxage/)() | Pobiera wartość maksymalnego wieku w sekundach, określającą czas, w którym klient zaakceptuje odpowiedź. |
| **bool** [get_MaxStale](./get_maxstale/)() | Pobiera wartość określającą, czy klient zaakceptuje odpowiedzi wygasłe. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MaxStaleLimit](./get_maxstalelimit/)() | Pobiera wartość w sekundach określającą czas, w którym klient zaakceptuje odpowiedzi wygasłe. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MinFresh](./get_minfresh/)() | Pobiera wartość określającą okres świeżości. |
| **bool** [get_MustRevalidate](./get_mustrevalidate/)() | Pobiera wartość określającą, czy serwer wymaga ponownej walidacji wpisu pamięci podręcznej, gdy stanie się przestarzały. |
| **bool** [get_NoCache](./get_nocache/)() | Pobiera wartość określającą, czy klient zaakceptuje odpowiedź z pamięci podręcznej. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_NoCacheHeaders](./get_nocacheheaders/)() | Pobiera kolekcję nazw pól w dyrektywie 'no-cache' w nagłówku 'Cache-Control'. |
| **bool** [get_NoStore](./get_nostore/)() | Pobiera wartość określającą, czy pamięć podręczna nie może przechowywać żadnej części żądania lub odpowiedzi HTTP. |
| **bool** [get_NoTransform](./get_notransform/)() | Pobiera wartość określającą, czy pamięć podręczna lub proxy nie mogą zmieniać żadnej części ciała encji. |
| **bool** [get_OnlyIfCached](./get_onlyifcached/)() | Pobiera wartość określającą, czy klient musi używać wyłącznie wpisów z pamięci podręcznej. |
| **bool** [get_Private](./get_private/)() | Pobiera wartość określającą, czy komunikat odpowiedzi HTTP lub jego część jest przeznaczona dla jednego użytkownika i nie może być buforowana przez współdzieloną pamięć podręczną. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_PrivateHeaders](./get_privateheaders/)() | Pobiera kolekcję nazw pól w dyrektywie 'private' w nagłówku 'Cache-Control'. |
| **bool** [get_ProxyRevalidate](./get_proxyrevalidate/)() | Pobiera wartość określającą, czy serwer wymaga ponownej walidacji wpisu pamięci podręcznej, gdy stanie się przestarzały dla współdzielonych pamięci podręcznych agentów użytkownika. |
| **bool** [get_Public](./get_public/)() | Pobiera wartość określającą, czy odpowiedź HTTP może być buforowana przez dowolną pamięć podręczną. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_SharedMaxAge](./get_sharedmaxage/)() | Pobiera współdzieloną wartość maksymalnego wieku w sekundach, która nadpisuje dyrektywę 'max-age' w nagłówku 'Cache-Control' lub nagłówek 'Expires' dla współdzielonej pamięci podręcznej. |
| static **int32_t** [GetCacheControlLength](./getcachecontrollength/)([String](../../system/string/), **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>, [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>\&) | Konwertuje przekazany ciąg znaków od określonego indeksu na instancję klasy [CacheControlHeaderValue](./). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Odpowiednik metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Odpowiednik operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje w rzeczywistości nic, jedynie inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje w rzeczywistości nic, jedynie inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\> [Parse](./parse/)([String](../../system/string/)) | Konwertuje przekazany ciąg znaków na instancję klasy [CacheControlHeaderValue](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągu znaków i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
| void [set_MaxAge](./set_maxage/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Ustawia wartość maksymalnego wieku w sekundach, określającą czas, w którym klient zaakceptuje odpowiedź. |
| void [set_MaxStale](./set_maxstale/)(**bool**) | Ustawia wartość określającą, czy klient zaakceptuje odpowiedzi wygasłe. |
| void [set_MaxStaleLimit](./set_maxstalelimit/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Ustawia wartość w sekundach określającą czas, w którym klient zaakceptuje odpowiedzi wygasłe. |
| void [set_MinFresh](./set_minfresh/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Ustawia wartość określającą okres świeżości. |
| void [set_MustRevalidate](./set_mustrevalidate/)(**bool**) | Ustawia wartość określającą, czy serwer wymaga ponownej walidacji wpisu pamięci podręcznej, gdy stanie się przestarzały. |
| void [set_NoCache](./set_nocache/)(**bool**) | Ustawia wartość określającą, czy klient zaakceptuje odpowiedź z pamięci podręcznej. |
| void [set_NoStore](./set_nostore/)(**bool**) | Ustawia wartość określającą, czy pamięć podręczna nie może przechowywać żadnej części żądania lub odpowiedzi HTTP. |
| void [set_NoTransform](./set_notransform/)(**bool**) | Ustawia wartość określającą, czy pamięć podręczna lub proxy nie mogą zmieniać żadnej części ciała encji. |
| void [set_OnlyIfCached](./set_onlyifcached/)(**bool**) | Ustawia wartość określającą, czy klient musi używać wyłącznie wpisów z pamięci podręcznej. |
| void [set_Private](./set_private/)(**bool**) | Ustawia wartość określającą, czy komunikat odpowiedzi HTTP lub jego część jest przeznaczona dla jednego użytkownika i nie może być buforowana przez współdzieloną pamięć podręczną. |
| void [set_ProxyRevalidate](./set_proxyrevalidate/)(**bool**) | Ustawia wartość określającą, czy serwer wymaga ponownej walidacji wpisu pamięci podręcznej, gdy stanie się przestarzały dla współdzielonych pamięci podręcznych agentów użytkownika. |
| void [set_Public](./set_public/)(**bool**) | Ustawia wartość określającą, czy odpowiedź HTTP może być buforowana przez dowolną pamięć podręczną. |
| void [set_SharedMaxAge](./set_sharedmaxage/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Ustawia współdzieloną wartość maksymalnego wieku w sekundach, która nadpisuje dyrektywę 'max-age' w nagłówku 'Cache-Control' lub nagłówek 'Expires' dla współdzielonej pamięci podręcznej. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Odpowiednik metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów do łańcucha znaków. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>\&) | Próbuje skonwertować przekazany ciąg znaków na instancję klasy [CacheControlHeaderValue](./). |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Usuwa obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [ICloneable](../../system/icloneable/)
* Przestrzeń nazw [System::Net::Http::Headers](../)
* Biblioteka [Aspose.Slides](../../)