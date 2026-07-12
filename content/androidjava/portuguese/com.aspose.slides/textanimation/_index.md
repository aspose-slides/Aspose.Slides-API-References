---
title: TextAnimation
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa animação de texto.
type: docs
url: /pt/com.aspose.slides/textanimation/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.ITextAnimation](../../com.aspose.slides/itextanimation)
```
public class TextAnimation implements ITextAnimation
```

Representa animação de texto.
## Construtores

| Construtor | Descrição |
| --- | --- |
| [TextAnimation()](#TextAnimation--) |  |
## Métodos

| Método | Descrição |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | Adiciona um novo efeito ao final da sequência atual até o final das animações de texto em grupo. |
| [getBuildType()](#getBuildType--) | Lista de tipo de construção (por exemplo. |
| [setBuildType(int value)](#setBuildType-int-) | Lista de tipo de construção (por exemplo. |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | Efeito de forma vinculada ao grupo ou não (null). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | Efeito de forma vinculada ao grupo ou não (null). |
### TextAnimation() {#TextAnimation--}
```
public TextAnimation()
```


### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public final IEffect addEffect(int effectType, int subtype, int triggerType)
```


Adiciona um novo efeito ao final da sequência atual até o final das animações de texto em grupo. Válido somente se a contagem de parágrafos de texto for igual ou maior que a contagem de efeitos deste grupo!

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| effectType | int | Tipo de um efeito de animação [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Subtipos de efeito de animação [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Tipo de gatilho do efeito [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Retorno:**
[IEffect](../../com.aspose.slides/ieffect) - Novo objeto de efeito [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public final int getBuildType()
```


Lista de tipo de construção (ex.: Parágrafo 1,2,3, Todos de Uma Vez) da animação de texto. Leitura/gravação [BuildType](../../com.aspose.slides/buildtype).

**Retorno:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public final void setBuildType(int value)
```


Lista de tipo de construção (ex.: Parágrafo 1,2,3, Todos de Uma Vez) da animação de texto. Leitura/gravação [BuildType](../../com.aspose.slides/buildtype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public final IEffect getEffectAnimateBackgroundShape()
```


Efeito de forma vinculada ao grupo ou não (null). Leitura/gravação [IEffect](../../com.aspose.slides/ieffect).

**Retorno:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public final void setEffectAnimateBackgroundShape(IEffect value)
```


Efeito de forma vinculada ao grupo ou não (null). Leitura/gravação [IEffect](../../com.aspose.slides/ieffect).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |