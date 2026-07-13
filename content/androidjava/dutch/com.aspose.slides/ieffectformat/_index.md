---
title: IEffectFormat
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt effecteigenschappen van een vorm voor.
type: docs
url: /nl/com.aspose.slides/ieffectformat/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IEffectParamSource](../../com.aspose.slides/ieffectparamsource)
```
public interface IEffectFormat extends IEffectParamSource
```

Stelt effecteigenschappen van een vorm voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [isNoEffects()](#isNoEffects--) | Retourneert true als alle effecten zijn uitgeschakeld (zoals net aangemaakt, standaard EffectFormat-object). |
| [getBlurEffect()](#getBlurEffect--) | Vervagingseffect. |
| [setBlurEffect(IBlur value)](#setBlurEffect-com.aspose.slides.IBlur-) | Vervagingseffect. |
| [getFillOverlayEffect()](#getFillOverlayEffect--) | Vulling overlay effect. |
| [setFillOverlayEffect(IFillOverlay value)](#setFillOverlayEffect-com.aspose.slides.IFillOverlay-) | Vulling overlay effect. |
| [getGlowEffect()](#getGlowEffect--) | Gloeieffect. |
| [setGlowEffect(IGlow value)](#setGlowEffect-com.aspose.slides.IGlow-) | Gloeieffect. |
| [getInnerShadowEffect()](#getInnerShadowEffect--) | Inwendige schaduw. |
| [setInnerShadowEffect(IInnerShadow value)](#setInnerShadowEffect-com.aspose.slides.IInnerShadow-) | Inwendige schaduw. |
| [getOuterShadowEffect()](#getOuterShadowEffect--) | Buitenste schaduw. |
| [setOuterShadowEffect(IOuterShadow value)](#setOuterShadowEffect-com.aspose.slides.IOuterShadow-) | Buitenste schaduw. |
| [getPresetShadowEffect()](#getPresetShadowEffect--) | Vooraf ingestelde schaduw. |
| [setPresetShadowEffect(IPresetShadow value)](#setPresetShadowEffect-com.aspose.slides.IPresetShadow-) | Vooraf ingestelde schaduw. |
| [getReflectionEffect()](#getReflectionEffect--) | Reflectie. |
| [setReflectionEffect(IReflection value)](#setReflectionEffect-com.aspose.slides.IReflection-) | Reflectie. |
| [getSoftEdgeEffect()](#getSoftEdgeEffect--) | Zachte rand. |
| [setSoftEdgeEffect(ISoftEdge value)](#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-) | Zachte rand. |
| [setBlurEffect(double radius, boolean grow)](#setBlurEffect-double-boolean-) | Stelt vervagingseffect in. |
| [enableFillOverlayEffect()](#enableFillOverlayEffect--) | Schakelt vulling overlay effect in. |
| [enableGlowEffect()](#enableGlowEffect--) | Schakelt gloeieffect in. |
| [enableInnerShadowEffect()](#enableInnerShadowEffect--) | Schakelt inwendige schaduw in. |
| [enableOuterShadowEffect()](#enableOuterShadowEffect--) | Schakelt buitenste schaduw in. |
| [enablePresetShadowEffect()](#enablePresetShadowEffect--) | Schakelt vooraf ingestelde schaduwen in. |
| [enableReflectionEffect()](#enableReflectionEffect--) | Schakelt reflectie in. |
| [enableSoftEdgeEffect()](#enableSoftEdgeEffect--) | Schakelt zachte rand in. |
| [disableBlurEffect()](#disableBlurEffect--) | Schakelt vervagingseffect uit. |
| [disableFillOverlayEffect()](#disableFillOverlayEffect--) | Schakelt vulling overlay effect uit. |
| [disableGlowEffect()](#disableGlowEffect--) | Schakelt gloeieffect uit. |
| [disableInnerShadowEffect()](#disableInnerShadowEffect--) | Schakelt inwendige schaduw uit. |
| [disableOuterShadowEffect()](#disableOuterShadowEffect--) | Schakelt buitenste schaduw uit. |
| [disablePresetShadowEffect()](#disablePresetShadowEffect--) | Schakelt vooraf ingestelde schaduw uit. |
| [disableReflectionEffect()](#disableReflectionEffect--) | Schakelt reflectie uit. |
| [disableSoftEdgeEffect()](#disableSoftEdgeEffect--) | Schakelt zachte rand uit. |
| [getEffective()](#getEffective--) | Haalt effectieve effectopmaakgegevens op met de toegepaste overerving. |
### isNoEffects() {#isNoEffects--}
```
public abstract boolean isNoEffects()
```

Retourneert true als alle effecten zijn uitgeschakeld (zoals net aangemaakt, standaard EffectFormat-object). Alleen-lezen boolean.

**Retourneert:**
boolean
### getBlurEffect() {#getBlurEffect--}
```
public abstract IBlur getBlurEffect()
```

Vervagingseffect. Lezen/schrijven [IBlur](../../com.aspose.slides/iblur).

**Retourneert:**
[IBlur](../../com.aspose.slides/iblur)
### setBlurEffect(IBlur value) {#setBlurEffect-com.aspose.slides.IBlur-}
```
public abstract void setBlurEffect(IBlur value)
```

Vervagingseffect. Lezen/schrijven [IBlur](../../com.aspose.slides/iblur).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IBlur](../../com.aspose.slides/iblur) |  |
### getFillOverlayEffect() {#getFillOverlayEffect--}
```
public abstract IFillOverlay getFillOverlayEffect()
```

Vulling overlay effect. Lezen/schrijven [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**Retourneert:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay)
### setFillOverlayEffect(IFillOverlay value) {#setFillOverlayEffect-com.aspose.slides.IFillOverlay-}
```
public abstract void setFillOverlayEffect(IFillOverlay value)
```

Vulling overlay effect. Lezen/schrijven [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IFillOverlay](../../com.aspose.slides/ifilloverlay) |  |
### getGlowEffect() {#getGlowEffect--}
```
public abstract IGlow getGlowEffect()
```

Gloeieffect. Lezen/schrijven [IGlow](../../com.aspose.slides/iglow).

**Retourneert:**
[IGlow](../../com.aspose.slides/iglow)
### setGlowEffect(IGlow value) {#setGlowEffect-com.aspose.slides.IGlow-}
```
public abstract void setGlowEffect(IGlow value)
```

Gloeieffect. Lezen/schrijven [IGlow](../../com.aspose.slides/iglow).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IGlow](../../com.aspose.slides/iglow) |  |
### getInnerShadowEffect() {#getInnerShadowEffect--}
```
public abstract IInnerShadow getInnerShadowEffect()
```

Inwendige schaduw. Lezen/schrijven [IInnerShadow](../../com.aspose.slides/iinnershadow).

**Retourneert:**
[IInnerShadow](../../com.aspose.slides/iinnershadow)
### setInnerShadowEffect(IInnerShadow value) {#setInnerShadowEffect-com.aspose.slides.IInnerShadow-}
```
public abstract void setInnerShadowEffect(IInnerShadow value)
```

Inwendige schaduw. Lezen/schrijven [IInnerShadow](../../com.aspose.slides/iinnershadow).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IInnerShadow](../../com.aspose.slides/iinnershadow) |  |
### getOuterShadowEffect() {#getOuterShadowEffect--}
```
public abstract IOuterShadow getOuterShadowEffect()
```

Buitenste schaduw. Lezen/schrijven [IOuterShadow](../../com.aspose.slides/ioutershadow).

**Retourneert:**
[IOuterShadow](../../com.aspose.slides/ioutershadow)
### setOuterShadowEffect(IOuterShadow value) {#setOuterShadowEffect-com.aspose.slides.IOuterShadow-}
```
public abstract void setOuterShadowEffect(IOuterShadow value)
```

Buitenste schaduw. Lezen/schrijven [IOuterShadow](../../com.aspose.slides/ioutershadow).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IOuterShadow](../../com.aspose.slides/ioutershadow) |  |
### getPresetShadowEffect() {#getPresetShadowEffect--}
```
public abstract IPresetShadow getPresetShadowEffect()
```

Vooraf ingestelde schaduw. Lezen/schrijven [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**Retourneert:**
[IPresetShadow](../../com.aspose.slides/ipresetshadow)
### setPresetShadowEffect(IPresetShadow value) {#setPresetShadowEffect-com.aspose.slides.IPresetShadow-}
```
public abstract void setPresetShadowEffect(IPresetShadow value)
```

Vooraf ingestelde schaduw. Lezen/schrijven [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IPresetShadow](../../com.aspose.slides/ipresetshadow) |  |
### getReflectionEffect() {#getReflectionEffect--}
```
public abstract IReflection getReflectionEffect()
```

Reflectie. Lezen/schrijven [IReflection](../../com.aspose.slides/ireflection).

**Retourneert:**
[IReflection](../../com.aspose.slides/ireflection)
### setReflectionEffect(IReflection value) {#setReflectionEffect-com.aspose.slides.IReflection-}
```
public abstract void setReflectionEffect(IReflection value)
```

Reflectie. Lezen/schrijven [IReflection](../../com.aspose.slides/ireflection).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IReflection](../../com.aspose.slides/ireflection) |  |
### getSoftEdgeEffect() {#getSoftEdgeEffect--}
```
public abstract ISoftEdge getSoftEdgeEffect()
```

Zachte rand. Lezen/schrijven [ISoftEdge](../../com.aspose.slides/isoftedge).

**Retourneert:**
[ISoftEdge](../../com.aspose.slides/isoftedge)
### setSoftEdgeEffect(ISoftEdge value) {#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-}
```
public abstract void setSoftEdgeEffect(ISoftEdge value)
```

Zachte rand. Lezen/schrijven [ISoftEdge](../../com.aspose.slides/isoftedge).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ISoftEdge](../../com.aspose.slides/isoftedge) |  |
### setBlurEffect(double radius, boolean grow) {#setBlurEffect-double-boolean-}
```
public abstract void setBlurEffect(double radius, boolean grow)
```

Stelt vervagingseffect in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| radius | double | Radius. |
| grow | boolean | Groei. |
### enableFillOverlayEffect() {#enableFillOverlayEffect--}
```
public abstract void enableFillOverlayEffect()
```

Schakelt vulling overlay effect in.
### enableGlowEffect() {#enableGlowEffect--}
```
public abstract void enableGlowEffect()
```

Schakelt gloeieffect in.
### enableInnerShadowEffect() {#enableInnerShadowEffect--}
```
public abstract void enableInnerShadowEffect()
```

Schakelt inwendige schaduw in.
### enableOuterShadowEffect() {#enableOuterShadowEffect--}
```
public abstract void enableOuterShadowEffect()
```

Schakelt buitenste schaduw in.
### enablePresetShadowEffect() {#enablePresetShadowEffect--}
```
public abstract void enablePresetShadowEffect()
```

Schakelt vooraf ingestelde schaduwen in.
### enableReflectionEffect() {#enableReflectionEffect--}
```
public abstract void enableReflectionEffect()
```

Schakelt reflectie in.
### enableSoftEdgeEffect() {#enableSoftEdgeEffect--}
```
public abstract void enableSoftEdgeEffect()
```

Schakelt zachte rand in.
### disableBlurEffect() {#disableBlurEffect--}
```
public abstract void disableBlurEffect()
```

Schakelt vervagingseffect uit.
### disableFillOverlayEffect() {#disableFillOverlayEffect--}
```
public abstract void disableFillOverlayEffect()
```

Schakelt vulling overlay effect uit.
### disableGlowEffect() {#disableGlowEffect--}
```
public abstract void disableGlowEffect()
```

Schakelt gloeieffect uit.
### disableInnerShadowEffect() {#disableInnerShadowEffect--}
```
public abstract void disableInnerShadowEffect()
```

Schakelt inwendige schaduw uit.
### disableOuterShadowEffect() {#disableOuterShadowEffect--}
```
public abstract void disableOuterShadowEffect()
```

Schakelt buitenste schaduw uit.
### disablePresetShadowEffect() {#disablePresetShadowEffect--}
```
public abstract void disablePresetShadowEffect()
```

Schakelt vooraf ingestelde schaduw uit.
### disableReflectionEffect() {#disableReflectionEffect--}
```
public abstract void disableReflectionEffect()
```

Schakelt reflectie uit.
### disableSoftEdgeEffect() {#disableSoftEdgeEffect--}
```
public abstract void disableSoftEdgeEffect()
```

Schakelt zachte rand uit.
### getEffective() {#getEffective--}
```
public abstract IEffectFormatEffectiveData getEffective()
```

Haalt effectieve effectopmaakgegevens op met de toegepaste overerving.

**Retourneert:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata) - A [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).