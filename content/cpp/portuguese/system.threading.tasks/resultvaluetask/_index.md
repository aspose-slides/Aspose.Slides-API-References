---
title: ResultValueTask
second_title: Referência da API Aspose.Slides para C++
description: Representa um tipo híbrido semelhante a tarefa que pode envolver tanto um valor de resultado direto quanto um ResultTask<T>.
type: docs
weight: 53
url: /pt/system.threading.tasks/resultvaluetask/
---
## ResultValueTask classe

Representa um tipo híbrido semelhante a tarefa que pode envolver tanto um valor de resultado direto quanto um ResultTask<T>.

```cpp
template<typename T>class ResultValueTask : public System::IEquatable<ResultValueTask<T>>,
                                            public System::Details::BoxableObjectBase
```

### Parâmetros de Modelo

| Parameter | Description |
| --- | --- |
| T | O tipo do resultado produzido pela tarefa. |

## Métodos

| Method | Description |
| --- | --- |
| [RTaskPtr](../../system/rtaskptr/)\<T\> [AsTask](./astask/)() const | Converte este [ResultValueTask](./) em um ponteiro compartilhado para ResultTask<T>. |
| [Runtime::CompilerServices::ConfiguredResultValueTaskAwaitable](../../system.runtime.compilerservices/configuredresultvaluetaskawaitable/)\<T\> [ConfigureAwait](./configureawait/)(**bool**) const | Configura um awaiter para esta tarefa. |
| **bool** [Equals](./equals/)([ResultValueTask](./)) override | Determina se esta instância é igual a outra instância de [ResultValueTask](./). |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Determina se esta instância é igual a outro objeto. |
| virtual **bool** [Equals](../../system/iequatable/equals/)(T) | Determina se os objetos atual e especificado são iguais. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora segundo IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora segundo IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| **bool** [get_IsCanceled](./get_iscanceled/)() const | Obtém um valor que indica se a tarefa foi concluída devido a cancelamento. |
| **bool** [get_IsCompleted](./get_iscompleted/)() const | Obtém um valor que indica se a tarefa foi concluída. |
| **bool** [get_IsCompletedSuccessfully](./get_iscompletedsuccessfully/)() const | Obtém um valor que indica se a tarefa foi concluída com sucesso. |
| **bool** [get_IsFaulted](./get_isfaulted/)() const | Obtém um valor que indica se a tarefa foi concluída devido a uma exceção não tratada. |
| T [get_Result](./get_result/)() | Obtém o resultado da tarefa concluída. |
| [Runtime::CompilerServices::ResultValueTaskAwaiter](../../system.runtime.compilerservices/resultvaluetaskawaiter/)\<T\> [GetAwaiter](./getawaiter/)() const | Obtém um awaiter para esta tarefa para suportar expressões await. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analógia do método C# [Object.GetHashCode()](../../system/object/gethashcode/). Habilita hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analógia da chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analógia do operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analógia do método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Habilita clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópia de subclasses. |
| **bool** [operator!=](./operator_not_equal/)(const [ResultValueTask](./)\&) const | Operador de desigualdade para [ResultValueTask](./). |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópia de subclasses. |
| **bool** [operator==](./operator_equal_equal/)(const [ResultValueTask](./)\&) const | Operador de igualdade para [ResultValueTask](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhado em um valor especificado. |
|  [ResultValueTask](./resultvaluetask/)() | Constrói um [ResultValueTask](./) vazio e não inicializado. |
|  [ResultValueTask](./resultvaluetask/)(const T\&) | Constrói um [ResultValueTask](./) concluído com o resultado especificado. |
|  [ResultValueTask](./resultvaluetask/)(const [RTaskPtr](../../system/rtaskptr/)\<T\>\&) | Constrói um [ResultValueTask](./) a partir de um ponteiro compartilhado para um ResultTask<T>. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite alternar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhado. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhado. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhado. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analógia do método C# [Object.ToString()](../../system/object/tostring/). Habilita a conversão de objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Observações

[ResultValueTask](./) combina os benefícios de [ValueTask](../valuetask/) (alocações reduzidas para resultados síncronos) com a capacidade de envolver objetos ResultTask<T> existentes. Ele fornece uma interface awaitable e vários métodos de inspeção de status de tarefa. 

## Veja Também

* Classe [IEquatable](../../system/iequatable/)
* Namespace [System::Threading::Tasks](../)
* Biblioteca [Aspose.Slides](../../)