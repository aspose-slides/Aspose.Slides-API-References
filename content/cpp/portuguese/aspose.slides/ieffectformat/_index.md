---
title: IEffectFormat
second_title: Referência da API Aspose.Slides para C++
description: Representa as propriedades de efeito da forma.
type: docs
weight: 2029
url: /pt/aspose.slides/ieffectformat/
---
## IEffectFormat classe

Representa as propriedades de efeito da forma.

```cpp
class IEffectFormat : public Aspose::Slides::IEffectParamSource
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual void [DisableBlurEffect](./disableblureffect/)() | Desativa o efeito de desfoque. |
| virtual void [DisableFillOverlayEffect](./disablefilloverlayeffect/)() | Desativa o efeito de sobreposição de preenchimento. |
| virtual void [DisableGlowEffect](./disablegloweffect/)() | Desativa o efeito de brilho. |
| virtual void [DisableInnerShadowEffect](./disableinnershadoweffect/)() | Desativa o efeito de sombra interna. |
| virtual void [DisableOuterShadowEffect](./disableoutershadoweffect/)() | Desativa o efeito de sombra externa. |
| virtual void [DisablePresetShadowEffect](./disablepresetshadoweffect/)() | Desativa o efeito de sombra predefinida. |
| virtual void [DisableReflectionEffect](./disablereflectioneffect/)() | Desativa o efeito de reflexão. |
| virtual void [DisableSoftEdgeEffect](./disablesoftedgeeffect/)() | Desativa o efeito de borda suave. |
| virtual void [EnableFillOverlayEffect](./enablefilloverlayeffect/)() | Ativa o efeito de sobreposição de preenchimento. |
| virtual void [EnableGlowEffect](./enablegloweffect/)() | Ativa o efeito de brilho. |
| virtual void [EnableInnerShadowEffect](./enableinnershadoweffect/)() | Ativa o efeito de sombra interna. |
| virtual void [EnableOuterShadowEffect](./enableoutershadoweffect/)() | Ativa o efeito de sombra externa. |
| virtual void [EnablePresetShadowEffect](./enablepresetshadoweffect/)() | Ativa o efeito de sombras predefinidas. |
| virtual void [EnableReflectionEffect](./enablereflectioneffect/)() | Ativa o efeito de reflexão. |
| virtual void [EnableSoftEdgeEffect](./enablesoftedgeeffect/)() | Ativa o efeito de borda suave. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante ao estilo C#, onde dois NaNs são considerados iguais, embora segundo IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante ao estilo C#, onde dois NaNs são considerados iguais, embora segundo IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IBlur](../../aspose.slides.effects/iblur/)\> [get_BlurEffect](./get_blureffect/)() | Efeito de desfoque. Leia [Effects::IBlur](../../aspose.slides.effects/iblur/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/)\> [get_FillOverlayEffect](./get_filloverlayeffect/)() | Efeito de sobreposição de preenchimento. Leia [Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IGlow](../../aspose.slides.effects/iglow/)\> [get_GlowEffect](./get_gloweffect/)() | Efeito de brilho. Leia [Effects::IGlow](../../aspose.slides.effects/iglow/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/)\> [get_InnerShadowEffect](./get_innershadoweffect/)() | Sombra interna. Leia [Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/). |
| virtual **bool** [get_IsNoEffects](./get_isnoeffects/)() | Retorna true se todos os efeitos estiverem desativados (como o objeto [EffectFormat](../effectformat/) recém-criado, padrão). **bool** somente leitura. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/)\> [get_OuterShadowEffect](./get_outershadoweffect/)() | Sombra externa. Leia [Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/)\> [get_PresetShadowEffect](./get_presetshadoweffect/)() | Sombra predefinida. Leia [Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IReflection](../../aspose.slides.effects/ireflection/)\> [get_ReflectionEffect](./get_reflectioneffect/)() | Reflexão. Leia [Effects::IReflection](../../aspose.slides.effects/ireflection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/)\> [get_SoftEdgeEffect](./get_softedgeeffect/)() | Borda suave. Leia [Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormatEffectiveData](../ieffectformateffectivedata/)\> [GetEffective](./geteffective/)() | Obtém os dados de formatação de efeito efetivo com a herança aplicada. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Habilita hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Habilita a clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia ao construir subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia ao construir subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| virtual void [set_BlurEffect](./set_blureffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IBlur](../../aspose.slides.effects/iblur/)\>) | Efeito de desfoque. Grava [Effects::IBlur](../../aspose.slides.effects/iblur/). |
| virtual void [set_FillOverlayEffect](./set_filloverlayeffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/)\>) | Efeito de sobreposição de preenchimento. Grava [Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/). |
| virtual void [set_GlowEffect](./set_gloweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IGlow](../../aspose.slides.effects/iglow/)\>) | Efeito de brilho. Grava [Effects::IGlow](../../aspose.slides.effects/iglow/). |
| virtual void [set_InnerShadowEffect](./set_innershadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/)\>) | Sombra interna. Grava [Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/). |
| virtual void [set_OuterShadowEffect](./set_outershadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/)\>) | Sombra externa. Grava [Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/). |
| virtual void [set_PresetShadowEffect](./set_presetshadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/)\>) | Sombra predefinida. Grava [Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/). |
| virtual void [set_ReflectionEffect](./set_reflectioneffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IReflection](../../aspose.slides.effects/ireflection/)\>) | Reflexão. Grava [Effects::IReflection](../../aspose.slides.effects/ireflection/). |
| virtual void [set_SoftEdgeEffect](./set_softedgeeffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/)\>) | Borda suave. Grava [Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/). |
| virtual void [SetBlurEffect](./setblureffect/)(**double**, **bool**) | Define o efeito de desfoque. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de template como ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e devolve o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Habilita a conversão de objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destrói o objeto. Libera todas as estruturas de dados internas. |

## Veja também

* Classe [IEffectParamSource](../ieffectparamsource/)
* Namespace [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)