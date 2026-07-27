---
title: Sequence
second_title: Referência da API Aspose.Slides para C++
description: Representa sequência (coleção de efeitos).
type: docs
weight: 560
url: /pt/aspose.slides.animation/sequence/
---
## Sequence classe

Representa sequência (coleção de efeitos).

```cpp
class Sequence : public Aspose::Slides::Animation::ISequence
```

## Métodos

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffect](../ieffect/)\> [AddEffect](./addeffect/)([System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\>, [EffectType](../effecttype/), [EffectSubtype](../effectsubtype/), [EffectTriggerType](../effecttriggertype/)) override | Adiciona novo efeito ao final da sequência. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffect](../ieffect/)\> [AddEffect](./addeffect/)([System::SharedPtr](../../system/sharedptr/)\<[IParagraph](../../aspose.slides/iparagraph/)\>, [EffectType](../effecttype/), [EffectSubtype](../effectsubtype/), [EffectTriggerType](../effecttriggertype/)) override | Adiciona novo efeito de animação para parágrafo ao final da sequência. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffect](../ieffect/)\> [AddEffect](./addeffect/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../aspose.slides.charts/ichart/)\>, [EffectChartMajorGroupingType](../effectchartmajorgroupingtype/), **int32_t**, [EffectType](../effecttype/), [EffectSubtype](../effectsubtype/), [EffectTriggerType](../effecttriggertype/)) override | Adiciona o novo efeito de animação de gráfico para categoria ou série ao final da sequência. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffect](../ieffect/)\> [AddEffect](./addeffect/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../aspose.slides.charts/ichart/)\>, [EffectChartMinorGroupingType](../effectchartminorgroupingtype/), **int32_t**, **int32_t**, [EffectType](../effecttype/), [EffectSubtype](../effectsubtype/), [EffectTriggerType](../effecttriggertype/)) override | Adiciona o novo efeito de animação de gráfico para elementos em categoria ou série ao final da sequência. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | Obtém iterador apontando para o primeiro elemento (se houver) da coleção. Este iterador não pode ser usado para alterar um objeto referenciado porque [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) retorna uma cópia do objeto T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | Obtém iterador apontando para o primeiro elemento (se houver) da instância da coleção qualificada como const. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | Obtém iterador apontando para o primeiro elemento qualificado como const (se houver) da coleção. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | Obtém iterador apontando logo após o último elemento qualificado como const (se houver) da coleção. |
| void [Clear](./clear/)() override | Remove todos os efeitos de uma coleção. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | Obtém iterador apontando logo após o último elemento (se houver) da coleção. Este iterador não pode ser usado para alterar um objeto referenciado porque [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) retorna uma cópia do objeto T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | Obtém iterador apontando logo após o último elemento (se houver) da instância da coleção qualificada como const. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos do tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos do tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante ao estilo C# onde dois NaN são considerados iguais, embora segundo IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante ao estilo C# onde dois NaN são considerados iguais, embora segundo IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| **int32_t** [get_Count](./get_count/)() override | Retorna o número de efeitos em uma sequência. Somente leitura **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [get_TriggerShape](./get_triggershape/)() override | Retorna o alvo de forma para sequência INTERACTIVE. Se a sequência não for interativa, retorna nulo. Ler [IShape](../../aspose.slides/ishape/). |
| **int32_t** [GetCount](./getcount/)([System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\>) override | Retorna a contagem de efeitos para a forma especificada. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IEffect](../ieffect/)\>\> [GetEffectsByParagraph](./geteffectsbyparagraph/)([System::SharedPtr](../../system/sharedptr/)\<[IParagraph](../../aspose.slides/iparagraph/)\>) override | Retorna um array de efeitos para o parágrafo especificado. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IEffect](../ieffect/)\>\> [GetEffectsByShape](./geteffectsbyshape/)([System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\>) override | Retorna um array de efeitos para a forma especificada. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[System::SharedPtr](../../system/sharedptr/)\<[IEffect](../ieffect/)\>\>\> [GetEnumerator](./getenumerator/)() override | Retorna um enumerador que itera através da coleção. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffect](../ieffect/)\> [idx_get](./idx_get/)(**int32_t**) override | Retorna um efeito no índice especificado. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Aplica uma função acumuladora sobre uma sequência. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | Determina se todos os elementos de uma sequência satisfazem uma condição. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Determina se uma sequência contém algum elemento. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | Determina se algum elemento de uma sequência existe ou satisfaz uma condição. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | Calcula a média de uma sequência de valores numéricos. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Calcula a média de uma sequência de valores obtidos ao invocar uma função de transformação em cada elemento da sequência de entrada. |
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
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Ordena os elementos de uma sequência em ordem crescente de acordo com os valores de chave selecionados por keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Ordena os elementos de uma sequência em ordem decrescente de acordo com os valores de chave selecionados por keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | Inverte a ordem dos elementos em uma sequência. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Transforma elementos de uma sequência. |
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
|  [Object](../../system/object/object/)() | Cria objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a construção de cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a construção de cópia de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| void [Remove](./remove/)([System::SharedPtr](../../system/sharedptr/)\<[IEffect](../ieffect/)\>) override | Remove o efeito especificado de uma coleção. |
| void [RemoveAt](./removeat/)(**int32_t**) override | Remove um efeito de uma coleção. |
| void [RemoveByShape](./removebyshape/)([System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\>) override | Remove o efeito da forma especificada. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhado pelo valor especificado. |
| void [set_TriggerShape](./set_triggershape/)([System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\>) override | Define o alvo da forma para sequência INTERACTIVE. Se a sequência não for interativa, retorna nulo. Escreva [IShape](../../aspose.slides/ishape/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de template como ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhado. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhado. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhado. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../../system.collections.generic/ienumerable/virtualizebeginconstiterator/)() const | Obtém a implementação do iterador begin const para o contêiner atual. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../../system.collections.generic/ienumerable/virtualizebeginiterator/)() | Obtém a implementação do iterador begin para o contêiner atual. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../../system.collections.generic/ienumerable/virtualizeendconstiterator/)() const | Obtém a implementação do iterador end const para o contêiner atual. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../../system.collections.generic/ienumerable/virtualizeenditerator/)() | Obtém a implementação do iterador end para o contêiner atual. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Veja Também

* Classe [ISequence](../isequence/)
* Espaço de nomes [Aspose::Slides::Animation](../)
* Biblioteca [Aspose.Slides](../../)