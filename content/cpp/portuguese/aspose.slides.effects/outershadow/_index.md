---
title: OuterShadow
second_title: Referência da API Aspose.Slides para C++
description: Representa um efeito de sombra externa.
type: docs
weight: 1041
url: /pt/aspose.slides.effects/outershadow/
---
## OuterShadow classe

Representa um efeito de sombra externa.

```cpp
class OuterShadow : public Aspose::Slides::Effects::IOuterShadow,
                    public Aspose::Slides::Effects::IVisualEffect,
                    public Aspose::Slides::IPVIObject
```

## Métodos

| Método | Descrição |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Determina se o [OuterShadow](./) especificado é igual ao [OuterShadow](./) atual. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante ao estilo C#, onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante ao estilo C#, onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| **double** [get_BlurRadius](./get_blurradius/)() override | [Blur](../blur/) raio, em pontos. Valor padrão — 0 pt. Somente leitura **double**. |
| **float** [get_Direction](./get_direction/)() override | Direção da sombra, em graus. Valor padrão — 0 ° (da esquerda para a direita). Somente leitura **float**. |
| **double** [get_Distance](./get_distance/)() override | Distância da sombra ao objeto, em pontos. Valor padrão — 0 pt. Somente leitura **double**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | Retorna o [IPresentationComponent](../../aspose.slides/ipresentationcomponent/) pai. Só de leitura [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() override | Alinhamento do retângulo. Valor padrão — [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Somente leitura [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() override | Indica se a sombra gira junto com a forma. Valor padrão — true. Somente leitura **bool**. |
| **double** [get_ScaleHorizontal](./get_scalehorizontal/)() override | Fator de escala horizontal, em porcentagem do tamanho original. Escala negativa inverte. Valor padrão — 100 %. Somente leitura **double**. |
| **double** [get_ScaleVertical](./get_scalevertical/)() override | Fator de escala vertical, em porcentagem do tamanho original. Escala negativa inverte. Valor padrão — 100 %. Somente leitura **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ShadowColor](./get_shadowcolor/)() override | Cor da sombra. Valor padrão — preto automático (dependente do tema). Só de leitura [IColorFormat](../../aspose.slides/icolorformat/). |
| **double** [get_SkewHorizontal](./get_skewhorizontal/)() override | Ângulo de inclinação horizontal, em graus. Valor padrão — 0 °. Somente leitura **double**. |
| **double** [get_SkewVertical](./get_skewvertical/)() override | Ângulo de inclinação vertical, em graus. Valor padrão — 0 °. Somente leitura **double**. |
| virtual ASPOSE_SLIDES_LOCAL_API **uint32_t** [get_Version](../../aspose.slides/ipviobject/get_version/)() | Versão. Só de leitura **uint32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| [System::SharedPtr](../../system/sharedptr/)\<[IOuterShadowEffectiveData](../ioutershadoweffectivedata/)\> [GetEffective](./geteffective/)() override | Obtém os dados efetivos do efeito Outer Shadow com a herança aplicada. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Serve como função hash para um tipo específico. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa bloqueio da declaração C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [set_BlurRadius](./set_blurradius/)(**double**) override | [Blur](../blur/) raio, em pontos. Valor padrão — 0 pt. Escrita **double**. |
| void [set_Direction](./set_direction/)(**float**) override | Direção da sombra, em graus. Valor padrão — 0 ° (da esquerda para a direita). Escrita **float**. |
| void [set_Distance](./set_distance/)(**double**) override | Distância da sombra ao objeto, em pontos. Valor padrão — 0 pt. Escrita **double**. |
| void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) override | Alinhamento do retângulo. Valor padrão — [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Escrita [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) override | Indica se a sombra gira junto com a forma. Valor padrão — true. Escrita **bool**. |
| void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) override | Fator de escala horizontal, em porcentagem do tamanho original. Escala negativa inverte. Valor padrão — 100 %. Escrita **double**. |
| void [set_ScaleVertical](./set_scalevertical/)(**double**) override | Fator de escala vertical, em porcentagem do tamanho original. Escala negativa inverte. Valor padrão — 100 %. Escrita **double**. |
| void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) override | Ângulo de inclinação horizontal, em graus. Valor padrão — 0 °. Escrita **double**. |
| void [set_SkewVertical](./set_skewvertical/)(**double**) override | Ângulo de inclinação vertical, em graus. Valor padrão — 0 °. Escrita **double**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa desbloqueio da declaração C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Ver também

* Classe [IOuterShadow](../ioutershadow/)
* Classe [IVisualEffect](../ivisualeffect/)
* Classe [IPVIObject](../../aspose.slides/ipviobject/)
* Espaço de nomes [Aspose::Slides::Effects](../)
* Biblioteca [Aspose.Slides](../../)