---
title: IEffectFormat
second_title: Aspose.Slides für Java API-Referenz
description: Stellt die Effekt-Eigenschaften einer Form dar.
type: docs
url: /de/com.aspose.slides/ieffectformat/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IEffectParamSource](../../com.aspose.slides/ieffectparamsource)
```
public interface IEffectFormat extends IEffectParamSource
```

Stellt die Effekt-Eigenschaften einer Form dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isNoEffects()](#isNoEffects--) | Gibt true zurück, wenn alle Effekte deaktiviert sind (wie bei einem neu erstellten, standardmäßigen EffectFormat-Objekt). |
| [getBlurEffect()](#getBlurEffect--) | Unschärfe-Effekt. |
| [setBlurEffect(IBlur value)](#setBlurEffect-com.aspose.slides.IBlur-) | Unschärfe-Effekt. |
| [getFillOverlayEffect()](#getFillOverlayEffect--) | Füllüberlagerungs-Effekt. |
| [setFillOverlayEffect(IFillOverlay value)](#setFillOverlayEffect-com.aspose.slides.IFillOverlay-) | Füllüberlagerungs-Effekt. |
| [getGlowEffect()](#getGlowEffect--) | Leuchteffekt. |
| [setGlowEffect(IGlow value)](#setGlowEffect-com.aspose.slides.IGlow-) | Leuchteffekt. |
| [getInnerShadowEffect()](#getInnerShadowEffect--) | Innerer Schatten. |
| [setInnerShadowEffect(IInnerShadow value)](#setInnerShadowEffect-com.aspose.slides.IInnerShadow-) | Innerer Schatten. |
| [getOuterShadowEffect()](#getOuterShadowEffect--) | Äußerer Schatten. |
| [setOuterShadowEffect(IOuterShadow value)](#setOuterShadowEffect-com.aspose.slides.IOuterShadow-) | Äußerer Schatten. |
| [getPresetShadowEffect()](#getPresetShadowEffect--) | Voreingestellter Schatten. |
| [setPresetShadowEffect(IPresetShadow value)](#setPresetShadowEffect-com.aspose.slides.IPresetShadow-) | Voreingestellter Schatten. |
| [getReflectionEffect()](#getReflectionEffect--) | Reflexion. |
| [setReflectionEffect(IReflection value)](#setReflectionEffect-com.aspose.slides.IReflection-) | Reflexion. |
| [getSoftEdgeEffect()](#getSoftEdgeEffect--) | Weiche Kante. |
| [setSoftEdgeEffect(ISoftEdge value)](#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-) | Weiche Kante. |
| [setBlurEffect(double radius, boolean grow)](#setBlurEffect-double-boolean-) | Setzt Unschärfe-Effekt. |
| [enableFillOverlayEffect()](#enableFillOverlayEffect--) | Aktiviert den Füllüberlagerungs-Effekt. |
| [enableGlowEffect()](#enableGlowEffect--) | Aktiviert den Leuchteffekt. |
| [enableInnerShadowEffect()](#enableInnerShadowEffect--) | Aktiviert den inneren Schatten-Effekt. |
| [enableOuterShadowEffect()](#enableOuterShadowEffect--) | Aktiviert den äußeren Schatten-Effekt. |
| [enablePresetShadowEffect()](#enablePresetShadowEffect--) | Aktiviert den voreingestellten Schatten-Effekt. |
| [enableReflectionEffect()](#enableReflectionEffect--) | Aktiviert den Reflexions-Effekt. |
| [enableSoftEdgeEffect()](#enableSoftEdgeEffect--) | Aktiviert den weichen Kanten-Effekt. |
| [disableBlurEffect()](#disableBlurEffect--) | Deaktiviert den Unschärfe-Effekt. |
| [disableFillOverlayEffect()](#disableFillOverlayEffect--) | Deaktiviert den Füllüberlagerungs-Effekt. |
| [disableGlowEffect()](#disableGlowEffect--) | Deaktiviert den Leuchteffekt. |
| [disableInnerShadowEffect()](#disableInnerShadowEffect--) | Deaktiviert den inneren Schatten-Effekt. |
| [disableOuterShadowEffect()](#disableOuterShadowEffect--) | Deaktiviert den äußeren Schatten-Effekt. |
| [disablePresetShadowEffect()](#disablePresetShadowEffect--) | Deaktiviert den voreingestellten Schatten-Effekt. |
| [disableReflectionEffect()](#disableReflectionEffect--) | Deaktiviert den Reflexions-Effekt. |
| [disableSoftEdgeEffect()](#disableSoftEdgeEffect--) | Deaktiviert den weichen Kanten-Effekt. |
| [getEffective()](#getEffective--) | Liefert die effektive Effekt-Formatierungsdaten mit angewandter Vererbung. |

### isNoEffects() {#isNoEffects--}
```
public abstract boolean isNoEffects()
```

Gibt true zurück, wenn alle Effekte deaktiviert sind (wie bei einem neu erstellten, standardmäßigen EffectFormat-Objekt). Nur lesbarer boolescher Wert.

**Rückgabe:**
boolean

### getBlurEffect() {#getBlurEffect--}
```
public abstract IBlur getBlurEffect()
```

Unschärfe-Effekt. Lese/Schreib [IBlur](../../com.aspose.slides/iblur).

**Rückgabe:**
[IBlur](../../com.aspose.slides/iblur)

### setBlurEffect(IBlur value) {#setBlurEffect-com.aspose.slides.IBlur-}
```
public abstract void setBlurEffect(IBlur value)
```

Unschärfe-Effekt. Lese/Schreib [IBlur](../../com.aspose.slides/iblur).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IBlur](../../com.aspose.slides/iblur) |  |

### getFillOverlayEffect() {#getFillOverlayEffect--}
```
public abstract IFillOverlay getFillOverlayEffect()
```

Füllüberlagerungs-Effekt. Lese/Schreib [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**Rückgabe:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay)

### setFillOverlayEffect(IFillOverlay value) {#setFillOverlayEffect-com.aspose.slides.IFillOverlay-}
```
public abstract void setFillOverlayEffect(IFillOverlay value)
```

Füllüberlagerungs-Effekt. Lese/Schreib [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IFillOverlay](../../com.aspose.slides/ifilloverlay) |  |

### getGlowEffect() {#getGlowEffect--}
```
public abstract IGlow getGlowEffect()
```

Leuchteffekt. Lese/Schreib [IGlow](../../com.aspose.slides/iglow).

**Rückgabe:**
[IGlow](../../com.aspose.slides/iglow)

### setGlowEffect(IGlow value) {#setGlowEffect-com.aspose.slides.IGlow-}
```
public abstract void setGlowEffect(IGlow value)
```

Leuchteffekt. Lese/Schreib [IGlow](../../com.aspose.slides/iglow).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IGlow](../../com.aspose.slides/iglow) |  |

### getInnerShadowEffect() {#getInnerShadowEffect--}
```
public abstract IInnerShadow getInnerShadowEffect()
```

Innerer Schatten. Lese/Schreib [IInnerShadow](../../com.aspose.slides/iinnershadow).

**Rückgabe:**
[IInnerShadow](../../com.aspose.slides/iinnershadow)

### setInnerShadowEffect(IInnerShadow value) {#setInnerShadowEffect-com.aspose.slides.IInnerShadow-}
```
public abstract void setInnerShadowEffect(IInnerShadow value)
```

Innerer Schatten. Lese/Schreib [IInnerShadow](../../com.aspose.slides/iinnershadow).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IInnerShadow](../../com.aspose.slides/iinnershadow) |  |

### getOuterShadowEffect() {#getOuterShadowEffect--}
```
public abstract IOuterShadow getOuterShadowEffect()
```

Äußerer Schatten. Lese/Schreib [IOuterShadow](../../com.aspose.slides/ioutershadow).

**Rückgabe:**
[IOuterShadow](../../com.aspose.slides/ioutershadow)

### setOuterShadowEffect(IOuterShadow value) {#setOuterShadowEffect-com.aspose.slides.IOuterShadow-}
```
public abstract void setOuterShadowEffect(IOuterShadow value)
```

Äußerer Schatten. Lese/Schreib [IOuterShadow](../../com.aspose.slides/ioutershadow).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IOuterShadow](../../com.aspose.slides/ioutershadow) |  |

### getPresetShadowEffect() {#getPresetShadowEffect--}
```
public abstract IPresetShadow getPresetShadowEffect()
```

Voreingestellter Schatten. Lese/Schreib [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**Rückgabe:**
[IPresetShadow](../../com.aspose.slides/ipresetshadow)

### setPresetShadowEffect(IPresetShadow value) {#setPresetShadowEffect-com.aspose.slides.IPresetShadow-}
```
public abstract void setPresetShadowEffect(IPresetShadow value)
```

Voreingestellter Schatten. Lese/Schreib [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IPresetShadow](../../com.aspose.slides/ipresetshadow) |  |

### getReflectionEffect() {#getReflectionEffect--}
```
public abstract IReflection getReflectionEffect()
```

Reflexion. Lese/Schreib [IReflection](../../com.aspose.slides/ireflection).

**Rückgabe:**
[IReflection](../../com.aspose.slides/ireflection)

### setReflectionEffect(IReflection value) {#setReflectionEffect-com.aspose.slides.IReflection-}
```
public abstract void setReflectionEffect(IReflection value)
```

Reflexion. Lese/Schreib [IReflection](../../com.aspose.slides/ireflection).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IReflection](../../com.aspose.slides/ireflection) |  |

### getSoftEdgeEffect() {#getSoftEdgeEffect--}
```
public abstract ISoftEdge getSoftEdgeEffect()
```

Weiche Kante. Lese/Schreib [ISoftEdge](../../com.aspose.slides/isoftedge).

**Rückgabe:**
[ISoftEdge](../../com.aspose.slides/isoftedge)

### setSoftEdgeEffect(ISoftEdge value) {#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-}
```
public abstract void setSoftEdgeEffect(ISoftEdge value)
```

Weiche Kante. Lese/Schreib [ISoftEdge](../../com.aspose.slides/isoftedge).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ISoftEdge](../../com.aspose.slides/isoftedge) |  |

### setBlurEffect(double radius, boolean grow) {#setBlurEffect-double-boolean-}
```
public abstract void setBlurEffect(double radius, boolean grow)
```

Setzt Unschärfe-Effekt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| radius | double | Radius. |
| grow | boolean | Vergrößern. |

### enableFillOverlayEffect() {#enableFillOverlayEffect--}
```
public abstract void enableFillOverlayEffect()
```

Aktiviert den Füllüberlagerungs-Effekt.

### enableGlowEffect() {#enableGlowEffect--}
```
public abstract void enableGlowEffect()
```

Aktiviert den Leuchteffekt.

### enableInnerShadowEffect() {#enableInnerShadowEffect--}
```
public abstract void enableInnerShadowEffect()
```

Aktiviert den inneren Schatten-Effekt.

### enableOuterShadowEffect() {#enableOuterShadowEffect--}
```
public abstract void enableOuterShadowEffect()
```

Aktiviert den äußeren Schatten-Effekt.

### enablePresetShadowEffect() {#enablePresetShadowEffect--}
```
public abstract void enablePresetShadowEffect()
```

Aktiviert den voreingestellten Schatten-Effekt.

### enableReflectionEffect() {#enableReflectionEffect--}
```
public abstract void enableReflectionEffect()
```

Aktiviert den Reflexions-Effekt.

### enableSoftEdgeEffect() {#enableSoftEdgeEffect--}
```
public abstract void enableSoftEdgeEffect()
```

Aktiviert den weichen Kanten-Effekt.

### disableBlurEffect() {#disableBlurEffect--}
```
public abstract void disableBlurEffect()
```

Deaktiviert den Unschärfe-Effekt.

### disableFillOverlayEffect() {#disableFillOverlayEffect--}
```
public abstract void disableFillOverlayEffect()
```

Deaktiviert den Füllüberlagerungs-Effekt.

### disableGlowEffect() {#disableGlowEffect--}
```
public abstract void disableGlowEffect()
```

Deaktiviert den Leuchteffekt.

### disableInnerShadowEffect() {#disableInnerShadowEffect--}
```
public abstract void disableInnerShadowEffect()
```

Deaktiviert den inneren Schatten-Effekt.

### disableOuterShadowEffect() {#disableOuterShadowEffect--}
```
public abstract void disableOuterShadowEffect()
```

Deaktiviert den äußeren Schatten-Effekt.

### disablePresetShadowEffect() {#disablePresetShadowEffect--}
```
public abstract void disablePresetShadowEffect()
```

Deaktiviert den voreingestellten Schatten-Effekt.

### disableReflectionEffect() {#disableReflectionEffect--}
```
public abstract void disableReflectionEffect()
```

Deaktiviert den Reflexions-Effekt.

### disableSoftEdgeEffect() {#disableSoftEdgeEffect--}
```
public abstract void disableSoftEdgeEffect()
```

Deaktiviert den weichen Kanten-Effekt.

### getEffective() {#getEffective--}
```
public abstract IEffectFormatEffectiveData getEffective()
```

Liefert die effektive Effekt-Formatierungsdaten mit angewandter Vererbung.

**Rückgabe:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata) - Ein [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).