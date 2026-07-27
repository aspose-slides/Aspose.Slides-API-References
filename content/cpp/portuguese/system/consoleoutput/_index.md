---
title: ConsoleOutput
second_title: Referência da API Aspose.Slides para C++
description: "Representa o fluxo de saída padrão. Objetos desta classe devem ser alocados apenas usando a função System::MakeObject(). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro System::SmartPtr e use esse ponteiro para passá-lo a funções como argumento."
type: docs
weight: 209
url: /pt/system/consoleoutput/
---
## ConsoleOutput classe

Representa o fluxo de saída padrão. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../smartptr/) e use esse ponteiro para passá-lo a funções como argumento.

```cpp
class ConsoleOutput : public System::IO::TextWriter
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual void [Close](../../system.io/textwriter/close/)() | Fecha o fluxo e libera os recursos adquiridos. |
| void [Dispose](../../system.io/textwriter/dispose/)() override | Libera todos os recursos usados pelo objeto atual e fecha o fluxo subjacente. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para fins internos. |
| virtual void [Flush](../../system.io/textwriter/flush/)() | Despeja o conteúdo do buffer no fluxo subjacente. |
| [SharedPtr](../sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() override | Sempre retorna codificação ASCII. |
| virtual [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\> [get_FormatProvider](../../system.io/textwriter/get_formatprovider/)() const | Retorna o objeto [IFormatProvider](../iformatprovider/) atualmente usado. |
| [IFormatProviderPtr](../iformatproviderptr/) [get_FormatProvider](../../system.io/textwriter/get_formatprovider/)() | Retorna o objeto [IFormatProvider](../iformatprovider/) atualmente usado. |
| virtual [System::String](../string/) [get_NewLine](../../system.io/textwriter/get_newline/)() const | Retorna uma string de terminador de linha. |
| [String](../string/) [get_NewLine](../../system.io/textwriter/get_newline/)() | Retorna uma string de terminador de linha. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analoga ao método C# [Object.GetHashCode()](../object/gethashcode/). Permite a hash de objetos personalizados. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Obtém o tipo real do objeto. Analoga à chamada C# [System.Object.GetType()](../object/gettype/). |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analoga ao operador C# 'is'. |
| void [Lock](../object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analoga ao método C# [Object.MemberwiseClone()](../object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../object/object/)([Object](../object/) const\&) | Construtor de cópia. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a cópia de subclasses. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operador de atribuição. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a cópia de subclasses. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Especialização de [Object::ReferenceEquals](../object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| virtual void [set_NewLine](../../system.io/textwriter/set_newline/)(const [System::String](../string/)\&) | Define uma string de terminador de linha. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de template como ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Analoga ao método C# [Object.ToString()](../object/tostring/). Permite converter objetos personalizados em string. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementa o construto C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [Write](./write/)(**bool**) override | Saída a representação em string do valor bool especificado para o fluxo de saída representado pelo objeto atual. |
| void [Write](./write/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) override | Saída a representação em string do objeto especificado para o fluxo de saída representado pelo objeto atual. |
| void [Write](./write/)(char_t) override | Saída o valor de caractere especificado para o fluxo de saída representado pelo objeto atual. |
| void [Write](./write/)([Decimal](../decimal/)) override | Saída a representação em string do valor [Decimal](../decimal/) para o fluxo de saída representado pelo objeto atual. |
| void [Write](./write/)(**double**) override | Saída a representação em string de valor de ponto flutuante de precisão dupla para o fluxo de saída representado pelo objeto atual. |
| void [Write](./write/)(**int32_t**) override | Saída a representação em string de valor inteiro de 32 bits para o fluxo de saída representado pelo objeto atual. |
| void [Write](./write/)(**int64_t**) override | Saída a representação em string de valor inteiro de 64 bits para o fluxo de saída representado pelo objeto atual. |
| void [Write](./write/)(**float**) override | Saída a representação em string de valor de ponto flutuante de precisão simples para o fluxo de saída representado pelo objeto atual. |
| void [Write](./write/)(const [String](../string/)\&) override | Saída o objeto string especificado para o fluxo de saída representado pelo objeto atual. |
| void [Write](./write/)(**uint32_t**) override | Saída a representação em string de valor inteiro sem sinal de 32 bits para o fluxo de saída representado pelo objeto atual. |
| void [Write](./write/)(**uint64_t**) override | Saída a representação em string de valor inteiro sem sinal de 64 bits para o fluxo de saída representado pelo objeto atual. |
| void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) override | Saída a representação em string do array de caracteres especificado para o fluxo de saída representado pelo objeto atual. |
| void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Saída a representação em string de um intervalo de valores do array de caracteres especificado para o fluxo de saída representado pelo objeto atual. |
| void [Write](./write/)(const char_t *) override | Saída a c-string especificada para o fluxo de saída representado pelo objeto atual. |
| void [Write](./write/)(const [TypeInfo](../typeinfo/)\&) override | Saída a representação em string do objeto [TypeInfo](../typeinfo/) especificado para o fluxo de saída representado pelo objeto atual. |
| void [Write](./write/)(const char *) |  |
| virtual void [Write](../../system.io/textwriter/write/)(int) | Escreve a representação em string do valor inteiro de 32 bits especificado no fluxo. |
| void [Write](../../system.io/textwriter/write/)(const [String](../string/)\&, const TArgs\&...) | Escreve os valores especificados formatados de acordo com o formato especificado no fluxo. |
| void [WriteLine](./writeline/)() override | Saída o terminador de linha atual para o fluxo de saída representado pelo objeto atual. |
| void [WriteLine](./writeline/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) override | Saída a representação em string do objeto especificado seguida pelo terminador de linha atual para o fluxo de saída representado pelo objeto atual. |
| void [WriteLine](./writeline/)(**bool**) override | Saída a representação em string do valor bool especificado seguida pelo terminador de linha atual para o fluxo de saída representado pelo objeto atual. |
| void [WriteLine](./writeline/)(char_t) override | Saída o valor de caractere especificado seguido pelo terminador de linha atual para o fluxo de saída representado pelo objeto atual. |
| void [WriteLine](./writeline/)([Decimal](../decimal/)) override | Saída a representação em string do valor [Decimal](../decimal/) seguida pelo terminador de linha atual para o fluxo de saída representado pelo objeto atual. |
| void [WriteLine](./writeline/)(**double**) override | Saída a representação em string de valor de ponto flutuante de precisão dupla seguida pelo terminador de linha atual para o fluxo de saída representado pelo objeto atual. |
| void [WriteLine](./writeline/)(int) override | Saída a representação em string de valor inteiro de 32 bits seguida pelo terminador de linha atual para o fluxo de saída representado pelo objeto atual. |
| void [WriteLine](./writeline/)(**int64_t**) override | Saída a representação em string de valor inteiro de 64 bits seguida pelo terminador de linha atual para o fluxo de saída representado pelo objeto atual. |
| void [WriteLine](./writeline/)(**float**) override | Saída a representação em string de valor de ponto flutuante de precisão simples seguida pelo terminador de linha atual para o fluxo de saída representado pelo objeto atual. |
| void [WriteLine](./writeline/)(const [String](../string/)\&) override | Saída o objeto string especificado seguido pelo terminador de linha atual para o fluxo de saída representado pelo objeto atual. |
| void [WriteLine](./writeline/)(**uint32_t**) override | Saída a representação em string de valor inteiro sem sinal de 32 bits seguida pelo terminador de linha atual para o fluxo de saída representado pelo objeto atual. |
| void [WriteLine](./writeline/)(**uint64_t**) override | Saída a representação em string de valor inteiro sem sinal de 64 bits seguida pelo terminador de linha atual para o fluxo de saída representado pelo objeto atual. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) override | Saída a representação em string do array de caracteres especificado seguida pelo terminador de linha atual para o fluxo de saída representado pelo objeto atual. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Saída a representação em string de um intervalo de valores do array de caracteres especificado seguida pelo terminador de linha atual para o fluxo de saída representado pelo objeto atual. |
| void [WriteLine](./writeline/)(const char_t *) override | Saída a c-string especificada seguida pelo terminador de linha atual para o fluxo de saída representado pelo objeto atual. |
| void [WriteLine](./writeline/)(const [TypeInfo](../typeinfo/)\&) override | Saída a representação em string do objeto [TypeInfo](../typeinfo/) especificado seguida pelo terminador de linha atual para o fluxo de saída representado pelo objeto atual. |
| void [WriteLine](./writeline/)(const char *) |  |
| void [WriteLine](../../system.io/textwriter/writeline/)(const [String](../string/)\&, const TArgs\&...) | Escreve os valores especificados formatados de acordo com o formato especificado seguidos pelos caracteres de término de linha no fluxo. |
| virtual  [~Object](../object/~object/)() | Destrói o objeto. Libera todas as estruturas de dados internas. |
| virtual  [~TextWriter](../../system.io/textwriter/~textwriter/)() | Destrutor. |

## Veja Também

* Classe [TextWriter](../../system.io/textwriter/)
* Namespace [System](../)
* Biblioteca [Aspose.Slides](../../)