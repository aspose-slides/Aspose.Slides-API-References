---
title: HttpRequestCachePolicy
second_title: Aspose.Slides dla C++ – dokumentacja API
description: "Polityka pamięci podręcznej HTTP opisująca semantykę buforowania HTTP zgodnie z RFC2616. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji System::MakeObject(). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ może to prowadzić do błędów w czasie wykonywania i/lub naruszeń asercji. Zawsze owiń tę klasę wskaźnikiem System::SmartPtr i używaj tego wskaźnika do przekazywania go jako argumentu do funkcji."
type: docs
weight: 1
url: /pl/system.net.cache/httprequestcachepolicy/
---
## HttpRequestCachePolicy klasa

Polityka pamięci podręcznej HTTP wyrażająca semantykę buforowania HTTP zgodnie z RFC2616. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie wykonywania i/lub naruszenia asercji. Zawsze owiń tę klasę w wskaźnik [System::SmartPtr](../../system/smartptr/) i używaj tego wskaźnika do przekazywania go do funkcji jako argument.

```cpp
class HttpRequestCachePolicy : public System::Net::Cache::RequestCachePolicy
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| [DateTime](../../system/datetime/) [get_CacheSyncDate](./get_cachesyncdate/)() const | Pobiera czas, kiedy zasoby przechowywane w pamięci podręcznej muszą zostać ponownie zweryfikowane. |
| [DateTime](../../system/datetime/) [get_InternalCacheSyncDateUtc](./get_internalcachesyncdateutc/)() const | Pobiera czas w formacie UTC, kiedy zasoby przechowywane w pamięci podręcznej muszą zostać ponownie zweryfikowane. Tylko do użytku wewnętrznego. |
| [HttpRequestCacheLevel](../httprequestcachelevel/) [get_Level](./get_level/)() const | Pobiera określoną wartość HttpRequestCacheLevel. |
| [RequestCacheLevel](../requestcachelevel/) [get_Level](../requestcachepolicy/get_level/)() | Pobiera określoną wartość RequestCacheLevel. |
| [TimeSpan](../../system/timespan/) [get_MaxAge](./get_maxage/)() const | Pobiera maksymalny dopuszczalny wiek zasobu. |
| [TimeSpan](../../system/timespan/) [get_MaxStale](./get_maxstale/)() const | Pobiera maksymalną dopuszczalną wartość przeterminowania zasobu. |
| [TimeSpan](../../system/timespan/) [get_MinFresh](./get_minfresh/)() const | Pobiera minimalny dopuszczalny wiek zasobu. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Odpowiednik metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
|  [HttpRequestCachePolicy](./httprequestcachepolicy/)() | Tworzy nową instancję. |
|  [HttpRequestCachePolicy](./httprequestcachepolicy/)([HttpRequestCacheLevel](../httprequestcachelevel/)) | Tworzy nową instancję. |
|  [HttpRequestCachePolicy](./httprequestcachepolicy/)([HttpCacheAgeControl](../httpcacheagecontrol/), [TimeSpan](../../system/timespan/)) | Tworzy nową instancję. |
|  [HttpRequestCachePolicy](./httprequestcachepolicy/)([HttpCacheAgeControl](../httpcacheagecontrol/), [TimeSpan](../../system/timespan/), [TimeSpan](../../system/timespan/)) | Tworzy nową instancję. |
|  [HttpRequestCachePolicy](./httprequestcachepolicy/)([DateTime](../../system/datetime/)) | Tworzy nową instancję. |
|  [HttpRequestCachePolicy](./httprequestcachepolicy/)([HttpCacheAgeControl](../httpcacheagecontrol/), [TimeSpan](../../system/timespan/), [TimeSpan](../../system/timespan/), [DateTime](../../system/datetime/)) | Tworzy nową instancję. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Odpowiednik operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę C# lock(). Wywołaj bezpośrednio lub użyj obiektu stróża [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. W rzeczywistości nie kopiuje nic, tylko inicjalizuje nowy obiekt i umożliwia kopiowanie konstrukcji podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. W rzeczywistości nie kopiuje nic, tylko inicjalizuje nowy obiekt i umożliwia kopiowanie konstrukcji podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku stringów. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
|  [RequestCachePolicy](../requestcachepolicy/requestcachepolicy/)() | Tworzy nową instancję. |
|  [RequestCachePolicy](../requestcachepolicy/requestcachepolicy/)([RequestCacheLevel](../requestcachelevel/)) | Tworzy nową instancję z określoną wartością RequestCacheLevel. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Inkrementuje współdzielony licznik referencji. Nie należy wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Dekrementuje i zwraca współdzielony licznik referencji. Nie należy wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Odpowiednik metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów na string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu stróża [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Inkrementuje słaby licznik referencji. Nie należy wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Dekrementuje słaby licznik referencji. Nie należy wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [RequestCachePolicy](../requestcachepolicy/)
* Przestrzeń nazw [System::Net::Cache](../)
* Biblioteka [Aspose.Slides](../../)