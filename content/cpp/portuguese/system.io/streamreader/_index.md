---
title: StreamReader
second_title: Referência da API Aspose.Slides para C++
description: "Representa um leitor que lê caracteres de um fluxo de bytes. Objetos desta classe devem ser alocados somente usando a função System::MakeObject(). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro System::SmartPtr e use esse ponteiro para passá-lo a funções como argumento."
type: docs
weight: 378
url: /pt/system.io/streamreader/
---
## StreamReader classe

Representa um leitor que lê caracteres de um fluxo de bytes. Objetos desta classe devem ser alocados somente usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento.

```cpp
class StreamReader : public System::IO::TextReader
```

## Métodos

| Method | Description |
| --- | --- |
| void [Close](./close/)() override | Fecha os streams atuais e subjacentes. |
| virtual void [Dispose](./dispose/)(**bool**) | Libera todos os recursos usados pelo objeto atual e fecha o stream subjacente. |
| void [Dispose](./dispose/)() override | Libera todos os recursos usados pelo objeto atual e fecha o stream subjacente. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante ao estilo C#, onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante ao estilo C#, onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() const | Retorna um ponteiro compartilhado para um objeto que representa o stream subjacente. |
| [EncodingPtr](../../system/encodingptr/) [get_CurrentEncoding](./get_currentencoding/)() | Retorna a codificação atualmente usada. |
| **bool** [get_EndOfStream](./get_endofstream/)() | Retorna um valor que indica se o fim do stream foi alcançado. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogia ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analogia à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analogia ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogia ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade, não copia nada, apenas inicializa um novo objeto e permite a construção por cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade, não copia nada, apenas inicializa um novo objeto e permite a construção por cópia de subclasses. |
| int [Peek](./peek/)() override | Lê um único caractere do stream sem mudar o cursor de leitura do stream. |
| int [Read](./read/)() override | Lê um único caractere do stream. |
| int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) override | Lê o número especificado de caracteres do stream, converte-os para codificação UTF-16 e grava os caracteres UTF-16 resultantes no array de caracteres especificado a partir da posição especificada. |
| virtual int [ReadBlock](../textreader/readblock/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Lê o número máximo especificado de caracteres do leitor de texto atual e grava os dados em um buffer, começando no índice especificado. |
| [String](../../system/string/) [ReadLine](./readline/)() override | Lê caracteres do stream até o fim da linha atual. |
| [String](../../system/string/) [ReadToEnd](./readtoend/)() override | Lê caracteres do stream até o fim do stream. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhado pelo valor especificado. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de template como ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhado. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhado. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhado. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Constrói uma instância do objeto [StreamReader](./) que lê caracteres do stream subjacente especificado usando codificação UTF-8 e um buffer com tamanho padrão de 1024 bytes. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **bool**) | Constrói uma instância do objeto [StreamReader](./) que lê caracteres do stream subjacente especificado usando codificação UTF-8 e um buffer com tamanho padrão de 1024 bytes. Um parâmetro especifica se a detecção de marca de ordem de bytes deve ser habilitada. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Constrói uma instância do objeto [StreamReader](./) que lê caracteres do stream subjacente especificado usando a codificação especificada e um buffer com tamanho padrão de 1024 bytes. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**) | Constrói uma instância do objeto [StreamReader](./) que lê caracteres do stream subjacente especificado usando a codificação especificada e um buffer com tamanho padrão de 1024 bytes. Um parâmetro especifica se a detecção de marca de ordem de bytes deve ser habilitada. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**, int) | Constrói uma instância do objeto [StreamReader](./) que lê caracteres do stream subjacente especificado usando a codificação especificada e um buffer do tamanho especificado. Um parâmetro especifica se a detecção de marca de ordem de bytes deve ser habilitada. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&) | Constrói uma instância do objeto [StreamReader](./) que lê caracteres do arquivo especificado usando codificação UTF-8 e um buffer com tamanho padrão de 4096 bytes. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, **bool**) | Constrói uma instância do objeto [StreamReader](./) que lê caracteres do arquivo especificado usando codificação UTF-8 e um buffer com tamanho padrão de 4096 bytes. Um parâmetro especifica se a detecção de marca de ordem de bytes deve ser habilitada. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Constrói uma instância do objeto [StreamReader](./) que lê caracteres do arquivo especificado usando a codificação especificada e um buffer com tamanho padrão de 4096 bytes. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**) | Constrói uma instância do objeto [StreamReader](./) que lê caracteres do stream subjacente especificado usando a codificação especificada e um buffer com tamanho padrão de 4096 bytes. Um parâmetro especifica se a detecção de marca de ordem de bytes deve ser habilitada. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**, int) | Constrói uma instância do objeto [StreamReader](./) que lê caracteres do arquivo especificado usando a codificação especificada e um buffer do tamanho especificado. Um parâmetro especifica se a detecção de marca de ordem de bytes deve ser habilitada. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogia ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destrói o objeto. Libera todas as estruturas de dados internas. |
|  [~StreamReader](./~streamreader/)() | Destrutor. |

## Veja Também

* Classe [TextReader](../textreader/)
* Namespace [System::IO](../)
* Biblioteca [Aspose.Slides](../../)