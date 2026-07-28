---
title: DynamicWeakPtr
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Klasa inteligentnego wskaźnika, która śledzi tryby wskaźników argumentów szablonu przechowywanego obiektu i aktualizuje je po każdym przypisaniu. Ten typ jest wskaźnikiem służącym do zarządzania usuwaniem innego obiektu. Powinna być alokowana na stosie i przekazywana do funkcji zarówno przez wartość, jak i przez stałą referencję.
type: docs
weight: 781
url: /pl/system/dynamicweakptr/
---
## DynamicWeakPtr klasa


Klasa inteligentnego wskaźnika, która śledzi tryby wskaźników argumentów szablonu przechowywanego obiektu i aktualizuje je po każdym przypisaniu. Ten typ jest wskaźnikiem służącym do zarządzania usuwaniem innego obiektu. Powinna być alokowana na stosie i przekazywana do funkcji zarówno przez wartość, jak i przez stałą referencję.

```cpp
template<typename T,SmartPtrMode,unsigned int ...>class DynamicWeakPtr : public System::SmartPtr<T>
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Pointee | typ. |
| trunkMode | Tryb samego inteligentnego wskaźnika, współdzielony lub słaby. |
| weakLeafs | Indeksy argumentów szablonu przechowywanego typu, które powinny być ustawione w trybie słabego wskaźnika. |
## Metody

| Metoda | Opis |
| --- | --- |
| auto [begin](../smartptr/begin/)() | Akcesor do metody [begin()](../smartptr/begin/) w podstawowej kolekcji. Kompiluje się tylko, jeśli SmartPtr_ jest typem specjalizacji z metodą [begin()](../smartptr/begin/). |
| auto [begin](../smartptr/begin/)() const | Akcesor do metody [begin()](../smartptr/begin/) w podstawowej kolekcji. Kompiluje się tylko, jeśli SmartPtr_ jest typem specjalizacji z metodą [begin()](../smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Rzutuje wskaźnik na jego własny typ. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Rzutuje wskaźnik na typ bazowy przy użyciu static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Rzutuje wskaźnik na typ pochodny przy użyciu dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Rzutuje wskaźnik na typ pochodny przy użyciu dynamic_cast. |
| auto [cbegin](../smartptr/cbegin/)() const | Akcesor do metody [cbegin()](../smartptr/cbegin/) w podstawowej kolekcji. Kompiluje się tylko, jeśli SmartPtr_ jest typem specjalizacji z metodą [cbegin()](../smartptr/cbegin/). |
| auto [cend](../smartptr/cend/)() const | Akcesor do metody [cend()](../smartptr/cend/) w podstawowej kolekcji. Kompiluje się tylko, jeśli SmartPtr_ jest typem specjalizacji z metodą [cend()](../smartptr/cend/). |
| [SmartPtr](../smartptr/)\<Y\> [const_pointer_cast](../smartptr/const_pointer_cast/)() const | Rzutuje wskaźnik na inny typ przy użyciu const_cast na wskazywanym obiekcie. |
| [SmartPtr](../smartptr/)\<Y\> [dynamic_pointer_cast](../smartptr/dynamic_pointer_cast/)() const | Rzutuje wskaźnik na inny typ przy użyciu dynamic_cast na wskazywanym obiekcie. |
|  [DynamicWeakPtr](./dynamicweakptr/)(std::nullptr_t) | Tworzy pusty inteligentny wskaźnik. |
|  [DynamicWeakPtr](./dynamicweakptr/)([Pointee_](../smartptr/pointee_/) *) | Tworzy inteligentny wskaźnik wskazujący na podany obiekt. |
|  [DynamicWeakPtr](./dynamicweakptr/)(const [SmartPtr_](./smartptr_/)\&) | Konstruktor kopiujący inteligentny wskaźnik. |
|  [DynamicWeakPtr](./dynamicweakptr/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Konstruktor kopiujący inteligentny wskaźnik. |
|  [DynamicWeakPtr](./dynamicweakptr/)(const [DynamicWeakPtr_](./dynamicweakptr_/)\&) | Konstruktor kopiujący inteligentny wskaźnik. |
|  [DynamicWeakPtr](./dynamicweakptr/)([SmartPtr_](./smartptr_/)\&&) | Konstruktor przenoszący inteligentny wskaźnik. |
| auto [end](../smartptr/end/)() | Akcesor do metody [end()](../smartptr/end/) w podstawowej kolekcji. Kompiluje się tylko, jeśli SmartPtr_ jest typem specjalizacji z metodą [end()](../smartptr/end/). |
| auto [end](../smartptr/end/)() const | Akcesor do metody [end()](../smartptr/end/) w podstawowej kolekcji. Kompiluje się tylko, jeśli SmartPtr_ jest typem specjalizacji z metodą [end()](../smartptr/end/). |
| [Pointee_](../smartptr/pointee_/) * [get](../smartptr/get/)() const | Zwraca wskazywany obiekt. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](../smartptr/get_mode/)() const | Zwraca tryb wskaźnika. |
| [Pointee_](../smartptr/pointee_/) * [get_shared](../smartptr/get_shared/)() const | Zwraca wskazywany obiekt, ale domaga się, że wskaźnik jest w trybie współdzielonym. |
| int [get_shared_count](../smartptr/get_shared_count/)() const | Zwraca liczbę istniejących współdzielonych wskaźników do referowanego obiektu, wliczając bieżący. Domaga się, że bieżący wskaźnik jest w trybie współdzielonym. |
| int [GetHashCode](../smartptr/gethashcode/)() const | Wywołuje [GetHashCode()](../smartptr/gethashcode/) na wskazywanym obiekcie. |
| T * [GetObjectNotNull](../smartptr/getobjectnotnull/)() const | Zwraca aktualnie referowany obiekt (jeśli istnieje) lub rzuca wyjątek. |
| [Object](../object/) * [GetObjectOrNull](../smartptr/getobjectornull/)() const | Zwraca wskazywany obiekt (jeśli istnieje) lub nullptr. To samo co [get()](../smartptr/get/). |
| [Object](../object/) * [GetObjectOwner](../smartptr/getobjectowner/)() const | Zwraca referowany obiekt. |
| [Pointee_](../smartptr/pointee_/) * [GetPointer](../smartptr/getpointer/)() const | Zwraca wskazywany obiekt (jeśli istnieje) lub nullptr. To samo co [get()](../smartptr/get/). |
| **bool** [Is](../smartptr/is/)(const [System::TypeInfo](../typeinfo/)\&) const | Sprawdza, czy wskazywany obiekt jest określonego typu lub jego typem potomnym. Zgodnie z semantyką C# 'is'. |
| **bool** [IsAliasingPtr](../smartptr/isaliasingptr/)() const | Sprawdza, czy wskaźnik wskazuje na inny obiekt niż posiadany (utworzony przez konstruktor aliasujący). |
| **bool** [IsShared](../smartptr/isshared/)() const | Sprawdza, czy wskaźnik jest w trybie współdzielonym. |
| **bool** [IsWeak](../smartptr/isweak/)() const | Sprawdza, czy wskaźnik jest w trybie słabym. |
| explicit  [operator bool](../smartptr/operator_bool/)() const | Sprawdza, czy wskaźnik nie jest nullem. |
| **bool** [operator!](../smartptr/operator_not/)() const | Sprawdza, czy wskaźnik jest nullem. |
| [Pointee_](../smartptr/pointee_/)\& [operator*](../smartptr/operator_star/)() const | Zwraca referencję do wskazywanego obiektu. Domaga się, że wskaźnik nie jest nullem. |
| [Pointee_](../smartptr/pointee_/) * [operator->](../smartptr/operator_minus_greater/)() const | Umożliwia dostęp do członków referowanego obiektu. |
| **bool** [operator<](../smartptr/operator_less/)(Y *) const | Zapewnia semantykę porównania mniejszości dla klasy [SmartPtr](../smartptr/). |
| **bool** [operator<](../smartptr/operator_less/)([SmartPtr](../smartptr/)\<Y\> const\&) const | Zapewnia semantykę porównania mniejszości dla klasy [SmartPtr](../smartptr/). |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)([SmartPtr_](./smartptr_/)\&&) | Przypisuje przenosząco inteligentny wskaźnik. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(const [SmartPtr_](./smartptr_/)\&) | Przypisuje kopiująco inteligentny wskaźnik. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Przypisuje kopiująco inteligentny wskaźnik. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(typename [SmartPtr_::Pointee_](../smartptr/pointee_/) *) | Przypisuje inteligentny wskaźnik. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(std::nullptr_t) | Ustawia inteligentny wskaźnik na null. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Sprawdza, czy inteligentny wskaźnik jest nullem. |
| [SmartPtr_](../smartptr/smartptr_/) [RemoveAliasing](../smartptr/removealiasing/)() const | Usuwa aliasowanie (utworzone przez konstruktor aliasujący) z wskaźnika, zapewnia, że zarządza (jeśli współdzielony) lub śledzi (jeśli słaby) tym samym obiektem, na który wskazuje. |
| void [reset](../smartptr/reset/)([Pointee_](../smartptr/pointee_/) *) | Ustawia wskazywany obiekt. |
| void [reset](../smartptr/reset/)() | Ustawia wskaźnik tak, aby wskazywał na nullptr. |
| void [set_Mode](../smartptr/set_mode/)([SmartPtrMode](../smartptrmode/)) | Ustawia tryb wskaźnika. Może zmienić liczniki referencji referowanego obiektu. |
| void [SetContainedTemplateWeakPtr](../smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Wywołuje metodę SetTemplateWeakPtr() na wskazywanym obiekcie (jeśli istnieje). |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtrMode](../smartptrmode/)) | Tworzy obiekt [SmartPtr](../smartptr/) wymaganego trybu. |
|  [SmartPtr](../smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | Tworzy obiekt [SmartPtr](../smartptr/) o wskaźniku null wymaganego trybu. |
|  [SmartPtr](../smartptr/smartptr/)([Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Tworzy [SmartPtr](../smartptr/) wskazujący na określony obiekt lub konwertuje surowy wskaźnik na [SmartPtr](../smartptr/). |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | Konstruktor kopiujący obiekt [SmartPtr](../smartptr/). Oba wskaźniki wskazują na ten sam obiekt po wywołaniu. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | Konstruktor kopiujący obiekt [SmartPtr](../smartptr/). Oba wskaźniki wskazują na ten sam obiekt po wywołaniu. Wykonuje konwersję typu, jeśli jest dozwolona. |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtr_](../smartptr/smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | Konstruktor przenoszący obiekt [SmartPtr](../smartptr/). Efektywnie zamienia dwa wskaźniki, jeśli oba mają ten sam tryb. x może być nieużywalny po wywołaniu. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | Konwertuje typ referowanej tablicy, tworząc nową tablicę innego typu. Przydatne, jeśli w C# istnieje rzutowanie typu tablicy, które nie jest obsługiwane w C++. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const Y\&) | Inicjalizuje pustą tablicę. Używane do tłumaczenia niektórych konstrukcji kodu C#. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<P\>\&, [Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Tworzy [SmartPtr](../smartptr/), który współdzieli informacje o własności z początkową wartością ptr, ale przechowuje niezwiązaną i niezarządzaną wskazówkę p. |
| [SmartPtr](../smartptr/)\<Y\> [static_pointer_cast](../smartptr/static_pointer_cast/)() const | Rzutuje wskaźnik na inny typ przy użyciu static_cast na wskazywanym obiekcie. |
| [SmartPtr](../smartptr/)\<[Object](../object/)\> [ToObjectPtr](../smartptr/toobjectptr/)() const | Konwertuje dowolny typ wskaźnika na wskaźnik do [Object](../object/). Nie wymaga pełnego typu Pointee_. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](../smartptr/type/)() | Skrót do pobrania obiektu [System::TypeInfo](../typeinfo/) dla typu Pointee_. |
|  [~SmartPtr](../smartptr/~smartptr/)() | Niszczy obiekt [SmartPtr](../smartptr/). Jeśli to konieczne, zmniejsza licznik referencji wskazywanego obiektu i usuwa obiekt. |
## Definicje typu

| Definicja typu | Opis |
| --- | --- |
| [SmartPtr_](./smartptr_/) | [SmartPtr](../smartptr/) alias klasy bazowej. |
| [DynamicWeakPtr_](./dynamicweakptr_/) | Alias typu własnego. |
| [Pointee_](./pointee_/) | Typ wskazywany. |

## Zobacz także

* Klasa [SmartPtr](../smartptr/)
* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)