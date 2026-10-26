---
title: IFontSchemeEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Oföränderligt objekt som innehåller effektiva fontschemats egenskaper.
type: docs
url: /sv/com.aspose.slides/ifontschemeeffectivedata/
---```
public interface IFontSchemeEffectiveData
```

Oföränderligt objekt som innehåller effektiva fontschemats egenskaper.

--------------------

Detta gränssnitt används som en del av [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getMinor()](#getMinor--) | Returns the fonts collection for a "body" part of the slide. |
| [getMajor()](#getMajor--) | Returns the fonts collection for a "heading" part of the slide. |
| [getName()](#getName--) | Returns the font scheme name. |
### getMinor() {#getMinor--}
```
public abstract IFontsEffectiveData getMinor()
```


Returnerar fontsamlingen för en "body"-del av sliden. Skrivskyddad [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**Returnerar:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getMajor() {#getMajor--}
```
public abstract IFontsEffectiveData getMajor()
```


Returnerar fontsamlingen för en "heading"-del av sliden. Skrivskyddad [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**Returnerar:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getName() {#getName--}
```
public abstract String getName()
```


Returnerar fontschemats namn. Skrivskyddad String.

**Returnerar:**
java.lang.String