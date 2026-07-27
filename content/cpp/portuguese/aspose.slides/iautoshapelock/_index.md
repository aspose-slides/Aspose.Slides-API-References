---
title: IAutoShapeLock
second_title: Referência da API Aspose.Slides para C++
description: Determina quais operações são desativadas no AutoshapeEx pai.
type: docs
weight: 1379
url: /pt/aspose.slides/iautoshapelock/
---
## IAutoShapeLock classe


Determina quais operações são desativadas no AutoshapeEx pai.

```cpp
class IAutoShapeLock : public virtual Aspose::Slides::IBaseShapeLock
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica [Object.Equals](../../system/object/equals/) do C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora segundo IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora segundo IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para fins internos. |
| virtual **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() | Determina se a alteração de valores de ajuste é proibida. Lê **bool**. |
| virtual **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() | Determina se a alteração de pontas de seta é proibida. Lê **bool**. |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | Determina se uma forma deve preservar a proporção ao redimensionar. Lê **bool**. |
| virtual **bool** [get_EditPointsLocked](./get_editpointslocked/)() | Determina se a alteração direta do contorno desta forma é proibida. Lê **bool**. |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | Determina se a adição desta forma a um grupo é proibida. Lê **bool**. |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | Retorna true se todas as bandeiras de bloqueio estiverem desativadas. Somente leitura **bool**. |
| virtual **bool** [get_PositionLocked](./get_positionlocked/)() | Determina se mover esta forma é proibido. Lê **bool**. |
| virtual **bool** [get_RotateLocked](./get_rotatelocked/)() | Determina se a alteração do ângulo de rotação desta forma é proibida. Lê **bool**. |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | Determina se selecionar esta forma é proibido. Lê **bool**. |
| virtual **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() | Determina se a mudança do tipo de forma é proibida. Lê **bool**. |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | Determina se redimensionar esta forma é proibido. Lê **bool**. |
| virtual **bool** [get_TextLocked](./get_textlocked/)() | Determina se editar texto é proibido. Lê **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analógico do método [Object.GetHashCode()](../../system/object/gethashcode/) do C#. Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analógico da chamada [System.Object.GetType()](../../system/object/gettype/) do C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analógico do operador 'is' do C#. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução lock() do C#. Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analógico do método [Object.MemberwiseClone()](../../system/object/memberwiseclone/) do C#. Permite clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópia de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhado pelo valor especificado. |
| virtual void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) | Determina se a alteração de valores de ajuste é proibida. Grava **bool**. |
| virtual void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) | Determina se a alteração de pontas de seta é proibida. Grava **bool**. |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | Determina se uma forma deve preservar a proporção ao redimensionar. Grava **bool**. |
| virtual void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) | Determina se a alteração direta do contorno desta forma é proibida. Grava **bool**. |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | Determina se a adição desta forma a um grupo é proibida. Grava **bool**. |
| virtual void [set_PositionLocked](./set_positionlocked/)(**bool**) | Determina se mover esta forma é proibido. Grava **bool**. |
| virtual void [set_RotateLocked](./set_rotatelocked/)(**bool**) | Determina se a alteração do ângulo de rotação desta forma é proibida. Grava **bool**. |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | Determina se selecionar esta forma é proibido. Grava **bool**. |
| virtual void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) | Determina se a mudança do tipo de forma é proibida. Grava **bool**. |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | Determina se redimensionar esta forma é proibido. Grava **bool**. |
| virtual void [set_TextLocked](./set_textlocked/)(**bool**) | Determina se editar texto é proibido. Grava **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhado. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhado. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhado. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analógico do método [Object.ToString()](../../system/object/tostring/) do C#. Permite converter objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa a liberação da instrução lock() do C#. Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Veja Também

* Classe [IBaseShapeLock](../ibaseshapelock/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)