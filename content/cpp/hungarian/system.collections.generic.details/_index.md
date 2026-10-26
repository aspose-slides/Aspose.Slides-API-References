---
title: "System::Collections::Generic::Details"
second_title: Aspose.Slides C++ API Referencia
description: 
type: docs
weight: 352
url: /hu/system.collections.generic.details/
---
## Osztályok

| Class | Leírás |
| --- | --- |
| [EnumerableAdapter](./enumerableadapter/) | Az IEnumerable.Cast() és IEnumerable.OfType() kiterjesztő metódusok által használt enumerable. |
| [EnumerableSelectAdapter](./enumerableselectadapter/) | Az IEnumerable.Select() kiterjesztő metódus által használt enumerable. |
| [EnumerableSelectIndexAdapter](./enumerableselectindexadapter/) |  |
| [EnumerableSelectManyAdapter](./enumerableselectmanyadapter/) |  |
| [EnumeratorCastAdapter](./enumeratorcastadapter/) | Az IEnumerable.Cast() kiterjesztő metódus által használt enumerátor. |
| [EnumeratorOfTypeAdapter](./enumeratoroftypeadapter/) | Az IEnumerable.OfType() kiterjesztő metódus által használt enumerátor. |
| [EnumeratorSelectAdapter](./enumeratorselectadapter/) | Az IEnumerable.Select() kiterjesztő metódus által használt enumerátor. |
| [EnumeratorSelectIndexAdapter](./enumeratorselectindexadapter/) |  |
| [EnumeratorSelectManyAdapter](./enumeratorselectmanyadapter/) |  |
| [GroupEnumerable](./groupenumerable/) |  |
| [Grouping](./grouping/) |  |

## Struktúrák

| Struktúra | Leírás |
| --- | --- |
| [ComparerType](./comparertype/) | Az elemeket 'less' szemantika szerint hasonlítja össze. |
| [ComparerType< SharedPtr< T > >](./comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/) | Az elemeket 'less' szemantika szerint hasonlítja össze. |
| [has_method_compareto](./has_method_compareto/) | Ellenőrzi, hogy a megadott típusban létezik-e a CompareTo metódus. Ha igen, örökli a std::true_type-t, egyébként a std::false_type-t. Használható a std::enable_if-ben. |
| [has_method_compareto_shared_ptr](./has_method_compareto_shared_ptr/) | Ellenőrzi, hogy a megadott típusban létezik-e a CompareTo(SharedPtr<T>) metódus. Ha igen, örökli a std::true_type-t, egyébként a std::false_type-t. Használható a std::enable_if-ben. |
| [IsEqualExist](./isequalexist/) | Ellenőrzi, hogy a típus biztosítja-e az operator ==-t. |

## Függvények

| Függvény | Leírás |
| --- | --- |
| **bool** [IsOutOfBounds](./isoutofbounds/)(int, const Container\&) | Ellenőrzi, hogy az index kívül esik-e a tároló határain, kivéve a tároló méretét. |
| **bool** [IsOutOfBounds](./isoutofbounds/)(std::int64_t, const Container\&) | Ellenőrzi, hogy az index kívül esik-e a tároló határain, kivéve a tároló méretét. |
| **bool** [IsOutOfSize](./isoutofsize/)(int, const Container\&) | Ellenőrzi, hogy az index kívül esik-e a tároló határain, beleértve a tároló méretét. |
| **bool** [IsOutOfSize](./isoutofsize/)(std::int64_t, const Container\&) | Ellenőrzi, hogy az index kívül esik-e a tároló határain, beleértve a tároló méretét. |
| std::true_type [HasOperatorEqualsHelper](./hasoperatorequalshelper/)(T *, T *) | Segédfüggvény annak meghatározására, hogy a adott osztálynak van-e operator ==. |
| std::false_type [HasOperatorEqualsHelper](./hasoperatorequalshelper/)(void *, void *) | Segédfüggvény annak meghatározására, hogy a adott osztálynak van-e operator ==. |
| T [TryGetFirst](./trygetfirst/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, **bool**\&) | Megkísérli a gyűjtemény első elemének lekérését. |
| T [TryGetFirst](./trygetfirst/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, const [Func](../system/func/)\<T, **bool**\>\&, **bool**\&) | Megkísérli a gyűjtemény első olyan elemének lekérését, amely megfelel az előrejelző függvénynek. |
| T [TryGetLast](./trygetlast/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, **bool**\&) | Megkísérli a gyűjtemény utolsó elemének lekérését. |

## Typedefek

| Typedef | Leírás |
| --- | --- |
| [has_operator_equals](./has_operator_equals/) | Metsző typedef az operator == létezésének ellenőrzésére. |