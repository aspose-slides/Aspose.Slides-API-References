---
title: IThemeEffectiveData
second_title: Aspose.Slides voor Java API Referentie
description: Onveranderlijk object dat effectieve thema-eigenschappen bevat.
type: docs
url: /nl/com.aspose.slides/ithemeeffectivedata/
---```
public interface IThemeEffectiveData
```

Onveranderlijk object dat effectieve thema-eigenschappen bevat.

--------------------

Deze interface wordt samen met de [ITheme](../../com.aspose.slides/itheme) interface gebruikt om effectieve opmaakwaarden met toegepaste overerving te retourneren.

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getColorScheme(Color styleColor)](#getColorScheme-java.awt.Color-) | Retourneert het kleurenschema. |
| [getFontScheme()](#getFontScheme--) | Retourneert het lettertype-schema. |
| [getFormatScheme()](#getFormatScheme--) | Retourneert het vorm-opmaak-schema. |
### getColorScheme(Color styleColor) {#getColorScheme-java.awt.Color-}
```
public abstract IColorSchemeEffectiveData getColorScheme(Color styleColor)
```


Retourneert het kleurenschema.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| styleColor | java.awt.Color | Color java.awt.Color |

**Retour:**  
[IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata) - kleurenschema [IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontSchemeEffectiveData getFontScheme()
```


Retourneert het lettertype-schema. Alleen-lezen [IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata).

**Retour:**  
[IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatSchemeEffectiveData getFormatScheme()
```


Retourneert het vorm-opmaak-schema. Alleen-lezen [IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata).

**Retour:**  
[IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)