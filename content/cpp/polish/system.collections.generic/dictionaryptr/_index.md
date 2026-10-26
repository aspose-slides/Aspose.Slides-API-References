---
title: DictionaryPtr
second_title: Referencja API Aspose.Slides dla C++
description: Klasa wskaźnika słownika z przeciążeniami operatorów. Ten typ jest wskaźnikiem służącym do zarządzania usuwaniem innych obiektów. Powinna być alokowana na stosie i przekazywana do funkcji zarówno przez wartość, jak i przez referencję const.
type: docs
weight: 170
url: /pl/system.collections.generic/dictionaryptr/
---
## DictionaryPtr klasa

[Dictionary](../dictionary/) pointer class with operator overloads. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
template<typename T,typename V>class DictionaryPtr : public System::SmartPtr<Dictionary<T, V>>
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ klucza. |
| V | Typ wartości. |
## Metody

| Metoda | Opis |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Akcesor dla metody [begin()](../../system/smartptr/begin/) w kolekcji bazowej. Kompiluje się tylko, jeśli SmartPtr_ jest typem specjalizacji z metodą [begin()](../../system/smartptr/begin/). |
| auto [begin](../../system/smartptr/begin/)() const | Akcesor dla metody [begin()](../../system/smartptr/begin/) w kolekcji bazowej. Kompiluje się tylko, jeśli SmartPtr_ jest typem specjalizacji z metodą [begin()](../../system/smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Rzutuje wskaźnik na jego własny typ. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Rzutuje wskaźnik na typ bazowy przy użyciu static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Rzutuje wskaźnik na typ pochodny przy użyciu dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Rzutuje wskaźnik na typ pochodny przy użyciu dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Akcesor dla metody [cbegin()](../../system/smartptr/cbegin/) w kolekcji bazowej. Kompiluje się tylko, jeśli SmartPtr_ jest typem specjalizacji z metodą [cbegin()](../../system/smartptr/cbegin/). |
| auto [cend](../../system/smartptr/cend/)() const | Akcesor dla metody [cend()](../../system/smartptr/cend/) w kolekcji bazowej. Kompiluje się tylko, jeśli SmartPtr_ jest typem specjalizacji z metodą [cend()](../../system/smartptr/cend/). |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Rzutuje wskaźnik na inny typ przy użyciu const_cast na wskazywanym obiekcie. |
| [DictionaryPtr](./dictionaryptr/)() | Inicjalizuje pusty wskaźnik. |
| [DictionaryPtr](./dictionaryptr/)(const [SharedPtr](../../system/sharedptr/)\<[Dictionary](../dictionary/)\<T, V\>\>\&) | Konwertuje typ wskaźnika. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Rzutuje wskaźnik na inny typ przy użyciu dynamic_cast na wskazywanym obiekcie. |
| auto [end](../../system/smartptr/end/)() | Akcesor dla metody [end()](../../system/smartptr/end/) w kolekcji bazowej. Kompiluje się tylko, jeśli SmartPtr_ jest typem specjalizacji z metodą [end()](../../system/smartptr/end/). |
| auto [end](../../system/smartptr/end/)() const | Akcesor dla metody [end()](../../system/smartptr/end/) w kolekcji bazowej. Kompiluje się tylko, jeśli SmartPtr_ jest typem specjalizacji z metodą [end()](../../system/smartptr/end/). |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Zwraca wskazywany obiekt. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Zwraca tryb wskaźnika. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Zwraca wskazywany obiekt, ale sprawdza, że wskaźnik jest w trybie współdzielonym. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Zwraca liczbę współdzielonych wskaźników istniejących do referowanego obiektu, włącznie z bieżącym. Sprawdza, że bieżący wskaźnik jest w trybie współdzielonym. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Wywołuje [GetHashCode()](../../system/smartptr/gethashcode/) na wskazywanym obiekcie. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Zwraca aktualnie referowany obiekt (jeśli istnieje) lub zgłasza wyjątek. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Zwraca wskazywany obiekt (jeśli istnieje) lub nullptr. To samo co [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Zwraca referowany obiekt. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Zwraca wskazywany obiekt (jeśli istnieje) lub nullptr. To samo co [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy wskazywany obiekt jest określonego typu lub jego podtypem. Zgodne z semantyką C# 'is'. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Sprawdza, czy wskaźnik wskazuje na inny obiekt niż własny (utworzony przez konstruktor aliasujący). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Sprawdza, czy wskaźnik jest w trybie współdzielonym. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Sprawdza, czy wskaźnik jest w trybie słabym. |
| explicit [operator bool](../../system/smartptr/operator_bool/)() const | Sprawdza, czy wskaźnik nie jest pusty. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Sprawdza, czy wskaźnik jest pusty. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Zwraca referencję do wskazywanego obiektu. Sprawdza, że wskaźnik nie jest pusty. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Umożliwia dostęp do członków referowanego obiektu. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Zapewnia semantykę porównania mniejszości dla klasy [SmartPtr](../../system/smartptr/). |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Zapewnia semantykę porównania mniejszości dla klasy [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Przypisuje przeniesieniem obiekt [SmartPtr](../../system/smartptr/). x staje się nieużywalny. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Kopiująco przypisuje obiekt [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Kopiująco przypisuje obiekt [SmartPtr](../../system/smartptr/). Wykonuje wymagane konwersje typów. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Przypisuje surowy wskaźnik do obiektu [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Ustawia wartość wskaźnika na nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Sprawdza, czy wskaźnik wskazuje na nullptr. |
| V\& [operator[]](./operator[]/)(const X\&) const | Operator dostępu służący do konwersji typu klucza. |
| V\& [operator[]](./operator[]/)(const T\&) const | Operator dostępu. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Usuwa aliasowanie (utworzone przez konstruktor aliasujący) ze wskaźnika, zapewniając, że zarządza (jeśli współdzielony) lub śledzi (jeśli słaby) tym samym obiektem, na który wskazuje. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Ustawia wskazywany obiekt. |
| void [reset](../../system/smartptr/reset/)() | Ustawia wskaźnik, aby wskazywał na nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Ustawia tryb wskaźnika. Może zmienić liczniki referencji referowanego obiektu. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Wywołuje metodę SetTemplateWeakPtr() na wskazywanym obiekcie (jeśli istnieje). |
| [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Tworzy obiekt [SmartPtr](../../system/smartptr/) w wymaganym trybie. |
| [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Tworzy obiekt [SmartPtr](../../system/smartptr/) z pustym wskaźnikiem w wymaganym trybie. |
| [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Tworzy [SmartPtr](../../system/smartptr/) wskazujący na określony obiekt lub konwertuje surowy wskaźnik na [SmartPtr](../../system/smartptr/). |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Kopiująco tworzy obiekt [SmartPtr](../../system/smartptr/). Oba wskaźniki wskazują na ten sam obiekt po wywołaniu. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Kopiująco tworzy obiekt [SmartPtr](../../system/smartptr/). Oba wskaźniki wskazują na ten sam obiekt po wywołaniu. Wykonuje konwersję typu, jeśli jest dozwolona. |
| [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Przenosząco tworzy obiekt [SmartPtr](../../system/smartptr/). Efektywnie zamienia dwa wskaźniki, jeśli oba są w tym samym trybie. x może być nieużywalny po wywołaniu. |
| explicit [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Konwertuje typ referowanej tablicy, tworząc nową tablicę innego typu. Przydatne, gdy w C# istnieje rzutowanie typów tablic, które nie jest obsługiwane w C++. |
| explicit [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Inicjalizuje pustą tablicę. Używane do tłumaczenia niektórych konstrukcji kodu C#. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Tworzy [SmartPtr](../../system/smartptr/), które współdzieli informacje o własności z początkową wartością ptr, ale posiada niepowiązany i niezarządzany wskaźnik p. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Rzutuje wskaźnik na inny typ przy użyciu static_cast na wskazywanym obiekcie. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Konwertuje dowolny typ wskaźnika na wskaźnik do [Object](../../system/object/). Nie wymaga, aby typ Pointee_ był kompletny. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Skrót do uzyskania obiektu [System::TypeInfo](../../system/typeinfo/) dla typu Pointee_. |
| [~SmartPtr](../../system/smartptr/~smartptr/)() | Usuwa obiekt [SmartPtr](../../system/smartptr/). W razie potrzeby zmniejsza licznik referencji wskazywanego obiektu i usuwa obiekt. |

## Zobacz także

* Klasa [SmartPtr](../../system/smartptr/)
* Przestrzeń nazw [System::Collections::Generic](../)
* Biblioteka [Aspose.Slides](../../)