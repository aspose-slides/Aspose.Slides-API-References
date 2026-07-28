---
title: "System::Collections::Generic::Details"
second_title: Aspose.Slides dla C++ Dokumentacja API
description:
type: docs
weight: 352
url: /pl/system.collections.generic.details/
---
## Klasy

| Klasa | Opis |
| --- | --- |
| [EnumerableAdapter](./enumerableadapter/) | Enumerable używany przez metody rozszerzeń IEnumerable.Cast() i IEnumerable.OfType(). |
| [EnumerableSelectAdapter](./enumerableselectadapter/) | Enumerable używany przez metodę rozszerzenia IEnumerable.Select(). |
| [EnumerableSelectIndexAdapter](./enumerableselectindexadapter/) |  |
| [EnumerableSelectManyAdapter](./enumerableselectmanyadapter/) |  |
| [EnumeratorCastAdapter](./enumeratorcastadapter/) | Enumerator używany przez metodę rozszerzenia IEnumerable.Cast(). |
| [EnumeratorOfTypeAdapter](./enumeratoroftypeadapter/) | Enumerator używany przez metodę rozszerzenia IEnumerable.OfType(). |
| [EnumeratorSelectAdapter](./enumeratorselectadapter/) | Enumerator używany przez metodę rozszerzenia IEnumerable.Select(). |
| [EnumeratorSelectIndexAdapter](./enumeratorselectindexadapter/) |  |
| [EnumeratorSelectManyAdapter](./enumeratorselectmanyadapter/) |  |
| [GroupEnumerable](./groupenumerable/) |  |
| [Grouping](./grouping/) |  |
## Struktury

| Struktura | Opis |
| --- | --- |
| [ComparerType](./comparertype/) | Porównuje elementy używając semantyki 'less'. |
| [ComparerType< SharedPtr< T > >](./comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/) | Porównuje elementy używając semantyki 'less'. |
| [has_method_compareto](./has_method_compareto/) | Sprawdza, czy metoda CompareTo istnieje w określonym typie. Jeśli tak, dziedziczy po std::true_type, w przeciwnym razie po std::false_type. Może być użyta w std::enable_if. |
| [has_method_compareto_shared_ptr](./has_method_compareto_shared_ptr/) | Sprawdza, czy metoda CompareTo(SharedPtr<T>) istnieje w określonym typie. Jeśli tak, dziedziczy po std::true_type, w przeciwnym razie po std::false_type. Może być użyta w std::enable_if. |
| [IsEqualExist](./isequalexist/) | Sprawdza, czy typ udostępnia operator ==. |
## Funkcje

| Funkcja | Opis |
| --- | --- |
| **bool** [IsOutOfBounds](./isoutofbounds/)(int, const Container\&) | Sprawdza, czy indeks jest poza granicami kontenera, z wyłączeniem rozmiaru kontenera. |
| **bool** [IsOutOfBounds](./isoutofbounds/)(std::int64_t, const Container\&) | Sprawdza, czy indeks jest poza granicami kontenera, z wyłączeniem rozmiaru kontenera. |
| **bool** [IsOutOfSize](./isoutofsize/)(int, const Container\&) | Sprawdza, czy indeks jest poza granicami kontenera, uwzględniając rozmiar kontenera. |
| **bool** [IsOutOfSize](./isoutofsize/)(std::int64_t, const Container\&) | Sprawdza, czy indeks jest poza granicami kontenera, uwzględniając rozmiar kontenera. |
| std::true_type [HasOperatorEqualsHelper](./hasoperatorequalshelper/)(T *, T *) | Funkcja pomocnicza służąca do określenia, czy dana klasa posiada operator ==. |
| std::false_type [HasOperatorEqualsHelper](./hasoperatorequalshelper/)(void *, void *) | Funkcja pomocnicza służąca do określenia, czy dana klasa posiada operator ==. |
| T [TryGetFirst](./trygetfirst/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, **bool**\&) | Próbuje pobrać pierwszy element kolekcji. |
| T [TryGetFirst](./trygetfirst/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, const [Func](../system/func/)\<T, **bool**\>\&, **bool**\&) | Próbuje pobrać pierwszy element kolekcji, który spełnia warunek funkcji predykatu. |
| T [TryGetLast](./trygetlast/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, **bool**\&) | Próbuje pobrać ostatni element kolekcji. |
## Definicje typów

| Definicja typu | Opis |
| --- | --- |
| [has_operator_equals](./has_operator_equals/) | Dummy typedef służący do sprawdzenia istnienia operatora ==. |