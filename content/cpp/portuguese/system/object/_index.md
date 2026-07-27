---
title: Object
second_title: Referência da API Aspose.Slides para C++
description: Classe base que permite usar os métodos disponíveis para a classe System.Object em C#. Todas as classes não triviais usadas no ambiente traduzido devem herdar dela.
type: docs
weight: 1132
url: /pt/system/object/
---
## Classe Object


Classe base que permite usar os métodos disponíveis para a classe [System.Object](./) em C#. Todas as classes não triviais usadas no ambiente traduzido devem herdar dela.

```cpp
class Object
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual **bool** [Equals](./equals/)([ptr](./ptr/)) | Compara objetos usando a semântica C# [Object.Equals](./equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](./equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](./equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](./equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante ao estilo C#, onde dois NaNs são considerados iguais, mesmo que segundo IEC 60559:1989 o NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](./equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante ao estilo C#, onde dois NaNs são considerados iguais, mesmo que segundo IEC 60559:1989 o NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](./fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| Detail::SmartPtrCounter * [GetCounter](./getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](./gethashcode/)() const | Analogia ao método C# [Object.GetHashCode()](./gethashcode/). Permite o hashing de objetos personalizados. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const | Obtém o tipo real do objeto. Analogia à chamada C# [System.Object.GetType()](./gettype/). |
| virtual **bool** [Is](./is/)(const [TypeInfo](../typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analogia ao operador C# 'is'. |
| void [Lock](./lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../lockcontext/). |
| virtual [ptr](./ptr/) [MemberwiseClone](./memberwiseclone/)() const | Analogia ao método C# [Object.MemberwiseClone()](./memberwiseclone/). Permite a clonagem de tipos personalizados. |
|  [Object](./object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](./object/)([Object](./) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção por cópia de subclasses. |
| [Object](./)\& [operator=](./operator_equal/)([Object](./) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção por cópia de subclasses. |
| static **bool** [ReferenceEquals](./referenceequals/)([ptr](./ptr/) const\&, [ptr](./ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](./referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](./referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](./referenceequals/)([String](../string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](./referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](./referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Especialização de [Object::ReferenceEquals](./referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](./removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| virtual void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de template como ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para o modo fraco. |
| int [SharedCount](./sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](./) * [SharedRefAdded](./sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](./sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../string/) [ToString](./tostring/)() const | Analogia ao método C# [Object.ToString()](./tostring/). Permite converter objetos personalizados para string. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Implementa a construção C# typeof([System.Object](./)). |
| void [Unlock](./unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](./weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](./weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](./~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |
## Tipos Definidos

| Tipo Definido | Descrição |
| --- | --- |
| [ptr](./ptr/) | Apelido para o tipo de ponteiro inteligente. |
## Observações


Além dos métodos disponíveis na classe C# [System.Object](./), também permite suporte a alguns conceitos específicos do ambiente de código traduzido. Isso inclui contagem de referência usada pelas classes de ponteiro inteligente ([System::SmartPtr](../smartptr/), [System::WeakPtr](../weakptr/), [System::DynamicWeakPtr](../dynamicweakptr/)) e outros serviços relacionados à gerenciamento de memória, depuração, etc.

Cada [Object](./) possui dois contadores de referência: contador de referência compartilhada e contador de referência fraca. O contador de referência fraca é sempre armazenado em uma estrutura de dados separada, e não no próprio [Object](./), o que permite que ponteiros fracos sobrevivam ao objeto referenciado. O contador de referência inteligente é armazenado ou no próprio objeto ou na mesma estrutura separada, dependendo do estado da macro ENABLE_EXTERNAL_REFCOUNT. Por padrão, ele está ativado em compilações de depuração e desativado em compilações de release. Se o contador de ponteiro inteligente estiver armazenado no próprio objeto, a estrutura separada é criada apenas se existirem ponteiros fracos para o objeto. Caso contrário, ela é criada junto com o próprio objeto.

Todos os ponteiros inteligentes usam esses dois contadores de referência e contribuem para o mesmo e único grupo de propriedade.

Se uma subclasse [Object](./) for criada na pilha, nenhum ponteiro inteligente para ela pode ser criado, caso contrário haverá um problema de exclusão na pilha.

Este tipo pode ser alocado tanto na pilha como tipo valor quanto no heap usando a função [System::MakeObject()](../makeobject/). Uma vez que o objeto é alocado, nunca misture esses dois casos de uso: ter ponteiros [SmartPtr](../smartptr/) para objetos alocados na pilha é estritamente proibido. 
## Veja Também

* Namespace [System](../)
* Library [Aspose.Slides](../../)