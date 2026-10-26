---
title: "System::Collections::Generic::Details"
second_title: Aspose.Slides för C++ API-referens
description: 
type: docs
weight: 352
url: /sv/system.collections.generic.details/
---
## Klasser

| Klass | Beskrivning |
| --- | --- |
| [EnumerableAdapter](./enumerableadapter/) | enumerable som används av extension-metoderna IEnumerable.Cast() och IEnumerable.OfType(). |
| [EnumerableSelectAdapter](./enumerableselectadapter/) | enumerable som används av extension-metoden IEnumerable.Select(). |
| [EnumerableSelectIndexAdapter](./enumerableselectindexadapter/) |  |
| [EnumerableSelectManyAdapter](./enumerableselectmanyadapter/) |  |
| [EnumeratorCastAdapter](./enumeratorcastadapter/) | enumerator som används av extension-metoden IEnumerable.Cast(). |
| [EnumeratorOfTypeAdapter](./enumeratoroftypeadapter/) | enumerator som används av extension-metoden IEnumerable.OfType(). |
| [EnumeratorSelectAdapter](./enumeratorselectadapter/) | enumerator som används av extension-metoden IEnumerable.Select(). |
| [EnumeratorSelectIndexAdapter](./enumeratorselectindexadapter/) |  |
| [EnumeratorSelectManyAdapter](./enumeratorselectmanyadapter/) |  |
| [GroupEnumerable](./groupenumerable/) |  |
| [Grouping](./grouping/) |  |
## Strukturer

| Struktur | Beskrivning |
| --- | --- |
| [ComparerType](./comparertype/) | Jämför element med 'less'-semantik. |
| [ComparerType< SharedPtr< T > >](./comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/) | Jämför element med 'less'-semantik. |
| [has_method_compareto](./has_method_compareto/) | Kontrollerar om CompareTo-metoden finns i den angivna typen. Om så är fallet ärver den std::true_type, annars ärver den std::false_type. Kan användas i std::enable_if. |
| [has_method_compareto_shared_ptr](./has_method_compareto_shared_ptr/) | Kontrollerar om CompareTo(SharedPtr<T>)-metoden finns i den angivna typen. Om så är fallet ärver den std::true_type, annars ärver den std::false_type. Kan användas i std::enable_if. |
| [IsEqualExist](./isequalexist/) | Kontrollerar om typen tillhandahåller operator ==. |
## Funktioner

| Funktion | Beskrivning |
| --- | --- |
| **bool** [IsOutOfBounds](./isoutofbounds/)(int, const Container\&) | Kontrollerar om index är utanför behållarens gränser, exklusive behållarens storlek. |
| **bool** [IsOutOfBounds](./isoutofbounds/)(std::int64_t, const Container\&) | Kontrollerar om index är utanför behållarens gränser, exklusive behållarens storlek. |
| **bool** [IsOutOfSize](./isoutofsize/)(int, const Container\&) | Kontrollerar om index är utanför behållarens gränser, inklusive behållarens storlek. |
| **bool** [IsOutOfSize](./isoutofsize/)(std::int64_t, const Container\&) | Kontrollerar om index är utanför behållarens gränser, inklusive behållarens storlek. |
| std::true_type [HasOperatorEqualsHelper](./hasoperatorequalshelper/)(T *, T *) | Hjälpfunktion för att avgöra om en specifik klass har operator ==. |
| std::false_type [HasOperatorEqualsHelper](./hasoperatorequalshelper/)(void *, void *) | Hjälpfunktion för att avgöra om en specifik klass har operator ==. |
| T [TryGetFirst](./trygetfirst/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, **bool**\&) | Försöker att hämta det första elementet i samlingen. |
| T [TryGetFirst](./trygetfirst/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, const [Func](../system/func/)\<T, **bool**\>\&, **bool**\&) | Försöker att hämta det första elementet i samlingen som uppfyller predikatfunktionen. |
| T [TryGetLast](./trygetlast/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, **bool**\&) | Försöker att hämta det sista elementet i samlingen. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [has_operator_equals](./has_operator_equals/) | Dummy-typedef för att kontrollera om operator == finns. |