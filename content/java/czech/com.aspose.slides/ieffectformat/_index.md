---
title: IEffectFormat
second_title: Aspose.Slides pro Java – Referenční API
description: Reprezentuje vlastnosti efektů tvaru.
type: docs
url: /cs/com.aspose.slides/ieffectformat/
---
**Všechna implementovaná rozhraní:**
[com.aspose.slides.IEffectParamSource](../../com.aspose.slides/ieffectparamsource)
```
public interface IEffectFormat extends IEffectParamSource
```

Reprezentuje vlastnosti efektů tvaru.
## Metody

| Metoda | Popis |
| --- | --- |
| [isNoEffects()](#isNoEffects--) | Vrací true, pokud jsou všechny efekty zakázány (jako právě vytvořený výchozí objekt EffectFormat). |
| [getBlurEffect()](#getBlurEffect--) | Rozmazávací efekt. |
| [setBlurEffect(IBlur value)](#setBlurEffect-com.aspose.slides.IBlur-) | Rozmazávací efekt. |
| [getFillOverlayEffect()](#getFillOverlayEffect--) | Efekt překrytí výplně. |
| [setFillOverlayEffect(IFillOverlay value)](#setFillOverlayEffect-com.aspose.slides.IFillOverlay-) | Efekt překrytí výplně. |
| [getGlowEffect()](#getGlowEffect--) | Efekt záře. |
| [setGlowEffect(IGlow value)](#setGlowEffect-com.aspose.slides.IGlow-) | Efekt záře. |
| [getInnerShadowEffect()](#getInnerShadowEffect--) | Vnitřní stín. |
| [setInnerShadowEffect(IInnerShadow value)](#setInnerShadowEffect-com.aspose.slides.IInnerShadow-) | Vnitřní stín. |
| [getOuterShadowEffect()](#getOuterShadowEffect--) | Vnější stín. |
| [setOuterShadowEffect(IOuterShadow value)](#setOuterShadowEffect-com.aspose.slides.IOuterShadow-) | Vnější stín. |
| [getPresetShadowEffect()](#getPresetShadowEffect--) | Předdefinovaný stín. |
| [setPresetShadowEffect(IPresetShadow value)](#setPresetShadowEffect-com.aspose.slides.IPresetShadow-) | Předdefinovaný stín. |
| [getReflectionEffect()](#getReflectionEffect--) | Odraz. |
| [setReflectionEffect(IReflection value)](#setReflectionEffect-com.aspose.slides.IReflection-) | Odraz. |
| [getSoftEdgeEffect()](#getSoftEdgeEffect--) | Měkký okraj. |
| [setSoftEdgeEffect(ISoftEdge value)](#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-) | Měkký okraj. |
| [setBlurEffect(double radius, boolean grow)](#setBlurEffect-double-boolean-) | Nastavuje rozmazávací efekt. |
| [enableFillOverlayEffect()](#enableFillOverlayEffect--) | Povolí efekt překrytí výplně. |
| [enableGlowEffect()](#enableGlowEffect--) | Povolí efekt záře. |
| [enableInnerShadowEffect()](#enableInnerShadowEffect--) | Povolí efekt vnitřního stínu. |
| [enableOuterShadowEffect()](#enableOuterShadowEffect--) | Povolí efekt vnějšího stínu. |
| [enablePresetShadowEffect()](#enablePresetShadowEffect--) | Povolí efekt předdefinovaných stínů. |
| [enableReflectionEffect()](#enableReflectionEffect--) | Povolí odrazový efekt. |
| [enableSoftEdgeEffect()](#enableSoftEdgeEffect--) | Povolí efekt měkkého okraje. |
| [disableBlurEffect()](#disableBlurEffect--) | Zakáže rozmazávací efekt. |
| [disableFillOverlayEffect()](#disableFillOverlayEffect--) | Zakáže efekt překrytí výplně. |
| [disableGlowEffect()](#disableGlowEffect--) | Zakáže efekt záře. |
| [disableInnerShadowEffect()](#disableInnerShadowEffect--) | Zakáže efekt vnitřního stínu. |
| [disableOuterShadowEffect()](#disableOuterShadowEffect--) | Zakáže efekt vnějšího stínu. |
| [disablePresetShadowEffect()](#disablePresetShadowEffect--) | Zakáže efekt předdefinovaného stínu. |
| [disableReflectionEffect()](#disableReflectionEffect--) | Zakáže odrazový efekt. |
| [disableSoftEdgeEffect()](#disableSoftEdgeEffect--) | Zakáže efekt měkkého okraje. |
| [getEffective()](#getEffective--) | Získá data efektového formátování s aplikovaným děděním. |

### isNoEffects() {#isNoEffects--}
```
public abstract boolean isNoEffects()
```

Vrací true, pokud jsou všechny efekty zakázány (jako právě vytvořený výchozí objekt EffectFormat). Pouze pro čtení boolean.

### getBlurEffect() {#getBlurEffect--}
```
public abstract IBlur getBlurEffect()
```

Rozmazávací efekt. Čtení/zápis [IBlur](../../com.aspose.slides/iblur).

**Vrací:**
[IBlur](../../com.aspose.slides/iblur)

### setBlurEffect(IBlur value) {#setBlurEffect-com.aspose.slides.IBlur-}
```
public abstract void setBlurEffect(IBlur value)
```

Rozmazávací efekt. Čtení/zápis [IBlur](../../com.aspose.slides/iblur).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IBlur](../../com.aspose.slides/iblur) |  |

### getFillOverlayEffect() {#getFillOverlayEffect--}
```
public abstract IFillOverlay getFillOverlayEffect()
```

Efekt překrytí výplně. Čtení/zápis [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**Vrací:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay)

### setFillOverlayEffect(IFillOverlay value) {#setFillOverlayEffect-com.aspose.slides.IFillOverlay-}
```
public abstract void setFillOverlayEffect(IFillOverlay value)
```

Efekt překrytí výplně. Čtení/zápis [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IFillOverlay](../../com.aspose.slides/ifilloverlay) |  |

### getGlowEffect() {#getGlowEffect--}
```
public abstract IGlow getGlowEffect()
```

Efekt záře. Čtení/zápis [IGlow](../../com.aspose.slides/iglow).

**Vrací:**
[IGlow](../../com.aspose.slides/iglow)

### setGlowEffect(IGlow value) {#setGlowEffect-com.aspose.slides.IGlow-}
```
public abstract void setGlowEffect(IGlow value)
```

Efekt záře. Čtení/zápis [IGlow](../../com.aspose.slides/iglow).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IGlow](../../com.aspose.slides/iglow) |  |

### getInnerShadowEffect() {#getInnerShadowEffect--}
```
public abstract IInnerShadow getInnerShadowEffect()
```

Vnitřní stín. Čtení/zápis [IInnerShadow](../../com.aspose.slides/iinnershadow).

**Vrací:**
[IInnerShadow](../../com.aspose.slides/iinnershadow)

### setInnerShadowEffect(IInnerShadow value) {#setInnerShadowEffect-com.aspose.slides.IInnerShadow-}
```
public abstract void setInnerShadowEffect(IInnerShadow value)
```

Vnitřní stín. Čtení/zápis [IInnerShadow](../../com.aspose.slides/iinnershadow).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IInnerShadow](../../com.aspose.slides/iinnershadow) |  |

### getOuterShadowEffect() {#getOuterShadowEffect--}
```
public abstract IOuterShadow getOuterShadowEffect()
```

Vnější stín. Čtení/zápis [IOuterShadow](../../com.aspose.slides/ioutershadow).

**Vrací:**
[IOuterShadow](../../com.aspose.slides/ioutershadow)

### setOuterShadowEffect(IOuterShadow value) {#setOuterShadowEffect-com.aspose.slides.IOuterShadow-}
```
public abstract void setOuterShadowEffect(IOuterShadow value)
```

Vnější stín. Čtení/zápis [IOuterShadow](../../com.aspose.slides/ioutershadow).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IOuterShadow](../../com.aspose.slides/ioutershadow) |  |

### getPresetShadowEffect() {#getPresetShadowEffect--}
```
public abstract IPresetShadow getPresetShadowEffect()
```

Předdefinovaný stín. Čtení/zápis [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**Vrací:**
[IPresetShadow](../../com.aspose.slides/ipresetshadow)

### setPresetShadowEffect(IPresetShadow value) {#setPresetShadowEffect-com.aspose.slides.IPresetShadow-}
```
public abstract void setPresetShadowEffect(IPresetShadow value)
```

Předdefinovaný stín. Čtení/zápis [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IPresetShadow](../../com.aspose.slides/ipresetshadow) |  |

### getReflectionEffect() {#getReflectionEffect--}
```
public abstract IReflection getReflectionEffect()
```

Odraz. Čtení/zápis [IReflection](../../com.aspose.slides/ireflection).

**Vrací:**
[IReflection](../../com.aspose.slides/ireflection)

### setReflectionEffect(IReflection value) {#setReflectionEffect-com.aspose.slides.IReflection-}
```
public abstract void setReflectionEffect(IReflection value)
```

Odraz. Čtení/zápis [IReflection](../../com.aspose.slides/ireflection).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IReflection](../../com.aspose.slides/ireflection) |  |

### getSoftEdgeEffect() {#getSoftEdgeEffect--}
```
public abstract ISoftEdge getSoftEdgeEffect()
```

Měkký okraj. Čtení/zápis [ISoftEdge](../../com.aspose.slides/isoftedge).

**Vrací:**
[ISoftEdge](../../com.aspose.slides/isoftedge)

### setSoftEdgeEffect(ISoftEdge value) {#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-}
```
public abstract void setSoftEdgeEffect(ISoftEdge value)
```

Měkký okraj. Čtení/zápis [ISoftEdge](../../com.aspose.slides/isoftedge).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [ISoftEdge](../../com.aspose.slides/isoftedge) |  |

### setBlurEffect(double radius, boolean grow) {#setBlurEffect-double-boolean-}
```
public abstract void setBlurEffect(double radius, boolean grow)
```

Nastavuje rozmazávací efekt.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| radius | double | Poloměr. |
| grow | boolean | Růst. |

### enableFillOverlayEffect() {#enableFillOverlayEffect--}
```
public abstract void enableFillOverlayEffect()
```

Povolí efekt překrytí výplně.

### enableGlowEffect() {#enableGlowEffect--}
```
public abstract void enableGlowEffect()
```

Povolí efekt záře.

### enableInnerShadowEffect() {#enableInnerShadowEffect--}
```
public abstract void enableInnerShadowEffect()
```

Povolí efekt vnitřního stínu.

### enableOuterShadowEffect() {#enableOuterShadowEffect--}
```
public abstract void enableOuterShadowEffect()
```

Povolí efekt vnějšího stínu.

### enablePresetShadowEffect() {#enablePresetShadowEffect--}
```
public abstract void enablePresetShadowEffect()
```

Povolí efekt předdefinovaných stínů.

### enableReflectionEffect() {#enableReflectionEffect--}
```
public abstract void enableReflectionEffect()
```

Povolí odrazový efekt.

### enableSoftEdgeEffect() {#enableSoftEdgeEffect--}
```
public abstract void enableSoftEdgeEffect()
```

Povolí efekt měkkého okraje.

### disableBlurEffect() {#disableBlurEffect--}
```
public abstract void disableBlurEffect()
```

Zakáže rozmazávací efekt.

### disableFillOverlayEffect() {#disableFillOverlayEffect--}
```
public abstract void disableFillOverlayEffect()
```

Zakáže efekt překrytí výplně.

### disableGlowEffect() {#disableGlowEffect--}
```
public abstract void disableGlowEffect()
```

Zakáže efekt záře.

### disableInnerShadowEffect() {#disableInnerShadowEffect--}
```
public abstract void disableInnerShadowEffect()
```

Zakáže efekt vnitřního stínu.

### disableOuterShadowEffect() {#disableOuterShadowEffect--}
```
public abstract void disableOuterShadowEffect()
```

Zakáže efekt vnějšího stínu.

### disablePresetShadowEffect() {#disablePresetShadowEffect--}
```
public abstract void disablePresetShadowEffect()
```

Zakáže efekt předdefinovaného stínu.

### disableReflectionEffect() {#disableReflectionEffect--}
```
public abstract void disableReflectionEffect()
```

Zakáže odrazový efekt.

### disableSoftEdgeEffect() {#disableSoftEdgeEffect--}
```
public abstract void disableSoftEdgeEffect()
```

Zakáže efekt měkkého okraje.

### getEffective() {#getEffective--}
```
public abstract IEffectFormatEffectiveData getEffective()
```

Získá data efektového formátování s aplikovaným děděním.

**Vrací:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata) - A [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).