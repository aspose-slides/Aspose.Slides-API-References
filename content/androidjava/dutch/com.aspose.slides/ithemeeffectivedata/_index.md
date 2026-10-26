---
title: IThemeEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Onveranderlijk object dat effectieve themaeigenschappen bevat.
type: docs
url: /nl/com.aspose.slides/ithemeeffectivedata/
---```
public interface IThemeEffectiveData
```

Onveranderlijk object dat effectieve themaeigenschappen bevat.

--------------------

Dit interface wordt samen met de [ITheme](../../com.aspose.slides/itheme) interface gebruikt om effectieve opmaakwaarden met geërfde instellingen terug te geven.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getColorScheme(Integer styleColor)](#getColorScheme-java.lang.Integer-) | Retourneert het kleurenschema. |
| [getFontScheme()](#getFontScheme--) | Retourneert het lettertype-schema. |
| [getFormatScheme()](#getFormatScheme--) | Retourneert het vormopmaakschema. |
### getColorScheme(Integer styleColor) {#getColorScheme-java.lang.Integer-}
```
public abstract IColorSchemeEffectiveData getColorScheme(Integer styleColor)
```


Retourneert het kleurenschema.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| styleColor | java.lang.Integer | Kleur java.lang.Integer |

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


Retourneert het vormopmaakschema. Alleen-lezen [IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata).

**Retour:**
[IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)