---
title: CookieContainer
second_title: Aspose.Slides dla C++ - dokumentacja API
description: "Zapewnia kontener dla instancji klasy CookieCollection. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji System::MakeObject(). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonywania i/lub awarie asercji. Zawsze opakowuj tę klasę w wskaźnik System::SmartPtr i używaj tego wskaźnika do przekazywania go jako argumentu do funkcji."
type: docs
weight: 40
url: /pl/system.net/cookiecontainer/
---
## CookieContainer klasa

Zapewnia kontener dla instancji klasy CookieCollection. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operator new, ponieważ spowoduje to błędy czasu wykonania i/lub awarie asercji. Zawsze opakowuj tę klasę w wskaźnik [System::SmartPtr](../../system/smartptr/) i używaj tego wskaźnika do przekazywania go jako argumentu do funkcji.

```cpp
class CookieContainer : public System::Object
```

## Metody

| Metoda | Opis |
| --- | --- |
| void [Add](./add/)([System::SharedPtr](../../system/sharedptr/)\<[Cookie](../cookie/)\>) | Dodaje ciasteczko do kolekcji. |
| void [Add](./add/)([System::SharedPtr](../../system/sharedptr/)\<[Cookie](../cookie/)\>, **bool**) | Dodaje ciasteczko do kolekcji. |
| void [Add](./add/)([System::SharedPtr](../../system/sharedptr/)\<[CookieCollection](../cookiecollection/)\>) | Kopiuje ciasteczka z określonej kolekcji do bieżącej. |
| void [Add](./add/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Cookie](../cookie/)\>) | Dodaje ciasteczko dla określonego URI. |
| void [Add](./add/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, [System::SharedPtr](../../system/sharedptr/)\<[CookieCollection](../cookiecollection/)\>) | Kopiuje ciasteczka z określonej kolekcji dla podanego URI do bieżącej kolekcji. |
|  [CookieContainer](./cookiecontainer/)() | Tworzy nową instancję. |
|  [CookieContainer](./cookiecontainer/)(**int32_t**) | Tworzy nową instancję. |
|  [CookieContainer](./cookiecontainer/)(**int32_t**, **int32_t**, **int32_t**) | Tworzy nową instancję. |
| [System::SharedPtr](../../system/sharedptr/)\<[CookieCollection](../cookiecollection/)\> [CookieCutter](./cookiecutter/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, [String](../../system/string/), [String](../../system/string/), **bool**) | Kopiuje ciasteczka z określonego nagłówka HTTP dla podanego URI. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| **int32_t** [get_Capacity](./get_capacity/)() | Pobiera pojemność kolekcji. |
| **int32_t** [get_Count](./get_count/)() | Zwraca liczbę elementów kolekcji. |
| **int32_t** [get_MaxCookieSize](./get_maxcookiesize/)() | Pobiera maksymalny rozmiar ciasteczka. |
| **int32_t** [get_PerDomainCapacity](./get_perdomaincapacity/)() | Pobiera pojemność kolekcji na domenę. |
| [String](../../system/string/) [GetCookieHeader](./getcookieheader/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Zwraca nagłówek HTTP zawierający ciasteczka powiązane z określonym URI. |
| [String](../../system/string/) [GetCookieHeader](./getcookieheader/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, [String](../../system/string/)\&) | Zwraca nagłówek HTTP zawierający ciasteczka powiązane z określonym URI. |
| [System::SharedPtr](../../system/sharedptr/)\<[CookieCollection](../cookiecollection/)\> [GetCookies](./getcookies/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Zwraca kolekcję ciasteczek powiązanych z określonym URI. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Odpowiednik metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[CookieCollection](../cookiecollection/)\> [InternalGetCookies](./internalgetcookies/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Zwraca kolekcję ciasteczek powiązanych z określonym URI. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Odpowiednik operatora C# 'is'. |
| **bool** [IsLocalDomain](./islocaldomain/)([String](../../system/string/)) | Sprawdza, czy podana domena jest localhost. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. W rzeczywistości nic nie kopiuje, jedynie inicjalizuje nowy obiekt i umożliwia kopiowanie konstruktorów podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. W rzeczywistości nic nie kopiuje, jedynie inicjalizuje nowy obiekt i umożliwia kopiowanie konstruktorów podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku łańcucha i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku łańcuchów. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
| void [set_Capacity](./set_capacity/)(**int32_t**) | Ustawia pojemność kolekcji. |
| void [set_MaxCookieSize](./set_maxcookiesize/)(**int32_t**) | Ustawia maksymalny rozmiar ciasteczka. |
| void [set_PerDomainCapacity](./set_perdomaincapacity/)(**int32_t**) | Ustawia pojemność kolekcji na domenę. |
| void [SetCookies](./setcookies/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, [String](../../system/string/)) | Kopiuje ciasteczka z określonego nagłówka do kolekcji i powiązuje je z określonym URI. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach w tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Odpowiednik metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów do łańcucha. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa słaby licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza słaby licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() |  Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Pola

| Pole | Opis |
| --- | --- |
| static [DefaultCookieLengthLimit](./defaultcookielengthlimit/) | Maksymalny rozmiar ciasteczka. |
| static [DefaultCookieLimit](./defaultcookielimit/) | Maksymalna liczba elementów kolekcji. |
| static [DefaultPerDomainCookieLimit](./defaultperdomaincookielimit/) | Maksymalna liczba elementów kolekcji na domenę. |

## Zobacz także

* Klasa [Object](../../system/object/)
* Przestrzeń nazw [System::Net](../)
* Biblioteka [Aspose.Slides](../../)