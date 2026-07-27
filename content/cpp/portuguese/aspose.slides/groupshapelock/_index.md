---
title: GroupShapeLock
second_title: Aspose.Slides para C++ Referência da API
description: Determina quais operações são desativadas no GroupShape pai.
type: docs
weight: 1210
url: /pt/aspose.slides/groupshapelock/
---
## classe GroupShapeLock

Determina quais operações estão desativadas no [GroupShape](../groupshape/) pai.

```cpp
class GroupShapeLock : public Aspose::Slides::BaseShapeLock,
                       public Aspose::Slides::IGroupShapeLock
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica [Object.Equals](../../system/object/equals/) do C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora conforme IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora conforme IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | Determina se a forma deve preservar a proporção ao redimensionar. Leitura **bool**. |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | Determina se a adição desta forma a um grupo é proibida. Leitura **bool**. |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | Retorna verdadeiro se todas as bandeiras de bloqueio estiverem desativadas. Somente leitura **bool**. |
| **bool** [get_PositionLocked](./get_positionlocked/)() override | Determina se mover esta forma é proibido. Leitura **bool**. |
| **bool** [get_RotationLocked](./get_rotationlocked/)() override | Determina se alterar o ângulo de rotação desta forma é proibido. Leitura **bool**. |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | Determina se selecionar esta forma é proibido. Leitura **bool**. |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | Determina se redimensionar esta forma é proibido. Leitura **bool**. |
| **bool** [get_UngroupingLocked](./get_ungroupinglocked/)() override | Determina se dividir este groupshape é proibido. Leitura **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogia ao método [Object.GetHashCode()](../../system/object/gethashcode/) do C#. Permite a criação de hash para objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analogia à chamada [System.Object.GetType()](../../system/object/gettype/) do C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analogia ao operador 'is' do C#. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogia ao método [Object.MemberwiseClone()](../../system/object/memberwiseclone/) do C#. Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade, não copia nada, apenas inicializa um novo objeto e habilita a construção por cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade, não copia nada, apenas inicializa um novo objeto e habilita a construção por cópia de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | Determina se a forma deve preservar a proporção ao redimensionar. Escrita **bool**. |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | Determina se a adição desta forma a um grupo é proibida. Escrita **bool**. |
| void [set_PositionLocked](./set_positionlocked/)(**bool**) override | Determina se mover esta forma é proibido. Escrita **bool**. |
| void [set_RotationLocked](./set_rotationlocked/)(**bool**) override | Determina se alterar o ângulo de rotação desta forma é proibido. Escrita **bool**. |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | Determina se selecionar esta forma é proibido. Escrita **bool**. |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | Determina se redimensionar esta forma é proibido. Escrita **bool**. |
| void [set_UngroupingLocked](./set_ungroupinglocked/)(**bool**) override | Determina se dividir este groupshape é proibido. Escrita **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para o modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogia ao método [Object.ToString()](../../system/object/tostring/) do C#. Permite converter objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Veja Também

* Classe [BaseShapeLock](../baseshapelock/)
* Classe [IGroupShapeLock](../igroupshapelock/)
* Namespace [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)