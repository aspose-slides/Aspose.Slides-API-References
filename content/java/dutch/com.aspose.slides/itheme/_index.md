---
title: ITheme
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een thema voor.
type: docs
url: /nl/com.aspose.slides/itheme/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
```
public interface ITheme extends IPresentationComponent
```

Stelt een thema voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Retourneert het kleurschema. |
| [getFontScheme()](#getFontScheme--) | Retourneert het lettertype-schema. |
| [getFormatScheme()](#getFormatScheme--) | Retourneert het vormopmaakschema. |
| [getEffective()](#getEffective--) | Haalt effectieve themagegevens op met de toegepaste overerving. |
### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```


Retourneert het kleurschema. Alleen-lezen [IColorScheme](../../com.aspose.slides/icolorscheme).

**Retour:** 
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```


Retourneert het lettertype-schema. Alleen-lezen [IFontScheme](../../com.aspose.slides/ifontscheme).

**Retour:** 
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```


Retourneert het vormopmaakschema. Alleen-lezen [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Retour:** 
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getEffective() {#getEffective--}
```
public abstract IThemeEffectiveData getEffective()
```


Haalt effectieve themagegevens op met de toegepaste overerving.

**Retour:** 
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - Een [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).