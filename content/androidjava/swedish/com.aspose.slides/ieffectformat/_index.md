---
title: IEffectFormat
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar effekt-egenskaper för en form.
type: docs
url: /sv/com.aspose.slides/ieffectformat/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IEffectParamSource](../../com.aspose.slides/ieffectparamsource)
```
public interface IEffectFormat extends IEffectParamSource
```

Representerar effekt-egenskaper för en form.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isNoEffects()](#isNoEffects--) | Returnerar true om alla effekter är inaktiverade (som precis skapats, standard EffectFormat-objekt). |
| [getBlurEffect()](#getBlurEffect--) | Blur effect. |
| [setBlurEffect(IBlur value)](#setBlurEffect-com.aspose.slides.IBlur-) | Blur effect. |
| [getFillOverlayEffect()](#getFillOverlayEffect--) | Fill overlay effect. |
| [setFillOverlayEffect(IFillOverlay value)](#setFillOverlayEffect-com.aspose.slides.IFillOverlay-) | Fill overlay effect. |
| [getGlowEffect()](#getGlowEffect--) | Glow effect. |
| [setGlowEffect(IGlow value)](#setGlowEffect-com.aspose.slides.IGlow-) | Glow effect. |
| [getInnerShadowEffect()](#getInnerShadowEffect--) | Inner shadow. |
| [setInnerShadowEffect(IInnerShadow value)](#setInnerShadowEffect-com.aspose.slides.IInnerShadow-) | Inner shadow. |
| [getOuterShadowEffect()](#getOuterShadowEffect--) | Outer shadow. |
| [setOuterShadowEffect(IOuterShadow value)](#setOuterShadowEffect-com.aspose.slides.IOuterShadow-) | Outer shadow. |
| [getPresetShadowEffect()](#getPresetShadowEffect--) | Preset shadow. |
| [setPresetShadowEffect(IPresetShadow value)](#setPresetShadowEffect-com.aspose.slides.IPresetShadow-) | Preset shadow. |
| [getReflectionEffect()](#getReflectionEffect--) | Reflection. |
| [setReflectionEffect(IReflection value)](#setReflectionEffect-com.aspose.slides.IReflection-) | Reflection. |
| [getSoftEdgeEffect()](#getSoftEdgeEffect--) | Soft edge. |
| [setSoftEdgeEffect(ISoftEdge value)](#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-) | Soft edge. |
| [setBlurEffect(double radius, boolean grow)](#setBlurEffect-double-boolean-) | Ställer in blur-effekt. |
| [enableFillOverlayEffect()](#enableFillOverlayEffect--) | Aktiverar fill overlay-effekt. |
| [enableGlowEffect()](#enableGlowEffect--) | Aktiverar glow-effekt. |
| [enableInnerShadowEffect()](#enableInnerShadowEffect--) | Aktiverar inner shadow-effekt. |
| [enableOuterShadowEffect()](#enableOuterShadowEffect--) | Aktiverar outer shadow-effekt. |
| [enablePresetShadowEffect()](#enablePresetShadowEffect--) | Aktiverar preset shadows-effekt. |
| [enableReflectionEffect()](#enableReflectionEffect--) | Aktiverar reflection-effekt. |
| [enableSoftEdgeEffect()](#enableSoftEdgeEffect--) | Aktiverar soft edge-effekt. |
| [disableBlurEffect()](#disableBlurEffect--) | Inaktiverar blur-effekt. |
| [disableFillOverlayEffect()](#disableFillOverlayEffect--) | Inaktiverar fill overlay-effekt. |
| [disableGlowEffect()](#disableGlowEffect--) | Inaktiverar glow-effekt. |
| [disableInnerShadowEffect()](#disableInnerShadowEffect--) | Inaktiverar inner shadow-effekt. |
| [disableOuterShadowEffect()](#disableOuterShadowEffect--) | Inaktiverar outer shadow-effekt. |
| [disablePresetShadowEffect()](#disablePresetShadowEffect--) | Inaktiverar preset shadow-effekt. |
| [disableReflectionEffect()](#disableReflectionEffect--) | Inaktiverar reflection-effekt. |
| [disableSoftEdgeEffect()](#disableSoftEdgeEffect--) | Inaktiverar soft edge-effekt. |
| [getEffective()](#getEffective--) | Hämtar effektuell formateringsdata med arv tillämpat. |
### isNoEffects() {#isNoEffects--}
```
public abstract boolean isNoEffects()
```


Returnerar true om alla effekter är inaktiverade (som precis skapats, standard EffectFormat-objekt). Skrivskyddad boolean.

**Returnerar:**
boolean
### getBlurEffect() {#getBlurEffect--}
```
public abstract IBlur getBlurEffect()
```


Blur-effekt. Läs/skriv [IBlur](../../com.aspose.slides/iblur).

**Returnerar:**
[IBlur](../../com.aspose.slides/iblur)
### setBlurEffect(IBlur value) {#setBlurEffect-com.aspose.slides.IBlur-}
```
public abstract void setBlurEffect(IBlur value)
```


Blur-effekt. Läs/skriv [IBlur](../../com.aspose.slides/iblur).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IBlur](../../com.aspose.slides/iblur) |  |

### getFillOverlayEffect() {#getFillOverlayEffect--}
```
public abstract IFillOverlay getFillOverlayEffect()
```


Fill overlay-effekt. Läs/skriv [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**Returnerar:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay)
### setFillOverlayEffect(IFillOverlay value) {#setFillOverlayEffect-com.aspose.slides.IFillOverlay-}
```
public abstract void setFillOverlayEffect(IFillOverlay value)
```


Fill overlay-effekt. Läs/skriv [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IFillOverlay](../../com.aspose.slides/ifilloverlay) |  |

### getGlowEffect() {#getGlowEffect--}
```
public abstract IGlow getGlowEffect()
```


Glow-effekt. Läs/skriv [IGlow](../../com.aspose.slides/iglow).

**Returnerar:**
[IGlow](../../com.aspose.slides/iglow)
### setGlowEffect(IGlow value) {#setGlowEffect-com.aspose.slides.IGlow-}
```
public abstract void setGlowEffect(IGlow value)
```


Glow-effekt. Läs/skriv [IGlow](../../com.aspose.slides/iglow).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IGlow](../../com.aspose.slides/iglow) |  |

### getInnerShadowEffect() {#getInnerShadowEffect--}
```
public abstract IInnerShadow getInnerShadowEffect()
```


Inner shadow-effekt. Läs/skriv [IInnerShadow](../../com.aspose.slides/iinnershadow).

**Returnerar:**
[IInnerShadow](../../com.aspose.slides/iinnershadow)
### setInnerShadowEffect(IInnerShadow value) {#setInnerShadowEffect-com.aspose.slides.IInnerShadow-}
```
public abstract void setInnerShadowEffect(IInnerShadow value)
```


Inner shadow-effekt. Läs/skriv [IInnerShadow](../../com.aspose.slides/iinnershadow).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IInnerShadow](../../com.aspose.slides/iinnershadow) |  |

### getOuterShadowEffect() {#getOuterShadowEffect--}
```
public abstract IOuterShadow getOuterShadowEffect()
```


Outer shadow-effekt. Läs/skriv [IOuterShadow](../../com.aspose.slides/ioutershadow).

**Returnerar:**
[IOuterShadow](../../com.aspose.slides/ioutershadow)
### setOuterShadowEffect(IOuterShadow value) {#setOuterShadowEffect-com.aspose.slides.IOuterShadow-}
```
public abstract void setOuterShadowEffect(IOuterShadow value)
```


Outer shadow-effekt. Läs/skriv [IOuterShadow](../../com.aspose.slides/ioutershadow).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IOuterShadow](../../com.aspose.slides/ioutershadow) |  |

### getPresetShadowEffect() {#getPresetShadowEffect--}
```
public abstract IPresetShadow getPresetShadowEffect()
```


Preset shadow-effekt. Läs/skriv [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**Returnerar:**
[IPresetShadow](../../com.aspose.slides/ipresetshadow)
### setPresetShadowEffect(IPresetShadow value) {#setPresetShadowEffect-com.aspose.slides.IPresetShadow-}
```
public abstract void setPresetShadowEffect(IPresetShadow value)
```


Preset shadow-effekt. Läs/skriv [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IPresetShadow](../../com.aspose.slides/ipresetshadow) |  |

### getReflectionEffect() {#getReflectionEffect--}
```
public abstract IReflection getReflectionEffect()
```


Reflection-effekt. Läs/skriv [IReflection](../../com.aspose.slides/ireflection).

**Returnerar:**
[IReflection](../../com.aspose.slides/ireflection)
### setReflectionEffect(IReflection value) {#setReflectionEffect-com.aspose.slides.IReflection-}
```
public abstract void setReflectionEffect(IReflection value)
```


Reflection-effekt. Läs/skriv [IReflection](../../com.aspose.slides/ireflection).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IReflection](../../com.aspose.slides/ireflection) |  |

### getSoftEdgeEffect() {#getSoftEdgeEffect--}
```
public abstract ISoftEdge getSoftEdgeEffect()
```


Soft edge-effekt. Läs/skriv [ISoftEdge](../../com.aspose.slides/isoftedge).

**Returnerar:**
[ISoftEdge](../../com.aspose.slides/isoftedge)
### setSoftEdgeEffect(ISoftEdge value) {#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-}
```
public abstract void setSoftEdgeEffect(ISoftEdge value)
```


Soft edge-effekt. Läs/skriv [ISoftEdge](../../com.aspose.slides/isoftedge).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ISoftEdge](../../com.aspose.slides/isoftedge) |  |

### setBlurEffect(double radius, boolean grow) {#setBlurEffect-double-boolean-}
```
public abstract void setBlurEffect(double radius, boolean grow)
```


Ställer in blur-effekt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| radius | double | Radie. |
| grow | boolean | Öka. |

### enableFillOverlayEffect() {#enableFillOverlayEffect--}
```
public abstract void enableFillOverlayEffect()
```


Aktiverar fill overlay-effekt.

### enableGlowEffect() {#enableGlowEffect--}
```
public abstract void enableGlowEffect()
```


Aktiverar glow-effekt.

### enableInnerShadowEffect() {#enableInnerShadowEffect--}
```
public abstract void enableInnerShadowEffect()
```


Aktiverar inner shadow-effekt.

### enableOuterShadowEffect() {#enableOuterShadowEffect--}
```
public abstract void enableOuterShadowEffect()
```


Aktiverar outer shadow-effekt.

### enablePresetShadowEffect() {#enablePresetShadowEffect--}
```
public abstract void enablePresetShadowEffect()
```


Aktiverar preset shadows-effekt.

### enableReflectionEffect() {#enableReflectionEffect--}
```
public abstract void enableReflectionEffect()
```


Aktiverar reflection-effekt.

### enableSoftEdgeEffect() {#enableSoftEdgeEffect--}
```
public abstract void enableSoftEdgeEffect()
```


Aktiverar soft edge-effekt.

### disableBlurEffect() {#disableBlurEffect--}
```
public abstract void disableBlurEffect()
```


Inaktiverar blur-effekt.

### disableFillOverlayEffect() {#disableFillOverlayEffect--}
```
public abstract void disableFillOverlayEffect()
```


Inaktiverar fill overlay-effekt.

### disableGlowEffect() {#disableGlowEffect--}
```
public abstract void disableGlowEffect()
```


Inaktiverar glow-effekt.

### disableInnerShadowEffect() {#disableInnerShadowEffect--}
```
public abstract void disableInnerShadowEffect()
```


Inaktiverar inner shadow-effekt.

### disableOuterShadowEffect() {#disableOuterShadowEffect--}
```
public abstract void disableOuterShadowEffect()
```


Inaktiverar outer shadow-effekt.

### disablePresetShadowEffect() {#disablePresetShadowEffect--}
```
public abstract void disablePresetShadowEffect()
```


Inaktiverar preset shadow-effekt.

### disableReflectionEffect() {#disableReflectionEffect--}
```
public abstract void disableReflectionEffect()
```


Inaktiverar reflection-effekt.

### disableSoftEdgeEffect() {#disableSoftEdgeEffect--}
```
public abstract void disableSoftEdgeEffect()
```


Inaktiverar soft edge-effekt.

### getEffective() {#getEffective--}
```
public abstract IEffectFormatEffectiveData getEffective()
```


Hämtar effektuell formateringsdata med arv tillämpat.

**Returnerar:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata) - En [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).