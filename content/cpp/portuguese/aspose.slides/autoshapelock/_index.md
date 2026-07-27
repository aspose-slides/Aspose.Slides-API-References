---
title: AutoShapeLock
second_title: Referência da API Aspose.Slides para C++
description: Determina quais operações são desativadas no AutoshapeEx pai.
type: docs
weight: 79
url: /pt/aspose.slides/autoshapelock/
---
## AutoShapeLock classe


Determina quais operações são desativadas no AutoshapeEx pai.

```cpp
class AutoShapeLock : public Aspose::Slides::BaseShapeLock,
                      public Aspose::Slides::IAutoShapeLock
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante ao estilo C#, onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, inclusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante ao estilo C#, onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, inclusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() override | Determina se a alteração dos valores de ajuste é proibida. Leitura **bool**. |
| **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() override | Determina se a alteração das pontas de flecha é proibida. Leitura **bool**. |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | Determina se uma forma deve preservar a proporção ao redimensionar. Leitura **bool**. |
| **bool** [get_EditPointsLocked](./get_editpointslocked/)() override | Determina se a alteração direta do contorno desta forma é proibida. Leitura **bool**. |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | Determina se a adição desta forma a um grupo é proibida. Leitura **bool**. |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | Retorna verdadeiro se todas as bandeiras de bloqueio estiverem desativadas. **bool** somente leitura. |
| **bool** [get_PositionLocked](./get_positionlocked/)() override | Determina se mover esta forma é proibido. Leitura **bool**. |
| **bool** [get_RotateLocked](./get_rotatelocked/)() override | Determina se a alteração do ângulo de rotação desta forma é proibida. Leitura **bool**. |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | Determina se a seleção desta forma é proibida. Leitura **bool**. |
| **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() override | Determina se a alteração do tipo de forma é proibida. Leitura **bool**. |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | Determina se o redimensionamento desta forma é proibido. Leitura **bool**. |
| **bool** [get_TextLocked](./get_textlocked/)() override | Determina se a edição de texto é proibida. Leitura **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hashing de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias em subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias em subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) override | Determina se a alteração dos valores de ajuste é proibida. Escrita **bool**. |
| void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) override | Determina se a alteração das pontas de flecha é proibida. Escrita **bool**. |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | Determina se uma forma deve preservar a proporção ao redimensionar. Escrita **bool**. |
| void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) override | Determina se a alteração direta do contorno desta forma é proibida. Escrita **bool**. |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | Determina se a adição desta forma a um grupo é proibida. Escrita **bool**. |
| void [set_PositionLocked](./set_positionlocked/)(**bool**) override | Determina se mover esta forma é proibido. Escrita **bool**. |
| void [set_RotateLocked](./set_rotatelocked/)(**bool**) override | Determina se a alteração do ângulo de rotação desta forma é proibida. Escrita **bool**. |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | Determina se a seleção desta forma é proibida. Escrita **bool**. |
| void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) override | Determina se a alteração do tipo de forma é proibida. Escrita **bool**. |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | Determina se o redimensionamento desta forma é proibido. Escrita **bool**. |
| void [set_TextLocked](./set_textlocked/)(**bool**) override | Determina se a edição de texto é proibida. Escrita **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de template como ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |
## Veja Também

* Classe [BaseShapeLock](../baseshapelock/)
* Classe [IAutoShapeLock](../iautoshapelock/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)