---
title: Reflection
second_title: Referência da API Aspose.Slides para C++
description: Representa um efeito de Reflexão.
type: docs
weight: 1067
url: /pt/aspose.slides.effects/reflection/
---
## Reflection classe

Representa um efeito [Reflection](./).

```cpp
class Reflection : public Aspose::Slides::Effects::IReflection,
                   public Aspose::Slides::Effects::IVisualEffect,
                   public Aspose::Slides::IPVIObject
```

## Métodos

| Método | Descrição |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Determina se o [Reflection](./) especificado é igual ao [Reflection](./) atual. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica [Object.Equals](../../system/object/equals/) do C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência ao estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante ao estilo C#, onde dois NaNs são considerados iguais, ainda que segundo IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante ao estilo C#, onde dois NaNs são considerados iguais, ainda que segundo IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| **double** [get_BlurRadius](./get_blurradius/)() override | [Blur](../blur/) raio. Lê **double**. |
| **float** [get_Direction](./get_direction/)() override | Direção da reflexão. Lê **float**. |
| **double** [get_Distance](./get_distance/)() override | Distância da reflexão. Lê **double**. |
| **float** [get_EndPosAlpha](./get_endposalpha/)() override | Especifica a posição final (ao longo da rampa de gradiente alfa) do valor alfa final (porcentagens). Lê **float**. |
| **float** [get_EndReflectionOpacity](./get_endreflectionopacity/)() override | Opacidade final da reflexão. (porcentagens). Lê **float**. |
| **float** [get_FadeDirection](./get_fadedirection/)() override | Especifica a direção para deslocar a reflexão. (ângulo). Lê **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | Retorna o [IPresentationComponent](../../aspose.slides/ipresentationcomponent/) pai. Somente leitura [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() override | Alinhamento do retângulo. Lê [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() override | Especifica se a reflexão deve girar com a forma quando a forma é rotacionada. Lê **bool**. |
| **double** [get_ScaleHorizontal](./get_scalehorizontal/)() override | Especifica o fator de escala horizontal, escala negativa causa inversão. (porcentagens) Lê **double**. |
| **double** [get_ScaleVertical](./get_scalevertical/)() override | Especifica o fator de escala vertical, escala negativa causa inversão. (porcentagens) Lê **double**. |
| **double** [get_SkewHorizontal](./get_skewhorizontal/)() override | Especifica o ângulo de inclinação horizontal. Lê **double**. |
| **double** [get_SkewVertical](./get_skewvertical/)() override | Especifica o ângulo de inclinação vertical. Lê **double**. |
| **float** [get_StartPosAlpha](./get_startposalpha/)() override | Especifica a posição inicial (ao longo da rampa de gradiente alfa) do valor alfa inicial (porcentagens). Lê **float**. |
| **float** [get_StartReflectionOpacity](./get_startreflectionopacity/)() override | Opacidade inicial da reflexão. (porcentagens). Lê **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API **uint32_t** [get_Version](../../aspose.slides/ipviobject/get_version/)() | Versão. Somente leitura **uint32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| [System::SharedPtr](../../system/sharedptr/)\<[IReflectionEffectiveData](../ireflectioneffectivedata/)\> [GetEffective](./geteffective/)() override | Obtém os dados de efeito [Reflection](./) efetivo com a herança aplicada. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Serve como função de hash para um tipo específico. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analogia à chamada [System.Object.GetType()](../../system/object/gettype/) do C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analogia ao operador 'is' do C#. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução lock() do C#. Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogia ao método [Object.MemberwiseClone()](../../system/object/memberwiseclone/) do C#. Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas internas de dados. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia ao construir subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia ao construir subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [set_BlurRadius](./set_blurradius/)(**double**) override | [Blur](../blur/) raio. Escreve **double**. |
| void [set_Direction](./set_direction/)(**float**) override | Direção da reflexão. Escreve **float**. |
| void [set_Distance](./set_distance/)(**double**) override | Distância da reflexão. Escreve **double**. |
| void [set_EndPosAlpha](./set_endposalpha/)(**float**) override | Especifica a posição final (ao longo da rampa de gradiente alfa) do valor alfa final (porcentagens). Escreve **float**. |
| void [set_EndReflectionOpacity](./set_endreflectionopacity/)(**float**) override | Opacidade final da reflexão. (porcentagens). Escreve **float**. |
| void [set_FadeDirection](./set_fadedirection/)(**float**) override | Especifica a direção para deslocar a reflexão. (ângulo). Escreve **float**. |
| void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) override | Alinhamento do retângulo. Escreve [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) override | Especifica se a reflexão deve girar com a forma quando a forma é rotacionada. Escreve **bool**. |
| void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) override | Especifica o fator de escala horizontal, escala negativa causa inversão. (porcentagens) Escreve **double**. |
| void [set_ScaleVertical](./set_scalevertical/)(**double**) override | Especifica o fator de escala vertical, escala negativa causa inversão. (porcentagens) Escreve **double**. |
| void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) override | Especifica o ângulo de inclinação horizontal. Escreve **double**. |
| void [set_SkewVertical](./set_skewvertical/)(**double**) override | Especifica o ângulo de inclinação vertical. Escreve **double**. |
| void [set_StartPosAlpha](./set_startposalpha/)(**float**) override | Especifica a posição inicial (ao longo da rampa de gradiente alfa) do valor alfa inicial (porcentagens). Escreve **float**. |
| void [set_StartReflectionOpacity](./set_startreflectionopacity/)(**float**) override | Opacidade inicial da reflexão. (porcentagens). Escreve **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogia ao método [Object.ToString()](../../system/object/tostring/) do C#. Permite converter objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução lock() do C#. Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas internas de dados. |

## Veja Também

* Classe [IReflection](../ireflection/)
* Classe [IVisualEffect](../ivisualeffect/)
* Classe [IPVIObject](../../aspose.slides/ipviobject/)
* Namespace [Aspose::Slides::Effects](../)
* Biblioteca [Aspose.Slides](../../)