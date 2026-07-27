---
title: "System::Collections::Generic::Details"
second_title: Aspose.Slides para C++ - Referência da API
description: 
type: docs
weight: 352
url: /pt/system.collections.generic.details/
---
## Classes

| Classe | Descrição |
| --- | --- |
| [EnumerableAdapter](./enumerableadapter/) | Enumerable usado pelos métodos de extensão IEnumerable.Cast() e IEnumerable.OfType(). |
| [EnumerableSelectAdapter](./enumerableselectadapter/) | Enumerable usado pelo método de extensão IEnumerable.Select(). |
| [EnumerableSelectIndexAdapter](./enumerableselectindexadapter/) |  |
| [EnumerableSelectManyAdapter](./enumerableselectmanyadapter/) |  |
| [EnumeratorCastAdapter](./enumeratorcastadapter/) | Enumerator usado pelo método de extensão IEnumerable.Cast(). |
| [EnumeratorOfTypeAdapter](./enumeratoroftypeadapter/) | Enumerator usado pelo método de extensão IEnumerable.OfType(). |
| [EnumeratorSelectAdapter](./enumeratorselectadapter/) | Enumerator usado pelo método de extensão IEnumerable.Select(). |
| [EnumeratorSelectIndexAdapter](./enumeratorselectindexadapter/) |  |
| [EnumeratorSelectManyAdapter](./enumeratorselectmanyadapter/) |  |
| [GroupEnumerable](./groupenumerable/) |  |
| [Grouping](./grouping/) |  |

## Estruturas

| Struct | Descrição |
| --- | --- |
| [ComparerType](./comparertype/) | Compara elementos usando semântica “less”. |
| [ComparerType< SharedPtr< T > >](./comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/) | Compara elementos usando semântica “less”. |
| [has_method_compareto](./has_method_compareto/) | Verifica se o método CompareTo existe no tipo especificado. Se sim, herda std::true_type, caso contrário herda std::false_type. Pode ser usado em std::enable_if. |
| [has_method_compareto_shared_ptr](./has_method_compareto_shared_ptr/) | Verifica se o método CompareTo(SharedPtr<T>) existe no tipo especificado. Se sim, herda std::true_type, caso contrário herda std::false_type. Pode ser usado em std::enable_if. |
| [IsEqualExist](./isequalexist/) | Verifica se o tipo fornece o operador ==. |

## Funções

| Função | Descrição |
| --- | --- |
| **bool** [IsOutOfBounds](./isoutofbounds/)(int, const Container\&) | Verifica se o índice está fora dos limites do contêiner, excluindo o tamanho do contêiner. |
| **bool** [IsOutOfBounds](./isoutofbounds/)(std::int64_t, const Container\&) | Verifica se o índice está fora dos limites do contêiner, excluindo o tamanho do contêiner. |
| **bool** [IsOutOfSize](./isoutofsize/)(int, const Container\&) | Verifica se o índice está fora dos limites do contêiner, incluindo o tamanho do contêiner. |
| **bool** [IsOutOfSize](./isoutofsize/)(std::int64_t, const Container\&) | Verifica se o índice está fora dos limites do contêiner, incluindo o tamanho do contêiner. |
| std::true_type [HasOperatorEqualsHelper](./hasoperatorequalshelper/)(T *, T *) | Função auxiliar para determinar se uma classe específica possui o operador ==. |
| std::false_type [HasOperatorEqualsHelper](./hasoperatorequalshelper/)(void *, void *) | Função auxiliar para determinar se uma classe específica possui o operador ==. |
| T [TryGetFirst](./trygetfirst/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, **bool**\&) | Tenta obter o primeiro elemento da coleção. |
| T [TryGetFirst](./trygetfirst/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, const [Func](../system/func/)\<T, **bool**\>\&, **bool**\&) | Tenta obter o primeiro elemento da coleção que satisfaça a função predicado. |
| T [TryGetLast](./trygetlast/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, **bool**\&) | Tenta obter o último elemento da coleção. |

## Typedefs

| Typedef | Descrição |
| --- | --- |
| [has_operator_equals](./has_operator_equals/) | Typedef fictício para verificar a existência do operador ==. |