---
title: StreamWriter
second_title: Referência da API Aspose.Slides para C++
description: "Representa um gravador que escreve caracteres em um fluxo de bytes. Objetos desta classe devem ser alocados somente usando a função System::MakeObject(). Nunca crie instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro System::SmartPtr e use esse ponteiro para passá-lo a funções como argumento."
type: docs
weight: 391
url: /pt/system.io/streamwriter/
---
## StreamWriter classe

Representa um gravador que escreve caracteres em um fluxo de bytes. Objetos desta classe devem ser alocados somente usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento.

```cpp
class StreamWriter : public System::IO::TextWriter
```

## Métodos

| Method | Description |
| --- | --- |
| void [Close](./close/)() override | Fecha o fluxo e libera os recursos adquiridos. |
| void [Dispose](./dispose/)() override | Libera todos os recursos usados pelo objeto atual e fecha o fluxo subjacente. |
| virtual void [Dispose](./dispose/)(**bool**) | Libera todos os recursos usados pelo objeto atual e fecha o fluxo subjacente. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos do tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos do tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| void [Flush](./flush/)() override | Despeja o conteúdo do buffer para o fluxo subjacente e então despeja o fluxo subjacente. |
| **bool** [get_AutoFlush](./get_autoflush/)() const | Retorna um valor que indica se o [StreamWriter](./) descartará os dados para o fluxo subjacente toda vez que o método [StreamWriter::Write](./write/) for chamado. |
| [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() const | Retorna um ponteiro compartilhado para um objeto que representa o fluxo subjacente. |
| [EncodingPtr](../../system/encodingptr/) [get_Encoding](./get_encoding/)() override | Retorna a codificação atualmente usada. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](../textwriter/get_formatprovider/)() const | Retorna o objeto [IFormatProvider](../../system/iformatprovider/) atualmente usado. |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](../textwriter/get_formatprovider/)() | Retorna o objeto [IFormatProvider](../../system/iformatprovider/) atualmente usado. |
| virtual [System::String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() const | Retorna uma string terminadora de linha. |
| [String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() | Retorna uma string terminadora de linha. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referências associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópia de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto do tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [set_AutoFlush](./set_autoflush/)(**bool**) | Retorna um valor que especifica se o [StreamWriter](./) deve descartar os dados para o fluxo subjacente toda vez que o método [StreamWriter::Write](./write/) for chamado. |
| virtual void [set_NewLine](../textwriter/set_newline/)(const [System::String](../../system/string/)\&) | Define uma string terminadora de linha. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de template como um ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Constrói uma instância do objeto [StreamWriter](./) que grava caracteres no fluxo subjacente especificado usando codificação UTF-8 e um buffer com tamanho padrão de 1024 bytes. |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Constrói uma instância do objeto [StreamWriter](./) que grava caracteres no fluxo subjacente especificado usando a codificação especificada e um buffer com tamanho padrão de 1024 bytes. |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, int, **bool**) | Constrói uma instância do objeto [StreamWriter](./) que grava caracteres no fluxo subjacente especificado usando a codificação especificada e um buffer do tamanho especificado. Um parâmetro indica se o fluxo subjacente deve ser fechado quando o objeto [StreamWriter](./) for descartado. |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&) | Constrói uma instância do objeto [StreamWriter](./) que grava caracteres no arquivo especificado usando codificação UTF-8 e um buffer com tamanho padrão de 1024 bytes. |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&, **bool**, const [EncodingPtr](../../system/encodingptr/)\&) | Constrói uma instância do objeto [StreamWriter](./) que grava caracteres no arquivo especificado usando a codificação especificada e um buffer com tamanho padrão de 1024 bytes. Um parâmetro indica se os dados devem ser acrescentados ao arquivo ou se o arquivo deve ser sobrescrito. |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&, **bool**, const [EncodingPtr](../../system/encodingptr/)\&, int) | Constrói uma instância do objeto [StreamWriter](./) que grava caracteres no arquivo especificado usando a codificação especificada e tamanho de buffer. Um parâmetro indica se os dados devem ser acrescentados ao arquivo ou se o arquivo deve ser sobrescrito. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| void [Write](./write/)(char_t) override | Grava o caractere especificado no fluxo. |
| void [Write](./write/)(const [String](../../system/string/)\&) override | Grava a string especificada no fluxo. |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) override | Grava a representação em string do objeto especificado no fluxo. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) override | Grava todos os caracteres do array especificado no fluxo. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Grava o subintervalo especificado de caracteres UTF-16 do array de caracteres especificado no fluxo. |
| void [Write](./write/)(const char_t *) override | Grava a c-string especificada no fluxo. |
| void [Write](./write/)(const [System::SharedPtr](../../system/sharedptr/)\<T\>\&) | Grava a representação em string do objeto especificado no fluxo. |
| virtual void [Write](../textwriter/write/)(**bool**) | Grava a representação em string do valor booleano especificado no fluxo. |
| virtual void [Write](../textwriter/write/)([Decimal](../../system/decimal/)) | Grava a representação em string do objeto [Decimal](../../system/decimal/) especificado no fluxo. |
| virtual void [Write](../textwriter/write/)(**double**) | Grava a representação em string do valor de ponto flutuante de dupla precisão especificado no fluxo. |
| virtual void [Write](../textwriter/write/)(int) | Grava a representação em string do valor inteiro de 32 bits especificado no fluxo. |
| virtual void [Write](../textwriter/write/)(**int64_t**) | Grava a representação em string do valor inteiro de 64 bits especificado no fluxo. |
| virtual void [Write](../textwriter/write/)(**float**) | Grava a representação em string do valor de ponto flutuante de precisão simples especificado no fluxo. |
| virtual void [Write](../textwriter/write/)(**uint32_t**) | Grava a representação em string do valor inteiro sem sinal de 32 bits especificado no fluxo. |
| virtual void [Write](../textwriter/write/)(**uint64_t**) | Grava a representação em string do valor inteiro sem sinal de 64 bits especificado no fluxo. |
| virtual void [Write](../textwriter/write/)(const [TypeInfo](../../system/typeinfo/)\&) | Grava a representação em string do objeto [TypeInfo](../../system/typeinfo/) especificado no fluxo. |
| void [Write](../textwriter/write/)(const [String](../../system/string/)\&, const TArgs\&...) | Grava os valores especificados formatados de acordo com o formato especificado no fluxo. |
| void [WriteLine](./writeline/)() override | Grava caracteres terminadores de linha no fluxo. |
| void [WriteLine](./writeline/)(const [String](../../system/string/)\&) override | Grava a string especificada seguida pelos caracteres terminadores de linha no fluxo. |
| void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) override | Grava a representação em string do objeto especificado seguida pelos caracteres terminadores de linha no fluxo. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) override | Grava todos os caracteres do array especificado seguido pelos caracteres terminadores de linha no fluxo. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Grava o subintervalo especificado de caracteres UTF-16 do array de caracteres especificado seguido pelos caracteres terminadores de linha no fluxo. |
| void [WriteLine](./writeline/)(const char_t *) override | Grava a c-string especificada seguida pelos caracteres terminadores de linha no fluxo. |
| void [WriteLine](./writeline/)(const [System::SharedPtr](../../system/sharedptr/)\<T\>\&) | Grava a representação em string do objeto especificado seguida pelos caracteres terminadores de linha no fluxo. |
| virtual void [WriteLine](../textwriter/writeline/)(**bool**) | Grava a representação em string do valor booleano especificado seguida pelos caracteres terminadores de linha no fluxo. |
| virtual void [WriteLine](../textwriter/writeline/)(char_t) | Grava o caractere especificado seguido pelos caracteres terminadores de linha no fluxo. |
| virtual void [WriteLine](../textwriter/writeline/)([Decimal](../../system/decimal/)) | Grava a representação em string do objeto [Decimal](../../system/decimal/) especificado seguida pelos caracteres terminadores de linha no fluxo. |
| virtual void [WriteLine](../textwriter/writeline/)(**double**) | Grava a representação em string do valor de ponto flutuante de dupla precisão especificado seguida pelos caracteres terminadores de linha no fluxo. |
| virtual void [WriteLine](../textwriter/writeline/)(int) | Grava a representação em string do valor inteiro de 32 bits especificado seguida pelos caracteres terminadores de linha no fluxo. |
| virtual void [WriteLine](../textwriter/writeline/)(**int64_t**) | Grava a representação em string do valor inteiro de 64 bits especificado seguida pelos caracteres terminadores de linha no fluxo. |
| virtual void [WriteLine](../textwriter/writeline/)(**float**) | Grava a representação em string do valor de ponto flutuante de precisão simples especificado seguida pelos caracteres terminadores de linha no fluxo. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint32_t**) | Grava a representação em string do valor inteiro sem sinal de 32 bits especificado seguida pelos caracteres terminadores de linha no fluxo. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint64_t**) | Grava a representação em string do valor inteiro sem sinal de 64 bits especificado seguida pelos caracteres terminadores de linha no fluxo. |
| virtual void [WriteLine](../textwriter/writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | Grava a representação em string do objeto [TypeInfo](../../system/typeinfo/) especificado seguida pelos caracteres terminadores de linha no fluxo. |
| void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | Grava os valores especificados formatados de acordo com o formato especificado seguida pelos caracteres terminadores de linha no fluxo. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |
|  [~StreamWriter](./~streamwriter/)() | Destrutor. |
| virtual  [~TextWriter](../textwriter/~textwriter/)() | Destrutor. |

## Veja Também

* Classe [TextWriter](../textwriter/)
* Namespace [System::IO](../)
* Biblioteca [Aspose.Slides](../../)