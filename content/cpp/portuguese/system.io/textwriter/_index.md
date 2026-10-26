---
title: TextWriter
second_title: Aspose.Slides para C++ Referência da API
description: "Uma classe base para classes que representam gravadores que escrevem sequências de caracteres em diferentes destinos. Objetos desta classe devem ser alocados apenas usando a função System::MakeObject(). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro System::SmartPtr e use esse ponteiro para passá-lo a funções como argumento."
type: docs
weight: 443
url: /pt/system.io/textwriter/
---
## TextWriter classe

Uma classe base para classes que representam gravadores que escrevem sequências de caracteres em diferentes destinos. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento.

```cpp
class TextWriter : public System::IDisposable
```

## Métodos

| Method | Description |
| --- | --- |
| virtual void [Close](./close/)() | Fecha o fluxo e libera os recursos adquiridos. |
| void [Dispose](./dispose/)() override | Libera todos os recursos usados pelo objeto atual e fecha o fluxo subjacente. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante ao estilo C#, onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, inclusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante ao estilo C#, onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, inclusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| virtual void [Flush](./flush/)() | Despeja o conteúdo do buffer para o fluxo subjacente. |
| virtual [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Retorna a codificação atualmente usada. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](./get_formatprovider/)() const | Retorna o objeto [IFormatProvider](../../system/iformatprovider/) atualmente usado. |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](./get_formatprovider/)() | Retorna o objeto [IFormatProvider](../../system/iformatprovider/) atualmente usado. |
| virtual [System::String](../../system/string/) [get_NewLine](./get_newline/)() const | Retorna uma string terminadora de linha. |
| [String](../../system/string/) [get_NewLine](./get_newline/)() | Retorna uma string terminadora de linha. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analógico ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analógico à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analógico ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analógico ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção por cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção por cópia de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| virtual void [set_NewLine](./set_newline/)(const [System::String](../../system/string/)\&) | Define uma string terminadora de linha. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para o modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analógico ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Escreve a representação em string do objeto especificado no fluxo. |
| virtual void [Write](./write/)(**bool**) | Escreve a representação em string do valor booleano especificado no fluxo. |
| virtual void [Write](./write/)(char_t) | Escreve o caractere especificado no fluxo. |
| virtual void [Write](./write/)([Decimal](../../system/decimal/)) | Escreve a representação em string do objeto [Decimal](../../system/decimal/) especificado no fluxo. |
| virtual void [Write](./write/)(**double**) | Escreve a representação em string do valor de ponto flutuante de precisão dupla especificado no fluxo. |
| virtual void [Write](./write/)(int) | Escreve a representação em string do valor inteiro de 32 bits especificado no fluxo. |
| virtual void [Write](./write/)(**int64_t**) | Escreve a representação em string do valor inteiro de 64 bits especificado no fluxo. |
| virtual void [Write](./write/)(**float**) | Escreve a representação em string do valor de ponto flutuante de precisão simples especificado no fluxo. |
| virtual void [Write](./write/)(const [String](../../system/string/)\&) | Escreve a string especificada no fluxo. |
| virtual void [Write](./write/)(**uint32_t**) | Escreve a representação em string do valor inteiro sem sinal de 32 bits especificado no fluxo. |
| virtual void [Write](./write/)(**uint64_t**) | Escreve a representação em string do valor inteiro sem sinal de 64 bits especificado no fluxo. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Escreve todos os caracteres do array especificado no fluxo. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Escreve o subintervalo especificado de caracteres UTF-16 do array de caracteres especificado no fluxo. |
| virtual void [Write](./write/)(const char_t *) | Escreve a c-string especificada no fluxo. |
| virtual void [Write](./write/)(const [TypeInfo](../../system/typeinfo/)\&) | Escreve a representação em string do objeto [TypeInfo](../../system/typeinfo/) especificado no fluxo. |
| void [Write](./write/)(const [String](../../system/string/)\&, const TArgs\&...) | Escreve os valores especificados formatados de acordo com o formato especificado no fluxo. |
| virtual void [WriteLine](./writeline/)() | Escreve caracteres terminadores de linha no fluxo. |
| virtual void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Escreve a representação em string do objeto especificado seguida pelos caracteres terminadores de linha no fluxo. |
| virtual void [WriteLine](./writeline/)(**bool**) | Escreve a representação em string do valor booleano especificado seguida pelos caracteres terminadores de linha no fluxo. |
| virtual void [WriteLine](./writeline/)(char_t) | Escreve o caractere especificado seguido pelos caracteres terminadores de linha no fluxo. |
| virtual void [WriteLine](./writeline/)([Decimal](../../system/decimal/)) | Escreve a representação em string do objeto [Decimal](../../system/decimal/) especificado seguida pelos caracteres terminadores de linha no fluxo. |
| virtual void [WriteLine](./writeline/)(**double**) | Escreve a representação em string do valor de ponto flutuante de precisão dupla especificado seguida pelos caracteres terminadores de linha no fluxo. |
| virtual void [WriteLine](./writeline/)(int) | Escreve a representação em string do valor inteiro de 32 bits especificado seguida pelos caracteres terminadores de linha no fluxo. |
| virtual void [WriteLine](./writeline/)(**int64_t**) | Escreve a representação em string do valor inteiro de 64 bits especificado seguida pelos caracteres terminadores de linha no fluxo. |
| virtual void [WriteLine](./writeline/)(**float**) | Escreve a representação em string do valor de ponto flutuante de precisão simples especificado seguida pelos caracteres terminadores de linha no fluxo. |
| virtual void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | Escreve a string especificada seguida pelos caracteres terminadores de linha no fluxo. |
| virtual void [WriteLine](./writeline/)(**uint32_t**) | Escreve a representação em string do valor inteiro sem sinal de 32 bits especificado seguida pelos caracteres terminadores de linha no fluxo. |
| virtual void [WriteLine](./writeline/)(**uint64_t**) | Escreve a representação em string do valor inteiro sem sinal de 64 bits especificado seguida pelos caracteres terminadores de linha no fluxo. |
| virtual void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Escreve todos os caracteres do array especificado seguido pelos caracteres terminadores de linha no fluxo. |
| virtual void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Escreve o subintervalo especificado de caracteres UTF-16 do array de caracteres especificado seguido pelos caracteres terminadores de linha no fluxo. |
| virtual void [WriteLine](./writeline/)(const char_t *) | Escreve a c-string especificada seguida pelos caracteres terminadores de linha no fluxo. |
| virtual void [WriteLine](./writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | Escreve a representação em string do objeto [TypeInfo](../../system/typeinfo/) especificado seguida pelos caracteres terminadores de linha no fluxo. |
| void [WriteLine](./writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | Escreve os valores especificados formatados de acordo com o formato especificado seguida pelos caracteres terminadores de linha no fluxo. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |
| virtual  [~TextWriter](./~textwriter/)() | Destrutor. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | Um alias para um ponteiro compartilhado desta classe. |

## Veja Também

* Classe [IDisposable](../../system/idisposable/)
* Namespace [System::IO](../)
* Biblioteca [Aspose.Slides](../../)