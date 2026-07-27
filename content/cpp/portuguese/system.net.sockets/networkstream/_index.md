---
title: NetworkStream
second_title: Referência da API Aspose.Slides para C++
description: "Fornece o fluxo subjacente dos dados para o acesso à rede. Objetos desta classe devem ser alocados apenas usando a função System::MakeObject() . Nunca crie instância deste tipo na pilha ou usando o operador new, pois resultará em erros em tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro System::SmartPtr e use esse ponteiro para passá-lo a funções como argumento."
type: docs
weight: 40
url: /pt/system.net.sockets/networkstream/
---
## classe NetworkStream


Fornece o fluxo subjacente dos dados para o acesso à rede. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros em tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento.

```cpp
class NetworkStream : public System::IO::Stream
```

## Métodos

| Método | Descrição |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginRead](./beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Inicia uma operação de leitura assíncrona. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../../system.io/stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Inicia uma operação de leitura assíncrona. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](./beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Inicia uma operação de gravação assíncrona. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../../system.io/stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Inicia uma operação de gravação assíncrona. |
| void [Close](./close/)(int) | Fecha a instância atual após o tempo especificado expirar. |
| virtual void [Close](../../system.io/stream/close/)() | Fecha o fluxo. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&) | Copia bytes para o fluxo especificado. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&, **int32_t**) | Copia bytes para o fluxo especificado, usando o tamanho de buffer especificado. |
| void [Dispose](../../system.io/stream/dispose/)() override | Libera todos os recursos usados pelo objeto atual e fecha o fluxo. |
| **int32_t** [EndRead](./endread/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Aguarda até que a operação de leitura assíncrona especificada seja concluída. |
| virtual int [EndRead](../../system.io/stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Aguarda até que a operação de leitura assíncrona especificada seja concluída. |
| void [EndWrite](./endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Finaliza uma operação de gravação assíncrona. Aguarda até que a operação de gravação assíncrona especificada seja concluída. |
| virtual void [EndWrite](../../system.io/stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Finaliza uma operação de gravação assíncrona. Aguarda até que a operação de gravação assíncrona especificada seja concluída. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência ao estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor ao estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para fins internos. |
| void [Flush](./flush/)() override | Limpa os buffers deste fluxo e grava todos os dados armazenados no armazenamento subjacente. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Limpa assíncronamente todos os buffers deste fluxo, faz com que quaisquer dados armazenados sejam gravados no dispositivo subjacente e monitora solicitações de cancelamento. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)() | Limpa assíncronamente todos os buffers deste fluxo, faz com que quaisquer dados armazenados sejam gravados no dispositivo subjacente e monitora solicitações de cancelamento. |
| **bool** [get_CanRead](./get_canread/)() const override | Determina se o fluxo é legível. |
| **bool** [get_CanSeek](./get_canseek/)() const override | Determina se o fluxo oferece suporte a busca. |
| **bool** [get_CanTimeout](./get_cantimeout/)() const override | Obtém um valor que determina se o fluxo atual pode expirar. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | Determina se o fluxo é gravável. |
| **bool** [get_DataAvailable](./get_dataavailable/)() const | Retorna um valor que indica se há dados disponíveis para leitura. |
| **int64_t** [get_Length](./get_length/)() const override | Retorna o comprimento do fluxo em bytes. |
| **int64_t** [get_Position](./get_position/)() const override | Retorna a posição atual do fluxo. |
| **int32_t** [get_ReadTimeout](./get_readtimeout/)() const override | Obtém um valor, em milissegundos, que determina quanto tempo o fluxo tentará ler antes de expirar. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Net::Sockets::Socket](../socket/)\> [get_Socket](./get_socket/)() | Obtém o [Socket](../socket/) subjacente. |
| **int32_t** [get_WriteTimeout](./get_writetimeout/)() const override | Obtém um valor, em milissegundos, que determina quanto tempo o fluxo tentará gravar antes de expirar. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analógico do método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analógico da chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analógico do operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analógico do método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [NetworkStream](./networkstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Sockets::Socket](../socket/)\>) | Constrói uma nova instância. |
|  [NetworkStream](./networkstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Sockets::Socket](../socket/)\>, [System::IO::FileAccess](../../system.io/fileaccess/), **bool**) | Constrói uma nova instância. |
|  [NetworkStream](./networkstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Sockets::Socket](../socket/)\>, **bool**) | Constrói uma nova instância. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Não copia nada, apenas inicializa um novo objeto e permite cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Não copia nada, apenas inicializa um novo objeto e permite cópia de subclasses. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Lê o número especificado de bytes do fluxo e grava-os no array de bytes especificado. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Lê o número especificado de bytes do fluxo e grava-os no array de bytes especificado. |
| **int32_t** [Read](../../system.io/stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Lê o número especificado de bytes do fluxo e grava-os no array de bytes especificado. |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Lê o número especificado de bytes do fluxo e grava-os no span de bytes especificado. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Lê assíncronamente uma sequência de bytes do fluxo atual, avança a posição dentro do fluxo pelo número de bytes lidos e monitora solicitações de cancelamento. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Lê assíncronamente uma sequência de bytes do fluxo atual, avança a posição dentro do fluxo pelo número de bytes lidos e monitora solicitações de cancelamento. |
| virtual int [ReadByte](../../system.io/stream/readbyte/)() | Lê um único byte do fluxo e retorna um valor inteiro de 32 bits equivalente ao valor do byte lido. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| **int64_t** [Seek](./seek/)(**int64_t**, [IO::SeekOrigin](../../system.io/seekorigin/)) override | Define a posição do fluxo representado pelo objeto atual. |
| void [set_Position](./set_position/)(**int64_t**) override | Define a posição do fluxo. |
| void [set_ReadTimeout](./set_readtimeout/)(**int32_t**) override | Define um valor que determina se o fluxo atual pode expirar. |
| virtual void [set_ReadTimeout](../../system.io/stream/set_readtimeout/)(int) | Define um valor que determina se o fluxo atual pode expirar. |
| void [set_WriteTimeout](./set_writetimeout/)(**int32_t**) override | Define um valor, em milissegundos, que determina quanto tempo o fluxo tentará ler antes de expirar. |
| virtual void [set_WriteTimeout](../../system.io/stream/set_writetimeout/)(int) | Define um valor, em milissegundos, que determina quanto tempo o fluxo tentará ler antes de expirar. |
| void [SetLength](./setlength/)(**int64_t**) override | Define o comprimento do fluxo representado pelo objeto atual. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analógico do método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa o construto C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Grava o sub-intervalo especificado de bytes do array de bytes especificado no fluxo. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Grava o sub-intervalo especificado de bytes do array de bytes especificado no fluxo. |
| void [Write](../../system.io/stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Grava o sub-intervalo especificado de bytes do array de bytes especificado no fluxo. |
| virtual void [Write](../../system.io/stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Grava o sub-intervalo especificado de bytes do span de bytes especificado no fluxo. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Grava assíncronamente uma sequência de bytes no fluxo atual, avança a posição atual neste fluxo pelo número de bytes gravados e monitora solicitações de cancelamento. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Grava assíncronamente uma sequência de bytes no fluxo atual, avança a posição atual neste fluxo pelo número de bytes gravados e monitora solicitações de cancelamento. |
| virtual void [WriteByte](../../system.io/stream/writebyte/)(**uint8_t**) | Grava o valor inteiro sem sinal de 8 bits especificado no fluxo. |
| virtual  [~NetworkStream](./~networkstream/)() | Destrói a instância atual. |
| virtual  [~Object](../../system/object/~object/)() | Destrói o objeto. Libera todas as estruturas de dados internas. |

## Campos

| Campo | Descrição |
| --- | --- |
| static [Null](../../system.io/stream/null/) | Um fluxo sem armazenamento subjacente. |

## Veja Também

* Classe [Stream](../../system.io/stream/)
* Espaço de nomes [System::Net::Sockets](../)
* Biblioteca [Aspose.Slides](../../)