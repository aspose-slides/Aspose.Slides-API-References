---
title: "System::Collections::Generic::Details"
second_title: Aspose.Slides für C++ API-Referenz
description: 
type: docs
weight: 352
url: /de/system.collections.generic.details/
---
## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [EnumerableAdapter](./enumerableadapter/) | Enumerable, das von den Erweiterungsmethoden IEnumerable.Cast() und IEnumerable.OfType() verwendet wird. |
| [EnumerableSelectAdapter](./enumerableselectadapter/) | Enumerable, das von der Erweiterungsmethode IEnumerable.Select() verwendet wird. |
| [EnumerableSelectIndexAdapter](./enumerableselectindexadapter/) |  |
| [EnumerableSelectManyAdapter](./enumerableselectmanyadapter/) |  |
| [EnumeratorCastAdapter](./enumeratorcastadapter/) | Enumerator, der von der Erweiterungsmethode IEnumerable.Cast() verwendet wird. |
| [EnumeratorOfTypeAdapter](./enumeratoroftypeadapter/) | Enumerator, der von der Erweiterungsmethode IEnumerable.OfType() verwendet wird. |
| [EnumeratorSelectAdapter](./enumeratorselectadapter/) | Enumerator, der von der Erweiterungsmethode IEnumerable.Select() verwendet wird. |
| [EnumeratorSelectIndexAdapter](./enumeratorselectindexadapter/) |  |
| [EnumeratorSelectManyAdapter](./enumeratorselectmanyadapter/) |  |
| [GroupEnumerable](./groupenumerable/) |  |
| [Grouping](./grouping/) |  |

## Strukturen

| Struktur | Beschreibung |
| --- | --- |
| [ComparerType](./comparertype/) | Vergleicht Elemente mithilfe der 'less'-Semantik. |
| [ComparerType< SharedPtr< T > >](./comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/) | Vergleicht Elemente mithilfe der 'less'-Semantik. |
| [has_method_compareto](./has_method_compareto/) | Prüft, ob die CompareTo-Methode im angegebenen Typ vorhanden ist. Falls ja, erbt std::true_type, andernfalls erbt std::false_type. Kann in std::enable_if verwendet werden. |
| [has_method_compareto_shared_ptr](./has_method_compareto_shared_ptr/) | Prüft, ob die CompareTo(SharedPtr<T>)-Methode im angegebenen Typ vorhanden ist. Falls ja, erbt std::true_type, andernfalls erbt std::false_type. Kann in std::enable_if verwendet werden. |
| [IsEqualExist](./isequalexist/) | Prüft, ob der Typ den Operator == bereitstellt. |

## Funktionen

| Funktion | Beschreibung |
| --- | --- |
| **bool** [IsOutOfBounds](./isoutofbounds/)(int, const Container\&) | Prüft, ob der Index außerhalb der Containergrenzen liegt, wobei die Containergröße ausgeschlossen ist. |
| **bool** [IsOutOfBounds](./isoutofbounds/)(std::int64_t, const Container\&) | Prüft, ob der Index außerhalb der Containergrenzen liegt, wobei die Containergröße ausgeschlossen ist. |
| **bool** [IsOutOfSize](./isoutofsize/)(int, const Container\&) | Prüft, ob der Index außerhalb der Containergrenzen liegt, einschließlich der Containergröße. |
| **bool** [IsOutOfSize](./isoutofsize/)(std::int64_t, const Container\&) | Prüft, ob der Index außerhalb der Containergrenzen liegt, einschließlich der Containergröße. |
| std::true_type [HasOperatorEqualsHelper](./hasoperatorequalshelper/)(T *, T *) | Hilfsfunktion zur Bestimmung, ob eine bestimmte Klasse den Operator == hat. |
| std::false_type [HasOperatorEqualsHelper](./hasoperatorequalshelper/)(void *, void *) | Hilfsfunktion zur Bestimmung, ob eine bestimmte Klasse den Operator == hat. |
| T [TryGetFirst](./trygetfirst/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, **bool**\&) | Versucht, das erste Element der Sammlung zu erhalten. |
| T [TryGetFirst](./trygetfirst/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, const [Func](../system/func/)\<T, **bool**\>\&, **bool**\&) | Versucht, das erste Element der Sammlung zu erhalten, das die Prädikatfunktion erfüllt. |
| T [TryGetLast](./trygetlast/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, **bool**\&) | Versucht, das letzte Element der Sammlung zu erhalten. |

## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [has_operator_equals](./has_operator_equals/) | Dummy-Typedef zum Prüfen der Existenz des Operators ==. |