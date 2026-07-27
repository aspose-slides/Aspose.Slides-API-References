---
title: WeakReference< T >
second_title: Aspose.Slides para C++ Referência da API
description: Representa uma referência fraca, que referencia um objeto enquanto ainda permite que esse objeto seja excluído.
type: docs
weight: 1509
url: /pt/system/weakreference_tmpl_t__end_tmpl/
---
## WeakReference< T > classe

Represents a weak reference, which references an object while still allowing that object to be deleted.

```cpp
template<typename T>class WeakReference< T > : public System::Object
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo do objeto referenciado. |

## Métodos

| Método | Descrição |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante em estilo C# onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante em estilo C# onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analógico ao método C# [Object.GetHashCode()](../object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Obtém o tipo real do objeto. Analógico à chamada C# [System.Object.GetType()](../object/gettype/). |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analógico ao operador C# 'is'. |
| void [Lock](../object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analógico ao método C# [Object.MemberwiseClone()](../object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../object/object/)([Object](../object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção por cópia de subclasses. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Verifica se o objeto referenciado não é nulo. |
| **bool** [operator!=](./operator_not_equal/)(const [WeakReference](./weakreference/)\<T\>\&) const | Compara o objeto referenciado a outra instância da classe WeakReference. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção por cópia de subclasses. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Verifica se o objeto referenciado é nulo. |
| **bool** [operator==](./operator_equal_equal/)(const [WeakReference](./weakreference/)\<T\>\&) const | Compara o objeto referenciado a outra instância da classe WeakReference. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Especialização de [Object::ReferenceEquals](../object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [reset](./reset/)() |  |
| void [SetTarget](./settarget/)(const [SmartPtr](../smartptr/)\<T\>\&) | Define o objeto (o alvo) referenciado pelo atual objeto WeakReference. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite alternar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Analógico ao método C# [Object.ToString()](../object/tostring/). Permite converter objetos personalizados para string. |
| **bool** [TryGetTarget](./trygettarget/)(const [SmartPtr](../smartptr/)\<T\>\&) const | Obtém o objeto (o alvo) referenciado pelo atual objeto WeakReference. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementa a construção C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Implementa a liberação da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
|  [WeakReference](./weakreference/)() | Construtor padrão. |
|  [WeakReference](./weakreference/)(std::nullptr_t) | Construtor a partir de nullptr. |
|  [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<T\>\&) | Inicializa uma nova instância da classe WeakReference, referenciando o objeto especificado. |
|  [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<T\>\&, **bool**) | Inicializa uma nova instância da classe WeakReference, referenciando o objeto especificado. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Veja também

* Classe [Object](../object/)
* Namespace [System](../)
* Biblioteca [Aspose.Slides](../../)