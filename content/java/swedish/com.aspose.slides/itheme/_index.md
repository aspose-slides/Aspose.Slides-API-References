---
title: ITheme
second_title: Aspose.Slides för Java API-referens
description: Representerar ett tema.
type: docs
url: /sv/com.aspose.slides/itheme/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
```
public interface ITheme extends IPresentationComponent
```

Representerar ett tema.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Returnerar färgschemat. |
| [getFontScheme()](#getFontScheme--) | Returnerar teckensnittsschemat. |
| [getFormatScheme()](#getFormatScheme--) | Returnerar formatmall för former. |
| [getEffective()](#getEffective--) | Hämtar effektiv temadata med arv tillämpat. |
### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```


Returnerar färgschemat. Skrivskyddad [IColorScheme](../../com.aspose.slides/icolorscheme).

**Returnerar:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```


Returnerar teckensnittsschemat. Skrivskyddad [IFontScheme](../../com.aspose.slides/ifontscheme).

**Returnerar:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```


Returnerar formatmall för former. Skrivskyddad [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Returnerar:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getEffective() {#getEffective--}
```
public abstract IThemeEffectiveData getEffective()
```


Hämtar effektiv temadata med arv tillämpat.

**Returnerar:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - En [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).