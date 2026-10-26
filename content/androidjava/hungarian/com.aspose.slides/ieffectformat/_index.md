---
title: IEffectFormat
second_title: Aspose.Slides Androidra a Java API hivatkozásával
description: Az alakzat effektus tulajdonságait képviseli.
type: docs
url: /hu/com.aspose.slides/ieffectformat/
---
**Az összes implementált interfész:**
[com.aspose.slides.IEffectParamSource](../../com.aspose.slides/ieffectparamsource)
```
public interface IEffectFormat extends IEffectParamSource
```

Az alakzat effektus tulajdonságait képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [isNoEffects()](#isNoEffects--) | Visszatér igaz értékkel, ha az összes effektus le van tiltva (újonnan létrehozott, alapértelmezett EffectFormat objektum). |
| [getBlurEffect()](#getBlurEffect--) | Elmosás effektus. |
| [setBlurEffect(IBlur value)](#setBlurEffect-com.aspose.slides.IBlur-) | Elmosás effektus. |
| [getFillOverlayEffect()](#getFillOverlayEffect--) | Kitöltés átfedés effektus. |
| [setFillOverlayEffect(IFillOverlay value)](#setFillOverlayEffect-com.aspose.slides.IFillOverlay-) | Kitöltés átfedés effektus. |
| [getGlowEffect()](#getGlowEffect--) | Ragyogás effektus. |
| [setGlowEffect(IGlow value)](#setGlowEffect-com.aspose.slides.IGlow-) | Ragyogás effektus. |
| [getInnerShadowEffect()](#getInnerShadowEffect--) | Belső árnyék. |
| [setInnerShadowEffect(IInnerShadow value)](#setInnerShadowEffect-com.aspose.slides.IInnerShadow-) | Belső árnyék. |
| [getOuterShadowEffect()](#getOuterShadowEffect--) | Külső árnyék. |
| [setOuterShadowEffect(IOuterShadow value)](#setOuterShadowEffect-com.aspose.slides.IOuterShadow-) | Külső árnyék. |
| [getPresetShadowEffect()](#getPresetShadowEffect--) | Előre beállított árnyék. |
| [setPresetShadowEffect(IPresetShadow value)](#setPresetShadowEffect-com.aspose.slides.IPresetShadow-) | Előre beállított árnyék. |
| [getReflectionEffect()](#getReflectionEffect--) | Tükröződés. |
| [setReflectionEffect(IReflection value)](#setReflectionEffect-com.aspose.slides.IReflection-) | Tükröződés. |
| [getSoftEdgeEffect()](#getSoftEdgeEffect--) | Lágy él. |
| [setSoftEdgeEffect(ISoftEdge value)](#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-) | Lágy él. |
| [setBlurEffect(double radius, boolean grow)](#setBlurEffect-double-boolean-) | Beállítja az elmosási effektust. |
| [enableFillOverlayEffect()](#enableFillOverlayEffect--) | Engedélyezi a kitöltés átfedés effektust. |
| [enableGlowEffect()](#enableGlowEffect--) | Engedélyezi a ragyogás effektust. |
| [enableInnerShadowEffect()](#enableInnerShadowEffect--) | Engedélyezi a belső árnyék effektust. |
| [enableOuterShadowEffect()](#enableOuterShadowEffect--) | Engedélyezi a külső árnyék effektust. |
| [enablePresetShadowEffect()](#enablePresetShadowEffect--) | Engedélyezi az előre beállított árnyék effektust. |
| [enableReflectionEffect()](#enableReflectionEffect--) | Engedélyezi a tükröződés effektust. |
| [enableSoftEdgeEffect()](#enableSoftEdgeEffect--) | Engedélyezi a lágy él effektust. |
| [disableBlurEffect()](#disableBlurEffect--) | Letiltja az elmosási effektust. |
| [disableFillOverlayEffect()](#disableFillOverlayEffect--) | Letiltja a kitöltés átfedés effektust. |
| [disableGlowEffect()](#disableGlowEffect--) | Letiltja a ragyogás effektust. |
| [disableInnerShadowEffect()](#disableInnerShadowEffect--) | Letiltja a belső árnyék effektust. |
| [disableOuterShadowEffect()](#disableOuterShadowEffect--) | Letiltja a külső árnyék effektust. |
| [disablePresetShadowEffect()](#disablePresetShadowEffect--) | Letiltja az előre beállított árnyék effektust. |
| [disableReflectionEffect()](#disableReflectionEffect--) | Letiltja a tükröződés effektust. |
| [disableSoftEdgeEffect()](#disableSoftEdgeEffect--) | Letiltja a lágy él effektust. |
| [getEffective()](#getEffective--) | Lekéri a hatékony effektus formázási adatokat a öröklődés alkalmazásával. |
### isNoEffects() {#isNoEffects--}
```
public abstract boolean isNoEffects()
```


Visszatér igaz értékkel, ha az összes effektus le van tiltva (újonnan létrehozott, alapértelmezett EffectFormat objektum). Csak olvasható boolean.

**Visszatér:**
boolean
### getBlurEffect() {#getBlurEffect--}
```
public abstract IBlur getBlurEffect()
```


Elmosás effektus. Olvasás/írás [IBlur](../../com.aspose.slides/iblur).

**Visszatér:**
[IBlur](../../com.aspose.slides/iblur)
### setBlurEffect(IBlur value) {#setBlurEffect-com.aspose.slides.IBlur-}
```
public abstract void setBlurEffect(IBlur value)
```


Elmosás effektus. Olvasás/írás [IBlur](../../com.aspose.slides/iblur).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IBlur](../../com.aspose.slides/iblur) |  |

### getFillOverlayEffect() {#getFillOverlayEffect--}
```
public abstract IFillOverlay getFillOverlayEffect()
```


Kitöltés átfedés effektus. Olvasás/írás [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**Visszatér:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay)
### setFillOverlayEffect(IFillOverlay value) {#setFillOverlayEffect-com.aspose.slides.IFillOverlay-}
```
public abstract void setFillOverlayEffect(IFillOverlay value)
```


Kitöltés átfedés effektus. Olvasás/írás [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IFillOverlay](../../com.aspose.slides/ifilloverlay) |  |

### getGlowEffect() {#getGlowEffect--}
```
public abstract IGlow getGlowEffect()
```


Ragyogás effektus. Olvasás/írás [IGlow](../../com.aspose.slides/iglow).

**Visszatér:**
[IGlow](../../com.aspose.slides/iglow)
### setGlowEffect(IGlow value) {#setGlowEffect-com.aspose.slides.IGlow-}
```
public abstract void setGlowEffect(IGlow value)
```


Ragyogás effektus. Olvasás/írás [IGlow](../../com.aspose.slides/iglow).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IGlow](../../com.aspose.slides/iglow) |  |

### getInnerShadowEffect() {#getInnerShadowEffect--}
```
public abstract IInnerShadow getInnerShadowEffect()
```


Belső árnyék. Olvasás/írás [IInnerShadow](../../com.aspose.slides/iinnershadow).

**Visszatér:**
[IInnerShadow](../../com.aspose.slides/iinnershadow)
### setInnerShadowEffect(IInnerShadow value) {#setInnerShadowEffect-com.aspose.slides.IInnerShadow-}
```
public abstract void setInnerShadowEffect(IInnerShadow value)
```


Belső árnyék. Olvasás/írás [IInnerShadow](../../com.aspose.slides/iinnershadow).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IInnerShadow](../../com.aspose.slides/iinnershadow) |  |

### getOuterShadowEffect() {#getOuterShadowEffect--}
```
public abstract IOuterShadow getOuterShadowEffect()
```


Külső árnyék. Olvasás/írás [IOuterShadow](../../com.aspose.slides/ioutershadow).

**Visszatér:**
[IOuterShadow](../../com.aspose.slides/ioutershadow)
### setOuterShadowEffect(IOuterShadow value) {#setOuterShadowEffect-com.aspose.slides.IOuterShadow-}
```
public abstract void setOuterShadowEffect(IOuterShadow value)
```


Külső árnyék. Olvasás/írás [IOuterShadow](../../com.aspose.slides/ioutershadow).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IOuterShadow](../../com.aspose.slides/ioutershadow) |  |

### getPresetShadowEffect() {#getPresetShadowEffect--}
```
public abstract IPresetShadow getPresetShadowEffect()
```


Előre beállított árnyék. Olvasás/írás [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**Visszatér:**
[IPresetShadow](../../com.aspose.slides/ipresetshadow)
### setPresetShadowEffect(IPresetShadow value) {#setPresetShadowEffect-com.aspose.slides.IPresetShadow-}
```
public abstract void setPresetShadowEffect(IPresetShadow value)
```


Előre beállított árnyék. Olvasás/írás [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IPresetShadow](../../com.aspose.slides/ipresetshadow) |  |

### getReflectionEffect() {#getReflectionEffect--}
```
public abstract IReflection getReflectionEffect()
```


Tükröződés. Olvasás/írás [IReflection](../../com.aspose.slides/ireflection).

**Visszatér:**
[IReflection](../../com.aspose.slides/ireflection)
### setReflectionEffect(IReflection value) {#setReflectionEffect-com.aspose.slides.IReflection-}
```
public abstract void setReflectionEffect(IReflection value)
```


Tükröződés. Olvasás/írás [IReflection](../../com.aspose.slides/ireflection).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IReflection](../../com.aspose.slides/ireflection) |  |

### getSoftEdgeEffect() {#getSoftEdgeEffect--}
```
public abstract ISoftEdge getSoftEdgeEffect()
```


Lágy él. Olvasás/írás [ISoftEdge](../../com.aspose.slides/isoftedge).

**Visszatér:**
[ISoftEdge](../../com.aspose.slides/isoftedge)
### setSoftEdgeEffect(ISoftEdge value) {#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-}
```
public abstract void setSoftEdgeEffect(ISoftEdge value)
```


Lágy él. Olvasás/írás [ISoftEdge](../../com.aspose.slides/isoftedge).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [ISoftEdge](../../com.aspose.slides/isoftedge) |  |

### setBlurEffect(double radius, boolean grow) {#setBlurEffect-double-boolean-}
```
public abstract void setBlurEffect(double radius, boolean grow)
```


Beállítja az elmosási effektust.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| radius | double | Sugár. |
| grow | boolean | Növelés. |

### enableFillOverlayEffect() {#enableFillOverlayEffect--}
```
public abstract void enableFillOverlayEffect()
```


Engedélyezi a kitöltés átfedés effektust.

### enableGlowEffect() {#enableGlowEffect--}
```
public abstract void enableGlowEffect()
```


Engedélyezi a ragyogás effektust.

### enableInnerShadowEffect() {#enableInnerShadowEffect--}
```
public abstract void enableInnerShadowEffect()
```


Engedélyezi a belső árnyék effektust.

### enableOuterShadowEffect() {#enableOuterShadowEffect--}
```
public abstract void enableOuterShadowEffect()
```


Engedélyezi a külső árnyék effektust.

### enablePresetShadowEffect() {#enablePresetShadowEffect--}
```
public abstract void enablePresetShadowEffect()
```


Engedélyezi az előre beállított árnyék effektust.

### enableReflectionEffect() {#enableReflectionEffect--}
```
public abstract void enableReflectionEffect()
```


Engedélyezi a tükröződés effektust.

### enableSoftEdgeEffect() {#enableSoftEdgeEffect--}
```
public abstract void enableSoftEdgeEffect()
```


Engedélyezi a lágy él effektust.

### disableBlurEffect() {#disableBlurEffect--}
```
public abstract void disableBlurEffect()
```


Letiltja az elmosási effektust.

### disableFillOverlayEffect() {#disableFillOverlayEffect--}
```
public abstract void disableFillOverlayEffect()
```


Letiltja a kitöltés átfedés effektust.

### disableGlowEffect() {#disableGlowEffect--}
```
public abstract void disableGlowEffect()
```


Letiltja a ragyogás effektust.

### disableInnerShadowEffect() {#disableInnerShadowEffect--}
```
public abstract void disableInnerShadowEffect()
```


Letiltja a belső árnyék effektust.

### disableOuterShadowEffect() {#disableOuterShadowEffect--}
```
public abstract void disableOuterShadowEffect()
```


Letiltja a külső árnyék effektust.

### disablePresetShadowEffect() {#disablePresetShadowEffect--}
```
public abstract void disablePresetShadowEffect()
```


Letiltja az előre beállított árnyék effektust.

### disableReflectionEffect() {#disableReflectionEffect--}
```
public abstract void disableReflectionEffect()
```


Letiltja a tükröződés effektust.

### disableSoftEdgeEffect() {#disableSoftEdgeEffect--}
```
public abstract void disableSoftEdgeEffect()
```


Letiltja a lágy él effektust.

### getEffective() {#getEffective--}
```
public abstract IEffectFormatEffectiveData getEffective()
```


Lekéri a hatékony effektus formázási adatokat a öröklődés alkalmazásával.

**Visszatér:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata) - egy [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).