---
title: Decoder
second_title: Referência da API Aspose.Slides para C++
description: "Encapsula a decodificação de sequência de bytes em sequência de caracteres. Objetos desta classe devem ser alocados apenas usando a função System::MakeObject(). Nunca crie uma instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro System::SmartPtr e use esse ponteiro para passá-lo a funções como argumento."
type: docs
weight: 14
url: /pt/system.text/decoder/
---
## Decoder classe

Encapsula a decodificação de sequência de bytes em sequência de caracteres. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo às funções como argumento.

```cpp
class Decoder : public System::Object
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual void [Convert](./convert/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, **bool**, int\&, int\&, **bool**\&) | Converte bytes em caracteres. |
| virtual void [Convert](./convert/)(const **uint8_t** *, int, char_t *, int, **bool**, int\&, int\&, **bool**\&) | Converte bytes em caracteres. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não é igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não é igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_Fallback](./get_fallback/)() const | Obtém fallback de tratamento de erro. |
| [DecoderFallbackBufferPtr](../../system/decoderfallbackbufferptr/) [get_FallbackBuffer](./get_fallbackbuffer/)() const | Obtém buffer de fallback. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Obtém o número de caracteres necessários para decodificar um buffer. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, **bool**) | Obtém o número de caracteres necessários para decodificar um buffer. |
| virtual int [GetCharCount](./getcharcount/)(const **uint8_t** *, int, **bool**) | Obtém o número de caracteres necessários para decodificar um buffer. |
| virtual int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | Obtém os caracteres resultantes da decodificação de um buffer. |
| virtual int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int, **bool**) | Obtém os caracteres resultantes da decodificação de um buffer. |
| virtual int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int, **bool**) | Obtém os caracteres resultantes da decodificação de um buffer. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia ao construir subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia ao construir subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| virtual void [Reset](./reset/)() | Limpa o estado interno do decodificador. |
| void [set_Fallback](./set_fallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Define o fallback de tratamento de erro. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n'th argumento de template como um ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Veja Também

* Classe [Object](../../system/object/)
* Espaço de nomes [System::Text](../)
* Biblioteca [Aspose.Slides](../../)