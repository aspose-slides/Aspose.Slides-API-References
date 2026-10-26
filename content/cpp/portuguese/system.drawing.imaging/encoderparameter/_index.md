---
title: EncoderParameter
second_title: Referência da API Aspose.Slides para C++
description: "Serve como um contêiner usado para passar valores a um codificador de imagem. Objetos desta classe devem ser alocados apenas usando a função System::MakeObject(). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro System::SmartPtr e use esse ponteiro para passá-lo a funções como argumento."
type: docs
weight: 66
url: /pt/system.drawing.imaging/encoderparameter/
---
## EncoderParameter classe

Serve como um contêiner usado para passar valores para um codificador de imagem. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento.

```cpp
class EncoderParameter : public System::Object
```

## Métodos

| Método | Descrição |
| --- | --- |
|  [EncoderParameter](./encoderparameter/)() | Constrói uma nova instância da classe [EncoderParameter](./). |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, **uint8_t**, **bool**) | Constrói uma nova instância da classe [EncoderParameter](./). |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, **int16_t**) | Constrói uma nova instância da classe [EncoderParameter](./). |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, **int64_t**) | Constrói uma nova instância da classe [EncoderParameter](./). |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, **int32_t**) | Constrói uma nova instância da classe [EncoderParameter](./). |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, **int32_t**, **int32_t**) | Constrói uma nova instância da classe [EncoderParameter](./) que representa uma fração. |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, **int64_t**, **int64_t**) | Constrói uma nova instância da classe [EncoderParameter](./) que representa um intervalo de valores inteiros. |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, **int32_t**, **int32_t**, **int32_t**, **int32_t**) | Constrói uma nova instância da classe [EncoderParameter](./) que representa um intervalo de frações. |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, const [String](../../system/string/)\&) | Constrói uma nova instância da classe [EncoderParameter](./). |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **bool**) | Constrói uma nova instância da classe [EncoderParameter](./) que representa um array de valores. |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int16_t**\>\&) | Constrói uma nova instância da classe [EncoderParameter](./) que representa um array de valores. |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int64_t**\>\&) | Constrói uma nova instância da classe [EncoderParameter](./) que representa um array de valores. |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int32_t**\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int32_t**\>\&) | Constrói uma nova instância da classe [EncoderParameter](./) que representa um array de frações. |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int64_t**\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int64_t**\>\&) | Constrói uma nova instância da classe [EncoderParameter](./) que representa um array de intervalos de inteiros. |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int32_t**\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int32_t**\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int32_t**\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int32_t**\>\&) | Constrói uma nova instância da classe [EncoderParameter](./) que representa um array de intervalos de frações. |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, int, [EncoderParameterValueType](../encoderparametervaluetype/), void *) | Constrói uma nova instância da classe [EncoderParameter](./) que representa o número especificado de valores do tipo especificado que são lidos do buffer especificado. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica [Object.Equals](../../system/object/equals/) do C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não é igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não é igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| [EncoderPtr](../encoderptr/) [get_Encoder](./get_encoder/)() const | Retorna o objeto [Encoder](../encoder/) associado ao objeto [EncoderParameter](./) atual. |
| int [get_NumberOfValues](./get_numberofvalues/)() const | Retorna o número de valores representados pelo objeto atual. |
| [EncoderParameterValueType](../encoderparametervaluetype/) [get_Type](./get_type/)() const | Retorna o tipo do(s) valor(es) representado(s) pelo objeto atual. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referências associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método [Object.GetHashCode()](../../system/object/gethashcode/) do C#. Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada [System.Object.GetType()](../../system/object/gettype/) do C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador 'is' do C#. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução lock() do C#. Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método [Object.MemberwiseClone()](../../system/object/memberwiseclone/) do C#. Permite a clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência o objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referências compartilhadas pelo valor especificado. |
| void [set_Encoder](./set_encoder/)(const [EncoderPtr](../encoderptr/)\&) | Associa o objeto [Encoder](../encoder/) especificado ao objeto [EncoderParameter](./) atual. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de template como um ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referências compartilhadas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referências compartilhadas. Não deve ser chamado diretamente; ao invés disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referências compartilhadas. Não deve ser chamado diretamente; ao invés disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método [Object.ToString()](../../system/object/tostring/) do C#. Permite converter objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução lock() do C#. Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referências fracas. Não deve ser chamado diretamente; ao invés disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referências fracas. Não deve ser chamado diretamente; ao invés disso, use ponteiros inteligentes ou ThisProtector. |
|  [~EncoderParameter](./~encoderparameter/)() | Destrutor. |
| virtual  [~Object](../../system/object/~object/)() | Destrói o objeto. Libera todas as estruturas de dados internas. |

## Veja Também

* Classe [Object](../../system/object/)
* Namespace [System::Drawing::Imaging](../)
* Biblioteca [Aspose.Slides](../../)