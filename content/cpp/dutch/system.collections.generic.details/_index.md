---
title: "System::Collections::Generic::Details"
second_title: Aspose.Slides voor C++ API-referentie
description: 
type: docs
weight: 352
url: /nl/system.collections.generic.details/
---
## Klassen

| Klasse | Beschrijving |
| --- | --- |
| [EnumerableAdapter](./enumerableadapter/) | Enumerable die wordt gebruikt door de IEnumerable.Cast() en IEnumerable.OfType() uitbreidingsmethoden. |
| [EnumerableSelectAdapter](./enumerableselectadapter/) | Enumerable die wordt gebruikt door de IEnumerable.Select() uitbreidingsmethode. |
| [EnumerableSelectIndexAdapter](./enumerableselectindexadapter/) |  |
| [EnumerableSelectManyAdapter](./enumerableselectmanyadapter/) |  |
| [EnumeratorCastAdapter](./enumeratorcastadapter/) | Enumerator gebruikt door de IEnumerable.Cast() uitbreidingsmethode. |
| [EnumeratorOfTypeAdapter](./enumeratoroftypeadapter/) | Enumerator gebruikt door de IEnumerable.OfType() uitbreidingsmethode. |
| [EnumeratorSelectAdapter](./enumeratorselectadapter/) | Enumerator gebruikt door de IEnumerable.Select() uitbreidingsmethode. |
| [EnumeratorSelectIndexAdapter](./enumeratorselectindexadapter/) |  |
| [EnumeratorSelectManyAdapter](./enumeratorselectmanyadapter/) |  |
| [GroupEnumerable](./groupenumerable/) |  |
| [Grouping](./grouping/) |  |
## Structuren

| Struct | Beschrijving |
| --- | --- |
| [ComparerType](./comparertype/) | Vergelijkt elementen met behulp van 'less'-semantiek. |
| [ComparerType< SharedPtr< T > >](./comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/) | Vergelijkt elementen met behulp van 'less'-semantiek. |
| [has_method_compareto](./has_method_compareto/) | Controleert of de CompareTo-methode bestaat in het opgegeven type. Zo ja, erft std::true_type, anders erft std::false_type. Kan gebruikt worden in std::enable_if. |
| [has_method_compareto_shared_ptr](./has_method_compareto_shared_ptr/) | Controleert of de CompareTo(SharedPtr<T>)-methode bestaat in het opgegeven type. Zo ja, erft std::true_type, anders erft std::false_type. Kan gebruikt worden in std::enable_if. |
| [IsEqualExist](./isequalexist/) | Controleert of het type operator == biedt. |
## Functies

| Functie | Beschrijving |
| --- | --- |
| **bool** [IsOutOfBounds](./isoutofbounds/)(int, const Container\&) | Controleert of de index buiten de grenzen van de container valt, exclusief de grootte van de container. |
| **bool** [IsOutOfBounds](./isoutofbounds/)(std::int64_t, const Container\&) | Controleert of de index buiten de grenzen van de container valt, exclusief de grootte van de container. |
| **bool** [IsOutOfSize](./isoutofsize/)(int, const Container\&) | Controleert of de index buiten de grenzen van de container valt, inclusief de grootte van de container. |
| **bool** [IsOutOfSize](./isoutofsize/)(std::int64_t, const Container\&) | Controleert of de index buiten de grenzen van de container valt, inclusief de grootte van de container. |
| std::true_type [HasOperatorEqualsHelper](./hasoperatorequalshelper/)(T *, T *) | Helperfunctie om te bepalen of een specifieke klasse operator == heeft. |
| std::false_type [HasOperatorEqualsHelper](./hasoperatorequalshelper/)(void *, void *) | Helperfunctie om te bepalen of een specifieke klasse operator == heeft. |
| T [TryGetFirst](./trygetfirst/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, **bool**\&) | Probeert het eerste element van de collectie op te halen. |
| T [TryGetFirst](./trygetfirst/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, const [Func](../system/func/)\<T, **bool**\>\&, **bool**\&) | Probeert het eerste element van de collectie op te halen dat voldoet aan de predikaatfunctie. |
| T [TryGetLast](./trygetlast/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, **bool**\&) | Probeert het laatste element van de collectie op te halen. |
## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [has_operator_equals](./has_operator_equals/) | Dummy-typedef om te controleren of operator == bestaat. |