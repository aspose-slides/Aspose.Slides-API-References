---
title: SimpleEnumerator
second_title: Referência da API Aspose.Slides para C++
description: "Classe iteradora para contêineres simples que armazenam elementos diretamente usando as funções rbegin() e rend(). Objetos desta classe devem ser alocados apenas usando a função System::MakeObject(). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro System::SmartPtr e use esse ponteiro para passá-lo como argumento para funções."
type: docs
weight: 508
url: /pt/system.collections.generic/simpleenumerator/
---
## SimpleEnumerator classe

Iterator class for simple containers holding elements directly using rbegin() and rend() functions. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<typename Container,typename Element>class SimpleEnumerator : public System::Collections::Generic::BaseEnumerator<Container, typename Container::value_type>
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Container | Tipo de contêiner a ser iterado. |
| Element | Tipo de elemento. |
## Métodos

| Método | Descrição |
| --- | --- |
| [IEnumerator](../ienumerator/) * [AsVirtualizedIterator](../ienumerator/asvirtualizediterator/)() | Prepara o iterador para ser usado pela VirtualizedIterator class. |
|  [BaseEnumerator](../baseenumerator/baseenumerator/)(const [Object::ptr](../../system/object/ptr/)\&, Container\&) | Inicializa o iterador. |
| System::Details::VirtualizedIteratorBase\<Element\> * [CloneIterator](./cloneiterator/)() const override | Clona o iterador atual. |
| virtual [MakeConstRef_t](../../system/makeconstref_t/)\<T\> [Current](../ienumerator/current/)() const | Obtém o elemento atual. |
| virtual void [Dispose](../../system/idisposable/dispose/)() | Não faz nada. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não é igual a nenhum valor, inclusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não é igual a nenhum valor, inclusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| [MakeConstRef_t](../../system/makeconstref_t/)\<Element\> [get_Current](./get_current/)() const override | Obtém o elemento 'atual'. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hashing de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
|  [IEnumerator](../ienumerator/ienumerator/)() |  |
| void [IncrementIterator](../ienumerator/incrementiterator/)() override | Move o iterador um passo à frente. |
| void [InitializeIterator](../ienumerator/initializeiterator/)() override | Faz a primeira chamada [MoveNext()](../ienumerator/movenext/) e prepara o objeto enumerador para ser usado pelo VirtualizedIterator. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| **bool** [IsValid](../baseenumerator/isvalid/)() const | Verifica se [MoveNext()](../baseenumerator/movenext/) foi chamado e se o fim não foi alcançado. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| void [MarkOwnedByVirtualizedIterator](../ienumerator/markownedbyvirtualizediterator/)() | Marca o enumerador pertencente ao iterador virtualizado. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite a clonagem de tipos personalizados. |
| **bool** [MoveNext](../baseenumerator/movenext/)() override | Incremento estilo enumerador. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia ao construir subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia ao construir subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [Reset](../baseenumerator/reset/)() override | Redefine o enumerador para permitir reenumerar os elementos. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
|  [SimpleEnumerator](./simpleenumerator/)([Object::ptr](../../system/object/ptr/), Container\&) | Cria um iterador simples. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~IEnumerator](../ienumerator/~ienumerator/)() |  |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Veja também

* Classe [BaseEnumerator](../baseenumerator/)
* Espaço de nomes [System::Collections::Generic](../)
* Biblioteca [Aspose.Slides](../../)