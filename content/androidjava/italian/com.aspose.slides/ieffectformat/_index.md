---
title: IEffectFormat
second_title: Aspose.Slides per Android tramite Java API Reference
description: Rappresenta le proprietà degli effetti della forma.
type: docs
url: /it/com.aspose.slides/ieffectformat/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IEffectParamSource](../../com.aspose.slides/ieffectparamsource)
```
public interface IEffectFormat extends IEffectParamSource
```

Rappresenta le proprietà degli effetti della forma.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [isNoEffects()](#isNoEffects--) | Restituisce true se tutti gli effetti sono disabilitati (come appena creato, oggetto EffectFormat predefinito). |
| [getBlurEffect()](#getBlurEffect--) | Effetto sfocatura. |
| [setBlurEffect(IBlur value)](#setBlurEffect-com.aspose.slides.IBlur-) | Effetto sfocatura. |
| [getFillOverlayEffect()](#getFillOverlayEffect--) | Effetto di riempimento sovrapposto. |
| [setFillOverlayEffect(IFillOverlay value)](#setFillOverlayEffect-com.aspose.slides.IFillOverlay-) | Effetto di riempimento sovrapposto. |
| [getGlowEffect()](#getGlowEffect--) | Effetto bagliore. |
| [setGlowEffect(IGlow value)](#setGlowEffect-com.aspose.slides.IGlow-) | Effetto bagliore. |
| [getInnerShadowEffect()](#getInnerShadowEffect--) | Ombra interna. |
| [setInnerShadowEffect(IInnerShadow value)](#setInnerShadowEffect-com.aspose.slides.IInnerShadow-) | Ombra interna. |
| [getOuterShadowEffect()](#getOuterShadowEffect--) | Ombra esterna. |
| [setOuterShadowEffect(IOuterShadow value)](#setOuterShadowEffect-com.aspose.slides.IOuterShadow-) | Ombra esterna. |
| [getPresetShadowEffect()](#getPresetShadowEffect--) | Ombra predefinita. |
| [setPresetShadowEffect(IPresetShadow value)](#setPresetShadowEffect-com.aspose.slides.IPresetShadow-) | Ombra predefinita. |
| [getReflectionEffect()](#getReflectionEffect--) | Riflesso. |
| [setReflectionEffect(IReflection value)](#setReflectionEffect-com.aspose.slides.IReflection-) | Riflesso. |
| [getSoftEdgeEffect()](#getSoftEdgeEffect--) | Bordo morbido. |
| [setSoftEdgeEffect(ISoftEdge value)](#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-) | Bordo morbido. |
| [setBlurEffect(double radius, boolean grow)](#setBlurEffect-double-boolean-) | Imposta l'effetto sfocatura. |
| [enableFillOverlayEffect()](#enableFillOverlayEffect--) | Abilita l'effetto di riempimento sovrapposto. |
| [enableGlowEffect()](#enableGlowEffect--) | Abilita l'effetto bagliore. |
| [enableInnerShadowEffect()](#enableInnerShadowEffect--) | Abilita l'effetto di ombra interna. |
| [enableOuterShadowEffect()](#enableOuterShadowEffect--) | Abilita l'effetto di ombra esterna. |
| [enablePresetShadowEffect()](#enablePresetShadowEffect--) | Abilita l'effetto di ombre predefinite. |
| [enableReflectionEffect()](#enableReflectionEffect--) | Abilita l'effetto di riflesso. |
| [enableSoftEdgeEffect()](#enableSoftEdgeEffect--) | Abilita l'effetto di bordo morbido. |
| [disableBlurEffect()](#disableBlurEffect--) | Disabilita l'effetto sfocatura. |
| [disableFillOverlayEffect()](#disableFillOverlayEffect--) | Disabilita l'effetto di riempimento sovrapposto. |
| [disableGlowEffect()](#disableGlowEffect--) | Disabilita l'effetto bagliore. |
| [disableInnerShadowEffect()](#disableInnerShadowEffect--) | Disabilita l'effetto di ombra interna. |
| [disableOuterShadowEffect()](#disableOuterShadowEffect--) | Disabilita l'effetto di ombra esterna. |
| [disablePresetShadowEffect()](#disablePresetShadowEffect--) | Disabilita l'effetto di ombra predefinita. |
| [disableReflectionEffect()](#disableReflectionEffect--) | Disabilita l'effetto di riflesso. |
| [disableSoftEdgeEffect()](#disableSoftEdgeEffect--) | Disabilita l'effetto di bordo morbido. |
| [getEffective()](#getEffective--) | Ottiene i dati di formattazione dell'effetto effettivo con l'ereditarietà applicata. |

### isNoEffects() {#isNoEffects--}
```
public abstract boolean isNoEffects()
```

Restituisce true se tutti gli effetti sono disabilitati (come appena creato, oggetto EffectFormat predefinito). Booleano di sola lettura.

**Restituisce:**
boolean

### getBlurEffect() {#getBlurEffect--}
```
public abstract IBlur getBlurEffect()
```

Effetto sfocatura. Lettura/scrittura [IBlur](../../com.aspose.slides/iblur).

**Restituisce:**
[IBlur](../../com.aspose.slides/iblur)

### setBlurEffect(IBlur value) {#setBlurEffect-com.aspose.slides.IBlur-}
```
public abstract void setBlurEffect(IBlur value)
```

Effetto sfocatura. Lettura/scrittura [IBlur](../../com.aspose.slides/iblur).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IBlur](../../com.aspose.slides/iblur) |  |

### getFillOverlayEffect() {#getFillOverlayEffect--}
```
public abstract IFillOverlay getFillOverlayEffect()
```

Effetto di riempimento sovrapposto. Lettura/scrittura [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**Restituisce:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay)

### setFillOverlayEffect(IFillOverlay value) {#setFillOverlayEffect-com.aspose.slides.IFillOverlay-}
```
public abstract void setFillOverlayEffect(IFillOverlay value)
```

Effetto di riempimento sovrapposto. Lettura/scrittura [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IFillOverlay](../../com.aspose.slides/ifilloverlay) |  |

### getGlowEffect() {#getGlowEffect--}
```
public abstract IGlow getGlowEffect()
```

Effetto bagliore. Lettura/scrittura [IGlow](../../com.aspose.slides/iglow).

**Restituisce:**
[IGlow](../../com.aspose.slides/iglow)

### setGlowEffect(IGlow value) {#setGlowEffect-com.aspose.slides.IGlow-}
```
public abstract void setGlowEffect(IGlow value)
```

Effetto bagliore. Lettura/scrittura [IGlow](../../com.aspose.slides/iglow).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IGlow](../../com.aspose.slides/iglow) |  |

### getInnerShadowEffect() {#getInnerShadowEffect--}
```
public abstract IInnerShadow getInnerShadowEffect()
```

Ombra interna. Lettura/scrittura [IInnerShadow](../../com.aspose.slides/iinnershadow).

**Restituisce:**
[IInnerShadow](../../com.aspose.slides/iinnershadow)

### setInnerShadowEffect(IInnerShadow value) {#setInnerShadowEffect-com.aspose.slides.IInnerShadow-}
```
public abstract void setInnerShadowEffect(IInnerShadow value)
```

Ombra interna. Lettura/scrittura [IInnerShadow](../../com.aspose.slides/iinnershadow).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IInnerShadow](../../com.aspose.slides/iinnershadow) |  |

### getOuterShadowEffect() {#getOuterShadowEffect--}
```
public abstract IOuterShadow getOuterShadowEffect()
```

Ombra esterna. Lettura/scrittura [IOuterShadow](../../com.aspose.slides/ioutershadow).

**Restituisce:**
[IOuterShadow](../../com.aspose.slides/ioutershadow)

### setOuterShadowEffect(IOuterShadow value) {#setOuterShadowEffect-com.aspose.slides.IOuterShadow-}
```
public abstract void setOuterShadowEffect(IOuterShadow value)
```

Ombra esterna. Lettura/scrittura [IOuterShadow](../../com.aspose.slides/ioutershadow).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IOuterShadow](../../com.aspose.slides/ioutershadow) |  |

### getPresetShadowEffect() {#getPresetShadowEffect--}
```
public abstract IPresetShadow getPresetShadowEffect()
```

Ombra predefinita. Lettura/scrittura [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**Restituisce:**
[IPresetShadow](../../com.aspose.slides/ipresetshadow)

### setPresetShadowEffect(IPresetShadow value) {#setPresetShadowEffect-com.aspose.slides.IPresetShadow-}
```
public abstract void setPresetShadowEffect(IPresetShadow value)
```

Ombra predefinita. Lettura/scrittura [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IPresetShadow](../../com.aspose.slides/ipresetshadow) |  |

### getReflectionEffect() {#getReflectionEffect--}
```
public abstract IReflection getReflectionEffect()
```

Riflesso. Lettura/scrittura [IReflection](../../com.aspose.slides/ireflection).

**Restituisce:**
[IReflection](../../com.aspose.slides/ireflection)

### setReflectionEffect(IReflection value) {#setReflectionEffect-com.aspose.slides.IReflection-}
```
public abstract void setReflectionEffect(IReflection value)
```

Riflesso. Lettura/scrittura [IReflection](../../com.aspose.slides/ireflection).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IReflection](../../com.aspose.slides/ireflection) |  |

### getSoftEdgeEffect() {#getSoftEdgeEffect--}
```
public abstract ISoftEdge getSoftEdgeEffect()
```

Bordo morbido. Lettura/scrittura [ISoftEdge](../../com.aspose.slides/isoftedge).

**Restituisce:**
[ISoftEdge](../../com.aspose.slides/isoftedge)

### setSoftEdgeEffect(ISoftEdge value) {#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-}
```
public abstract void setSoftEdgeEffect(ISoftEdge value)
```

Bordo morbido. Lettura/scrittura [ISoftEdge](../../com.aspose.slides/isoftedge).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ISoftEdge](../../com.aspose.slides/isoftedge) |  |

### setBlurEffect(double radius, boolean grow) {#setBlurEffect-double-boolean-}
```
public abstract void setBlurEffect(double radius, boolean grow)
```

Imposta l'effetto sfocatura.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| radius | double | Raggio. |
| grow | boolean | Crescita. |

### enableFillOverlayEffect() {#enableFillOverlayEffect--}
```
public abstract void enableFillOverlayEffect()
```

Abilita l'effetto di riempimento sovrapposto.

### enableGlowEffect() {#enableGlowEffect--}
```
public abstract void enableGlowEffect()
```

Abilita l'effetto bagliore.

### enableInnerShadowEffect() {#enableInnerShadowEffect--}
```
public abstract void enableInnerShadowEffect()
```

Abilita l'effetto di ombra interna.

### enableOuterShadowEffect() {#enableOuterShadowEffect--}
```
public abstract void enableOuterShadowEffect()
```

Abilita l'effetto di ombra esterna.

### enablePresetShadowEffect() {#enablePresetShadowEffect--}
```
public abstract void enablePresetShadowEffect()
```

Abilita l'effetto di ombre predefinite.

### enableReflectionEffect() {#enableReflectionEffect--}
```
public abstract void enableReflectionEffect()
```

Abilita l'effetto di riflesso.

### enableSoftEdgeEffect() {#enableSoftEdgeEffect--}
```
public abstract void enableSoftEdgeEffect()
```

Abilita l'effetto di bordo morbido.

### disableBlurEffect() {#disableBlurEffect--}
```
public abstract void disableBlurEffect()
```

Disabilita l'effetto sfocatura.

### disableFillOverlayEffect() {#disableFillOverlayEffect--}
```
public abstract void disableFillOverlayEffect()
```

Disabilita l'effetto di riempimento sovrapposto.

### disableGlowEffect() {#disableGlowEffect--}
```
public abstract void disableGlowEffect()
```

Disabilita l'effetto bagliore.

### disableInnerShadowEffect() {#disableInnerShadowEffect--}
```
public abstract void disableInnerShadowEffect()
```

Disabilita l'effetto di ombra interna.

### disableOuterShadowEffect() {#disableOuterShadowEffect--}
```
public abstract void disableOuterShadowEffect()
```

Disabilita l'effetto di ombra esterna.

### disablePresetShadowEffect() {#disablePresetShadowEffect--}
```
public abstract void disablePresetShadowEffect()
```

Disabilita l'effetto di ombra predefinita.

### disableReflectionEffect() {#disableReflectionEffect--}
```
public abstract void disableReflectionEffect()
```

Disabilita l'effetto di riflesso.

### disableSoftEdgeEffect() {#disableSoftEdgeEffect--}
```
public abstract void disableSoftEdgeEffect()
```

Disabilita l'effetto di bordo morbido.

### getEffective() {#getEffective--}
```
public abstract IEffectFormatEffectiveData getEffective()
```

Ottiene i dati di formattazione dell'effetto effettivo con l'ereditarietà applicata.

**Restituisce:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata) - A [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).