---
title: IEffectFormat
second_title: Aspose.Slides Java API Referencia
description: Az alakzat effektus tulajdonságait ábrázolja.
type: docs
url: /hu/com.aspose.slides/ieffectformat/
---
**All Implemented Interfaces:**
[com.aspose.slides.IEffectParamSource](../../com.aspose.slides/ieffectparamsource)
```
public interface IEffectFormat extends IEffectParamSource
```

Ábrázolja az alakzat effektus tulajdonságait.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [isNoEffects()](#isNoEffects--) | Igaz értéket ad vissza, ha minden effektus ki van kapcsolva (újonnan létrehozott, alapértelmezett EffectFormat objektum). |
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
| [setBlurEffect(double radius, boolean grow)](#setBlurEffect-double-boolean-) | Sets blur effect. |
| [enableFillOverlayEffect()](#enableFillOverlayEffect--) | Enables fill overlay effect. |
| [enableGlowEffect()](#enableGlowEffect--) | Enables glow effect. |
| [enableInnerShadowEffect()](#enableInnerShadowEffect--) | Enables inner shadow effect. |
| [enableOuterShadowEffect()](#enableOuterShadowEffect--) | Enables outer shadow effect. |
| [enablePresetShadowEffect()](#enablePresetShadowEffect--) | Enables preset shadows effect. |
| [enableReflectionEffect()](#enableReflectionEffect--) | Enables reflection effect. |
| [enableSoftEdgeEffect()](#enableSoftEdgeEffect--) | Enables soft edge effect. |
| [disableBlurEffect()](#disableBlurEffect--) | Disables blur effect. |
| [disableFillOverlayEffect()](#disableFillOverlayEffect--) | Disables fill overlay effect. |
| [disableGlowEffect()](#disableGlowEffect--) | Disable glow effect. |
| [disableInnerShadowEffect()](#disableInnerShadowEffect--) | Disables inner shadow effect. |
| [disableOuterShadowEffect()](#disableOuterShadowEffect--) | Disables outer shadow effect. |
| [disablePresetShadowEffect()](#disablePresetShadowEffect--) | Disables preset shadow effect. |
| [disableReflectionEffect()](#disableReflectionEffect--) | Disables reflection effect. |
| [disableSoftEdgeEffect()](#disableSoftEdgeEffect--) | Disables soft edge effect. |
| [getEffective()](#getEffective--) | Gets effective effect formatting data with the inheritance applied. |
### isNoEffects() {#isNoEffects--}
```
public abstract boolean isNoEffects()
```

Igaz értéket ad vissza, ha minden effektus ki van kapcsolva (újonnan létrehozott, alapértelmezett EffectFormat objektum). Csak-olvasás boolean.

**Visszatér:**
boolean
### getBlurEffect() {#getBlurEffect--}
```
public abstract IBlur getBlurEffect()
```

Blur effect. Olvasás/írás [IBlur](../../com.aspose.slides/iblur).

**Visszatér:**
[IBlur](../../com.aspose.slides/iblur)
### setBlurEffect(IBlur value) {#setBlurEffect-com.aspose.slides.IBlur-}
```
public abstract void setBlurEffect(IBlur value)
```

Blur effect. Olvasás/írás [IBlur](../../com.aspose.slides/iblur).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IBlur](../../com.aspose.slides/iblur) |  |

### getFillOverlayEffect() {#getFillOverlayEffect--}
```
public abstract IFillOverlay getFillOverlayEffect()
```

Fill overlay effect. Olvasás/írás [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**Visszatér:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay)
### setFillOverlayEffect(IFillOverlay value) {#setFillOverlayEffect-com.aspose.slides.IFillOverlay-}
```
public abstract void setFillOverlayEffect(IFillOverlay value)
```

Fill overlay effect. Olvasás/írás [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IFillOverlay](../../com.aspose.slides/ifilloverlay) |  |

### getGlowEffect() {#getGlowEffect--}
```
public abstract IGlow getGlowEffect()
```

Glow effect. Olvasás/írás [IGlow](../../com.aspose.slides/iglow).

**Visszatér:**
[IGlow](../../com.aspose.slides/iglow)
### setGlowEffect(IGlow value) {#setGlowEffect-com.aspose.slides.IGlow-}
```
public abstract void setGlowEffect(IGlow value)
```

Glow effect. Olvasás/írás [IGlow](../../com.aspose.slides/iglow).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IGlow](../../com.aspose.slides/iglow) |  |

### getInnerShadowEffect() {#getInnerShadowEffect--}
```
public abstract IInnerShadow getInnerShadowEffect()
```

Inner shadow. Olvasás/írás [IInnerShadow](../../com.aspose.slides/iinnershadow).

**Visszatér:**
[IInnerShadow](../../com.aspose.slides/iinnershadow)
### setInnerShadowEffect(IInnerShadow value) {#setInnerShadowEffect-com.aspose.slides.IInnerShadow-}
```
public abstract void setInnerShadowEffect(IInnerShadow value)
```

Inner shadow. Olvasás/írás [IInnerShadow](../../com.aspose.slides/iinnershadow).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IInnerShadow](../../com.aspose.slides/iinnershadow) |  |

### getOuterShadowEffect() {#getOuterShadowEffect--}
```
public abstract IOuterShadow getOuterShadowEffect()
```

Outer shadow. Olvasás/írás [IOuterShadow](../../com.aspose.slides/ioutershadow).

**Visszatér:**
[IOuterShadow](../../com.aspose.slides/ioutershadow)
### setOuterShadowEffect(IOuterShadow value) {#setOuterShadowEffect-com.aspose.slides.IOuterShadow-}
```
public abstract void setOuterShadowEffect(IOuterShadow value)
```

Outer shadow. Olvasás/írás [IOuterShadow](../../com.aspose.slides/ioutershadow).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IOuterShadow](../../com.aspose.slides/ioutershadow) |  |

### getPresetShadowEffect() {#getPresetShadowEffect--}
```
public abstract IPresetShadow getPresetShadowEffect()
```

Preset shadow. Olvasás/írás [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**Visszatér:**
[IPresetShadow](../../com.aspose.slides/ipresetshadow)
### setPresetShadowEffect(IPresetShadow value) {#setPresetShadowEffect-com.aspose.slides.IPresetShadow-}
```
public abstract void setPresetShadowEffect(IPresetShadow value)
```

Preset shadow. Olvasás/írás [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IPresetShadow](../../com.aspose.slides/ipresetshadow) |  |

### getReflectionEffect() {#getReflectionEffect--}
```
public abstract IReflection getReflectionEffect()
```

Reflection. Olvasás/írás [IReflection](../../com.aspose.slides/ireflection).

**Visszatér:**
[IReflection](../../com.aspose.slides/ireflection)
### setReflectionEffect(IReflection value) {#setReflectionEffect-com.aspose.slides.IReflection-}
```
public abstract void setReflectionEffect(IReflection value)
```

Reflection. Olvasás/írás [IReflection](../../com.aspose.slides/ireflection).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IReflection](../../com.aspose.slides/ireflection) |  |

### getSoftEdgeEffect() {#getSoftEdgeEffect--}
```
public abstract ISoftEdge getSoftEdgeEffect()
```

Soft edge. Olvasás/írás [ISoftEdge](../../com.aspose.slides/isoftedge).

**Visszatér:**
[ISoftEdge](../../com.aspose.slides/isoftedge)
### setSoftEdgeEffect(ISoftEdge value) {#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-}
```
public abstract void setSoftEdgeEffect(ISoftEdge value)
```

Soft edge. Olvasás/írás [ISoftEdge](../../com.aspose.slides/isoftedge).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [ISoftEdge](../../com.aspose.slides/isoftedge) |  |

### setBlurEffect(double radius, boolean grow) {#setBlurEffect-double-boolean-}
```
public abstract void setBlurEffect(double radius, boolean grow)
```

Beállítja a blur effectet.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| radius | double | Radius. |
| grow | boolean | Grow. |

### enableFillOverlayEffect() {#enableFillOverlayEffect--}
```
public abstract void enableFillOverlayEffect()
```

Engedélyezi fill overlay effect.

### enableGlowEffect() {#enableGlowEffect--}
```
public abstract void enableGlowEffect()
```

Engedélyezi glow effect.

### enableInnerShadowEffect() {#enableInnerShadowEffect--}
```
public abstract void enableInnerShadowEffect()
```

Engedélyezi inner shadow effect.

### enableOuterShadowEffect() {#enableOuterShadowEffect--}
```
public abstract void enableOuterShadowEffect()
```

Engedélyezi outer shadow effect.

### enablePresetShadowEffect() {#enablePresetShadowEffect--}
```
public abstract void enablePresetShadowEffect()
```

Engedélyezi preset shadows effect.

### enableReflectionEffect() {#enableReflectionEffect--}
```
public abstract void enableReflectionEffect()
```

Engedélyezi reflection effect.

### enableSoftEdgeEffect() {#enableSoftEdgeEffect--}
```
public abstract void enableSoftEdgeEffect()
```

Engedélyezi soft edge effect.

### disableBlurEffect() {#disableBlurEffect--}
```
public abstract void disableBlurEffect()
```

Letiltja blur effect.

### disableFillOverlayEffect() {#disableFillOverlayEffect--}
```
public abstract void disableFillOverlayEffect()
```

Letiltja fill overlay effect.

### disableGlowEffect() {#disableGlowEffect--}
```
public abstract void disableGlowEffect()
```

Disable glow effect.

### disableInnerShadowEffect() {#disableInnerShadowEffect--}
```
public abstract void disableInnerShadowEffect()
```

Letiltja inner shadow effect.

### disableOuterShadowEffect() {#disableOuterShadowEffect--}
```
public abstract void disableOuterShadowEffect()
```

Letiltja outer shadow effect.

### disablePresetShadowEffect() {#disablePresetShadowEffect--}
```
public abstract void disablePresetShadowEffect()
```

Letiltja preset shadow effect.

### disableReflectionEffect() {#disableReflectionEffect--}
```
public abstract void disableReflectionEffect()
```

Letiltja reflection effect.

### disableSoftEdgeEffect() {#disableSoftEdgeEffect--}
```
public abstract void disableSoftEdgeEffect()
```

Letiltja soft edge effect.

### getEffective() {#getEffective--}
```
public abstract IEffectFormatEffectiveData getEffective()
```

Lekéri a hatékony effektus formázási adatokat az öröklődés alkalmazásával.

**Visszatér:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata) - A [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).