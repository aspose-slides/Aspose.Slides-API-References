---
title: StringWriter
second_title: Referência da API Aspose.Slides para C++
description: "Implementa um TextWriter que grava informações em uma string. Objetos desta classe devem ser alocados apenas usando a função System::MakeObject(). Nunca crie uma instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro System::SmartPtr e use esse ponteiro para passá-lo a funções como argumento."
type: docs
weight: 417
url: /pt/system.io/stringwriter/
---
## StringWriter classe

Implementa um [TextWriter](../textwriter/) que grava informações em uma string. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie uma instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento.

```cpp
class StringWriter : public System::IO::TextWriter
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual void [Close](../textwriter/close/)() | Fecha o fluxo e libera recursos adquiridos. |
| void [Dispose](../textwriter/dispose/)() override | Libera todos os recursos usados pelo objeto atual e fecha o fluxo subjacente. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora segundo IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora segundo IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para fins internos. |
| virtual void [Flush](../textwriter/flush/)() | Despeja o conteúdo do buffer no fluxo subjacente. |
| [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() override | Retorna a codificação atualmente usada. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](../textwriter/get_formatprovider/)() const | Retorna o objeto [IFormatProvider](../../system/iformatprovider/) atualmente usado. |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](../textwriter/get_formatprovider/)() | Retorna o objeto [IFormatProvider](../../system/iformatprovider/) atualmente usado. |
| virtual [System::String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() const | Retorna uma string terminadora de linha. |
| [String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() | Retorna uma string terminadora de linha. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite a hash de objetos personalizados. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\> [GetStringBuilder](./getstringbuilder/)() | Retorna o StringBuilder atualmente usado. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite a clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas internas de dados. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção por cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção por cópia de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| virtual void [set_NewLine](../textwriter/set_newline/)(const [System::String](../../system/string/)\&) | Define uma string terminadora de linha. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de template como um ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
|  [StringWriter](./stringwriter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | Constrói uma nova instância de [StringWriter](./) usando o StringBuilder especificado e [IFormatProvider](../../system/iformatprovider/). |
|  [StringWriter](./stringwriter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | Constrói uma nova instância de [StringWriter](./) usando o StringBuilder especificado e [IFormatProvider](../../system/iformatprovider/) da cultura atual. |
|  [StringWriter](./stringwriter/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | Constrói uma nova instância de [StringWriter](./) usando o [IFormatProvider](../../system/iformatprovider/) especificado. |
|  [StringWriter](./stringwriter/)() | Constrói uma nova instância de [StringWriter](./) usando [IFormatProvider](../../system/iformatprovider/) da cultura atual. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Retorna a string subjacente. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa o construto C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| void [Write](./write/)(char_t) override | Escreve o caractere especificado no fluxo. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Escreve o sub-intervalo especificado de caracteres do array de caracteres especificado no fluxo. |
| void [Write](./write/)(const [String](../../system/string/)\&) override | Escreve a string especificada no fluxo. |
| virtual void [Write](../textwriter/write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Escreve a representação em string do objeto especificado no fluxo. |
| virtual void [Write](../textwriter/write/)(**bool**) | Escreve a representação em string do valor booleano especificado no fluxo. |
| virtual void [Write](../textwriter/write/)([Decimal](../../system/decimal/)) | Escreve a representação em string do objeto [Decimal](../../system/decimal/) especificado no fluxo. |
| virtual void [Write](../textwriter/write/)(**double**) | Escreve a representação em string do valor de ponto flutuante de dupla precisão especificado no fluxo. |
| virtual void [Write](../textwriter/write/)(int) | Escreve a representação em string do valor inteiro de 32 bits especificado no fluxo. |
| virtual void [Write](../textwriter/write/)(**int64_t**) | Escreve a representação em string do valor inteiro de 64 bits especificado no fluxo. |
| virtual void [Write](../textwriter/write/)(**float**) | Escreve a representação em string do valor de ponto flutuante de precisão simples especificado no fluxo. |
| virtual void [Write](../textwriter/write/)(**uint32_t**) | Escreve a representação em string do valor inteiro sem sinal de 32 bits especificado no fluxo. |
| virtual void [Write](../textwriter/write/)(**uint64_t**) | Escreve a representação em string do valor inteiro sem sinal de 64 bits especificado no fluxo. |
| virtual void [Write](../textwriter/write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Escreve todos os caracteres do array especificado no fluxo. |
| virtual void [Write](../textwriter/write/)(const char_t *) | Escreve a c-string especificada no fluxo. |
| virtual void [Write](../textwriter/write/)(const [TypeInfo](../../system/typeinfo/)\&) | Escreve a representação em string do objeto [TypeInfo](../../system/typeinfo/) especificado no fluxo. |
| void [Write](../textwriter/write/)(const [String](../../system/string/)\&, const TArgs\&...) | Escreve os valores especificados formatados de acordo com o formato especificado no fluxo. |
| virtual void [WriteLine](../textwriter/writeline/)() | Escreve os caracteres terminadores de linha no fluxo. |
| virtual void [WriteLine](../textwriter/writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Escreve a representação em string do objeto especificado seguida pelos caracteres terminadores de linha no fluxo. |
| virtual void [WriteLine](../textwriter/writeline/)(**bool**) | Escreve a representação em string do valor booleano especificado seguida pelos caracteres terminadores de linha no fluxo. |
| virtual void [WriteLine](../textwriter/writeline/)(char_t) | Escreve o caractere especificado seguido pelos caracteres terminadores de linha no fluxo. |
| virtual void [WriteLine](../textwriter/writeline/)([Decimal](../../system/decimal/)) | Escreve a representação em string do objeto [Decimal](../../system/decimal/) especificado seguida pelos caracteres terminadores de linha no fluxo. |
| virtual void [WriteLine](../textwriter/writeline/)(**double**) | Escreve a representação em string do valor de ponto flutuante de dupla precisão especificado seguida pelos caracteres terminadores de linha no fluxo. |
| virtual void [WriteLine](../textwriter/writeline/)(int) | Escreve a representação em string do valor inteiro de 32 bits especificado seguida pelos caracteres terminadores de linha no fluxo. |
| virtual void [WriteLine](../textwriter/writeline/)(**int64_t**) | Escreve a representação em string do valor inteiro de 64 bits especificado seguida pelos caracteres terminadores de linha no fluxo. |
| virtual void [WriteLine](../textwriter/writeline/)(**float**) | Escreve a representação em string do valor de ponto flutuante de precisão simples especificado seguida pelos caracteres terminadores de linha no fluxo. |
| virtual void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&) | Escreve a string especificada seguida pelos caracteres terminadores de linha no fluxo. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint32_t**) | Escreve a representação em string do valor inteiro sem sinal de 32 bits especificado seguida pelos caracteres terminadores de linha no fluxo. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint64_t**) | Escreve a representação em string do valor inteiro sem sinal de 64 bits especificado seguida pelos caracteres terminadores de linha no fluxo. |
| virtual void [WriteLine](../textwriter/writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Escreve todos os caracteres do array especificado seguida pelos caracteres terminadores de linha no fluxo. |
| virtual void [WriteLine](../textwriter/writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Escreve o sub-intervalo especificado de caracteres UTF-16 do array de caracteres especificado seguido pelos caracteres terminadores de linha no fluxo. |
| virtual void [WriteLine](../textwriter/writeline/)(const char_t *) | Escreve a c-string especificada seguida pelos caracteres terminadores de linha no fluxo. |
| virtual void [WriteLine](../textwriter/writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | Escreve a representação em string do objeto [TypeInfo](../../system/typeinfo/) especificado seguida pelos caracteres terminadores de linha no fluxo. |
| void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | Escreve os valores especificados formatados de acordo com o formato especificado seguida pelos caracteres terminadores de linha no fluxo. |
| virtual  [~Object](../../system/object/~object/)() | Destrói o objeto. Libera todas as estruturas internas de dados. |
| virtual  [~TextWriter](../textwriter/~textwriter/)() | Destrutor. |

## Veja Também

* Classe [TextWriter](../textwriter/)
* Espaço de nomes [System::IO](../)
* Biblioteca [Aspose.Slides](../../)