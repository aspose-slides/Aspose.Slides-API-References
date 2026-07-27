---
title: List
second_title: Referência da API Aspose.Slides para C++
description: Declaração antecipada da List.
type: docs
weight: 430
url: /pt/system.collections.generic/list/
---
## Classe List


[List](./) declaração antecipada.

```cpp
template<typename T>class List : public virtual System::Object,
                                 public System::Collections::Generic::IList<T>
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo do elemento. |
## Métodos

| Método | Descrição |
| --- | --- |
| void [_add_range](./_add_range/)(std::initializer_list\<T\>) | Específico C++. |
| void [Add](./add/)(const T\&) override | Adiciona elemento ao final da lista. |
| void [AddInitializer](./addinitializer/)(int, const T *) | Adiciona elementos à lista; usado ao traduzir inicializadores. |
| void [AddRange](./addrange/)([IEnumerablePtr](./ienumerableptr/)) | Adiciona todos os elementos de uma coleção (ou dela mesma) ao final da lista atual. |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](./asreadonly/)() | Obtém referência somente-leitura a esta coleção. |
| [iterator](../ienumerable/iterator/) [begin](./begin/)() | Obtém iterador para o primeiro elemento da coleção. |
| [const_iterator](../ienumerable/const_iterator/) [begin](./begin/)() const | Obtém iterador para o primeiro elemento da coleção qualificada como const. |
| int [BinarySearch](./binarysearch/)(const T\&) const | Procura item em uma lista ordenada. |
| int [BinarySearch](./binarysearch/)(const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | Procura item em uma lista ordenada. |
| int [BinarySearch](./binarysearch/)(int, int, const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | Procura item em uma lista ordenada. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](./cbegin/)() const | Obtém iterador para o primeiro elemento qualificado como const da coleção. |
| [const_iterator](../ienumerable/const_iterator/) [cend](./cend/)() const | Obtém iterador para um elemento const inexistente atrás do fim da coleção. |
| void [Clear](./clear/)() override | Exclui todos os elementos. |
| **bool** [Contains](./contains/)(const T\&) const override | Verifica se o item está presente na lista. |
| [SharedPtr](../../system/sharedptr/)\<[List](./)\<OutputType\>\> [ConvertAll](./convertall/)([Converter](../../system/converter/)\<T, OutputType\>) | Cria uma lista de elementos convertidos para um tipo diferente. |
| void [CopyTo](./copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) override | Copia elementos da lista para elementos existentes de um array. |
| void [CopyTo](./copyto/)(const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&) | Copia todos os elementos para elementos existentes de um array. |
| void [CopyTo](./copyto/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&, int, int) | Copia elementos a partir do índice especificado para elementos existentes de um array. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | Obtém um iterador reverso para o último elemento qualificado como const da coleção (primeiro em ordem reversa). |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | Obtém um iterador reverso para um elemento const inexistente antes do início da coleção. |
| [vector_t](./vector_t/)\& [data](./data/)() | Função de acesso à estrutura de dados subjacente. |
| const [vector_t](./vector_t/)\& [data](./data/)() const | Função de acesso à estrutura de dados subjacente. |
| [iterator](../ienumerable/iterator/) [end](./end/)() | Obtém iterador para um elemento inexistente atrás do fim da coleção. |
| [const_iterator](../ienumerable/const_iterator/) [end](./end/)() const | Obtém iterador para um elemento inexistente atrás do fim da coleção qualificada como const. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora segundo IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora segundo IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN. |
| **bool** [Exists](./exists/)([System::Predicate](../../system/predicate/)\<T\>) | Verifica se existe elemento que satisfaz o predicado especificado na lista. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| T [Find](./find/)([System::Predicate](../../system/predicate/)\<T\>) | Procura elemento que satisfaz predicado específico. |
| [ListPtr](../listptr/)\<T\> [FindAll](./findall/)([System::Predicate](../../system/predicate/)\<T\>) | Procura elementos que satisfazem predicado específico. |
| int [FindIndex](./findindex/)([System::Predicate](../../system/predicate/)\<T\>) | Procura elemento que satisfaz predicado específico. |
| int [FindIndex](./findindex/)(int, [System::Predicate](../../system/predicate/)\<T\>) | Procura elemento que satisfaz predicado específico. |
| int [FindIndex](./findindex/)(int, int, [System::Predicate](../../system/predicate/)\<T\>) | Procura elemento que satisfaz predicado específico. |
| T [FindLast](./findlast/)([System::Predicate](../../system/predicate/)\<T\>) | Procura o último elemento que satisfaz predicado específico. |
| void [ForEach](./foreach/)([System::Action](../../system/action/)\<T\>) | Aplica ação a todos os elementos da lista. |
| int [get_Capacity](./get_capacity/)() const | Obtém a capacidade atual da lista. |
| int [get_Count](./get_count/)() const override | Obtém o número de elementos na lista atual. |
| **bool** [get_IsFixedSize](../ilist/get_isfixedsize/)() | Verifica se a coleção tem tamanho fixo. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | Verifica se a coleção é somente-leitura. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | Obtém o objeto pelo qual a coleção está sendo sincronizada. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referências associada ao objeto. |
| [IEnumeratorPtr](./ienumeratorptr/) [GetEnumerator](./getenumerator/)() override | Obtém enumerador para iterar pelos elementos da lista. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| **ThisPtr** [GetRange](./getrange/)(int, int) | Cria uma fatia da lista. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
|  [ICollection](../icollection/icollection/)() | Construtor padrão. |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | Construtor de cópia. |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | Construtor de movimento. |
| T [idx_get](./idx_get/)(int) const override | Obtém elemento na posição especificada. |
| void [idx_set](./idx_set/)(int, T) override | Define elemento na posição especificada. |
| int [IndexOf](./indexof/)(const T\&) const override | Obtém o primeiro índice de um item específico. |
| int [IndexOf](./indexof/)(const T\&, int) const | Procura item específico na lista. |
| void [Insert](./insert/)(int, const T\&) override | Insere item na posição especificada. |
| void [InsertRange](./insertrange/)(int, [IEnumerablePtr](./ienumerableptr/)) | Insere intervalo de dados na posição especificada. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&) const | Procura o objeto especificado e devolve o índice base-zero da última ocorrência em toda a lista. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&, **int32_t**) const | Procura o objeto especificado e devolve o índice base-zero da última ocorrência no intervalo de elementos em [List](./) que se estende do primeiro elemento até o índice especificado. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&, **int32_t**, **int32_t**) const | Procura o objeto especificado e devolve o índice base-zero da última ocorrência no intervalo de elementos em [List](./) que contém o número especificado de elementos e termina no índice especificado. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Aplica uma função acumuladora sobre uma sequência. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | Determina se todos os elementos de uma sequência satisfazem uma condição. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Determina se uma sequência contém algum elemento. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | Determina se existe algum elemento em uma sequência ou se ele satisfaz uma condição. |
| T [LINQ_Average](../ienumerable/linq_average/)() | Calcula a média de uma sequência de valores numéricos. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Calcula a média de uma sequência de valores obtidos ao invocar uma função de transformação em cada elemento da sequência de entrada. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | Converte os elementos para o tipo especificado. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | Concatena duas sequências. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | Determina se uma sequência contém o valor especificado. |
| int [LINQ_Count](../ienumerable/linq_count/)() | Retorna o número de elementos na sequência (calculado via contagem direta). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Retorna o número de elementos na sequência que satisfazem a condição especificada. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | Retorna o elemento em um índice especificado em uma sequência. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | Retorna o elemento em um índice especificado em uma sequência. |
| T [LINQ_First](../ienumerable/linq_first/)() | Retorna o primeiro elemento de uma sequência. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Retorna o primeiro elemento de uma sequência que satisfaz a condição especificada. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | Retorna o primeiro elemento de uma sequência, ou um valor padrão se a sequência estiver vazia. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Retorna o primeiro elemento da sequência que satisfaz uma condição ou um valor padrão se nenhum tal elemento for encontrado. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Agrupa os elementos de uma sequência. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Agrupa os elementos de uma sequência. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | Retorna o último elemento de uma sequência. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | Retorna o último elemento de uma sequência, ou um valor padrão se a sequência estiver vazia. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Invoca uma função de transformação em cada elemento de uma sequência genérica e devolve o maior valor resultante. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Invoca uma função de transformação em cada elemento de uma sequência genérica e devolve o menor valor resultante. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | Filtra os elementos da sequência com base no tipo especificado. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Ordena os elementos de uma sequência em ordem ascendente de acordo com os valores de chave selecionados por keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Ordena os elementos de uma sequência em ordem descendente de acordo com os valores de chave selecionados por keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | Inverte a ordem dos elementos em uma sequência. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Transforma os elementos de uma sequência. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Transforma cada elemento de uma sequência em uma nova forma incorporando o índice do elemento. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | Projeta cada elemento de uma sequência e combina as sequências resultantes em uma única sequência. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | Ignora um número especificado de elementos contíguos do início de uma sequência e devolve o restante. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | Devolve um número especificado de elementos contíguos do início de uma sequência. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | Cria um array a partir de uma sequência. |
| [SharedPtr](../../system/sharedptr/)\<[List](./)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | Cria um List<T> a partir de uma sequência. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | Filtra uma sequência com base no predicado especificado. |
|  [List](./list/)() | Cria uma lista vazia. |
|  [List](./list/)(int) | Cria uma lista com capacidade pré-definida. |
|  [List](./list/)([IEnumerablePtr](./ienumerableptr/)) | Construtor de cópia. |
| void [Lock](../../system/object/lock/)() | Implementa a instrução C# lock() para bloqueio. Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Não copia nada, apenas inicializa um novo objeto e permite cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Não copia nada, apenas inicializa um novo objeto e permite cópia de subclasses. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | Operador de atribuição de movimento. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | Operador de atribuição de movimento. |
| vector_t::reference [operator[]](./operator[]/)(int) | Função de acesso. |
| vector_t::const_reference [operator[]](./operator[]/)(int) const | Função de acesso. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | Obtém um iterador reverso para o último elemento da coleção (primeiro em ordem reversa). |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | Obtém um iterador reverso para o último elemento da coleção qualificada como const (primeiro em ordem reversa). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| **bool** [Remove](./remove/)(const T\&) override | Remove a primeira ocorrência de um item específico da lista. |
| int [RemoveAll](./removeall/)([Predicate](../../system/predicate/)\<T\>) | Remove todos os elementos que correspondem ao predicado específico. |
| void [RemoveAt](./removeat/)(int) override | Remove o item na posição especificada. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referências compartilhadas pelo valor especificado. |
| void [RemoveRange](./removerange/)(int, int) | Remove uma fatia da lista. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | Obtém um iterador reverso para um elemento inexistente antes do início da coleção. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | Obtém um iterador reverso para um elemento inexistente antes do início da coleção qualificada como const. |
| void [Reverse](./reverse/)() | Inverte a ordem dos elementos de toda a lista. |
| void [Reverse](./reverse/)(int, int) | Inverte a ordem dos elementos da fatia da lista. |
| void [set_Capacity](./set_capacity/)(int) | Define a capacidade da lista. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em containers para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referências compartilhadas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referências compartilhadas. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e devolve o contador de referências compartilhadas. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| void [Sort](./sort/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | Ordena os elementos da lista. |
| void [Sort](./sort/)() | Ordena os elementos da lista usando o comparador padrão. |
| void [Sort](./sort/)(int, int, [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>) | Ordena a fatia da lista. |
| void [Sort](./sort/)([Comparison](../../system/comparison/)\<T\>, **bool**) | Ordena os elementos da lista. |
| [ArrayPtr](../../system/arrayptr/)\<T\> [ToArray](./toarray/)() const | Converte a lista para array. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados para string. |
| void [TrimExcess](./trimexcess/)() | Ajusta a capacidade da lista para caber ao seu tamanho. |
| **bool** [TrueForAll](./trueforall/)([System::Predicate](../../system/predicate/)\<T\>) | Determina se todos os elementos da coleção correspondem às condições definidas pelo predicado especificado. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa a instrução C# lock() para desbloqueio. Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Obtém a implementação do iterador const begin para o contêiner atual. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Obtém a implementação do iterador begin para o contêiner atual. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Obtém a implementação do iterador const end para o contêiner atual. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | Obtém a implementação do iterador end para o contêiner atual. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referências fracas. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referências fracas. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual  [~ICollection](../icollection/~icollection/)() | Destrutor. |
| virtual  [~Object](../../system/object/~object/)() | Destrói o objeto. Libera todas as estruturas de dados internas. |
## Definições de tipo

| Definição de tipo | Descrição |
| --- | --- |
| [ValueType](./valuetype/) | Este tipo. |
| [BaseType](./basetype/) | Tipo de interface. |
| [vector_t](./vector_t/) | Tipo de dado subjacente. |
| [iterator](./iterator/) | Tipo de iterador. |
| [const_iterator](./const_iterator/) | Tipo de iterador const. |
| [reverse_iterator](./reverse_iterator/) | Tipo de iterador reverso. |
| [const_reverse_iterator](./const_reverse_iterator/) | Tipo de iterador reverso const. |
| [IEnumerablePtr](./ienumerableptr/) | Contêiner que mantém elementos do mesmo tipo que mantemos. |
| [IEnumeratorPtr](./ienumeratorptr/) | **Enumerator** type. |
## Observações


[List](./) - wrapper em torno de std::vector a ser usado em código traduzido. Requer que o operador == seja implementado para o tipo de elemento. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando operator new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-la a funções como argumento.


```cpp
#include <system/collections/list.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // Crie a primeira lista.
  auto list1 = MakeObject<List<int>>();

  // Preencha a primeira lista.
  list1->Add(3);
  list1->Add(1);
  list1->Add(-5);
  list1->Add(8);

  // Ordene a primeira lista.
  // Os itens da primeira lista serão: {-5, 1, 3, 8}
  list1->Sort();

  // Remova o item no índice 2.
  // Os itens da primeira lista serão: {-5, 1, 8}
  list1->RemoveAt(2);

  // Insira o item no índice 1.
  // Os itens da primeira lista serão: {-5, 15, 1, 8}
  list1->Insert(1, 15);

  // Crie a segunda lista.
  auto list2 = MakeObject<List<int>>();

  // Preencha a segunda lista.
  list2->Add(10);
  list2->Add(20);
  list2->Add(30);

  // Anexe elementos da segunda lista à primeira.
  list1->AddRange(list2);

  // Imprima os itens da primeira lista.
  for (const auto item: list1)
  {
    std::cout << item << ' ';
  }

  return 0;
}
/*
Este exemplo de código produz a seguinte saída:
- 5 15 1 8 10 20 30
*/
```

## Veja também

* Classe [Object](../../system/object/)
* Classe [IList](../ilist/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.Slides](../../)