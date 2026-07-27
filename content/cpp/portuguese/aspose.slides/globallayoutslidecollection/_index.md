---
title: GlobalLayoutSlideCollection
second_title: Referência da API Aspose.Slides para C++
description: Representa uma coleção de todos os slides de layout em uma apresentação. Estende a classe LayoutSlideCollection com métodos para adicionar/clonar slides de layout no contexto de unir as coleções individuais de slides de layout mestre.
type: docs
weight: 1093
url: /pt/aspose.slides/globallayoutslidecollection/
---
## GlobalLayoutSlideCollection classe

Representa uma coleção de todos os slides de layout em uma apresentação. Estende a classe [LayoutSlideCollection](../layoutslidecollection/) com métodos para adicionar/clonar slides de layout no contexto de união das coleções individuais de slides de layout mestre.

```cpp
class GlobalLayoutSlideCollection : public Aspose::Slides::LayoutSlideCollection,
                                    public Aspose::Slides::IGlobalLayoutSlideCollection
```


## Métodos

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\> [Add](./add/)([System::SharedPtr](../../system/sharedptr/)\<[IMasterSlide](../imasterslide/)\>, [SlideLayoutType](../slidelayouttype/), [System::String](../../system/string/)) override | Adiciona um novo slide de layout à apresentação. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\> [AddClone](./addclone/)([System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\>) override | Adiciona uma cópia de um slide de layout especificado à apresentação. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\> [AddClone](./addclone/)([System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlide](../imasterslide/)\>) override | Adiciona uma cópia de um slide de layout especificado à apresentação. |
| [iterator](../layoutslidecollection/iterator/) [begin](../layoutslidecollection/begin/)() | Obtém um iterador apontando para o primeiro elemento (se houver) da coleção. |
| [const_iterator](../layoutslidecollection/const_iterator/) [begin](../layoutslidecollection/begin/)() const | Obtém um iterador apontando para o primeiro elemento (se houver) da instância da coleção qualificada como const. |
| [const_iterator](../layoutslidecollection/const_iterator/) [cbegin](../layoutslidecollection/cbegin/)() const | Obtém um iterador apontando para o primeiro elemento qualificado como const (se houver) da coleção. |
| [const_iterator](../layoutslidecollection/const_iterator/) [cend](../layoutslidecollection/cend/)() const | Obtém um iterador apontando logo após o último elemento qualificado como const (se houver) da coleção. |
| void [CopyTo](../layoutslidecollection/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\>\>, **int32_t**) override | Copia todos os elementos da coleção para o array especificado. |
| virtual void [CopyTo](../igenericcollection/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, **int32_t**) | Copia todos os elementos da coleção para o array especificado. |
| [iterator](../layoutslidecollection/iterator/) [end](../layoutslidecollection/end/)() | Obtém um iterador apontando logo após o último elemento (se houver) da coleção. |
| [const_iterator](../layoutslidecollection/const_iterator/) [end](../layoutslidecollection/end/)() const | Obtém um iterador apontando logo após o último elemento (se houver) da instância da coleção qualificada como const. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante no estilo C#, onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não é igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante no estilo C#, onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não é igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| **int32_t** [get_Count](../layoutslidecollection/get_count/)() override | Retorna o número de slides de layout em uma coleção. Somente leitura **int32_t**. |
| **bool** [get_IsSynchronized](../layoutslidecollection/get_issynchronized/)() override | Retorna um valor que indica se o acesso à coleção é sincronizado (thread-safe). Somente leitura **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_SyncRoot](../layoutslidecollection/get_syncroot/)() override | Retorna uma raiz de sincronização. Somente leitura [System::Object](../../system/object/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\> [GetByType](../layoutslidecollection/getbytype/)([SlideLayoutType](../slidelayouttype/)) override | Retorna o primeiro slide de layout do tipo especificado. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\>\>\> [GetEnumerator](../layoutslidecollection/getenumerator/)() override | Retorna um enumerador que itera pela coleção. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\> [idx_get](../layoutslidecollection/idx_get/)(**int32_t**) override | Retorna o slide de layout pelo índice. Somente leitura [LayoutSlide](../layoutslide/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Aplica uma função acumuladora sobre uma sequência. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | Determina se todos os elementos de uma sequência satisfazem uma condição. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Determina se uma sequência contém algum elemento. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | Determina se existe algum elemento em uma sequência ou se algum satisfaz uma condição. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | Computa a média de uma sequência de valores numéricos. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Computa a média de uma sequência de valores obtidos invocando uma função de transformação em cada elemento da sequência de entrada. |
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
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Retorna o primeiro elemento da sequência que satisfaça uma condição ou um valor padrão se nenhum elemento for encontrado. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Agrupa os elementos de uma sequência. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Agrupa os elementos de uma sequência. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | Retorna o último elemento de uma sequência. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | Retorna o último elemento de uma sequência, ou um valor padrão se a sequência estiver vazia. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Invoca uma função de transformação em cada elemento de uma sequência genérica e retorna o maior valor resultante. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Invoca uma função de transformação em cada elemento de uma sequência genérica e retorna o menor valor resultante. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | Filtra os elementos da sequência com base no tipo especificado. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Ordena os elementos de uma sequência em ordem crescente de acordo com os valores de chave selecionados por keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Ordena os elementos de uma sequência em ordem decrescente de acordo com os valores de chave selecionados por keySelector. |
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
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | Cria um List<T> a partir de uma sequência. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | Filtra uma sequência com base no predicado especificado. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a cópia de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| void [Remove](../layoutslidecollection/remove/)([System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\>) override | Remove um layout da coleção. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [RemoveUnused](../layoutslidecollection/removeunused/)() override | Remove slides de layout não utilizados (slides de layout cujo HasDependingSlides é false). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de template como um ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa o construto C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| [virtualized_iterator](../layoutslidecollection/virtualized_iterator/) * [virtualizeBeginConstIterator](../layoutslidecollection/virtualizebeginconstiterator/)() const override | Obtém um iterador apontando para o primeiro elemento (se houver) da instância da coleção qualificada como const. |
| [virtualized_iterator](../layoutslidecollection/virtualized_iterator/) * [virtualizeBeginIterator](../layoutslidecollection/virtualizebeginiterator/)() override | Obtém um iterador apontando para o primeiro elemento (se houver) da coleção. |
| [virtualized_iterator](../layoutslidecollection/virtualized_iterator/) * [virtualizeEndConstIterator](../layoutslidecollection/virtualizeendconstiterator/)() const override | Obtém um iterador apontando logo após o último elemento (se houver) da instância da coleção qualificada como const. |
| [virtualized_iterator](../layoutslidecollection/virtualized_iterator/) * [virtualizeEndIterator](../layoutslidecollection/virtualizeenditerator/)() override | Obtém um iterador apontando logo após o último elemento (se houver) da coleção. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Veja Também

* Classe [LayoutSlideCollection](../layoutslidecollection/)
* Classe [IGlobalLayoutSlideCollection](../igloballayoutslidecollection/)
* Espaço de nomes [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)