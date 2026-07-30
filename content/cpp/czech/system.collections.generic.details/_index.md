---
title: "System::Collections::Generic::Details"
second_title: Aspose.Slides pro C++ – reference API
description: 
type: docs
weight: 352
url: /cs/system.collections.generic.details/
---
## Třídy

| Třída | Popis |
| --- | --- |
| [EnumerableAdapter](./enumerableadapter/) | Enumerable používaný metodami rozšíření IEnumerable.Cast() a IEnumerable.OfType(). |
| [EnumerableSelectAdapter](./enumerableselectadapter/) | Enumerable používaný metodou rozšíření IEnumerable.Select(). |
| [EnumerableSelectIndexAdapter](./enumerableselectindexadapter/) |  |
| [EnumerableSelectManyAdapter](./enumerableselectmanyadapter/) |  |
| [EnumeratorCastAdapter](./enumeratorcastadapter/) | Enumerator používaný metodou rozšíření IEnumerable.Cast(). |
| [EnumeratorOfTypeAdapter](./enumeratoroftypeadapter/) | Enumerator používaný metodou rozšíření IEnumerable.OfType(). |
| [EnumeratorSelectAdapter](./enumeratorselectadapter/) | Enumerator používaný metodou rozšíření IEnumerable.Select(). |
| [EnumeratorSelectIndexAdapter](./enumeratorselectindexadapter/) |  |
| [EnumeratorSelectManyAdapter](./enumeratorselectmanyadapter/) |  |
| [GroupEnumerable](./groupenumerable/) |  |
| [Grouping](./grouping/) |  |

## Struktury

| Struktura | Popis |
| --- | --- |
| [ComparerType](./comparertype/) | Porovnává prvky pomocí sémantiky 'less'. |
| [ComparerType< SharedPtr< T > >](./comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/) | Porovnává prvky pomocí sémantiky 'less'. |
| [has_method_compareto](./has_method_compareto/) | Kontroluje, zda metoda CompareTo existuje v určeném typu. Pokud ano, dědí std::true_type, jinak dědí std::false_type. Lze použít v std::enable_if. |
| [has_method_compareto_shared_ptr](./has_method_compareto_shared_ptr/) | Kontroluje, zda metoda CompareTo(SharedPtr<T>) existuje v určeném typu. Pokud ano, dědí std::true_type, jinak dědí std::false_type. Lze použít v std::enable_if. |
| [IsEqualExist](./isequalexist/) | Kontroluje, zda typ poskytuje operátor ==. |

## Funkce

| Funkce | Popis |
| --- | --- |
| **bool** [IsOutOfBounds](./isoutofbounds/)(int, const Container\&) | Kontroluje, zda je index mimo meze kontejneru, vyjma velikosti kontejneru. |
| **bool** [IsOutOfBounds](./isoutofbounds/)(std::int64_t, const Container\&) | Kontroluje, zda je index mimo meze kontejneru, vyjma velikosti kontejneru. |
| **bool** [IsOutOfSize](./isoutofsize/)(int, const Container\&) | Kontroluje, zda je index mimo meze kontejneru, včetně velikosti kontejneru. |
| **bool** [IsOutOfSize](./isoutofsize/)(std::int64_t, const Container\&) | Kontroluje, zda je index mimo meze kontejneru, včetně velikosti kontejneru. |
| std::true_type [HasOperatorEqualsHelper](./hasoperatorequalshelper/)(T *, T *) | Pomocná funkce pro určení, zda konkrétní třída má operátor ==. |
| std::false_type [HasOperatorEqualsHelper](./hasoperatorequalshelper/)(void *, void *) | Pomocná funkce pro určení, zda konkrétní třída má operátor ==. |
| T [TryGetFirst](./trygetfirst/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, **bool**\&) | Pokouší se získat první prvek kolekce. |
| T [TryGetFirst](./trygetfirst/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, const [Func](../system/func/)\<T, **bool**\>\&, **bool**\&) | Pokouší se získat první prvek kolekce, který splňuje predikátovou funkci. |
| T [TryGetLast](./trygetlast/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, **bool**\&) | Pokouší se získat poslední prvek kolekce. |

## Typedefy

| Typedef | Popis |
| --- | --- |
| [has_operator_equals](./has_operator_equals/) | Fiktivní typedef pro kontrolu existence operátoru ==. |