---
title: IEffectFormat
second_title: Referência da API Aspose.Slides para Java
description: Representa propriedades de efeito da forma.
type: docs
url: /pt/com.aspose.slides/ieffectformat/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IEffectParamSource](../../com.aspose.slides/ieffectparamsource)
```
public interface IEffectFormat extends IEffectParamSource
```

Representa propriedades de efeito da forma.
## Métodos

| Método | Descrição |
| --- | --- |
| [isNoEffects()](#isNoEffects--) | Retorna true se todos os efeitos estiverem desativados (como recém-criado, objeto EffectFormat padrão). |
| [getBlurEffect()](#getBlurEffect--) | Efeito de desfoque. |
| [setBlurEffect(IBlur value)](#setBlurEffect-com.aspose.slides.IBlur-) | Efeito de desfoque. |
| [getFillOverlayEffect()](#getFillOverlayEffect--) | Efeito de sobreposição de preenchimento. |
| [setFillOverlayEffect(IFillOverlay value)](#setFillOverlayEffect-com.aspose.slides.IFillOverlay-) | Efeito de sobreposição de preenchimento. |
| [getGlowEffect()](#getGlowEffect--) | Efeito de brilho. |
| [setGlowEffect(IGlow value)](#setGlowEffect-com.aspose.slides.IGlow-) | Efeito de brilho. |
| [getInnerShadowEffect()](#getInnerShadowEffect--) | Sombra interna. |
| [setInnerShadowEffect(IInnerShadow value)](#setInnerShadowEffect-com.aspose.slides.IInnerShadow-) | Sombra interna. |
| [getOuterShadowEffect()](#getOuterShadowEffect--) | Sombra externa. |
| [setOuterShadowEffect(IOuterShadow value)](#setOuterShadowEffect-com.aspose.slides.IOuterShadow-) | Sombra externa. |
| [getPresetShadowEffect()](#getPresetShadowEffect--) | Sombra predefinida. |
| [setPresetShadowEffect(IPresetShadow value)](#setPresetShadowEffect-com.aspose.slides.IPresetShadow-) | Sombra predefinida. |
| [getReflectionEffect()](#getReflectionEffect--) | Reflexo. |
| [setReflectionEffect(IReflection value)](#setReflectionEffect-com.aspose.slides.IReflection-) | Reflexo. |
| [getSoftEdgeEffect()](#getSoftEdgeEffect--) | Borda suave. |
| [setSoftEdgeEffect(ISoftEdge value)](#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-) | Borda suave. |
| [setBlurEffect(double radius, boolean grow)](#setBlurEffect-double-boolean-) | Define efeito de desfoque. |
| [enableFillOverlayEffect()](#enableFillOverlayEffect--) | Habilita efeito de sobreposição de preenchimento. |
| [enableGlowEffect()](#enableGlowEffect--) | Habilita efeito de brilho. |
| [enableInnerShadowEffect()](#enableInnerShadowEffect--) | Habilita efeito de sombra interna. |
| [enableOuterShadowEffect()](#enableOuterShadowEffect--) | Habilita efeito de sombra externa. |
| [enablePresetShadowEffect()](#enablePresetShadowEffect--) | Habilita efeito de sombras predefinidas. |
| [enableReflectionEffect()](#enableReflectionEffect--) | Habilita efeito de reflexo. |
| [enableSoftEdgeEffect()](#enableSoftEdgeEffect--) | Habilita efeito de borda suave. |
| [disableBlurEffect()](#disableBlurEffect--) | Desabilita efeito de desfoque. |
| [disableFillOverlayEffect()](#disableFillOverlayEffect--) | Desabilita efeito de sobreposição de preenchimento. |
| [disableGlowEffect()](#disableGlowEffect--) | Desabilita efeito de brilho. |
| [disableInnerShadowEffect()](#disableInnerShadowEffect--) | Desabilita efeito de sombra interna. |
| [disableOuterShadowEffect()](#disableOuterShadowEffect--) | Desabilita efeito de sombra externa. |
| [disablePresetShadowEffect()](#disablePresetShadowEffect--) | Desabilita efeito de sombra predefinida. |
| [disableReflectionEffect()](#disableReflectionEffect--) | Desabilita efeito de reflexo. |
| [disableSoftEdgeEffect()](#disableSoftEdgeEffect--) | Desabilita efeito de borda suave. |
| [getEffective()](#getEffective--) | Obtém dados de formatação de efeito efetivo com herança aplicada. |

### isNoEffects() {#isNoEffects--}
```
public abstract boolean isNoEffects()
```

Retorna true se todos os efeitos estiverem desativados (como recém-criado, objeto EffectFormat padrão). Somente leitura boolean.

**Retorna:**
boolean

### getBlurEffect() {#getBlurEffect--}
```
public abstract IBlur getBlurEffect()
```

Efeito de desfoque. Leitura/gravação [IBlur](../../com.aspose.slides/iblur).

**Retorna:**
[IBlur](../../com.aspose.slides/iblur)

### setBlurEffect(IBlur value) {#setBlurEffect-com.aspose.slides.IBlur-}
```
public abstract void setBlurEffect(IBlur value)
```

Efeito de desfoque. Leitura/gravação [IBlur](../../com.aspose.slides/iblur).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IBlur](../../com.aspose.slides/iblur) |  |

### getFillOverlayEffect() {#getFillOverlayEffect--}
```
public abstract IFillOverlay getFillOverlayEffect()
```

Efeito de sobreposição de preenchimento. Leitura/gravação [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**Retorna:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay)

### setFillOverlayEffect(IFillOverlay value) {#setFillOverlayEffect-com.aspose.slides.IFillOverlay-}
```
public abstract void setFillOverlayEffect(IFillOverlay value)
```

Efeito de sobreposição de preenchimento. Leitura/gravação [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IFillOverlay](../../com.aspose.slides/ifilloverlay) |  |

### getGlowEffect() {#getGlowEffect--}
```
public abstract IGlow getGlowEffect()
```

Efeito de brilho. Leitura/gravação [IGlow](../../com.aspose.slides/iglow).

**Retorna:**
[IGlow](../../com.aspose.slides/iglow)

### setGlowEffect(IGlow value) {#setGlowEffect-com.aspose.slides.IGlow-}
```
public abstract void setGlowEffect(IGlow value)
```

Efeito de brilho. Leitura/gravação [IGlow](../../com.aspose.slides/iglow).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IGlow](../../com.aspose.slides/iglow) |  |

### getInnerShadowEffect() {#getInnerShadowEffect--}
```
public abstract IInnerShadow getInnerShadowEffect()
```

Sombra interna. Leitura/gravação [IInnerShadow](../../com.aspose.slides/iinnershadow).

**Retorna:**
[IInnerShadow](../../com.aspose.slides/iinnershadow)

### setInnerShadowEffect(IInnerShadow value) {#setInnerShadowEffect-com.aspose.slides.IInnerShadow-}
```
public abstract void setInnerShadowEffect(IInnerShadow value)
```

Sombra interna. Leitura/gravação [IInnerShadow](../../com.aspose.slides/iinnershadow).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IInnerShadow](../../com.aspose.slides/iinnershadow) |  |

### getOuterShadowEffect() {#getOuterShadowEffect--}
```
public abstract IOuterShadow getOuterShadowEffect()
```

Sombra externa. Leitura/gravação [IOuterShadow](../../com.aspose.slides/ioutershadow).

**Retorna:**
[IOuterShadow](../../com.aspose.slides/ioutershadow)

### setOuterShadowEffect(IOuterShadow value) {#setOuterShadowEffect-com.aspose.slides.IOuterShadow-}
```
public abstract void setOuterShadowEffect(IOuterShadow value)
```

Sombra externa. Leitura/gravação [IOuterShadow](../../com.aspose.slides/ioutershadow).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IOuterShadow](../../com.aspose.slides/ioutershadow) |  |

### getPresetShadowEffect() {#getPresetShadowEffect--}
```
public abstract IPresetShadow getPresetShadowEffect()
```

Sombra predefinida. Leitura/gravação [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**Retorna:**
[IPresetShadow](../../com.aspose.slides/ipresetshadow)

### setPresetShadowEffect(IPresetShadow value) {#setPresetShadowEffect-com.aspose.slides.IPresetShadow-}
```
public abstract void setPresetShadowEffect(IPresetShadow value)
```

Sombra predefinida. Leitura/gravação [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IPresetShadow](../../com.aspose.slides/ipresetshadow) |  |

### getReflectionEffect() {#getReflectionEffect--}
```
public abstract IReflection getReflectionEffect()
```

Reflexo. Leitura/gravação [IReflection](../../com.aspose.slides/ireflection).

**Retorna:**
[IReflection](../../com.aspose.slides/ireflection)

### setReflectionEffect(IReflection value) {#setReflectionEffect-com.aspose.slides.IReflection-}
```
public abstract void setReflectionEffect(IReflection value)
```

Reflexo. Leitura/gravação [IReflection](../../com.aspose.slides/ireflection).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IReflection](../../com.aspose.slides/ireflection) |  |

### getSoftEdgeEffect() {#getSoftEdgeEffect--}
```
public abstract ISoftEdge getSoftEdgeEffect()
```

Borda suave. Leitura/gravação [ISoftEdge](../../com.aspose.slides/isoftedge).

**Retorna:**
[ISoftEdge](../../com.aspose.slides/isoftedge)

### setSoftEdgeEffect(ISoftEdge value) {#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-}
```
public abstract void setSoftEdgeEffect(ISoftEdge value)
```

Borda suave. Leitura/gravação [ISoftEdge](../../com.aspose.slides/isoftedge).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [ISoftEdge](../../com.aspose.slides/isoftedge) |  |

### setBlurEffect(double radius, boolean grow) {#setBlurEffect-double-boolean-}
```
public abstract void setBlurEffect(double radius, boolean grow)
```

Define efeito de desfoque.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| radius | double | Raio. |
| grow | boolean | Crescer. |

### enableFillOverlayEffect() {#enableFillOverlayEffect--}
```
public abstract void enableFillOverlayEffect()
```

Habilita efeito de sobreposição de preenchimento.

### enableGlowEffect() {#enableGlowEffect--}
```
public abstract void enableGlowEffect()
```

Habilita efeito de brilho.

### enableInnerShadowEffect() {#enableInnerShadowEffect--}
```
public abstract void enableInnerShadowEffect()
```

Habilita efeito de sombra interna.

### enableOuterShadowEffect() {#enableOuterShadowEffect--}
```
public abstract void enableOuterShadowEffect()
```

Habilita efeito de sombra externa.

### enablePresetShadowEffect() {#enablePresetShadowEffect--}
```
public abstract void enablePresetShadowEffect()
```

Habilita efeito de sombras predefinidas.

### enableReflectionEffect() {#enableReflectionEffect--}
```
public abstract void enableReflectionEffect()
```

Habilita efeito de reflexo.

### enableSoftEdgeEffect() {#enableSoftEdgeEffect--}
```
public abstract void enableSoftEdgeEffect()
```

Habilita efeito de borda suave.

### disableBlurEffect() {#disableBlurEffect--}
```
public abstract void disableBlurEffect()
```

Desabilita efeito de desfoque.

### disableFillOverlayEffect() {#disableFillOverlayEffect--}
```
public abstract void disableFillOverlayEffect()
```

Desabilita efeito de sobreposição de preenchimento.

### disableGlowEffect() {#disableGlowEffect--}
```
public abstract void disableGlowEffect()
```

Desabilita efeito de brilho.

### disableInnerShadowEffect() {#disableInnerShadowEffect--}
```
public abstract void disableInnerShadowEffect()
```

Desabilita efeito de sombra interna.

### disableOuterShadowEffect() {#disableOuterShadowEffect--}
```
public abstract void disableOuterShadowEffect()
```

Desabilita efeito de sombra externa.

### disablePresetShadowEffect() {#disablePresetShadowEffect--}
```
public abstract void disablePresetShadowEffect()
```

Desabilita efeito de sombra predefinida.

### disableReflectionEffect() {#disableReflectionEffect--}
```
public abstract void disableReflectionEffect()
```

Desabilita efeito de reflexo.

### disableSoftEdgeEffect() {#disableSoftEdgeEffect--}
```
public abstract void disableSoftEdgeEffect()
```

Desabilita efeito de borda suave.

### getEffective() {#getEffective--}
```
public abstract IEffectFormatEffectiveData getEffective()
```

Obtém dados de formatação de efeito efetivo com herança aplicada.

**Retorna:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata) - Um [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).