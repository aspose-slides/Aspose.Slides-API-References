---
title: "System::Collections::Generic::Details"
second_title: Riferimento API di Aspose.Slides per C++
description: 
type: docs
weight: 352
url: /it/system.collections.generic.details/
---
## Classi

| Classe | Descrizione |
| --- | --- |
| [EnumerableAdapter](./enumerableadapter/) | Enumerable utilizzato dai metodi di estensione IEnumerable.Cast() e IEnumerable.OfType(). |
| [EnumerableSelectAdapter](./enumerableselectadapter/) | Enumerable utilizzato dal metodo di estensione IEnumerable.Select(). |
| [EnumerableSelectIndexAdapter](./enumerableselectindexadapter/) |  |
| [EnumerableSelectManyAdapter](./enumerableselectmanyadapter/) |  |
| [EnumeratorCastAdapter](./enumeratorcastadapter/) | Enumerator utilizzato dal metodo di estensione IEnumerable.Cast(). |
| [EnumeratorOfTypeAdapter](./enumeratoroftypeadapter/) | Enumerator utilizzato dal metodo di estensione IEnumerable.OfType(). |
| [EnumeratorSelectAdapter](./enumeratorselectadapter/) | Enumerator utilizzato dal metodo di estensione IEnumerable.Select(). |
| [EnumeratorSelectIndexAdapter](./enumeratorselectindexadapter/) |  |
| [EnumeratorSelectManyAdapter](./enumeratorselectmanyadapter/) |  |
| [GroupEnumerable](./groupenumerable/) |  |
| [Grouping](./grouping/) |  |
## Strutture

| Struttura | Descrizione |
| --- | --- |
| [ComparerType](./comparertype/) | Confronta gli elementi usando la semantica 'less'. |
| [ComparerType< SharedPtr< T > >](./comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/) | Confronta gli elementi usando la semantica 'less'. |
| [has_method_compareto](./has_method_compareto/) | Verifica se il metodo CompareTo esiste nel tipo specificato. In tal caso, eredita std::true_type, altrimenti eredita std::false_type. Può essere usato in std::enable_if. |
| [has_method_compareto_shared_ptr](./has_method_compareto_shared_ptr/) | Verifica se il metodo CompareTo(SharedPtr<T>) esiste nel tipo specificato. In tal caso, eredita std::true_type, altrimenti eredita std::false_type. Può essere usato in std::enable_if. |
| [IsEqualExist](./isequalexist/) | Verifica se il tipo fornisce l'operatore ==. |
## Funzioni

| Funzione | Descrizione |
| --- | --- |
| **bool** [IsOutOfBounds](./isoutofbounds/)(int, const Container\&) | Verifica se l'indice è fuori dai limiti del contenitore, escludendo la dimensione del contenitore. |
| **bool** [IsOutOfBounds](./isoutofbounds/)(std::int64_t, const Container\&) | Verifica se l'indice è fuori dai limiti del contenitore, escludendo la dimensione del contenitore. |
| **bool** [IsOutOfSize](./isoutofsize/)(int, const Container\&) | Verifica se l'indice è fuori dai limiti del contenitore, includendo la dimensione del contenitore. |
| **bool** [IsOutOfSize](./isoutofsize/)(std::int64_t, const Container\&) | Verifica se l'indice è fuori dai limiti del contenitore, includendo la dimensione del contenitore. |
| std::true_type [HasOperatorEqualsHelper](./hasoperatorequalshelper/)(T *, T *) | Funzione di supporto per determinare se una classe specifica ha l'operatore ==. |
| std::false_type [HasOperatorEqualsHelper](./hasoperatorequalshelper/)(void *, void *) | Funzione di supporto per determinare se una classe specifica ha l'operatore ==. |
| T [TryGetFirst](./trygetfirst/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, **bool**\&) | Cerca di ottenere il primo elemento della collezione. |
| T [TryGetFirst](./trygetfirst/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, const [Func](../system/func/)\<T, **bool**\>\&, **bool**\&) | Cerca di ottenere il primo elemento della collezione che soddisfa la funzione predicato. |
| T [TryGetLast](./trygetlast/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, **bool**\&) | Cerca di ottenere l'ultimo elemento della collezione. |
## Typedef

| Typedef | Descrizione |
| --- | --- |
| [has_operator_equals](./has_operator_equals/) | Typedef fittizio per verificare l'esistenza dell'operatore ==. |