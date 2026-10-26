---
title: IEffectFormat
second_title: Aspose.Slides dla Androida - odniesienie API Java
description: Reprezentuje właściwości efektów kształtu.
type: docs
url: /pl/com.aspose.slides/ieffectformat/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IEffectParamSource](../../com.aspose.slides/ieffectparamsource)
```
public interface IEffectFormat extends IEffectParamSource
```

Reprezentuje właściwości efektów kształtu.
## Metody

| Metoda | Opis |
| --- | --- |
| [isNoEffects()](#isNoEffects--) | Zwraca true, jeśli wszystkie efekty są wyłączone (tak jak zaraz po utworzeniu, domyślny obiekt EffectFormat). |
| [getBlurEffect()](#getBlurEffect--) | Efekt rozmycia. |
| [setBlurEffect(IBlur value)](#setBlurEffect-com.aspose.slides.IBlur-) | Efekt rozmycia. |
| [getFillOverlayEffect()](#getFillOverlayEffect--) | Efekt nakładki wypełnienia. |
| [setFillOverlayEffect(IFillOverlay value)](#setFillOverlayEffect-com.aspose.slides.IFillOverlay-) | Efekt nakładki wypełnienia. |
| [getGlowEffect()](#getGlowEffect--) | Efekt poświaty. |
| [setGlowEffect(IGlow value)](#setGlowEffect-com.aspose.slides.IGlow-) | Efekt poświaty. |
| [getInnerShadowEffect()](#getInnerShadowEffect--) | Cień wewnętrzny. |
| [setInnerShadowEffect(IInnerShadow value)](#setInnerShadowEffect-com.aspose.slides.IInnerShadow-) | Cień wewnętrzny. |
| [getOuterShadowEffect()](#getOuterShadowEffect--) | Cień zewnętrzny. |
| [setOuterShadowEffect(IOuterShadow value)](#setOuterShadowEffect-com.aspose.slides.IOuterShadow-) | Cień zewnętrzny. |
| [getPresetShadowEffect()](#getPresetShadowEffect--) | Cień wstępnie ustawiony. |
| [setPresetShadowEffect(IPresetShadow value)](#setPresetShadowEffect-com.aspose.slides.IPresetShadow-) | Cień wstępnie ustawiony. |
| [getReflectionEffect()](#getReflectionEffect--) | Odbicie. |
| [setReflectionEffect(IReflection value)](#setReflectionEffect-com.aspose.slides.IReflection-) | Odbicie. |
| [getSoftEdgeEffect()](#getSoftEdgeEffect--) | Miękka krawędź. |
| [setSoftEdgeEffect(ISoftEdge value)](#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-) | Miękka krawędź. |
| [setBlurEffect(double radius, boolean grow)](#setBlurEffect-double-boolean-) | Ustawia efekt rozmycia. |
| [enableFillOverlayEffect()](#enableFillOverlayEffect--) | Włącza efekt nakładki wypełnienia. |
| [enableGlowEffect()](#enableGlowEffect--) | Włącza efekt poświaty. |
| [enableInnerShadowEffect()](#enableInnerShadowEffect--) | Włącza efekt cienia wewnętrznego. |
| [enableOuterShadowEffect()](#enableOuterShadowEffect--) | Włącza efekt cienia zewnętrznego. |
| [enablePresetShadowEffect()](#enablePresetShadowEffect--) | Włącza efekt cieni wstępnie ustawionych. |
| [enableReflectionEffect()](#enableReflectionEffect--) | Włącza efekt odbicia. |
| [enableSoftEdgeEffect()](#enableSoftEdgeEffect--) | Włącza efekt miękkiej krawędzi. |
| [disableBlurEffect()](#disableBlurEffect--) | Wyłącza efekt rozmycia. |
| [disableFillOverlayEffect()](#disableFillOverlayEffect--) | Wyłącza efekt nakładki wypełnienia. |
| [disableGlowEffect()](#disableGlowEffect--) | Wyłącza efekt poświaty. |
| [disableInnerShadowEffect()](#disableInnerShadowEffect--) | Wyłącza efekt cienia wewnętrznego. |
| [disableOuterShadowEffect()](#disableOuterShadowEffect--) | Wyłącza efekt cienia zewnętrznego. |
| [disablePresetShadowEffect()](#disablePresetShadowEffect--) | Wyłącza efekt cienia wstępnie ustawionego. |
| [disableReflectionEffect()](#disableReflectionEffect--) | Wyłącza efekt odbicia. |
| [disableSoftEdgeEffect()](#disableSoftEdgeEffect--) | Wyłącza efekt miękkiej krawędzi. |
| [getEffective()](#getEffective--) | Pobiera skuteczne dane formatowania efektów z uwzględnionym dziedziczeniem. |
### isNoEffects() {#isNoEffects--}
```
public abstract boolean isNoEffects()
```

Zwraca true, jeśli wszystkie efekty są wyłączone (tak jak zaraz po utworzeniu, domyślny obiekt EffectFormat). Tylko do odczytu, boolean.

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

Efekt nakładki wypełnienia. Odczyt/zapis [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**Zwraca:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay)
### setFillOverlayEffect(IFillOverlay value) {#setFillOverlayEffect-com.aspose.slides.IFillOverlay-}
```
public abstract void setFillOverlayEffect(IFillOverlay value)
```

Efekt nakładki wypełnienia. Odczyt/zapis [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IFillOverlay](../../com.aspose.slides/ifilloverlay) |  |
### getGlowEffect() {#getGlowEffect--}
```
public abstract IGlow getGlowEffect()
```

Efekt poświaty. Odczyt/zapis [IGlow](../../com.aspose.slides/iglow).

**Zwraca:**
[IGlow](../../com.aspose.slides/iglow)
### setGlowEffect(IGlow value) {#setGlowEffect-com.aspose.slides.IGlow-}
```
public abstract void setGlowEffect(IGlow value)
```

Efekt poświaty. Odczyt/zapis [IGlow](../../com.aspose.slides/iglow).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IGlow](../../com.aspose.slides/iglow) |  |
### getInnerShadowEffect() {#getInnerShadowEffect--}
```
public abstract IInnerShadow getInnerShadowEffect()
```

Cień wewnętrzny. Odczyt/zapis [IInnerShadow](../../com.aspose.slides/iinnershadow).

**Zwraca:**
[IInnerShadow](../../com.aspose.slides/iinnershadow)
### setInnerShadowEffect(IInnerShadow value) {#setInnerShadowEffect-com.aspose.slides.IInnerShadow-}
```
public abstract void setInnerShadowEffect(IInnerShadow value)
```

Cień wewnętrzny. Odczyt/zapis [IInnerShadow](../../com.aspose.slides/iinnershadow).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IInnerShadow](../../com.aspose.slides/iinnershadow) |  |
### getOuterShadowEffect() {#getOuterShadowEffect--}
```
public abstract IOuterShadow getOuterShadowEffect()
```

Cień zewnętrzny. Odczyt/zapis [IOuterShadow](../../com.aspose.slides/ioutershadow).

**Zwraca:**
[IOuterShadow](../../com.aspose.slides/ioutershadow)
### setOuterShadowEffect(IOuterShadow value) {#setOuterShadowEffect-com.aspose.slides.IOuterShadow-}
```
public abstract void setOuterShadowEffect(IOuterShadow value)
```

Cień zewnętrzny. Odczyt/zapis [IOuterShadow](../../com.aspose.slides/ioutershadow).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IOuterShadow](../../com.aspose.slides/ioutershadow) |  |
### getPresetShadowEffect() {#getPresetShadowEffect--}
```
public abstract IPresetShadow getPresetShadowEffect()
```

Cień wstępnie ustawiony. Odczyt/zapis [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**Zwraca:**
[IPresetShadow](../../com.aspose.slides/ipresetshadow)
### setPresetShadowEffect(IPresetShadow value) {#setPresetShadowEffect-com.aspose.slides.IPresetShadow-}
```
public abstract void setPresetShadowEffect(IPresetShadow value)
```

Cień wstępnie ustawiony. Odczyt/zapis [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IPresetShadow](../../com.aspose.slides/ipresetshadow) |  |
### getReflectionEffect() {#getReflectionEffect--}
```
public abstract IReflection getReflectionEffect()
```

Odbicie. Odczyt/zapis [IReflection](../../com.aspose.slides/ireflection).

**Zwraca:**
[IReflection](../../com.aspose.slides/ireflection)
### setReflectionEffect(IReflection value) {#setReflectionEffect-com.aspose.slides.IReflection-}
```
public abstract void setReflectionEffect(IReflection value)
```

Odbicie. Odczyt/zapis [IReflection](../../com.aspose.slides/ireflection).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IReflection](../../com.aspose.slides/ireflection) |  |
### getSoftEdgeEffect() {#getSoftEdgeEffect--}
```
public abstract ISoftEdge getSoftEdgeEffect()
```

Miękka krawędź. Odczyt/zapis [ISoftEdge](../../com.aspose.slides/isoftedge).

**Zwraca:**
[ISoftEdge](../../com.aspose.slides/isoftedge)
### setSoftEdgeEffect(ISoftEdge value) {#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-}
```
public abstract void setSoftEdgeEffect(ISoftEdge value)
```

Miękka krawędź. Odczyt/zapis [ISoftEdge](../../com.aspose.slides/isoftedge).

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
| radius | double | Promień. |
| grow | boolean | Rozszerzanie. |
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

Włącza efekt cienia wewnętrznego.
### enableOuterShadowEffect() {#enableOuterShadowEffect--}
```
public abstract void enableOuterShadowEffect()
```

Włącza efekt cienia zewnętrznego.
### enablePresetShadowEffect() {#enablePresetShadowEffect--}
```
public abstract void enablePresetShadowEffect()
```

Włącza efekt cieni wstępnie ustawionych.
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

Wyłącza efekt poświaty.
### disableInnerShadowEffect() {#disableInnerShadowEffect--}
```
public abstract void disableInnerShadowEffect()
```

Wyłącza efekt cienia wewnętrznego.
### disableOuterShadowEffect() {#disableOuterShadowEffect--}
```
public abstract void disableOuterShadowEffect()
```

Wyłącza efekt cienia zewnętrznego.
### disablePresetShadowEffect() {#disablePresetShadowEffect--}
```
public abstract void disablePresetShadowEffect()
```

Wyłącza efekt cienia wstępnie ustawionego.
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

Pobiera skuteczne dane formatowania efektów z uwzględnionym dziedziczeniem.

**Zwraca:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata) - A [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).