---
title: IThemeEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Neměnný objekt, který obsahuje efektivní vlastnosti motivu.
type: docs
url: /cs/com.aspose.slides/ithemeeffectivedata/
---```
public interface IThemeEffectiveData
```

Neměnný objekt, který obsahuje efektivní vlastnosti motivu.

--------------------

Toto rozhraní se používá spolu s rozhraním [ITheme](../../com.aspose.slides/itheme) k vrácení efektivních hodnot formátování s aplikovaným děděním.
## Metody

| Metoda | Popis |
| --- | --- |
| [getColorScheme(Integer styleColor)](#getColorScheme-java.lang.Integer-) | Returns the color scheme. |
| [getFontScheme()](#getFontScheme--) | Returns the font scheme. |
| [getFormatScheme()](#getFormatScheme--) | Returns the shape format scheme. |
### getColorScheme(Integer styleColor) {#getColorScheme-java.lang.Integer-}
```
public abstract IColorSchemeEffectiveData getColorScheme(Integer styleColor)
```


Vrací schéma barev.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| styleColor | java.lang.Integer | Barva java.lang.Integer |

**Vrací:**
[IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata) - Schéma barev [IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontSchemeEffectiveData getFontScheme()
```


Vrací schéma písma. Pouze pro čtení [IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata).

**Vrací:**
[IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatSchemeEffectiveData getFormatScheme()
```


Vrací schéma formátu tvaru. Pouze pro čtení [IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata).

**Vrací:**
[IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)