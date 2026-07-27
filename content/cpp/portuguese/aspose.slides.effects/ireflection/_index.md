---
title: IReflection
second_title: Referência da API Aspose.Slides para C++
description: Representa um efeito de reflexão.
type: docs
weight: 937
url: /pt/aspose.slides.effects/ireflection/
---
## IReflection classe

Representa um efeito de reflexão.

```cpp
class IReflection : public virtual Aspose::Slides::Effects::IImageTransformOperation,
                    public Aspose::Slides::IAccessiblePVIObject<System::SharedPtr<Aspose::Slides::Effects::IReflectionEffectiveData>>
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não é igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não é igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| virtual **double** [get_BlurRadius](./get_blurradius/)() | [Blur](../blur/) raio. Leia **double**. |
| virtual **float** [get_Direction](./get_direction/)() | Direção da reflexão. Leia **float**. |
| virtual **double** [get_Distance](./get_distance/)() | Distância da reflexão. Leia **double**. |
| virtual **float** [get_EndPosAlpha](./get_endposalpha/)() | Especifica a posição final (ao longo da rampa de gradiente alfa) do valor alfa final (porcentagens). Leia **float**. |
| virtual **float** [get_EndReflectionOpacity](./get_endreflectionopacity/)() | Opacidade final da reflexão. (porcentagens). Leia **float**. |
| virtual **float** [get_FadeDirection](./get_fadedirection/)() | Especifica a direção para deslocar a reflexão. (ângulo). Leia **float**. |
| virtual [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() | Alinhamento do retângulo. Leia [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() | Especifica se a reflexão deve girar com a forma se a forma for girada. Leia **bool**. |
| virtual **double** [get_ScaleHorizontal](./get_scalehorizontal/)() | Especifica o fator de escala horizontal, escala negativa provoca inversão. (porcentagens) Leia **double**. |
| virtual **double** [get_ScaleVertical](./get_scalevertical/)() | Especifica o fator de escala vertical, escala negativa provoca inversão. (porcentagens) Leia **double**. |
| virtual **double** [get_SkewHorizontal](./get_skewhorizontal/)() | Especifica o ângulo de inclinação horizontal. Leia **double**. |
| virtual **double** [get_SkewVertical](./get_skewvertical/)() | Especifica o ângulo de inclinação vertical. Leia **double**. |
| virtual **float** [get_StartPosAlpha](./get_startposalpha/)() | Especifica a posição inicial (ao longo da rampa de gradiente alfa) do valor alfa inicial (porcentagens). Leia **float**. |
| virtual **float** [get_StartReflectionOpacity](./get_startreflectionopacity/)() | Opacidade inicial da reflexão. (porcentagens). Leia **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual T [GetEffective](../../aspose.slides/iaccessiblepviobject/geteffective/)() | Obtém os dados efetivos com a herança aplicada. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hashing de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| virtual void [set_BlurRadius](./set_blurradius/)(**double**) | [Blur](../blur/) raio. Grava **double**. |
| virtual void [set_Direction](./set_direction/)(**float**) | Direção da reflexão. Grava **float**. |
| virtual void [set_Distance](./set_distance/)(**double**) | Distância da reflexão. Grava **double**. |
| virtual void [set_EndPosAlpha](./set_endposalpha/)(**float**) | Especifica a posição final (ao longo da rampa de gradiente alfa) do valor alfa final (porcentagens). Grava **float**. |
| virtual void [set_EndReflectionOpacity](./set_endreflectionopacity/)(**float**) | Opacidade final da reflexão. (porcentagens). Grava **float**. |
| virtual void [set_FadeDirection](./set_fadedirection/)(**float**) | Especifica a direção para deslocar a reflexão. (ângulo). Grava **float**. |
| virtual void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) | Alinhamento do retângulo. Grava [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) | Especifica se a reflexão deve girar com a forma se a forma for girada. Grava **bool**. |
| virtual void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) | Especifica o fator de escala horizontal, escala negativa provoca inversão. (porcentagens) Grava **double**. |
| virtual void [set_ScaleVertical](./set_scalevertical/)(**double**) | Especifica o fator de escala vertical, escala negativa provoca inversão. (porcentagens) Grava **double**. |
| virtual void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) | Especifica o ângulo de inclinação horizontal. Grava **double**. |
| virtual void [set_SkewVertical](./set_skewvertical/)(**double**) | Especifica o ângulo de inclinação vertical. Grava **double**. |
| virtual void [set_StartPosAlpha](./set_startposalpha/)(**float**) | Especifica a posição inicial (ao longo da rampa de gradiente alfa) do valor alfa inicial (porcentagens). Grava **float**. |
| virtual void [set_StartReflectionOpacity](./set_startreflectionopacity/)(**float**) | Opacidade inicial da reflexão. (porcentagens). Grava **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
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

* Classe [IImageTransformOperation](../iimagetransformoperation/)
* Classe [IAccessiblePVIObject](../../aspose.slides/iaccessiblepviobject/)
* Namespace [Aspose::Slides::Effects](../)
* Biblioteca [Aspose.Slides](../../)