---
title: CryptoStream
second_title: Referência da API Aspose.Slides para C++
description: "Implementação de fluxo que envolve um fluxo existente com uma função criptográfica. Objetos desta classe devem ser alocados apenas usando a função System::MakeObject(). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro System::SmartPtr e use esse ponteiro para passá-lo a funções como argumento."
type: docs
weight: 53
url: /pt/system.security.cryptography/cryptostream/
---
## CryptoStream classe

Implementação de fluxo que envolve um fluxo existente com uma função criptográfica. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento.

```cpp
class CryptoStream : public System::IO::Stream
```

## Métodos

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../../system.io/stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Inicia uma operação de leitura assíncrona. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../../system.io/stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Inicia uma operação de gravação assíncrona. |
| void [Close](./close/)() override | Fecha a conexão. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&) | Copia bytes para o fluxo especificado. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&, **int32_t**) | Copia bytes para o fluxo especificado, usando o tamanho de buffer especificado. |
|  [CryptoStream](./cryptostream/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\>\&, [CryptoStreamMode](../cryptostreammode/)) | Construtor. |
| void [Dispose](../../system.io/stream/dispose/)() override | Libera todos os recursos usados pelo objeto atual e fecha o fluxo. |
| virtual int [EndRead](../../system.io/stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Aguarda até que a operação de leitura assíncrona especificada seja concluída. |
| virtual void [EndWrite](../../system.io/stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Finaliza uma operação de gravação assíncrona. Aguarda até que a operação de gravação assíncrona especificada seja concluída. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora segundo IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora segundo IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para fins internos. |
| void [Flush](./flush/)() override | Esvazia o buffer no fluxo encapsulado. Não faz nada pois o algoritmo de transformação ainda pode estar aguardando mais dados. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Limpa assíncronamente todos os buffers deste fluxo, faz com que quaisquer dados em buffer sejam escritos no dispositivo subjacente e monitora solicitações de cancelamento. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)() | Limpa assíncronamente todos os buffers deste fluxo, faz com que quaisquer dados em buffer sejam escritos no dispositivo subjacente e monitora solicitações de cancelamento. |
| void [FlushFinalBlock](./flushfinalblock/)() | Escreve os dados que ainda estão no buffer para o fluxo. |
| **bool** [get_CanRead](./get_canread/)() const override | Verifica se o fluxo é legível. |
| **bool** [get_CanSeek](./get_canseek/)() const override | Verifica se o fluxo permite busca. |
| virtual **bool** [get_CanTimeout](../../system.io/stream/get_cantimeout/)() const | Obtém um valor que determina se o fluxo atual pode expirar. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | Verifica se o fluxo é gravável. |
| **int64_t** [get_Length](./get_length/)() const override | Obtém o comprimento do fluxo. Não suportado. |
| **int64_t** [get_Position](./get_position/)() const override | Obtém a posição atual no fluxo. Não suportado. |
| virtual int [get_ReadTimeout](../../system.io/stream/get_readtimeout/)() const | Obtém um valor, em milissegundos, que determina por quanto tempo o fluxo tentará ler antes de expirar. |
| virtual int [get_WriteTimeout](../../system.io/stream/get_writetimeout/)() const | Obtém um valor, em milissegundos, que determina por quanto tempo o fluxo tentará gravar antes de expirar. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referências associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hashing de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias em subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias em subclasses. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Lê dados do fluxo. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Lê dados do fluxo. |
| **int32_t** [Read](../../system.io/stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Lê o número especificado de bytes do fluxo e os grava no array de bytes especificado. |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Lê o número especificado de bytes do fluxo e os grava na região de bytes especificada. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Lê assíncronamente uma sequência de bytes do fluxo atual, avança a posição dentro do fluxo pelo número de bytes lidos e monitora solicitações de cancelamento. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Lê assíncronamente uma sequência de bytes do fluxo atual, avança a posição dentro do fluxo pelo número de bytes lidos e monitora solicitações de cancelamento. |
| virtual int [ReadByte](../../system.io/stream/readbyte/)() | Lê um único byte do fluxo e retorna um valor inteiro de 32 bits equivalente ao valor do byte lido. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| **int64_t** [Seek](./seek/)(**int64_t**, [IO::SeekOrigin](../../system.io/seekorigin/)) override | Posiciona no fluxo. Não suportado. |
| void [set_Position](./set_position/)(**int64_t**) override | Posiciona no fluxo. Não suportado. |
| virtual void [set_ReadTimeout](../../system.io/stream/set_readtimeout/)(int) | Define um valor que determina se o fluxo atual pode expirar. |
| virtual void [set_WriteTimeout](../../system.io/stream/set_writetimeout/)(int) | Define um valor, em milissegundos, que determina por quanto tempo o fluxo tentará ler antes de expirar. |
| void [SetLength](./setlength/)(**int64_t**) override | Posiciona o tamanho do fluxo. Não suportado. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Escreve dados no fluxo. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Escreve dados no fluxo. |
| void [Write](../../system.io/stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Escreve o sub-intervalo especificado de bytes do array de bytes especificado no fluxo. |
| virtual void [Write](../../system.io/stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Escreve o sub-intervalo especificado de bytes da região de bytes especificada no fluxo. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Escreve assíncronamente uma sequência de bytes no fluxo atual, avança a posição atual dentro deste fluxo pelo número de bytes escritos e monitora solicitações de cancelamento. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Escreve assíncronamente uma sequência de bytes no fluxo atual, avança a posição atual dentro deste fluxo pelo número de bytes escritos e monitora solicitações de cancelamento. |
| virtual void [WriteByte](../../system.io/stream/writebyte/)(**uint8_t**) | Escreve o valor inteiro sem sinal de 8 bits especificado no fluxo. |
| virtual  [~Object](../../system/object/~object/)() | Destrói o objeto. Libera todas as estruturas de dados internas. |

## Campos

| Field | Description |
| --- | --- |
| static [Null](../../system.io/stream/null/) | Um fluxo sem armazenamento subjacente. |

## Ver também

* Classe [Stream](../../system.io/stream/)
* Espaço de nomes [System::Security::Cryptography](../)
* Biblioteca [Aspose.Slides](../../)