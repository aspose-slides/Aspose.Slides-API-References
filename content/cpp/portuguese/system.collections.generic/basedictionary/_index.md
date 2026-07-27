---
title: BaseDictionary
second_title: Referência da API Aspose.Slides para C++
description: "Implementa código comum para várias estruturas de dados semelhantes a dicionários (por exemplo, Dictionary, SortedDictionary). Não deve ser usado diretamente, exceto por herança ao definir contêineres. Objetos desta classe devem ser alocados apenas usando a função System::MakeObject(). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros em tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro System::SmartPtr e use esse ponteiro ao passá-lo para funções como argumento."
type: docs
weight: 53
url: /pt/system.collections.generic/basedictionary/
---
## BaseDictionary classe

Implementa código comum para várias estruturas de dados semelhantes a dicionário (e. g. [Dictionary](../dictionary/), [SortedDictionary](../sorteddictionary/)). Não deve ser usado diretamente, exceto por herança ao definir contêineres. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros em tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento.

```cpp
template<typename Map>class BaseDictionary : public System::Collections::Generic::IDictionary<Map::key_type, Map::mapped_type>
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Map | Tipo de mapa subjacente. |

## Métodos

| Método | Descrição |
| --- | --- |
| void [_add_range](./_add_range/)(std::initializer_list\<typename Map::value_type\>) | Específico de C++. |
| void [Add](./add/)(const key_t\&, const mapped_t\&) override | Adiciona par chave-valor ao dicionário. |
| [BaseDictionary](./basedictionary/)() | Cria estrutura de dados vazia. |
| [BaseDictionary](./basedictionary/)(int, const Args\&...) | Construtor de encaminhamento para repassar argumentos ao construtor do mapa subjacente. |
| [BaseDictionary](./basedictionary/)([BaseType](./basetype/) *, const Args\&...) | Construtor de cópia. |
| [BaseDictionary](./basedictionary/)([BaseType](./basetype/) *) | Construtor de cópia. |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | Retorna um iterador para o wrapper KVPair do elemento chave-valor do contêiner. Implementado no estilo C# – o iterador deve retornar o objeto KVPair com as interfaces get_Key() e get_Value(). Se o contêiner estiver vazio, o iterador retornado será igual a [end()](../ienumerable/end/). |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | Obtém um iterador apontando para o primeiro elemento (se houver) da coleção. Este iterador não pode ser usado para alterar o objeto referenciado porque [GetEnumerator()](../ienumerable/getenumerator/) retorna um objeto cópia de T. |
| stl_const_iterator [cbegin](./cbegin/)() const | Retorna um iterador para o primeiro elemento do contêiner. Implementado no estilo STL. Se o contêiner estiver vazio, o iterador retornado será igual a [end()](../ienumerable/end/). |
| stl_const_iterator [cend](./cend/)() const | Retorna um iterador para o elemento que segue o último elemento do contêiner. Implementado no estilo STL. Este elemento funciona como um placeholder; tentar acessá-lo resulta em comportamento indefinido. |
| void [Clear](./clear/)() override | Exclui todos os elementos. |
| **bool** [ContainsKey](./containskey/)(const key_t\&) const override | Verifica se a chave está presente no dicionário. |
| **bool** [ContainsValue](./containsvalue/)(const mapped_t\&) | Verifica se o valor está presente no dicionário. Usa o operador == para comparar valores. |
| void [CopyTo](../idictionary/copyto/)([ArrayPtr](../../system/arrayptr/)\<[KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\>, int) override | Copia o conteúdo do dicionário para elementos de array existentes. |
| Map\& [data](./data/)() | Acessador de armazenamento de dados subjacente. |
| const Map\& [data](./data/)() const | Acessador de armazenamento de dados subjacente. |
| [const_iterator](./const_iterator/) [end](./end/)() const | Retorna um iterador para o wrapper KVPair do elemento chave-valor que segue o último elemento do contêiner. Implementado no estilo C# – o iterador deve retornar o objeto KVPair com as interfaces get_Key() e get_Value(). Este elemento funciona como um placeholder; tentar acessá-lo resulta em comportamento indefinido. |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | Obtém um iterador apontando logo após o último elemento (se houver) da coleção. Este iterador não pode ser usado para alterar o objeto referenciado porque [GetEnumerator()](../ienumerable/getenumerator/) retorna um objeto cópia de T. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica [Object.Equals](../../system/object/equals/) de C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| **int32_t** [get_Count](./get_count/)() const override | Obtém a contagem de elementos. |
| **bool** [get_IsFixedSize](../idictionary/get_isfixedsize/)() const | Verifica se o tamanho da coleção é fixo. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | Verifica se a coleção é somente leitura. |
| **bool** [get_IsSynchronized](../idictionary/get_issynchronized/)() const | Verifica se o contêiner é seguro para threads. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICollection](../icollection/)\<TKey\>\> [get_Keys](../idictionary/get_keys/)() const | Acessa a coleção de chaves. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | Obtém o objeto através do qual a coleção está sendo sincronizada. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICollection](../icollection/)\<TValue\>\> [get_Values](../idictionary/get_values/)() const | Acessa a coleção de valores. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<[KeyValuePair](../keyvaluepair/)\<key_t, mapped_t\>\>\> [GetEnumerator](./getenumerator/)() | Cria instância de enumerador, deve ser implementada pela subclasse. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método [Object.GetHashCode()](../../system/object/gethashcode/) de C#. Permite hash de objetos customizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada [System.Object.GetType()](../../system/object/gettype/) de C#. |
| mapped_t [GetValueOrDefault](./getvalueordefault/)(const key_t\&) const override | Retorna o valor se encontrado; ou **Value()** caso contrário. |
| mapped_t [GetValueOrDefault](./getvalueordefault/)(const key_t\&, const mapped_t\&) const override | Retorna o valor se encontrado; ou **defaultValue** caso contrário. |
| mapped_t [GetValueOrNull](./getvalueornull/)(const key_t\&) const override | Retorna o valor se encontrado; ou **null** caso contrário. Faz sentido apenas para tipos de referência. |
| [ICollection](../icollection/icollection/)() | Construtor padrão. |
| [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | Construtor de cópia. |
| [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | Construtor de movimento. |
| mapped_t [idx_get](./idx_get/)(const key_t\&) const override | Função getter indexada. |
| void [idx_set](./idx_set/)(const key_t\&, mapped_t) override | Função setter indexada. Altera ou cria elemento. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador 'is' de C#. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Aplica uma função acumuladora sobre uma sequência. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | Determina se todos os elementos de uma sequência satisfazem uma condição. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Determina se uma sequência contém algum elemento. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | Determina se algum elemento de uma sequência existe ou satisfaz uma condição. |
| T [LINQ_Average](../ienumerable/linq_average/)() | Calcula a média de uma sequência de valores numéricos. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Calcula a média de uma sequência de valores obtidos ao invocar uma função de transformação em cada elemento da sequência de entrada. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | Converte os elementos para o tipo especificado. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | Concatena duas sequências. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | Determina se uma sequência contém um valor especificado. |
| int [LINQ_Count](../ienumerable/linq_count/)() | Retorna o número de elementos na sequência (calculado via contagem direta). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Retorna o número de elementos na sequência que satisfazem a condição especificada. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | Retorna o elemento em um índice especificado em uma sequência. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | Retorna o elemento em um índice especificado em uma sequência. |
| T [LINQ_First](../ienumerable/linq_first/)() | Retorna o primeiro elemento de uma sequência. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Retorna o primeiro elemento de uma sequência que satisfaz a condição especificada. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | Retorna o primeiro elemento de uma sequência, ou um valor padrão se a sequência estiver vazia. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Retorna o primeiro elemento da sequência que satisfaz uma condição ou um valor padrão se nenhum elemento for encontrado. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Agrupa os elementos de uma sequência. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Agrupa os elementos de uma sequência. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | Retorna o último elemento de uma sequência. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | Retorna o último elemento de uma sequência, ou um valor padrão se a sequência estiver vazia. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Invoca uma função de transformação em cada elemento de uma sequência genérica e retorna o valor máximo resultante. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Invoca uma função de transformação em cada elemento de uma sequência genérica e retorna o valor mínimo resultante. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | Filtra os elementos da sequência com base no tipo especificado. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Ordena os elementos de uma sequência em ordem crescente de acordo com os valores de chave selecionados por keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Ordena os elementos de uma sequência em ordem decrescente de acordo com os valores de chave selecionados por keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | Inverte a ordem dos elementos em uma sequência. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Transforma os elementos de uma sequência. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Transforma cada elemento de uma sequência em uma nova forma incorporando o índice do elemento. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | Projeta cada elemento de uma sequência e combina as sequências resultantes em uma única sequência. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | Ignora um número especificado de elementos contíguos do início de uma sequência e retorna o restante. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | Retorna um número especificado de elementos contíguos do início de uma sequência. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | Cria um array a partir de uma sequência. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | Cria uma List<T> a partir de uma sequência. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | Filtra uma sequência com base no predicado especificado. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método [Object.MemberwiseClone()](../../system/object/memberwiseclone/) de C#. Permite clonar tipos customizados. |
| [Object](../../system/object/object/)() | Cria objeto. Inicializa todas as estruturas de dados internas. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Não copia nada, realmente; apenas inicializa um novo objeto e permite a construção de cópia em subclasses. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | Operador de atribuição por movimento. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | Operador de atribuição por movimento. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Não copia nada, realmente; apenas inicializa um novo objeto e permite a construção de cópia em subclasses. |
| virtual mapped_t\& [operator[]](./operator[]/)(const key_t\&) | Função de acesso. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| **bool** [Remove](./remove/)(const key_t\&) override | Remove chave específica do dicionário. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada por um valor especificado. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(unsigned int) override |  |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método [Object.ToString()](../../system/object/tostring/) de C#. Permite converter objetos customizados para string. |
| **bool** [TryGetValue](./trygetvalue/)(const key_t\&, mapped_t\&) const override | Procura o valor indexado e o recupera se encontrado. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| System::Details::VirtualizedIteratorBase\<[KVPair](./kvpair/)\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Obtém a implementação do iterador const begin para o contêiner atual. |
| System::Details::VirtualizedIteratorBase\<[KVPair](./kvpair/)\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Obtém a implementação do iterador begin para o contêiner atual. |
| System::Details::VirtualizedIteratorBase\<[KVPair](./kvpair/)\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Obtém a implementação do iterador const end para o contêiner atual. |
| System::Details::VirtualizedIteratorBase\<[KVPair](./kvpair/)\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | Obtém a implementação do iterador end para o contêiner atual. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual  [~ICollection](../icollection/~icollection/)() | Destrutor. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Tipos definidos

| Tipo definido | Descrição |
| --- | --- |
| [map_t](./map_t/) | Tipo de mapa interno. |
| [KeyCollection](./keycollection/) | Certifique-se de usar o alocador correto com o tipo de armazenamento subjacente. |
| [ValueCollection](./valuecollection/) | Coleção de valores. |
| [KVPair](./kvpair/) | Tipo de par chave-valor. |
| [BaseType](./basetype/) | Interface implementada. |
| [iterator](./iterator/) | Tipo de iterador. |
| [const_iterator](./const_iterator/) | Tipo de iterador const. |

## Ver também

* Classe [IDictionary](../idictionary/)
* Namespace [System::Collections::Generic](../)
* Biblioteca [Aspose.Slides](../../)