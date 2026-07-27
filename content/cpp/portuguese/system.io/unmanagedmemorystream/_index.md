---
title: UnmanagedMemoryStream
second_title: Referência da API Aspose.Slides para C++
description: "Fornece acesso à memória não gerenciada. Objetos desta classe devem ser alocados apenas usando a função System::MakeObject(). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro System::SmartPtr e use esse ponteiro para passá-lo a funções como argumento."
type: docs
weight: 456
url: /pt/system.io/unmanagedmemorystream/
---
## UnmanagedMemoryStream classe


Fornece acesso à memória não gerenciada. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie uma instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use este ponteiro para passá-lo a funções como argumento.

```cpp
class UnmanagedMemoryStream : public System::IO::Stream
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Inicia uma operação de leitura assíncrona. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Inicia uma operação de gravação assíncrona. |
| virtual void [Close](../stream/close/)() | Fecha o fluxo. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Copia bytes para o fluxo especificado. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | Copia bytes para o fluxo especificado, usando o tamanho de buffer especificado. |
| void [Dispose](../stream/dispose/)() override | Libera todos os recursos usados pelo objeto atual e fecha o fluxo. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Aguarda até que a operação de leitura assíncrona especificada seja concluída. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Finaliza uma operação de gravação assíncrona. Aguarda até que a operação de gravação assíncrona especificada seja concluída. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante no estilo C#, onde dois NaNs são considerados iguais, embora segundo IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante no estilo C#, onde dois NaNs são considerados iguais, embora segundo IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| void [Flush](./flush/)() override | Não faz nada. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Limpa assincronamente todos os buffers deste fluxo, faz com que quaisquer dados armazenados sejam gravados no dispositivo subjacente e monitora solicitações de cancelamento. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | Limpa assincronamente todos os buffers deste fluxo, faz com que quaisquer dados armazenados sejam gravados no dispositivo subjacente e monitora solicitações de cancelamento. |
| **bool** [get_CanRead](./get_canread/)() const override | Determina se o fluxo é legível. |
| **bool** [get_CanSeek](./get_canseek/)() const override | Determina se o fluxo suporta busca. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | Obtém um valor que determina se o fluxo atual pode expirar. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | Determina se o fluxo é gravável. |
| virtual **int64_t** [get_Capacity](./get_capacity/)() const | Retorna a capacidade atual do buffer de memória subjacente. |
| **int64_t** [get_Length](./get_length/)() const override | Retorna o comprimento do fluxo em bytes. |
| **int64_t** [get_Position](./get_position/)() const override | Retorna a posição atual do fluxo. |
| **uint8_t** * [get_PositionPointer](./get_positionpointer/)() | NÃO IMPLEMENTADO. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | Obtém um valor, em milissegundos, que determina por quanto tempo o fluxo tentará ler antes de expirar. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | Obtém um valor, em milissegundos, que determina por quanto tempo o fluxo tentará gravar antes de expirar. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analógico do método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analógico da chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analógico do operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analógico do método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias em subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias em subclasses. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Lê o número especificado de bytes do fluxo e os grava no array de bytes especificado. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Lê o número especificado de bytes do fluxo e os grava no array de bytes especificado. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Lê o número especificado de bytes do fluxo e os grava no array de bytes especificado. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Lê o número especificado de bytes do fluxo e os grava no span de bytes especificado. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Lê assincronamente uma sequência de bytes do fluxo atual, avança a posição dentro do fluxo pelo número de bytes lidos e monitora solicitações de cancelamento. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Lê assincronamente uma sequência de bytes do fluxo atual, avança a posição dentro do fluxo pelo número de bytes lidos e monitora solicitações de cancelamento. |
| virtual int [ReadByte](../stream/readbyte/)() | Lê um único byte do fluxo e retorna um valor inteiro de 32 bits equivalente ao valor do byte lido. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhado pelo valor especificado. |
| **int64_t** [Seek](./seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | Define a posição do fluxo representado pelo objeto atual. |
| void [set_Position](./set_position/)(**int64_t**) override | Define a posição do fluxo. |
| void [set_PositionPointer](./set_positionpointer/)(**uint8_t** *) | NÃO IMPLEMENTADO. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | Define um valor que determina se o fluxo atual pode expirar. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | Define um valor, em milissegundos, que determina por quanto tempo o fluxo tentará ler antes de expirar. |
| void [SetLength](./setlength/)(**int64_t**) override | NÃO IMPLEMENTADO. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhado. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhado. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhado. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analógico do método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
|  [UnmanagedMemoryStream](./unmanagedmemorystream/)(**uint8_t** *, **int64_t**) | Constrói uma nova instância de [UnmanagedMemoryStream](./). |
|  [UnmanagedMemoryStream](./unmanagedmemorystream/)(**uint8_t** *, **int64_t**, **int64_t**, [FileAccess](../fileaccess/)) | Constrói uma nova instância de [UnmanagedMemoryStream](./). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | NÃO IMPLEMENTADO. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | NÃO IMPLEMENTADO. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Grava o sub-intervalo de bytes especificado do array de bytes especificado no fluxo. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Grava o sub-intervalo de bytes especificado do span de bytes especificado no fluxo. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Grava assincronamente uma sequência de bytes no fluxo atual, avança a posição atual dentro deste fluxo pelo número de bytes gravados e monitora solicitações de cancelamento. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Grava assincronamente uma sequência de bytes no fluxo atual, avança a posição atual dentro deste fluxo pelo número de bytes gravados e monitora solicitações de cancelamento. |
| virtual void [WriteByte](../stream/writebyte/)(**uint8_t**) | Grava o valor inteiro sem sinal de 8 bits especificado no fluxo. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Campos

| Campo | Descrição |
| --- | --- |
| static [Null](../stream/null/) | Um fluxo sem armazenamento subjacente. |

## Veja Também

* Classe [Stream](../stream/)
* Namespace [System::IO](../)
* Biblioteca [Aspose.Slides](../../)