---
title: IEffectFormat
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa as propriedades de efeito da forma.
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
| [getReflectionEffect()](#getReflectionEffect--) | Reflexão. |
| [setReflectionEffect(IReflection value)](#setReflectionEffect-com.aspose.slides.IReflection-) | Reflexão. |
| [getSoftEdgeEffect()](#getSoftEdgeEffect--) | Borda suave. |
| [setSoftEdgeEffect(ISoftEdge value)](#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-) | Borda suave. |
| [setBlurEffect(double radius, boolean grow)](#setBlurEffect-double-boolean-) | Define o efeito de desfoque. |
| [enableFillOverlayEffect()](#enableFillOverlayEffect--) | Ativa o efeito de sobreposição de preenchimento. |
| [enableGlowEffect()](#enableGlowEffect--) | Ativa o efeito de brilho. |
| [enableInnerShadowEffect()](#enableInnerShadowEffect--) | Ativa o efeito de sombra interna. |
| [enableOuterShadowEffect()](#enableOuterShadowEffect--) | Ativa o efeito de sombra externa. |
| [enablePresetShadowEffect()](#enablePresetShadowEffect--) | Ativa o efeito de sombras predefinidas. |
| [enableReflectionEffect()](#enableReflectionEffect--) | Ativa o efeito de reflexão. |
| [enableSoftEdgeEffect()](#enableSoftEdgeEffect--) | Ativa o efeito de borda suave. |
| [disableBlurEffect()](#disableBlurEffect--) | Desativa o efeito de desfoque. |
| [disableFillOverlayEffect()](#disableFillOverlayEffect--) | Desativa o efeito de sobreposição de preenchimento. |
| [disableGlowEffect()](#disableGlowEffect--) | Desativa o efeito de brilho. |
| [disableInnerShadowEffect()](#disableInnerShadowEffect--) | Desativa o efeito de sombra interna. |
| [disableOuterShadowEffect()](#disableOuterShadowEffect--) | Desativa o efeito de sombra externa. |
| [disablePresetShadowEffect()](#disablePresetShadowEffect--) | Desativa o efeito de sombra predefinida. |
| [disableReflectionEffect()](#disableReflectionEffect--) | Desativa o efeito de reflexão. |
| [disableSoftEdgeEffect()](#disableSoftEdgeEffect--) | Desativa o efeito de borda suave. |
| [getEffective()](#getEffective--) | Obtém dados de formatação de efeito efetivo com a herança aplicada. |
### isNoEffects() {#isNoEffects--}
```
public abstract boolean isNoEffects()
```


Retorna true se todos os efeitos estiverem desativados (como recém-criado, objeto EffectFormat padrão). Boolean somente leitura.

**Retorna:**
boolean
### getBlurEffect() {#getBlurEffect--}
```
public abstract IBlur getBlurEffect()
```


Efeito de desfoque. Leitura/Gravação [IBlur](../../com.aspose.slides/iblur).

**Retorna:**
[IBlur](../../com.aspose.slides/iblur)
### setBlurEffect(IBlur value) {#setBlurEffect-com.aspose.slides.IBlur-}
```
public abstract void setBlurEffect(IBlur value)
```


Efeito de desfoque. Leitura/Gravação [IBlur](../../com.aspose.slides/iblur).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IBlur](../../com.aspose.slides/iblur) |  |

### getFillOverlayEffect() {#getFillOverlayEffect--}
```
public abstract IFillOverlay getFillOverlayEffect()
```


Efeito de sobreposição de preenchimento. Leitura/Gravação [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**Retorna:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay)
### setFillOverlayEffect(IFillOverlay value) {#setFillOverlayEffect-com.aspose.slides.IFillOverlay-}
```
public abstract void setFillOverlayEffect(IFillOverlay value)
```


Efeito de sobreposição de preenchimento. Leitura/Gravação [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IFillOverlay](../../com.aspose.slides/ifilloverlay) |  |

### getGlowEffect() {#getGlowEffect--}
```
public abstract IGlow getGlowEffect()
```


Efeito de brilho. Leitura/Gravação [IGlow](../../com.aspose.slides/iglow).

**Retorna:**
[IGlow](../../com.aspose.slides/iglow)
### setGlowEffect(IGlow value) {#setGlowEffect-com.aspose.slides.IGlow-}
```
public abstract void setGlowEffect(IGlow value)
```


Efeito de brilho. Leitura/Gravação [IGlow](../../com.aspose.slides/iglow).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IGlow](../../com.aspose.slides/iglow) |  |

### getInnerShadowEffect() {#getInnerShadowEffect--}
```
public abstract IInnerShadow getInnerShadowEffect()
```


Sombra interna. Leitura/Gravação [IInnerShadow](../../com.aspose.slides/iinnershadow).

**Retorna:**
[IInnerShadow](../../com.aspose.slides/iinnershadow)
### setInnerShadowEffect(IInnerShadow value) {#setInnerShadowEffect-com.aspose.slides.IInnerShadow-}
```
public abstract void setInnerShadowEffect(IInnerShadow value)
```


Sombra interna. Leitura/Gravação [IInnerShadow](../../com.aspose.slides/iinnershadow).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IInnerShadow](../../com.aspose.slides/iinnershadow) |  |

### getOuterShadowEffect() {#getOuterShadowEffect--}
```
public abstract IOuterShadow getOuterShadowEffect()
```


Sombra externa. Leitura/Gravação [IOuterShadow](../../com.aspose.slides/ioutershadow).

**Retorna:**
[IOuterShadow](../../com.aspose.slides/ioutershadow)
### setOuterShadowEffect(IOuterShadow value) {#setOuterShadowEffect-com.aspose.slides.IOuterShadow-}
```
public abstract void setOuterShadowEffect(IOuterShadow value)
```


Sombra externa. Leitura/Gravação [IOuterShadow](../../com.aspose.slides/ioutershadow).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IOuterShadow](../../com.aspose.slides/ioutershadow) |  |

### getPresetShadowEffect() {#getPresetShadowEffect--}
```
public abstract IPresetShadow getPresetShadowEffect()
```


Sombra predefinida. Leitura/Gravação [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**Retorna:**
[IPresetShadow](../../com.aspose.slides/ipresetshadow)
### setPresetShadowEffect(IPresetShadow value) {#setPresetShadowEffect-com.aspose.slides.IPresetShadow-}
```
public abstract void setPresetShadowEffect(IPresetShadow value)
```


Sombra predefinida. Leitura/Gravação [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IPresetShadow](../../com.aspose.slides/ipresetshadow) |  |

### getReflectionEffect() {#getReflectionEffect--}
```
public abstract IReflection getReflectionEffect()
```


Reflexão. Leitura/Gravação [IReflection](../../com.aspose.slides/ireflection).

**Retorna:**
[IReflection](../../com.aspose.slides/ireflection)
### setReflectionEffect(IReflection value) {#setReflectionEffect-com.aspose.slides.IReflection-}
```
public abstract void setReflectionEffect(IReflection value)
```


Reflexão. Leitura/Gravação [IReflection](../../com.aspose.slides/ireflection).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IReflection](../../com.aspose.slides/ireflection) |  |

### getSoftEdgeEffect() {#getSoftEdgeEffect--}
```
public abstract ISoftEdge getSoftEdgeEffect()
```


Borda suave. Leitura/Gravação [ISoftEdge](../../com.aspose.slides/isoftedge).

**Retorna:**
[ISoftEdge](../../com.aspose.slides/isoftedge)
### setSoftEdgeEffect(ISoftEdge value) {#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-}
```
public abstract void setSoftEdgeEffect(ISoftEdge value)
```


Borda suave. Leitura/Gravação [ISoftEdge](../../com.aspose.slides/isoftedge).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [ISoftEdge](../../com.aspose.slides/isoftedge) |  |

### setBlurEffect(double radius, boolean grow) {#setBlurEffect-double-boolean-}
```
public abstract void setBlurEffect(double radius, boolean grow)
```


Define o efeito de desfoque.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| radius | double | Raio. |
| grow | boolean | Crescer. |

### enableFillOverlayEffect() {#enableFillOverlayEffect--}
```
public abstract void enableFillOverlayEffect()
```


Ativa o efeito de sobreposição de preenchimento.

### enableGlowEffect() {#enableGlowEffect--}
```
public abstract void enableGlowEffect()
```


Ativa o efeito de brilho.

### enableInnerShadowEffect() {#enableInnerShadowEffect--}
```
public abstract void enableInnerShadowEffect()
```


Ativa o efeito de sombra interna.

### enableOuterShadowEffect() {#enableOuterShadowEffect--}
```
public abstract void enableOuterShadowEffect()
```


Ativa o efeito de sombra externa.

### enablePresetShadowEffect() {#enablePresetShadowEffect--}
```
public abstract void enablePresetShadowEffect()
```


Ativa o efeito de sombras predefinidas.

### enableReflectionEffect() {#enableReflectionEffect--}
```
public abstract void enableReflectionEffect()
```


Ativa o efeito de reflexão.

### enableSoftEdgeEffect() {#enableSoftEdgeEffect--}
```
public abstract void enableSoftEdgeEffect()
```


Ativa o efeito de borda suave.

### disableBlurEffect() {#disableBlurEffect--}
```
public abstract void disableBlurEffect()
```


Desativa o efeito de desfoque.

### disableFillOverlayEffect() {#disableFillOverlayEffect--}
```
public abstract void disableFillOverlayEffect()
```


Desativa o efeito de sobreposição de preenchimento.

### disableGlowEffect() {#disableGlowEffect--}
```
public abstract void disableGlowEffect()
```


Desativa o efeito de brilho.

### disableInnerShadowEffect() {#disableInnerShadowEffect--}
```
public abstract void disableInnerShadowEffect()
```


Desativa o efeito de sombra interna.

### disableOuterShadowEffect() {#disableOuterShadowEffect--}
```
public abstract void disableOuterShadowEffect()
```


Desativa o efeito de sombra externa.

### disablePresetShadowEffect() {#disablePresetShadowEffect--}
```
public abstract void disablePresetShadowEffect()
```


Desativa o efeito de sombra predefinida.

### disableReflectionEffect() {#disableReflectionEffect--}
```
public abstract void disableReflectionEffect()
```


Desativa o efeito de reflexão.

### disableSoftEdgeEffect() {#disableSoftEdgeEffect--}
```
public abstract void disableSoftEdgeEffect()
```


Desativa o efeito de borda suave.

### getEffective() {#getEffective--}
```
public abstract IEffectFormatEffectiveData getEffective()
```


Obtém dados de formatação de efeito efetivo com a herança aplicada.

**Retorna:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata) - Um [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).