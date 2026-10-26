---
title: IThemeEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Neměnný objekt, který obsahuje efektivní vlastnosti motivu.
type: docs
url: /cs/com.aspose.slides/ithemeeffectivedata/
---```
public interface IThemeEffectiveData
```

Immutable object which contains effective theme properties.

--------------------

This interface is used together with the [ITheme](../../com.aspose.slides/itheme) interface to return effective formatting values with inheritance applied.
## Metody

| Metoda | Popis |
| --- | --- |
| [getColorScheme(Color styleColor)](#getColorScheme-java.awt.Color-) | Vrací barevné schéma. |
| [getFontScheme()](#getFontScheme--) | Vrací schéma písem. |
| [getFormatScheme()](#getFormatScheme--) | Vrací schéma formátu tvaru. |
### getColorScheme(Color styleColor) {#getColorScheme-java.awt.Color-}
```
public abstract IColorSchemeEffectiveData getColorScheme(Color styleColor)
```

Vrací barevné schéma.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| styleColor | java.awt.Color | Color java.awt.Color |

**Vrací:**
[IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata) - barevné schéma [IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata)
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