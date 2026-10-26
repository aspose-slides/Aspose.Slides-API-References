---
title: TimeZone
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: "Reprezentuje strefę czasową. Obiekty tej klasy powinny być przydzielane wyłącznie przy użyciu funkcji System::MakeObject(). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ może to spowodować błędy czasu wykonania i/lub naruszenia asercji. Zawsze otaczaj tę klasę wskaźnikiem System::SmartPtr i używaj tego wskaźnika do przekazywania jej jako argumentu do funkcji."
type: docs
weight: 1327
url: /pl/system/timezone/
---
## Klasa TimeZone

Represents a time zone. Objects of this class should only be allocated using [System::MakeObject()](../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class TimeZone : public System::Object
```

## Metody

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za rowne, mimo ze zgodnie z IEC 60559:1989 NaN nie jest rowny zadnej wartosci, w tym NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za rowne, mimo ze zgodnie z IEC 60559:1989 NaN nie jest rowny zadnej wartosci, w tym NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do uzytkowania wewnetrznego. |
| static [TimeZonePtr](../timezoneptr/) [get_CurrentTimeZone](./get_currenttimezone/)() | Zwraca nowa instancje klasy [TimeZone](./), ktora reprezentuje biezaca strefe czasowa. |
| virtual [String](../string/) [get_DaylightName](./get_daylightname/)() const | Zwraca nazwe czasu letniego strefy czasowej reprezentowanej przez biezacy obiekt. |
| virtual [String](../string/) [get_StandardName](./get_standardname/)() const | Zwraca nazwe czasu standardowego strefy czasowej reprezentowanej przez biezacy obiekt. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Pobiera strukture danych licznika referencji powiazana z obiektem. |
| virtual [Globalization::DaylightTimePtr](../../system.globalization/daylighttimeptr/) [GetDaylightChanges](./getdaylightchanges/)(**int32_t**) | Zwraca okres czasu letniego dla konkretnego roku. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../object/gethashcode/). Umożliwia haszowanie obiektów niestandardowych. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywolania C# [System.Object.GetType()](../object/gettype/). |
| virtual [TimeSpan](../timespan/) [GetUtcOffset](./getutcoffset/)([DateTime](../datetime/)) | Zwraca przesuniecie UTC dla okreslonego czasu lokalnego. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Sprawdza, czy obiekt jest instancja typu opisanego przez targetType. Analog operatora C# 'is'. |
| virtual **bool** [IsDaylightSavingTime](./isdaylightsavingtime/)([DateTime](../datetime/)) | Okresla, czy wartosc daty i czasu reprezentowana przez okreslony obiekt [DateTime](../datetime/) miesci sie w zakresie czasu letniego dla strefy czasowej reprezentowanej przez biezacy obiekt [TimeZone](./). |
| void [Lock](../object/lock/)() | Implementuje blokade instrukcji C# lock(). Wywolaj bezposrednio lub uzyj obiektu straznika [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../object/memberwiseclone/). Umożliwia klonowanie typów niestandardowych. |
|  [Object](../object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnetrzne struktury danych. |
|  [Object](../object/object/)([Object](../object/) const\&) | Konstruktor kopiujacy. W praktyce nic nie kopiuje, jedynie inicjalizuje nowy obiekt i umozliwia kopiowanie podklas. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operator przypisania. W praktyce nic nie kopiuje, jedynie inicjalizuje nowy obiekt i umozliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Porównuje obiekty przez referencje. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencje. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartosciowego z nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specjalizacja [Object::ReferenceEquals](../object/referenceequals/) dla przypadku stringow. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Zmniejsza wspoldzielony licznik referencji o podana wartosc. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako slaby wskaznik (zamiast wspoldzielonego). Umozliwia przełączanie wskaznikow w kontenerach na tryb slaby. |
| int [SharedCount](../object/sharedcount/)() const | Pobiera biezaca wartosc wspoldzielonego licznika referencji. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Zwieksza wspoldzielony licznik referencji. Nie powinno sie wywolywac bezposrednio; zamiast tego uzyj inteligentnych wskaznikow lub ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Zmniejsza i zwraca wspoldzielony licznik referencji. Nie powinno sie wywolywac bezposrednio; zamiast tego uzyj inteligentnych wskaznikow lub ThisProtector. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Analog metody C# [Object.ToString()](../object/tostring/). Umozliwia konwertowanie obiektow niestandardowych na lancuch znakow. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementuje konstrukcje C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywolaj bezposrednio lub uzyj obiektu straznika [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Zwieksza slaby licznik referencji. Nie powinno sie wywolywac bezposrednio; zamiast tego uzyj inteligentnych wskaznikow lub ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Zmniejsza slaby licznik referencji. Nie powinno sie wywolywac bezposrednio; zamiast tego uzyj inteligentnych wskaznikow lub ThisProtector. |
| virtual  [~Object](../object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnetrzne struktury danych. |

## Zobacz też

* Klasa [Object](../object/)
* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)