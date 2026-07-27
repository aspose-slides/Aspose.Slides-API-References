---
title: MemoryStream
second_title: Referência da API Aspose.Slides para C++
description: "Representa um fluxo que lê e grava na memória. Objetos desta classe devem ser alocados apenas usando a função System::MakeObject(). Nunca crie uma instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro System::SmartPtr e use esse ponteiro para passá-lo a funções como argumento."
type: docs
weight: 326
url: /pt/system.io/memorystream/
---
## MemoryStream classe

Representa um fluxo que lê e grava na memória. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie uma instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento.

```cpp
class MemoryStream : public System::IO::Stream
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Inicia uma operação de leitura assíncrona. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Inicia uma operação de gravação assíncrona. |
| void [Close](./close/)() override | Fecha o stream. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Copia bytes para o stream especificado. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | Copia bytes para o stream especificado, usando o tamanho de buffer especificado. |
| void [Dispose](../stream/dispose/)() override | Libera todos os recursos usados pelo objeto atual e fecha o stream. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Aguarda até que a operação de leitura assíncrona especificada seja concluída. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Finaliza uma operação de gravação assíncrona. Aguarda até que a operação de gravação assíncrona especificada seja concluída. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante ao estilo C#, onde dois NaNs são considerados iguais, ainda que segundo IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante ao estilo C#, onde dois NaNs são considerados iguais, ainda que segundo IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| void [Flush](./flush/)() override | Não faz nada. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Limpa assíncronamente todos os buffers deste stream, faz com que quaisquer dados em buffer sejam gravados no dispositivo subjacente e monitora solicitações de cancelamento. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | Limpa assíncronamente todos os buffers deste stream, faz com que quaisquer dados em buffer sejam gravados no dispositivo subjacente e monitora solicitações de cancelamento. |
| **bool** [get_CanRead](./get_canread/)() const override | Determina se o stream é legível. |
| **bool** [get_CanSeek](./get_canseek/)() const override | Determina se o stream suporta busca. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | Obtém um valor que determina se o stream atual pode expirar. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | Determina se o stream é gravável. |
| int [get_Capacity](./get_capacity/)() | Retorna a capacidade atual do buffer de memória subjacente. |
| **int64_t** [get_Length](./get_length/)() const override | Retorna o comprimento do stream em bytes. |
| **int64_t** [get_Position](./get_position/)() const override | Retorna a posição atual do stream. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | Obtém um valor, em milissegundos, que determina quanto tempo o stream tentará ler antes de expirar. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | Obtém um valor, em milissegundos, que determina quanto tempo o stream tentará gravar antes de expirar. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBuffer](./getbuffer/)() | Retorna um ponteiro para o buffer subjacente. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referências associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoga ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analoga à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analoga ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoga ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonagem de tipos personalizados. |
| [MemoryStream](./memorystream/)() | Constrói uma nova instância da classe [MemoryStream](./) com capacidade inicial igual a 0. |
| [MemoryStream](./memorystream/)(int) | Constrói uma nova instância da classe [MemoryStream](./) que representa um stream baseado em um buffer de memória do tamanho especificado. |
| [MemoryStream](./memorystream/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **bool**) | Constrói uma nova instância da classe [MemoryStream](./) que representa um stream de memória conectado ao buffer de memória especificado. Um parâmetro define se o stream é gravável. |
| [MemoryStream](./memorystream/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int, **bool**, **bool**) | Constrói uma nova instância da classe [MemoryStream](./) que representa um stream de memória conectado a um segmento do buffer de memória especificado, começando no índice especificado e incluindo o número especificado de elementos. Os parâmetros definem se o stream é gravável e se o método GetBytes() pode ser chamado. |
| [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias em subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias em subclasses. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Lê o número especificado de bytes do stream e grava-os no array de bytes especificado. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Lê o número especificado de bytes do stream e grava-os no array de bytes especificado. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Lê o número especificado de bytes do stream e grava-os no array de bytes especificado. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Lê o número especificado de bytes do stream e grava-os no span de bytes especificado. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Lê assincronamente uma sequência de bytes do stream atual, avança a posição dentro do stream pelo número de bytes lidos e monitora solicitações de cancelamento. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Lê assincronamente uma sequência de bytes do stream atual, avança a posição dentro do stream pelo número de bytes lidos e monitora solicitações de cancelamento. |
| int [ReadByte](./readbyte/)() override | Lê um único byte do stream e retorna um valor inteiro de 32 bits equivalente ao valor do byte lido. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| **int64_t** [Seek](./seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | Define a posição do stream representado pelo objeto atual. |
| void [set_Capacity](./set_capacity/)(int) | Define a capacidade do buffer de memória subjacente. |
| void [set_Position](./set_position/)(**int64_t**) override | Define a posição do stream. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | Define um valor que determina se o stream atual pode expirar. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | Define um valor, em milissegundos, que determina quanto tempo o stream tentará ler antes de expirar. |
| void [SetLength](./setlength/)(**int64_t**) override | Define o comprimento do stream representado pelo objeto atual. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ToArray](./toarray/)() | Retorna uma cópia do buffer de memória subjacente como um array de bytes. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoga ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados em string. |
| **bool** [TryGetBuffer](./trygetbuffer/)([ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\&) | Retorna o array de bytes sem sinal a partir do qual este stream foi criado. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Grava o subintervalo especificado de bytes do array de bytes especificado no stream. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Grava o subintervalo especificado de bytes do array de bytes especificado no stream. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Grava o subintervalo especificado de bytes do array de bytes especificado no stream. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Grava o subintervalo especificado de bytes do span de bytes especificado no stream. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Grava assincronamente uma sequência de bytes no stream atual, avança a posição atual dentro deste stream pelo número de bytes gravados e monitora solicitações de cancelamento. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Grava assincronamente uma sequência de bytes no stream atual, avança a posição atual dentro deste stream pelo número de bytes gravados e monitora solicitações de cancelamento. |
| void [WriteByte](./writebyte/)(**uint8_t**) override | Grava o valor inteiro sem sinal de 8 bits especificado no stream. |
| virtual void [WriteTo](./writeto/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>) | Grava o conteúdo do buffer subjacente no stream especificado. |
| virtual  [~Object](../../system/object/~object/)() | Destrói o objeto. Libera todas as estruturas de dados internas. |

## Campos

| Campo | Descrição |
| --- | --- |
| static [Null](../stream/null/) | Um stream sem armazenamento subjacente. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | Um alias para um ponteiro compartilhado para si mesmo. |

## Veja Também

* Classe [Stream](../stream/)
* Espaço de nomes [System::IO](../)
* Biblioteca [Aspose.Slides](../../)