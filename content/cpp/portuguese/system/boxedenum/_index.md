---
title: BoxedEnum
second_title: Referência da API Aspose.Slides para C++
description: "Representa um valor de enumeração encapsulado. Objetos desta classe devem ser alocados somente usando a função System::MakeObject() . Nunca crie instância deste tipo na pilha ou usando o operador new, pois resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro System::SmartPtr e use esse ponteiro para passá-lo a funções como argumento."
type: docs
weight: 92
url: /pt/system/boxedenum/
---
## BoxedEnum classe

Representa um valor de enumeração encapsulado. Objetos desta classe devem ser alocados somente usando a função [System::MakeObject()](../makeobject/). Nunca crie instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre embrulhe esta classe em um ponteiro [System::SmartPtr](../smartptr/) e use esse ponteiro para passá-lo a funções como argumento.

```cpp
template<typename E,typename UT>class BoxedEnum : public System::BoxedValue<typename std::underlying_type<E>::type>
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| E | Tipo do valor da enumeração |
| UT | O tipo subjacente da enumeração **E** |

## Métodos

| Método | Descrição |
| --- | --- |
|  [BoxedEnum](./boxedenum/)(E) | Constrói uma instância que representa o valor da enumeração especificado. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não é igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não é igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Obtém a estrutura de dados do contador de referências associado ao objeto. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analogo do método C# [Object.GetHashCode()](../object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Obtém o tipo real do objeto. Analogo da chamada C# [System.Object.GetType()](../object/gettype/). |
| virtual [TypeCode](../typecode/) [GetTypeCode](../boxedvaluebase/gettypecode/)() const | Retorna o valor que representa o tipo do valor encapsulado representado pelo objeto atual. |
| **uint64_t** [GetUnsignedLongLongValue](./getunsignedlonglongvalue/)() const override | Converte o valor da constante da enumeração encapsulada para um valor inteiro de 64 bits. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analogo do operador C# 'is'. |
| **bool** [IsBoxedEnum](./isboxedenum/)() override | Determina se o objeto atual representa um valor encapsulado do tipo enum. |
| void [Lock](../object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analogo do método C# [Object.MemberwiseClone()](../object/memberwiseclone/). Permite clonagem de tipos personalizados. |
|  [Object](../object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../object/object/)([Object](../object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../boxedvaluebase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | Encapsula o valor da constante de enumeração da enumeração especificada com o nome especificado. Um parâmetro indica se a diferença entre maiúsculas e minúsculas deve ser ignorada ao interpretar a string que especifica o nome da constante da enumeração. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../boxedvaluebase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&) | Encapsula o valor da constante de enumeração da enumeração especificada com o nome especificado. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Especialização de [Object::ReferenceEquals](../object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Diminui o contador de referências compartilhadas pelo valor especificado. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de template como ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../object/sharedcount/)() const | Obtém o valor atual do contador de referências compartilhadas. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Incrementa o contador de referências compartilhadas. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referências compartilhadas. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| [System::String](../string/) [ToString](./tostring/)() const override | Converte o valor encapsulado representado pelo objeto atual para string. |
| [System::String](../string/) [ToString](../boxedvaluebase/tostring/)(const [System::String](../string/)\&) const | Converte o objeto encapsulado para string usando a string de formato especificada. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementa a construção C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Incrementa o contador de referências fracas. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Decrementa o contador de referências fracas. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../object/~object/)() | Destrói o objeto. Libera todas as estruturas de dados internas. |

## Ver também

* Classe [BoxedValue](../boxedvalue/)
* Namespace [System](../)
* Biblioteca [Aspose.Slides](../../)