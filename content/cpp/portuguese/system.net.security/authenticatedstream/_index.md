---
title: AuthenticatedStream
second_title: Referência da API Aspose.Slides para C++
description: "Contém os métodos para passar credenciais através de um fluxo. Objetos desta classe devem ser alocados apenas usando a função System::MakeObject(). Nunca crie uma instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro System::SmartPtr e use esse ponteiro para passá-lo a funções como argumento."
type: docs
weight: 1
url: /pt/system.net.security/authenticatedstream/
---
## AuthenticatedStream classe


Contém os métodos para passar credenciais através de um fluxo. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento.

```cpp
class AuthenticatedStream : public System::IO::Stream
```

## Métodos

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../../system.io/stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Inicia uma operação de leitura assíncrona. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../../system.io/stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Inicia uma operação de escrita assíncrona. |
| virtual void [Close](../../system.io/stream/close/)() | Fecha o fluxo. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&) | Copia bytes para o fluxo especificado. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&, **int32_t**) | Copia bytes para o fluxo especificado, usando o tamanho de buffer especificado. |
| void [Dispose](../../system.io/stream/dispose/)() override | Libera todos os recursos usados pelo objeto atual e fecha o fluxo. |
| virtual int [EndRead](../../system.io/stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Aguarda até que a operação de leitura assíncrona especificada seja concluída. |
| virtual void [EndWrite](../../system.io/stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Finaliza uma operação de escrita assíncrona. Aguarda até que a operação de escrita assíncrona especificada seja concluída. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante estilo C# onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante estilo C# onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| virtual void [Flush](../../system.io/stream/flush/)() | Limpa os buffers deste fluxo e grava todos os dados em buffer no armazenamento subjacente. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Limpa assincronamente todos os buffers deste fluxo, faz com que quaisquer dados em buffer sejam gravados no dispositivo subjacente e monitora solicitações de cancelamento. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)() | Limpa assincronamente todos os buffers deste fluxo, faz com que quaisquer dados em buffer sejam gravados no dispositivo subjacente e monitora solicitações de cancelamento. |
| virtual **bool** [get_CanRead](../../system.io/stream/get_canread/)() const | Determina se o fluxo pode ser lido. |
| virtual **bool** [get_CanSeek](../../system.io/stream/get_canseek/)() const | Determina se o fluxo oferece suporte a busca. |
| virtual **bool** [get_CanTimeout](../../system.io/stream/get_cantimeout/)() const | Obtém um valor que determina se o fluxo atual pode expirar. |
| virtual **bool** [get_CanWrite](../../system.io/stream/get_canwrite/)() const | Determina se o fluxo pode ser escrito. |
| virtual **bool** [get_IsAuthenticated](./get_isauthenticated/)() const | Retorna um valor que indica se a autenticação foi passada com sucesso. |
| virtual **bool** [get_IsEncrypted](./get_isencrypted/)() const | Retorna um valor que indica se os dados enviados através deste fluxo são criptografados. |
| virtual **bool** [get_IsMutuallyAuthenticated](./get_ismutuallyauthenticated/)() const | Retorna um valor que indica se um servidor e um cliente estão autenticados. |
| virtual **bool** [get_IsServer](./get_isserver/)() const | Retorna um valor que indica se o lado local da conexão é o servidor. |
| virtual **bool** [get_IsSigned](./get_issigned/)() const | Retorna um valor que indica se os dados enviados através deste fluxo são assinados. |
| **bool** [get_LeaveInnerStreamOpen](./get_leaveinnerstreamopen/)() const | Retorna o fluxo que é usado pelas instâncias da classe atual para enviar e receber dados. |
| virtual **int64_t** [get_Length](../../system.io/stream/get_length/)() const | Retorna o comprimento do fluxo em bytes. |
| virtual **int64_t** [get_Position](../../system.io/stream/get_position/)() const | Retorna a posição atual do fluxo. |
| virtual int [get_ReadTimeout](../../system.io/stream/get_readtimeout/)() const | Obtém um valor, em milissegundos, que determina por quanto tempo o fluxo tentará ler antes de expirar. |
| virtual int [get_WriteTimeout](../../system.io/stream/get_writetimeout/)() const | Obtém um valor, em milissegundos, que determina por quanto tempo o fluxo tentará escrever antes de expirar. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referências associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópia de subclasses. |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Lê o número especificado de bytes do fluxo e grava-os no array de bytes especificado. |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Lê o número especificado de bytes do fluxo e grava-os no array de bytes especificado. |
| **int32_t** [Read](../../system.io/stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Lê o número especificado de bytes do fluxo e grava-os no array de bytes especificado. |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Lê o número especificado de bytes do fluxo e grava-os no span de bytes especificado. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Lê assincronamente uma sequência de bytes do fluxo atual, avança a posição dentro do fluxo pelo número de bytes lidos e monitora solicitações de cancelamento. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Lê assincronamente uma sequência de bytes do fluxo atual, avança a posição dentro do fluxo pelo número de bytes lidos e monitora solicitações de cancelamento. |
| virtual int [ReadByte](../../system.io/stream/readbyte/)() | Lê um único byte do fluxo e retorna um valor inteiro de 32 bits equivalente ao valor do byte lido. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| virtual **int64_t** [Seek](../../system.io/stream/seek/)(**int64_t**, [SeekOrigin](../../system.io/seekorigin/)) | Define a posição do fluxo representado pelo objeto atual. |
| virtual void [set_Position](../../system.io/stream/set_position/)(**int64_t**) | Define a posição do fluxo. |
| virtual void [set_ReadTimeout](../../system.io/stream/set_readtimeout/)(int) | Define um valor que determina se o fluxo atual pode expirar. |
| virtual void [set_WriteTimeout](../../system.io/stream/set_writetimeout/)(int) | Define um valor, em milissegundos, que determina por quanto tempo o fluxo tentará ler antes de expirar. |
| virtual void [SetLength](../../system.io/stream/setlength/)(**int64_t**) | Define o comprimento do fluxo representado pelo objeto atual. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual void [Write](../../system.io/stream/write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Grava o subintervalo especificado de bytes do array de bytes especificado no fluxo. |
| virtual void [Write](../../system.io/stream/write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Grava o subintervalo especificado de bytes do array de bytes especificado no fluxo. |
| void [Write](../../system.io/stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Grava o subintervalo especificado de bytes do array de bytes especificado no fluxo. |
| virtual void [Write](../../system.io/stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Grava o subintervalo especificado de bytes do span de bytes especificado no fluxo. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Escreve assincronamente uma sequência de bytes no fluxo atual, avança a posição atual dentro deste fluxo pelo número de bytes escritos e monitora solicitações de cancelamento. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Escreve assincronamente uma sequência de bytes no fluxo atual, avança a posição atual dentro deste fluxo pelo número de bytes escritos e monitora solicitações de cancelamento. |
| virtual void [WriteByte](../../system.io/stream/writebyte/)(**uint8_t**) | Grava o valor inteiro sem sinal de 8 bits especificado no fluxo. |
| virtual  [~Object](../../system/object/~object/)() | Destrói o objeto. Libera todas as estruturas de dados internas. |
## Campos

| Field | Description |
| --- | --- |
| static [Null](../../system.io/stream/null/) | Um fluxo sem armazenamento subjacente. |
## Veja Também

* Classe [Stream](../../system.io/stream/)
* Namespace [System::Net::Security](../)
* Biblioteca [Aspose.Slides](../../)