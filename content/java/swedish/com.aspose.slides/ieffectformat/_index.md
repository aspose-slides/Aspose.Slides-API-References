---
title: IEffectFormat
second_title: Aspose.Slides för Java API-referens
description: Representerar effektens egenskaper för form.
type: docs
url: /sv/com.aspose.slides/ieffectformat/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IEffectParamSource](../../com.aspose.slides/ieffectparamsource)
```
public interface IEffectFormat extends IEffectParamSource
```

Representerar effektinställningar för form.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isNoEffects()](#isNoEffects--) | Returnerar true om alla effekter är inaktiverade (som precis skapad, standard-EffectFormat-objekt). |
| [getBlurEffect()](#getBlurEffect--) | Oskärpe-effekt. |
| [setBlurEffect(IBlur value)](#setBlurEffect-com.aspose.slides.IBlur-) | Oskärpe-effekt. |
| [getFillOverlayEffect()](#getFillOverlayEffect--) | Överlagrings-fyll-effekt. |
| [setFillOverlayEffect(IFillOverlay value)](#setFillOverlayEffect-com.aspose.slides.IFillOverlay-) | Överlagrings-fyll-effekt. |
| [getGlowEffect()](#getGlowEffect--) | Glöd-effekt. |
| [setGlowEffect(IGlow value)](#setGlowEffect-com.aspose.slides.IGlow-) | Glöd-effekt. |
| [getInnerShadowEffect()](#getInnerShadowEffect--) | Inre skugga. |
| [setInnerShadowEffect(IInnerShadow value)](#setInnerShadowEffect-com.aspose.slides.IInnerShadow-) | Inre skugga. |
| [getOuterShadowEffect()](#getOuterShadowEffect--) | Yttre skugga. |
| [setOuterShadowEffect(IOuterShadow value)](#setOuterShadowEffect-com.aspose.slides.IOuterShadow-) | Yttre skugga. |
| [getPresetShadowEffect()](#getPresetShadowEffect--) | Förinställd skugga. |
| [setPresetShadowEffect(IPresetShadow value)](#setPresetShadowEffect-com.aspose.slides.IPresetShadow-) | Förinställd skugga. |
| [getReflectionEffect()](#getReflectionEffect--) | Reflektion. |
| [setReflectionEffect(IReflection value)](#setReflectionEffect-com.aspose.slides.IReflection-) | Reflektion. |
| [getSoftEdgeEffect()](#getSoftEdgeEffect--) | Mjuk kant. |
| [setSoftEdgeEffect(ISoftEdge value)](#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-) | Mjuk kant. |
| [setBlurEffect(double radius, boolean grow)](#setBlurEffect-double-boolean-) | Ställer in oskärpe-effekt. |
| [enableFillOverlayEffect()](#enableFillOverlayEffect--) | Aktiverar överlagrings-fyll-effekt. |
| [enableGlowEffect()](#enableGlowEffect--) | Aktiverar glöd-effekt. |
| [enableInnerShadowEffect()](#enableInnerShadowEffect--) | Aktiverar inre skugga-effekt. |
| [enableOuterShadowEffect()](#enableOuterShadowEffect--) | Aktiverar yttre skugga-effekt. |
| [enablePresetShadowEffect()](#enablePresetShadowEffect--) | Aktiverar förinställd skugga-effekt. |
| [enableReflectionEffect()](#enableReflectionEffect--) | Aktiverar reflektion-effekt. |
| [enableSoftEdgeEffect()](#enableSoftEdgeEffect--) | Aktiverar mjuk kant-effekt. |
| [disableBlurEffect()](#disableBlurEffect--) | Inaktiverar oskärpe-effekt. |
| [disableFillOverlayEffect()](#disableFillOverlayEffect--) | Inaktiverar överlagrings-fyll-effekt. |
| [disableGlowEffect()](#disableGlowEffect--) | Inaktiverar glöd-effekt. |
| [disableInnerShadowEffect()](#disableInnerShadowEffect--) | Inaktiverar inre skugga-effekt. |
| [disableOuterShadowEffect()](#disableOuterShadowEffect--) | Inaktiverar yttre skugga-effekt. |
| [disablePresetShadowEffect()](#disablePresetShadowEffect--) | Inaktiverar förinställd skugga-effekt. |
| [disableReflectionEffect()](#disableReflectionEffect--) | Inaktiverar reflektion-effekt. |
| [disableSoftEdgeEffect()](#disableSoftEdgeEffect--) | Inaktiverar mjuk kant-effekt. |
| [getEffective()](#getEffective--) | Hämtar effektiverade effekt-formateringsdata med arv tillämpat. |
### isNoEffects() {#isNoEffects--}
```
public abstract boolean isNoEffects()
```


Returnerar true om alla effekter är inaktiverade (som precis skapad, standard-EffectFormat-objekt). Skrivskyddad boolean.

**Returnerar:**
boolean
### getBlurEffect() {#getBlurEffect--}
```
public abstract IBlur getBlurEffect()
```


Oskärpe-effekt. Läs/skriv [IBlur](../../com.aspose.slides/iblur).

**Returnerar:**
[IBlur](../../com.aspose.slides/iblur)
### setBlurEffect(IBlur value) {#setBlurEffect-com.aspose.slides.IBlur-}
```
public abstract void setBlurEffect(IBlur value)
```


Oskärpe-effekt. Läs/skriv [IBlur](../../com.aspose.slides/iblur).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IBlur](../../com.aspose.slides/iblur) |  |

### getFillOverlayEffect() {#getFillOverlayEffect--}
```
public abstract IFillOverlay getFillOverlayEffect()
```


Överlagrings-fyll-effekt. Läs/skriv [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**Returnerar:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay)
### setFillOverlayEffect(IFillOverlay value) {#setFillOverlayEffect-com.aspose.slides.IFillOverlay-}
```
public abstract void setFillOverlayEffect(IFillOverlay value)
```


Överlagrings-fyll-effekt. Läs/skriv [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IFillOverlay](../../com.aspose.slides/ifilloverlay) |  |

### getGlowEffect() {#getGlowEffect--}
```
public abstract IGlow getGlowEffect()
```


Glöd-effekt. Läs/skriv [IGlow](../../com.aspose.slides/iglow).

**Returnerar:**
[IGlow](../../com.aspose.slides/iglow)
### setGlowEffect(IGlow value) {#setGlowEffect-com.aspose.slides.IGlow-}
```
public abstract void setGlowEffect(IGlow value)
```


Glöd-effekt. Läs/skriv [IGlow](../../com.aspose.slides/iglow).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IGlow](../../com.aspose.slides/iglow) |  |

### getInnerShadowEffect() {#getInnerShadowEffect--}
```
public abstract IInnerShadow getInnerShadowEffect()
```


Inre skugga. Läs/skriv [IInnerShadow](../../com.aspose.slides/iinnershadow).

**Returnerar:**
[IInnerShadow](../../com.aspose.slides/iinnershadow)
### setInnerShadowEffect(IInnerShadow value) {#setInnerShadowEffect-com.aspose.slides.IInnerShadow-}
```
public abstract void setInnerShadowEffect(IInnerShadow value)
```


Inre skugga. Läs/skriv [IInnerShadow](../../com.aspose.slides/iinnershadow).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IInnerShadow](../../com.aspose.slides/iinnershadow) |  |

### getOuterShadowEffect() {#getOuterShadowEffect--}
```
public abstract IOuterShadow getOuterShadowEffect()
```


Yttre skugga. Läs/skriv [IOuterShadow](../../com.aspose.slides/ioutershadow).

**Returnerar:**
[IOuterShadow](../../com.aspose.slides/ioutershadow)
### setOuterShadowEffect(IOuterShadow value) {#setOuterShadowEffect-com.aspose.slides.IOuterShadow-}
```
public abstract void setOuterShadowEffect(IOuterShadow value)
```


Yttre skugga. Läs/skriv [IOuterShadow](../../com.aspose.slides/ioutershadow).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IOuterShadow](../../com.aspose.slides/ioutershadow) |  |

### getPresetShadowEffect() {#getPresetShadowEffect--}
```
public abstract IPresetShadow getPresetShadowEffect()
```


Förinställd skugga. Läs/skriv [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**Returnerar:**
[IPresetShadow](../../com.aspose.slides/ipresetshadow)
### setPresetShadowEffect(IPresetShadow value) {#setPresetShadowEffect-com.aspose.slides.IPresetShadow-}
```
public abstract void setPresetShadowEffect(IPresetShadow value)
```


Förinställd skugga. Läs/skriv [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IPresetShadow](../../com.aspose.slides/ipresetshadow) |  |

### getReflectionEffect() {#getReflectionEffect--}
```
public abstract IReflection getReflectionEffect()
```


Reflektion. Läs/skriv [IReflection](../../com.aspose.slides/ireflection).

**Returnerar:**
[IReflection](../../com.aspose.slides/ireflection)
### setReflectionEffect(IReflection value) {#setReflectionEffect-com.aspose.slides.IReflection-}
```
public abstract void setReflectionEffect(IReflection value)
```


Reflektion. Läs/skriv [IReflection](../../com.aspose.slides/ireflection).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IReflection](../../com.aspose.slides/ireflection) |  |

### getSoftEdgeEffect() {#getSoftEdgeEffect--}
```
public abstract ISoftEdge getSoftEdgeEffect()
```


Mjuk kant. Läs/skriv [ISoftEdge](../../com.aspose.slides/isoftedge).

**Returnerar:**
[ISoftEdge](../../com.aspose.slides/isoftedge)
### setSoftEdgeEffect(ISoftEdge value) {#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-}
```
public abstract void setSoftEdgeEffect(ISoftEdge value)
```


Mjuk kant. Läs/skriv [ISoftEdge](../../com.aspose.slides/isoftedge).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ISoftEdge](../../com.aspose.slides/isoftedge) |  |

### setBlurEffect(double radius, boolean grow) {#setBlurEffect-double-boolean-}
```
public abstract void setBlurEffect(double radius, boolean grow)
```


Ställer in oskärpe-effekt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| radius | double | Radie. |
| grow | boolean | Växa. |

### enableFillOverlayEffect() {#enableFillOverlayEffect--}
```
public abstract void enableFillOverlayEffect()
```


Aktiverar överlagrings-fyll-effekt.

### enableGlowEffect() {#enableGlowEffect--}
```
public abstract void enableGlowEffect()
```


Aktiverar glöd-effekt.

### enableInnerShadowEffect() {#enableInnerShadowEffect--}
```
public abstract void enableInnerShadowEffect()
```


Aktiverar inre skugga-effekt.

### enableOuterShadowEffect() {#enableOuterShadowEffect--}
```
public abstract void enableOuterShadowEffect()
```


Aktiverar yttre skugga-effekt.

### enablePresetShadowEffect() {#enablePresetShadowEffect--}
```
public abstract void enablePresetShadowEffect()
```


Aktiverar förinställd skugga-effekt.

### enableReflectionEffect() {#enableReflectionEffect--}
```
public abstract void enableReflectionEffect()
```


Aktiverar reflektion-effekt.

### enableSoftEdgeEffect() {#enableSoftEdgeEffect--}
```
public abstract void enableSoftEdgeEffect()
```


Aktiverar mjuk kant-effekt.

### disableBlurEffect() {#disableBlurEffect--}
```
public abstract void disableBlurEffect()
```


Inaktiverar oskärpe-effekt.

### disableFillOverlayEffect() {#disableFillOverlayEffect--}
```
public abstract void disableFillOverlayEffect()
```


Inaktiverar överlagrings-fyll-effekt.

### disableGlowEffect() {#disableGlowEffect--}
```
public abstract void disableGlowEffect()
```


Inaktiverar glöd-effekt.

### disableInnerShadowEffect() {#disableInnerShadowEffect--}
```
public abstract void disableInnerShadowEffect()
```


Inaktiverar inre skugga-effekt.

### disableOuterShadowEffect() {#disableOuterShadowEffect--}
```
public abstract void disableOuterShadowEffect()
```


Inaktiverar yttre skugga-effekt.

### disablePresetShadowEffect() {#disablePresetShadowEffect--}
```
public abstract void disablePresetShadowEffect()
```


Inaktiverar förinställd skugga-effekt.

### disableReflectionEffect() {#disableReflectionEffect--}
```
public abstract void disableReflectionEffect()
```


Inaktiverar reflektion-effekt.

### disableSoftEdgeEffect() {#disableSoftEdgeEffect--}
```
public abstract void disableSoftEdgeEffect()
```


Inaktiverar mjuk kant-effekt.

### getEffective() {#getEffective--}
```
public abstract IEffectFormatEffectiveData getEffective()
```


Hämtar effektiverade effekt-formateringsdata med arv tillämpat.

**Returnerar:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata) - En [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).