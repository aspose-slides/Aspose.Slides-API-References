---
title: IThemeEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective theme properties.
type: docs
url: /pl/com.aspose.slides/ithemeeffectivedata/
---```
public interface IThemeEffectiveData
```

Niezmienny obiekt, który zawiera efektywne właściwości motywu.

--------------------

Ten interfejs jest używany razem z interfejsem [ITheme](../../com.aspose.slides/itheme), aby zwrócić efektywne wartości formatowania z zastosowanym dziedziczeniem.
## Metody

| Method | Description |
| --- | --- |
| [getColorScheme(Color styleColor)](#getColorScheme-java.awt.Color-) | Returns the color scheme. |
| [getFontScheme()](#getFontScheme--) | Returns the font scheme. |
| [getFormatScheme()](#getFormatScheme--) | Returns the shape format scheme. |
### getColorScheme(Color styleColor) {#getColorScheme-java.awt.Color-}
```
public abstract IColorSchemeEffectiveData getColorScheme(Color styleColor)
```

Zwraca schemat kolorów.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| styleColor | java.awt.Color | Color java.awt.Color |

**Zwraca:**
[IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata) - Schemat kolorów [IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontSchemeEffectiveData getFontScheme()
```

Zwraca schemat czcionek. Tylko do odczytu [IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata).

**Zwraca:**
[IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatSchemeEffectiveData getFormatScheme()
```

Zwraca schemat formatowania kształtów. Tylko do odczytu [IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata).

**Zwraca:**
[IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)