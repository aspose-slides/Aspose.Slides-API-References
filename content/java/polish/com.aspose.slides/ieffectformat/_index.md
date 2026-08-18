---
title: IEffectFormat
second_title: Referencja API Aspose.Slides dla Javy
description: Reprezentuje właściwości efektów kształtu.
type: docs
url: /pl/com.aspose.slides/ieffectformat/
---
**All Implemented Interfaces:**
[com.aspose.slides.IEffectParamSource](../../com.aspose.slides/ieffectparamsource)
```
public interface IEffectFormat extends IEffectParamSource
```

Represents effect properties of shape.
## Metody

| Metoda | Opis |
| --- | --- |
| [isNoEffects()](#isNoEffects--) | Returns true if all effects are disabled (as just created, default EffectFormat object). |
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

Zwraca true, jeśli wszystkie efekty są wyłączone (tak jak po utworzeniu, domyślny obiekt EffectFormat). Tylko do odczytu boolean.

**Zwraca:**
boolean
### getBlurEffect() {#getBlurEffect--}
```
public abstract IBlur getBlurEffect()
```

Efekt rozmycia. Odczyt/zapis [IBlur](../../com.aspose.slides/iblur).

**Zwraca:**
[IBlur](../../com.aspose.slides/iblur)
### setBlurEffect(IBlur value) {#setBlurEffect-com.aspose.slides.IBlur-}
```
public abstract void setBlurEffect(IBlur value)
```

Efekt rozmycia. Odczyt/zapis [IBlur](../../com.aspose.slides/iblur).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IBlur](../../com.aspose.slides/iblur) |  |

### getFillOverlayEffect() {#getFillOverlayEffect--}
```
public abstract IFillOverlay getFillOverlayEffect()
```

Fill overlay effect. Odczyt/zapis [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**Zwraca:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay)
### setFillOverlayEffect(IFillOverlay value) {#setFillOverlayEffect-com.aspose.slides.IFillOverlay-}
```
public abstract void setFillOverlayEffect(IFillOverlay value)
```

Fill overlay effect. Odczyt/zapis [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IFillOverlay](../../com.aspose.slides/ifilloverlay) |  |

### getGlowEffect() {#getGlowEffect--}
```
public abstract IGlow getGlowEffect()
```

Glow effect. Odczyt/zapis [IGlow](../../com.aspose.slides/iglow).

**Zwraca:**
[IGlow](../../com.aspose.slides/iglow)
### setGlowEffect(IGlow value) {#setGlowEffect-com.aspose.slides.IGlow-}
```
public abstract void setGlowEffect(IGlow value)
```

Glow effect. Odczyt/zapis [IGlow](../../com.aspose.slides/iglow).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IGlow](../../com.aspose.slides/iglow) |  |

### getInnerShadowEffect() {#getInnerShadowEffect--}
```
public abstract IInnerShadow getInnerShadowEffect()
```

Inner shadow. Odczyt/zapis [IInnerShadow](../../com.aspose.slides/iinnershadow).

**Zwraca:**
[IInnerShadow](../../com.aspose.slides/iinnershadow)
### setInnerShadowEffect(IInnerShadow value) {#setInnerShadowEffect-com.aspose.slides.IInnerShadow-}
```
public abstract void setInnerShadowEffect(IInnerShadow value)
```

Inner shadow. Odczyt/zapis [IInnerShadow](../../com.aspose.slides/iinnershadow).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IInnerShadow](../../com.aspose.slides/iinnershadow) |  |

### getOuterShadowEffect() {#getOuterShadowEffect--}
```
public abstract IOuterShadow getOuterShadowEffect()
```

Outer shadow. Odczyt/zapis [IOuterShadow](../../com.aspose.slides/ioutershadow).

**Zwraca:**
[IOuterShadow](../../com.aspose.slides/ioutershadow)
### setOuterShadowEffect(IOuterShadow value) {#setOuterShadowEffect-com.aspose.slides.IOuterShadow-}
```
public abstract void setOuterShadowEffect(IOuterShadow value)
```

Outer shadow. Odczyt/zapis [IOuterShadow](../../com.aspose.slides/ioutershadow).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IOuterShadow](../../com.aspose.slides/ioutershadow) |  |

### getPresetShadowEffect() {#getPresetShadowEffect--}
```
public abstract IPresetShadow getPresetShadowEffect()
```

Preset shadow. Odczyt/zapis [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**Zwraca:**
[IPresetShadow](../../com.aspose.slides/ipresetshadow)
### setPresetShadowEffect(IPresetShadow value) {#setPresetShadowEffect-com.aspose.slides.IPresetShadow-}
```
public abstract void setPresetShadowEffect(IPresetShadow value)
```

Preset shadow. Odczyt/zapis [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IPresetShadow](../../com.aspose.slides/ipresetshadow) |  |

### getReflectionEffect() {#getReflectionEffect--}
```
public abstract IReflection getReflectionEffect()
```

Reflection. Odczyt/zapis [IReflection](../../com.aspose.slides/ireflection).

**Zwraca:**
[IReflection](../../com.aspose.slides/ireflection)
### setReflectionEffect(IReflection value) {#setReflectionEffect-com.aspose.slides.IReflection-}
```
public abstract void setReflectionEffect(IReflection value)
```

Reflection. Odczyt/zapis [IReflection](../../com.aspose.slides/ireflection).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IReflection](../../com.aspose.slides/ireflection) |  |

### getSoftEdgeEffect() {#getSoftEdgeEffect--}
```
public abstract ISoftEdge getSoftEdgeEffect()
```

Soft edge. Odczyt/zapis [ISoftEdge](../../com.aspose.slides/isoftedge).

**Zwraca:**
[ISoftEdge](../../com.aspose.slides/isoftedge)
### setSoftEdgeEffect(ISoftEdge value) {#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-}
```
public abstract void setSoftEdgeEffect(ISoftEdge value)
```

Soft edge. Odczyt/zapis [ISoftEdge](../../com.aspose.slides/isoftedge).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [ISoftEdge](../../com.aspose.slides/isoftedge) |  |

### setBlurEffect(double radius, boolean grow) {#setBlurEffect-double-boolean-}
```
public abstract void setBlurEffect(double radius, boolean grow)
```

Ustawia efekt rozmycia.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| radius | double | Radius. |
| grow | boolean | Grow. |

### enableFillOverlayEffect() {#enableFillOverlayEffect--}
```
public abstract void enableFillOverlayEffect()
```

Włącza efekt nakładki wypełnienia.

### enableGlowEffect() {#enableGlowEffect--}
```
public abstract void enableGlowEffect()
```

Włącza efekt poświaty.

### enableInnerShadowEffect() {#enableInnerShadowEffect--}
```
public abstract void enableInnerShadowEffect()
```

Włącza efekt wewnętrznego cienia.

### enableOuterShadowEffect() {#enableOuterShadowEffect--}
```
public abstract void enableOuterShadowEffect()
```

Włącza efekt zewnętrznego cienia.

### enablePresetShadowEffect() {#enablePresetShadowEffect--}
```
public abstract void enablePresetShadowEffect()
```

Włącza efekt predefiniowanego cienia.

### enableReflectionEffect() {#enableReflectionEffect--}
```
public abstract void enableReflectionEffect()
```

Włącza efekt odbicia.

### enableSoftEdgeEffect() {#enableSoftEdgeEffect--}
```
public abstract void enableSoftEdgeEffect()
```

Włącza efekt miękkiej krawędzi.

### disableBlurEffect() {#disableBlurEffect--}
```
public abstract void disableBlurEffect()
```

Wyłącza efekt rozmycia.

### disableFillOverlayEffect() {#disableFillOverlayEffect--}
```
public abstract void disableFillOverlayEffect()
```

Wyłącza efekt nakładki wypełnienia.

### disableGlowEffect() {#disableGlowEffect--}
```
public abstract void disableGlowEffect()
```

Disable glow effect.

### disableInnerShadowEffect() {#disableInnerShadowEffect--}
```
public abstract void disableInnerShadowEffect()
```

Wyłącza efekt wewnętrznego cienia.

### disableOuterShadowEffect() {#disableOuterShadowEffect--}
```
public abstract void disableOuterShadowEffect()
```

Wyłącza efekt zewnętrznego cienia.

### disablePresetShadowEffect() {#disablePresetShadowEffect--}
```
public abstract void disablePresetShadowEffect()
```

Wyłącza efekt predefiniowanego cienia.

### disableReflectionEffect() {#disableReflectionEffect--}
```
public abstract void disableReflectionEffect()
```

Wyłącza efekt odbicia.

### disableSoftEdgeEffect() {#disableSoftEdgeEffect--}
```
public abstract void disableSoftEdgeEffect()
```

Wyłącza efekt miękkiej krawędzi.

### getEffective() {#getEffective--}
```
public abstract IEffectFormatEffectiveData getEffective()
```

Pobiera efektywne dane formatowania efektu z zastosowanym dziedziczeniem.

**Zwraca:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata) - A [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).