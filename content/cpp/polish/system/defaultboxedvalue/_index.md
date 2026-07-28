---
title: DefaultBoxedValue
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Implementacja klasy BoxedValue. Umożliwia zadeklarowanie specjalizacji BoxingValue bez powielania wspólnego kodu. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji System::MakeObject() . Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonania i/lub błędy asercji. Zawsze opakowuj tę klasę w wskaźnik System::SmartPtr i używaj tego wskaźnika do przekazywania go do funkcji jako argument."
type: docs
weight: 274
url: /pl/system/defaultboxedvalue/
---
## DefaultBoxedValue klasa


[BoxedValue](../boxedvalue/) implementacja klasy. Pozwala na zadeklarowanie specjalizacji BoxingValue bez powielania wspólnego kodu. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu działania i/lub błędy asercji. Zawsze opakowuj tę klasę w wskaźnik [System::SmartPtr](../smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argumentu.

```cpp
template<class T>class DefaultBoxedValue : public System::Object
```

## Metody

| Metoda | Opis |
| --- | --- |
|  [DefaultBoxedValue](./defaultboxedvalue/)(const T\&) | Tworzy nową instancję klasy [DefaultBoxedValue](./), która reprezentuje określoną wartość. |
| **bool** [Equals](./equals/)([ptr](../object/ptr/)) override | Określa równość zapakowanych wartości reprezentowanych przez bieżący i określony obiekt. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| int [GetHashCode](./gethashcode/)() const override | Zwraca kod skrótu dla bieżącego obiektu. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | Pobiera rzeczywisty typ obiektu. |
| **bool** [is](./is/)() const | Określa, czy typ zapakowanej wartości reprezentowanej przez bieżący obiekt jest **V**. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Sprawdza, czy obiekt reprezentuje instancję typu opisanego przez targetType. Analog operatora 'is' w C#. |
| void [Lock](../object/lock/)() | Implementuje blokowanie instrukcji lock() z C#. Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analog metody [Object.MemberwiseClone()](../object/memberwiseclone/) z C#. Umożliwia klonowanie typów niestandardowych. |
|  [Object](../object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../object/object/)([Object](../object/) const\&) | Konstruktor kopiujący. W rzeczywistości nie kopiuje nic, tylko inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operator przypisania. W rzeczywistości nie kopiuje nic, tylko inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specjalizacja [Object::ReferenceEquals](../object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| [String](../string/) [ToString](./tostring/)() const override | Zwraca reprezentację tekstową zapakowanej wartości. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../object/)). |
| const T\& [unbox](./unbox/)() const | Odpakowuje zapakowaną wartość. |
| void [Unlock](../object/unlock/)() | Implementuje odblokowywanie instrukcji lock() z C#. Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Zwiększa słaby licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Zmniejsza słaby licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../object/~object/)() | Usuwa obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |
## Zobacz także

* Klasa [Object](../object/)
* Przestrzeń nazw [System](../)
* Library [Aspose.Slides](../../)