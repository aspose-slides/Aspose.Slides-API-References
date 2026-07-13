---
title: IEffectFormat
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Reprezentuje vlastnosti efektu tvaru.
type: docs
url: /cs/com.aspose.slides/ieffectformat/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IEffectParamSource](../../com.aspose.slides/ieffectparamsource)
```
public interface IEffectFormat extends IEffectParamSource
```

Representuje vlastnosti efektu tvaru.
## Metody

| Metoda | Popis |
| --- | --- |
| [isNoEffects()](#isNoEffects--) | Vrací true, pokud jsou všechny efekty zakázány (jako právě vytvořený, výchozí objekt EffectFormat). |
| [getBlurEffect()](#getBlurEffect--) | Efekt rozostření. |
| [setBlurEffect(IBlur value)](#setBlurEffect-com.aspose.slides.IBlur-) | Efekt rozostření. |
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
| [setBlurEffect(double radius, boolean grow)](#setBlurEffect-double-boolean-) | Nastavuje efekt rozostření. |
| [enableFillOverlayEffect()](#enableFillOverlayEffect--) | Povoluje efekt překrytí výplně. |
| [enableGlowEffect()](#enableGlowEffect--) | Povoluje efekt záře. |
| [enableInnerShadowEffect()](#enableInnerShadowEffect--) | Povoluje efekt vnitřního stínu. |
| [enableOuterShadowEffect()](#enableOuterShadowEffect--) | Povoluje efekt vnějšího stínu. |
| [enablePresetShadowEffect()](#enablePresetShadowEffect--) | Povoluje efekt předdefinovaných stínů. |
| [enableReflectionEffect()](#enableReflectionEffect--) | Povoluje efekt odrazu. |
| [enableSoftEdgeEffect()](#enableSoftEdgeEffect--) | Povoluje efekt měkkého okraje. |
| [disableBlurEffect()](#disableBlurEffect--) | Zakazuje efekt rozostření. |
| [disableFillOverlayEffect()](#disableFillOverlayEffect--) | Zakazuje efekt překrytí výplně. |
| [disableGlowEffect()](#disableGlowEffect--) | Zakazuje efekt záře. |
| [disableInnerShadowEffect()](#disableInnerShadowEffect--) | Zakazuje efekt vnitřního stínu. |
| [disableOuterShadowEffect()](#disableOuterShadowEffect--) | Zakazuje efekt vnějšího stínu. |
| [disablePresetShadowEffect()](#disablePresetShadowEffect--) | Zakazuje efekt předdefinovaného stínu. |
| [disableReflectionEffect()](#disableReflectionEffect--) | Zakazuje efekt odrazu. |
| [disableSoftEdgeEffect()](#disableSoftEdgeEffect--) | Zakazuje efekt měkkého okraje. |
| [getEffective()](#getEffective--) | Získává data efektového formátování s aplikovaným děděním. |
### isNoEffects() {#isNoEffects--}
```
public abstract boolean isNoEffects()
```

Vrací true, pokud jsou všechny efekty zakázány (jako právě vytvořený, výchozí objekt EffectFormat). Pouze pro čtení, boolean.

**Vrací:**
boolean
### getBlurEffect() {#getBlurEffect--}
```
public abstract IBlur getBlurEffect()
```

Efekt rozostření. Čtení/zápis [IBlur](../../com.aspose.slides/iblur).

**Vrací:**
[IBlur](../../com.aspose.slides/iblur)
### setBlurEffect(IBlur value) {#setBlurEffect-com.aspose.slides.IBlur-}
```
public abstract void setBlurEffect(IBlur value)
```

Efekt rozostření. Čtení/zápis [IBlur](../../com.aspose.slides/iblur).

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

Nastavuje efekt rozostření.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| radius | double | Poloměr. |
| grow | boolean | Zvětšení. |
### enableFillOverlayEffect() {#enableFillOverlayEffect--}
```
public abstract void enableFillOverlayEffect()
```

Povoluje efekt překrytí výplně.

### enableGlowEffect() {#enableGlowEffect--}
```
public abstract void enableGlowEffect()
```

Povoluje efekt záře.

### enableInnerShadowEffect() {#enableInnerShadowEffect--}
```
public abstract void enableInnerShadowEffect()
```

Povoluje efekt vnitřního stínu.

### enableOuterShadowEffect() {#enableOuterShadowEffect--}
```
public abstract void enableOuterShadowEffect()
```

Povoluje efekt vnějšího stínu.

### enablePresetShadowEffect() {#enablePresetShadowEffect--}
```
public abstract void enablePresetShadowEffect()
```

Povoluje efekt předdefinovaných stínů.

### enableReflectionEffect() {#enableReflectionEffect--}
```
public abstract void enableReflectionEffect()
```

Povoluje efekt odrazu.

### enableSoftEdgeEffect() {#enableSoftEdgeEffect--}
```
public abstract void enableSoftEdgeEffect()
```

Povoluje efekt měkkého okraje.

### disableBlurEffect() {#disableBlurEffect--}
```
public abstract void disableBlurEffect()
```

Zakazuje efekt rozostření.

### disableFillOverlayEffect() {#disableFillOverlayEffect--}
```
public abstract void disableFillOverlayEffect()
```

Zakazuje efekt překrytí výplně.

### disableGlowEffect() {#disableGlowEffect--}
```
public abstract void disableGlowEffect()
```

Zakazuje efekt záře.

### disableInnerShadowEffect() {#disableInnerShadowEffect--}
```
public abstract void disableInnerShadowEffect()
```

Zakazuje efekt vnitřního stínu.

### disableOuterShadowEffect() {#disableOuterShadowEffect--}
```
public abstract void disableOuterShadowEffect()
```

Zakazuje efekt vnějšího stínu.

### disablePresetShadowEffect() {#disablePresetShadowEffect--}
```
public abstract void disablePresetShadowEffect()
```

Zakazuje efekt předdefinovaného stínu.

### disableReflectionEffect() {#disableReflectionEffect--}
```
public abstract void disableReflectionEffect()
```

Zakazuje efekt odrazu.

### disableSoftEdgeEffect() {#disableSoftEdgeEffect--}
```
public abstract void disableSoftEdgeEffect()
```

Zakazuje efekt měkkého okraje.

### getEffective() {#getEffective--}
```
public abstract IEffectFormatEffectiveData getEffective()
```

Získává data efektového formátování s aplikovaným děděním.

**Vrací:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata) - A [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).