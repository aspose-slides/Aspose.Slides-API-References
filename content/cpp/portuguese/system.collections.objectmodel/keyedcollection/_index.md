---
title: KeyedCollection
second_title: Referência da API Aspose.Slides para C++
description: "Coleção abstrata de elementos com chaves incorporadas. Objetos desta classe devem ser alocados apenas usando a função System::MakeObject(). Nunca crie instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro System::SmartPtr e use esse ponteiro para passá-lo a funções como argumento."
type: docs
weight: 14
url: /pt/system.collections.objectmodel/keyedcollection/
---
## KeyedCollection classe

Coleta abstracta de elementos com chaves incorporadas. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento.

```cpp
template<typename TKey,typename TItem>class KeyedCollection : public System::Collections::ObjectModel::Collection<TItem>
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| TKey | Key type. |
| TItem | value type. |
## Métodos

| Método | Descrição |
| --- | --- |
| void [Add](./add/)(const TItem\&) override | Adiciona item ao final do contêiner. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | Obtém um iterador apontando para o primeiro elemento (se houver) da coleção. Este iterador não pode ser usado para alterar um objeto referenciado porque [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) retorna um objeto-cópia de T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | Obtém um iterador apontando para o primeiro elemento (se houver) da instância da coleção qualificada como const. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | Obtém um iterador apontando para o primeiro elemento qualificado como const (se houver) da coleção. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | Obtém um iterador apontando logo após o último elemento qualificado como const (se houver) da coleção. |
| void [Clear](../collection/clear/)() override | Exclui todos os elementos. |
| [Collection](../collection/collection/)() | Cria uma coleção vazia. |
| [Collection](../collection/collection/)([SharedPtr](../../system/sharedptr/)\<[Generic::IList](../../system.collections.generic/ilist/)\<T\>\>) |  |
| **bool** [Contains](./contains/)(TKey) | Verifica se a chave está presente no contêiner. |
| **bool** [Contains](../collection/contains/)(const T\&) const override | Verifica se o item está presente na coleção. |
| void [CopyTo](../collection/copyto/)([ArrayPtr](../../system/arrayptr/)\<T\>, int) override | Copia os elementos da coleção para elementos de array existentes. |
| [const_reverse_iterator](../collection/const_reverse_iterator/) [crbegin](../collection/crbegin/)() const | Obtém um iterador reverso para o último elemento qualificado como const da coleção (primeiro em reverso). |
| [const_reverse_iterator](../collection/const_reverse_iterator/) [crend](../collection/crend/)() const | Obtém um iterador reverso para um elemento não-existente qualificado como const antes do início da coleção. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | Obtém um iterador apontando logo após o último elemento (se houver) da coleção. Este iterador não pode ser usado para alterar um objeto referenciado porque [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) retorna um objeto-cópia de T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | Obtém um iterador apontando logo após o último elemento (se houver) da instância da coleção qualificada como const. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação em ponto flutuante ao estilo C# onde dois NaNs são considerados iguais embora, conforme IEC 60559:1989, NaN não seja igual a nenhum valor, inclusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação em ponto flutuante ao estilo C# onde dois NaNs são considerados iguais embora, conforme IEC 60559:1989, NaN não seja igual a nenhum valor, inclusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEqualityComparer](../../system.collections.generic/iequalitycomparer/)\<TKey\>\> [get_Comparer](./get_comparer/)() | Obtém comparador. |
| int [get_Count](../collection/get_count/)() const override | Obtém o número de elementos. |
| **bool** [get_IsFixedSize](../../system.collections.generic/ilist/get_isfixedsize/)() | Verifica se a coleção tem tamanho fixo. |
| virtual **bool** [get_IsReadOnly](../../system.collections.generic/icollection/get_isreadonly/)() const | Verifica se a coleção é somente leitura. |
| [SharedPtr](../../system/sharedptr/)\<[Generic::IList](../../system.collections.generic/ilist/)\<T\>\> [get_Items](../collection/get_items/)() | Acessador da estrutura de dados interna. |
| const [Generic::ListPtr](../../system.collections.generic/listptr/)\<T\> [get_Items](../collection/get_items/)() const | Acessador da estrutura de dados interna. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | Obtém o objeto através do qual a coleção está sendo sincronizada. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados contador de referência associada ao objeto. |
| [SharedPtr](../../system/sharedptr/)\<[Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<T\>\> [GetEnumerator](../collection/getenumerator/)() override | Obtém enumerador para iterar pela coleção. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| [ICollection](../../system.collections.generic/icollection/icollection/)() | Construtor padrão. |
| [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Construtor de cópia. |
| [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)\&&) | Construtor de movimento. |
| TItem [idx_get](./idx_get/)(TKey) | Obtém item em índice específico. |
| T [idx_get](../collection/idx_get/)(int) const override | Obtém valor no índice especificado. |
| void [idx_set](../collection/idx_set/)(int, T) override | Define valor no índice especificado. |
| int [IndexOf](../collection/indexof/)(const T\&) const override | Procura elemento na coleção. |
| void [Insert](../collection/insert/)(int, const T\&) override | Insere item na posição especificada. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Aplica uma função acumuladora sobre uma sequência. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | Determina se todos os elementos de uma sequência satisfazem uma condição. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Determina se uma sequência contém algum elemento. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | Determina se algum elemento de uma sequência existe ou satisfaz uma condição. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | Computa a média de uma sequência de valores numéricos. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Computa a média de uma sequência de valores obtidos ao invocar uma função de transformação em cada elemento da sequência de entrada. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | Converte os elementos para o tipo especificado. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | Concatena duas sequências. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | Determina se uma sequência contém um valor especificado. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | Retorna o número de elementos na sequência (calculado por contagem direta). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Retorna o número de elementos na sequência que satisfazem a condição especificada. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | Retorna o elemento em um índice especificado em uma sequência. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | Retorna o elemento em um índice especificado em uma sequência. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | Retorna o primeiro elemento de uma sequência. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Retorna o primeiro elemento de uma sequência que satisfaça a condição especificada. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | Retorna o primeiro elemento de uma sequência, ou um valor padrão se a sequência estiver vazia. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Retorna o primeiro elemento da sequência que satisfaz uma condição ou um valor padrão se nenhum elemento for encontrado. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Agrupa os elementos de uma sequência. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Agrupa os elementos de uma sequência. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | Retorna o último elemento de uma sequência. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | Retorna o último elemento de uma sequência, ou um valor padrão se a sequência estiver vazia. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Invoca uma função de transformação em cada elemento de uma sequência genérica e retorna o valor máximo resultante. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Invoca uma função de transformação em cada elemento de uma sequência genérica e retorna o valor mínimo resultante. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | Filtra os elementos da sequência com base no tipo especificado. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Ordena os elementos de uma sequência em ordem ascendente de acordo com os valores de chave selecionados por keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Ordena os elementos de uma sequência em ordem descendente de acordo com os valores de chave selecionados por keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | Inverte a ordem dos elementos em uma sequência. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Transforma os elementos de uma sequência. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Transforma cada elemento de uma sequência em uma nova forma incorporando o índice do elemento. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | Projeta cada elemento de uma sequência e combina as sequências resultantes em uma única sequência. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | Ignora um número especificado de elementos contíguos do início de uma sequência e retorna o restante. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | Retorna um número especificado de elementos contíguos do início de uma sequência. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | Cria um array a partir de uma sequência. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | Cria uma List<T> a partir de uma sequência. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | Filtra uma sequência com base no predicado especificado. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
| [Object](../../system/object/object/)() | Cria objeto. Inicializa todas as estruturas de dados internas. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa novo objeto e permite a cópia ao construir subclasses. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)\&&) | Operador de atribuição por movimento. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Operador de atribuição por movimento. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa novo objeto e permite a cópia ao construir subclasses. |
| T\& [operator[]](../collection/operator[]/)(int) | Obtém valor no índice especificado. |
| const T\& [operator[]](../collection/operator[]/)(int) const | Obtém valor no índice especificado. |
| [reverse_iterator](../collection/reverse_iterator/) [rbegin](../collection/rbegin/)() | Obtém um iterador reverso para o último elemento da coleção (primeiro em reverso). |
| [const_reverse_iterator](../collection/const_reverse_iterator/) [rbegin](../collection/rbegin/)() const | Obtém um iterador reverso para o último elemento da coleção qualificada como const (primeiro em reverso). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| **bool** [Remove](./remove/)(TKey) | Remove chave do contêiner. |
| **bool** [Remove](../collection/remove/)(const T\&) override | Remove item específico. |
| void [RemoveAt](../collection/removeat/)(int) override | Remove item em posição específica. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| [reverse_iterator](../collection/reverse_iterator/) [rend](../collection/rend/)() | Obtém um iterador reverso para um elemento inexistente antes do início da coleção. |
| [const_reverse_iterator](../collection/const_reverse_iterator/) [rend](../collection/rend/)() const | Obtém um iterador reverso para um elemento inexistente antes do início da coleção qualificada como const. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Faz com que argumento de modelo específico seja tratado como ponteiro fraco em vez de ponteiro compartilhado (se aplicável). |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamada diretamente; use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamada diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](../collection/virtualizebeginconstiterator/)() const override | Obtém a implementação do iterador const begin para o contêiner atual. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](../collection/virtualizebeginiterator/)() override | Obtém a implementação do iterador begin para o contêiner atual. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](../collection/virtualizeendconstiterator/)() const override | Obtém a implementação do iterador const end para o contêiner atual. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](../collection/virtualizeenditerator/)() override | Obtém a implementação do iterador end para o contêiner atual. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamada diretamente; use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamada diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual [~ICollection](../../system.collections.generic/icollection/~icollection/)() | Destrutor. |
| virtual [~Object](../../system/object/~object/)() | Destrói o objeto. Libera todas as estruturas de dados internas. |
## Campos

| Campo | Descrição |
| --- | --- |
| static [defaultThreshold](./defaultthreshold/) | Limite de criação de dicionário de pesquisa, padrão. |
## Ver também

* Classe [Collection](../collection/)
* Namespace [System::Collections::ObjectModel](../)
* Library [Aspose.Slides](../../)