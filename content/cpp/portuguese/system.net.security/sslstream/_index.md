---
title: SslStream
second_title: Referência da API Aspose.Slides para C++
description: Um fluxo que usa o protocolo SSL para autenticar o servidor e, opcionalmente, o cliente.
type: docs
weight: 14
url: /pt/system.net.security/sslstream/
---
## SslStream classe

Um fluxo que usa o protocolo SSL para autenticar o servidor e, opcionalmente, o cliente.

```cpp
class SslStream : public System::Net::Security::AuthenticatedStream
```

## Métodos

| Method | Description |
| --- | --- |
| virtual void [AuthenticateAsClient](./authenticateasclient/)([String](../../system/string/)) | Autentica o lado cliente da conexão. |
| virtual void [AuthenticateAsClient](./authenticateasclient/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\>, [System::Security::Authentication::SslProtocols](../../system.security.authentication/sslprotocols/), **bool**) | Autentica o lado cliente da conexão. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginRead](./beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Inicia uma operação de leitura assíncrona. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../../system.io/stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Inicia uma operação de leitura assíncrona. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](./beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Inicia uma operação de escrita assíncrona. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../../system.io/stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Inicia uma operação de escrita assíncrona. |
| void [Close](./close/)() override | Fecha o fluxo. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&) | Copia bytes para o fluxo especificado. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&, **int32_t**) | Copia bytes para o fluxo especificado, usando o tamanho de buffer especificado. |
| void [Dispose](./dispose/)(**bool**) override | Libera todos os recursos usados pelo objeto atual e fecha o fluxo. |
| void [Dispose](../../system.io/stream/dispose/)() override | Libera todos os recursos usados pelo objeto atual e fecha o fluxo. |
| **int32_t** [EndRead](./endread/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Aguarda até que a operação de leitura assíncrona especificada seja concluída. |
| virtual int [EndRead](../../system.io/stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Aguarda até que a operação de leitura assíncrona especificada seja concluída. |
| void [EndWrite](./endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Finaliza uma operação de escrita assíncrona. Aguarda até que a operação de escrita assíncrona especificada seja concluída. |
| virtual void [EndWrite](../../system.io/stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Finaliza uma operação de escrita assíncrona. Aguarda até que a operação de escrita assíncrona especificada seja concluída. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante ao estilo C#, onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante ao estilo C#, onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| void [Flush](./flush/)() override | Limpa os buffers deste fluxo e grava todos os dados armazenados no dispositivo subjacente. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Limpa assíncronamente todos os buffers deste fluxo, faz com que quaisquer dados armazenados sejam gravados no dispositivo subjacente e monitora solicitações de cancelamento. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)() | Limpa assíncronamente todos os buffers deste fluxo, faz com que quaisquer dados armazenados sejam gravados no dispositivo subjacente e monitora solicitações de cancelamento. |
| **bool** [get_CanRead](./get_canread/)() const override | Determina se o fluxo é legível. |
| **bool** [get_CanSeek](./get_canseek/)() const override | Determina se o fluxo suporta busca. |
| **bool** [get_CanTimeout](./get_cantimeout/)() const override | Obtém um valor que determina se o fluxo atual pode expirar. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | Determina se o fluxo é gravável. |
| virtual **bool** [get_CheckCertRevocationStatus](./get_checkcertrevocationstatus/)() | Retorna um valor que indica se a lista de revogação de certificados é verificada durante o processo de validação do certificado. |
| virtual [System::Security::Authentication::CipherAlgorithmType](../../system.security.authentication/cipheralgorithmtype/) [get_CipherAlgorithm](./get_cipheralgorithm/)() | Retorna o algoritmo de criptografia. |
| virtual **int32_t** [get_CipherStrength](./get_cipherstrength/)() | Retorna a força do algoritmo de criptografia usado. |
| virtual [System::Security::Authentication::HashAlgorithmType](../../system.security.authentication/hashalgorithmtype/) [get_HashAlgorithm](./get_hashalgorithm/)() | Retorna o algoritmo de hash. |
| virtual **int32_t** [get_HashStrength](./get_hashstrength/)() | Retorna a força do algoritmo de hash usado. |
| **bool** [get_IsAuthenticated](./get_isauthenticated/)() const override | Retorna um valor que indica se a autenticação foi concluída com sucesso. |
| **bool** [get_IsEncrypted](./get_isencrypted/)() const override | Retorna um valor que indica se os dados enviados usando este fluxo são criptografados. |
| **bool** [get_IsMutuallyAuthenticated](./get_ismutuallyauthenticated/)() const override | Retorna um valor que indica se um servidor e um cliente estão autenticados. |
| **bool** [get_IsServer](./get_isserver/)() const override | Retorna um valor que indica se o lado local da conexão é o servidor. |
| **bool** [get_IsSigned](./get_issigned/)() const override | Retorna um valor que indica se os dados enviados usando este fluxo são assinados. |
| virtual **int32_t** [get_KeyExchangeStrength](./get_keyexchangestrength/)() | Retorna a força do algoritmo de troca de chaves usado. |
| **bool** [get_LeaveInnerStreamOpen](../authenticatedstream/get_leaveinnerstreamopen/)() const | Retorna o fluxo usado pelas instâncias da classe atual para enviar e receber dados. |
| **int64_t** [get_Length](./get_length/)() const override | Retorna o comprimento do fluxo em bytes. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_LocalCertificate](./get_localcertificate/)() | Retorna o certificado usado para autenticar o ponto de extremidade local. |
| **int64_t** [get_Position](./get_position/)() const override | Retorna a posição atual do fluxo. |
| **int32_t** [get_ReadTimeout](./get_readtimeout/)() const override | Obtém um valor, em milissegundos, que determina quanto tempo o fluxo tentará ler antes de expirar. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_RemoteCertificate](./get_remotecertificate/)() | Retorna o certificado usado para autenticar o ponto de extremidade remoto. |
| virtual [System::Security::Authentication::SslProtocols](../../system.security.authentication/sslprotocols/) [get_SslProtocol](./get_sslprotocol/)() | Retorna o protocolo SSL. |
| **int32_t** [get_WriteTimeout](./get_writetimeout/)() const override | Obtém um valor, em milissegundos, que determina quanto tempo o fluxo tentará escrever antes de expirar. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referências associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo do método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analogo da chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analogo do operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo do método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a construção de cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a construção de cópia de subclasses. |
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
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e devolve o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>) | Constrói uma nova instância. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**) | Constrói uma nova instância. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../remotecertificatevalidationcallback/)) | Constrói uma nova instância. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../remotecertificatevalidationcallback/), [LocalCertificateSelectionCallback](../localcertificateselectioncallback/)) | Constrói uma nova instância. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../remotecertificatevalidationcallback/), [LocalCertificateSelectionCallback](../localcertificateselectioncallback/), [EncryptionPolicy](../encryptionpolicy/)) | Constrói uma nova instância. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo do método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa a liberação da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Grava o array de bytes especificado no fluxo. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Grava o subintervalo especificado de bytes do array de bytes especificado no fluxo. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Grava o array de bytes especificado no fluxo. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Grava o subintervalo especificado de bytes do array de bytes especificado no fluxo. |
| void [Write](../../system.io/stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Grava o subintervalo especificado de bytes do array de bytes especificado no fluxo. |
| virtual void [Write](../../system.io/stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Grava o subintervalo especificado de bytes do span de bytes especificado no fluxo. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Escreve assíncronamente uma sequência de bytes no fluxo atual, avança a posição atual dentro deste fluxo pelo número de bytes escritos e monitora solicitações de cancelamento. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Escreve assíncronamente uma sequência de bytes no fluxo atual, avança a posição atual dentro deste fluxo pelo número de bytes escritos e monitora solicitações de cancelamento. |
| virtual void [WriteByte](../../system.io/stream/writebyte/)(**uint8_t**) | Grava o valor inteiro sem sinal de 8 bits especificado no fluxo. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Campos

| Field | Description |
| --- | --- |
| static [Null](../../system.io/stream/null/) | Um fluxo sem armazenamento subjacente. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [AsyncResultType](./asyncresulttype/) | Tipo de AsyncResultType. |
| [StreamImplementationPtr](./streamimplementationptr/) | Tipo de ponteiro para a implementação. |

## Veja Também

* Classe [AuthenticatedStream](../authenticatedstream/)
* Namespace [System::Net::Security](../)
* Biblioteca [Aspose.Slides](../../)