---
title: WeakPtr
second_title: Aspose.Slides dla C++ – referencja API
description: "Podklasa System::SmartPtr, która ustawia się w tryb słaby przy konstrukcji. Należy zauważyć, że ta klasa nie gwarantuje, że jej instancja zawsze pozostanie w trybie słabym, ponieważ set_Mode() jest nadal dostępny. Ten typ jest wskaźnikiem służącym do zarządzania usuwaniem innych obiektów. Powinien być alokowany na stosie i przekazywany do funkcji albo przez wartość, albo przez referencję const."
type: docs
weight: 1496
url: /pl/system/weakptr/
---
## Klasa WeakPtr

Podklasa [System::SmartPtr](../smartptr/) ustawiająca się w trybie słabym przy konstrukcji. Należy zauważyć, że ta klasa nie gwarantuje, że jej instancja zawsze pozostanie w trybie słabym, ponieważ [set_Mode()](../smartptr/set_mode/) jest nadal dostępny. Ten typ jest wskaźnikiem służącym do zarządzania usuwaniem innych obiektów. Powinien być alokowany na stosie i przekazywany do funkcji przez wartość lub przez referencję const.

```cpp
template<class T>class WeakPtr : public System::SmartPtr<T>
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ obiektu wskazywanego. |
## Metody

| Metoda | Opis |
| --- | --- |
| auto [begin](../smartptr/begin/)() | Akcesor do metody [begin()](../smartptr/begin/) podkładowej kolekcji. Kompiluje się tylko, jeśli SmartPtr_ jest typem specjalizacji z metodą [begin()](../smartptr/begin/). |
| auto [begin](../smartptr/begin/)() const | Akcesor do metody [begin()](../smartptr/begin/) podkładowej kolekcji. Kompiluje się tylko, jeśli SmartPtr_ jest typem specjalizacji z metodą [begin()](../smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Rzutuje wskaźnik na jego własny typ. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Rzutuje wskaźnik na typ bazowy przy użyciu static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Rzutuje wskaźnik na typ pochodny przy użyciu dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Rzutuje wskaźnik na typ pochodny przy użyciu dynamic_cast. |
| auto [cbegin](../smartptr/cbegin/)() const | Akcesor do metody [cbegin()](../smartptr/cbegin/) podkładowej kolekcji. Kompiluje się tylko, jeśli SmartPtr_ jest typem specjalizacji z metodą [cbegin()](../smartptr/cbegin/). |
| auto [cend](../smartptr/cend/)() const | Akcesor do metody [cend()](../smartptr/cend/) podkładowej kolekcji. Kompiluje się tylko, jeśli SmartPtr_ jest typem specjalizacji z metodą [cend()](../smartptr/cend/). |
| [SmartPtr](../smartptr/)\<Y\> [const_pointer_cast](../smartptr/const_pointer_cast/)() const | Rzutuje wskaźnik na inny typ przy użyciu const_cast na wskazywanym obiekcie. |
| [SmartPtr](../smartptr/)\<Y\> [dynamic_pointer_cast](../smartptr/dynamic_pointer_cast/)() const | Rzutuje wskaźnik na inny typ przy użyciu dynamic_cast na wskazywanym obiekcie. |
| auto [end](../smartptr/end/)() | Akcesor do metody [end()](../smartptr/end/) podkładowej kolekcji. Kompiluje się tylko, jeśli SmartPtr_ jest typem specjalizacji z metodą [end()](../smartptr/end/). |
| auto [end](../smartptr/end/)() const | Akcesor do metody [end()](../smartptr/end/) podkładowej kolekcji. Kompiluje się tylko, jeśli SmartPtr_ jest typem specjalizacji z metodą [end()](../smartptr/end/). |
| **bool** [expired](./expired/)() const | Sprawdza, czy odwoływany obiekt został już usunięty. |
| [Pointee_](../smartptr/pointee_/) * [get](../smartptr/get/)() const | Zwraca obiekt, na który wskazuje. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](../smartptr/get_mode/)() const | Zwraca tryb wskaźnika. |
| [Pointee_](../smartptr/pointee_/) * [get_shared](../smartptr/get_shared/)() const | Zwraca obiekt, na który wskazuje, ale asertywuje, że wskaźnik jest w trybie współdzielonym. |
| int [get_shared_count](../smartptr/get_shared_count/)() const | Zwraca liczbę istniejących współdzielonych wskaźników do odwoływanego obiektu, w tym bieżącego. Asertywuje, że bieżący wskaźnik jest w trybie współdzielonym. |
| [Object](../object/) * [get_weak](./get_weak/)() const | Zwraca odwoływany obiekt. Asertywuje, że wskaźnik jest w trybie słabym. |
| int [GetHashCode](../smartptr/gethashcode/)() const | Wywołuje [GetHashCode()](../smartptr/gethashcode/) na wskazanym obiekcie. |
| T * [GetObjectNotNull](../smartptr/getobjectnotnull/)() const | Zwraca aktualnie odwoływany obiekt (jeśli istnieje) lub zgłasza wyjątek. |
| [Object](../object/) * [GetObjectOrNull](../smartptr/getobjectornull/)() const | Zwraca wskazywany obiekt (jeśli istnieje) lub nullptr. To samo co [get()](../smartptr/get/). |
| [Object](../object/) * [GetObjectOwner](../smartptr/getobjectowner/)() const | Zwraca odwoływany obiekt. |
| [Pointee_](../smartptr/pointee_/) * [GetPointer](../smartptr/getpointer/)() const | Zwraca wskazywany obiekt (jeśli istnieje) lub nullptr. To samo co [get()](../smartptr/get/). |
| **bool** [Is](../smartptr/is/)(const [System::TypeInfo](../typeinfo/)\&) const | Sprawdza, czy wskazywany obiekt jest określonego typu lub jego typem potomnym. Zgodnie ze semantyką C# 'is'. |
| **bool** [IsAliasingPtr](../smartptr/isaliasingptr/)() const | Sprawdza, czy wskaźnik wskazuje na inny obiekt niż własny (utworzony przez konstruktor aliasujący). |
| **bool** [IsShared](../smartptr/isshared/)() const | Sprawdza, czy wskaźnik jest w trybie współdzielonym. |
| **bool** [IsWeak](../smartptr/isweak/)() const | Sprawdza, czy wskaźnik jest w trybie słabym. |
| explicit  [operator bool](../smartptr/operator_bool/)() const | Sprawdza, czy wskaźnik nie jest nullem. |
| **bool** [operator!](../smartptr/operator_not/)() const | Sprawdza, czy wskaźnik jest nullem. |
| [Pointee_](../smartptr/pointee_/)\& [operator*](../smartptr/operator_star/)() const | Zwraca referencję do wskazywanego obiektu. Asertywuje, że wskaźnik nie jest nullem. |
| [Pointee_](../smartptr/pointee_/) * [operator->](../smartptr/operator_minus_greater/)() const | Umożliwia dostęp do członków odwoływanego obiektu. |
| **bool** [operator<](../smartptr/operator_less/)(Y *) const | Zapewnia semantykę porównania mniejszości dla klasy [SmartPtr](../smartptr/). |
| **bool** [operator<](../smartptr/operator_less/)([SmartPtr](../smartptr/)\<Y\> const\&) const | Zapewnia semantykę porównania mniejszości dla klasy [SmartPtr](../smartptr/). |
| [WeakPtr](./)\& [operator=](./operator_equal/)(Q\&&) | Przypisuje wartość do słabego wskaźnika. Wywołuje określony operator przypisania SmartPtr_. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)([SmartPtr_](../smartptr/smartptr_/)\&&) | Przenosi przypisanie obiektu [SmartPtr](../smartptr/). x staje się nieużyteczne. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(const [SmartPtr_](../smartptr/smartptr_/)\&) | Kopiujące przypisanie obiektu [SmartPtr](../smartptr/). |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Kopiujące przypisanie obiektu [SmartPtr](../smartptr/). Wykonuje wymagane konwersje typów. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)([Pointee_](../smartptr/pointee_/) *) | Przypisuje surowy wskaźnik do obiektu [SmartPtr](../smartptr/). |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(std::nullptr_t) | Ustawia wartość wskaźnika na nullptr. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Sprawdza, czy słaby wskaźnik jest nullem. |
| [SmartPtr_](../smartptr/smartptr_/) [RemoveAliasing](../smartptr/removealiasing/)() const | Usuwa aliasowanie (utworzone przez konstruktor aliasujący) z wskaźnika, zapewniając, że zarządza (jeśli współdzielony) lub śledzi (jeśli słaby) tym samym obiektem, na który wskazuje. |
| void [reset](../smartptr/reset/)([Pointee_](../smartptr/pointee_/) *) | Ustawia wskazywany obiekt. |
| void [reset](../smartptr/reset/)() | Ustawia wskaźnik, aby wskazywał na nullptr. |
| void [set_Mode](../smartptr/set_mode/)([SmartPtrMode](../smartptrmode/)) | Ustawia tryb wskaźnika. Może zmienić liczniki referencji odwoływanego obiektu. |
| void [SetContainedTemplateWeakPtr](../smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Wywołuje metodę SetTemplateWeakPtr() na wskazanym obiekcie (jeśli istnieje). |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtrMode](../smartptrmode/)) | Tworzy obiekt [SmartPtr](../smartptr/) wymaganego trybu. |
|  [SmartPtr](../smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | Tworzy obiekt [SmartPtr](../smartptr/) z null-pointerem wymaganego trybu. |
|  [SmartPtr](../smartptr/smartptr/)([Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Tworzy [SmartPtr](../smartptr/) wskazujący na określony obiekt lub konwertuje surowy wskaźnik na [SmartPtr](../smartptr/). |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | Kopiująco tworzy obiekt [SmartPtr](../smartptr/). Oba wskaźniki wskazują na ten sam obiekt po operacji. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | Kopiująco tworzy obiekt [SmartPtr](../smartptr/). Oba wskaźniki wskazują na ten sam obiekt po operacji. Wykonuje konwersję typu, jeśli jest dozwolona. |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtr_](../smartptr/smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | Przenosząco tworzy obiekt [SmartPtr](../smartptr/). W praktyce zamienia dwa wskaźniki, jeśli oba są tego samego trybu. x może być nieużyteczne po wywołaniu. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | Konwertuje typ odwoływanej tablicy, tworząc nową tablicę innego typu. Przydatne, gdy w C# istnieje rzutowanie typu tablicy, które nie jest obsługiwane w C++. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const Y\&) | Inicjalizuje pustą tablicę. Używane do tłumaczenia niektórych konstrukcji kodu C#. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<P\>\&, [Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Tworzy [SmartPtr](../smartptr/), który współdzieli informacje o własności z początkową wartością ptr, ale przechowuje niepowiązany i niezarządzany wskaźnik p. |
| [SmartPtr](../smartptr/)\<Y\> [static_pointer_cast](../smartptr/static_pointer_cast/)() const | Rzutuje wskaźnik na inny typ przy użyciu static_cast na wskazanym obiekcie. |
| [SmartPtr](../smartptr/)\<[Object](../object/)\> [ToObjectPtr](../smartptr/toobjectptr/)() const | Konwertuje dowolny typ wskaźnika na wskaźnik do [Object](../object/). Nie wymaga pełnego typu Pointee_. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](../smartptr/type/)() | Skrót do uzyskania obiektu [System::TypeInfo](../typeinfo/) dla typu Pointee_. |
|  [WeakPtr](./weakptr/)(std::nullptr_t) | Tworzy null pointer. |
|  [WeakPtr](./weakptr/)([Pointee_](../smartptr/pointee_/) *) | Tworzy słaby wskaźnik do podanego obiektu. |
|  [WeakPtr](./weakptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&) | Tworzy słaby wskaźnik odwołujący się do tego samego wskaźnika, na który wskazuje ptr. |
|  [WeakPtr](./weakptr/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Tworzy słaby wskaźnik odwołujący się do tego samego wskaźnika, na który wskazuje x. |
|  [WeakPtr](./weakptr/)(const [WeakPtr_](./weakptr_/)\&) | Kopiująco tworzy słaby wskaźnik. |
|  [WeakPtr](./weakptr/)(const [WeakPtr](./)\<Q\>\&) | Kopiująco tworzy słaby wskaźnik. |
|  [WeakPtr](./weakptr/)([SmartPtr_](../smartptr/smartptr_/)\&&) | Przenosząco tworzy słaby wskaźnik. |
|  [~SmartPtr](../smartptr/~smartptr/)() | Niszczy obiekt [SmartPtr](../smartptr/). Jeśli to konieczne, zmniejsza licznik referencji wskazywanego obiektu i usuwa obiekt. |
## Typedefy

| Typedef | Opis |
| --- | --- |
| [SmartPtr_](./smartptr_/) | Alias dla odpowiadającej klasy [SmartPtr](../smartptr/). |
| [WeakPtr_](./weakptr_/) | Alias dla własnego typu. |
| [Pointee_](./pointee_/) | Typ wskazywany. |

## Zobacz także

* Klasa [SmartPtr](../smartptr/)
* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)