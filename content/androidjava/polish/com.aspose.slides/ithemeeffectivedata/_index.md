---
title: IThemeEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Niezmienny obiekt zawierający efektywne właściwości motywu.
type: docs
url: /pl/com.aspose.slides/ithemeeffectivedata/
---```
public interface IThemeEffectiveData
```

Niezmienny obiekt zawierający efektywne właściwości motywu.

--------------------

Ten interfejs jest używany razem z interfejsem [ITheme](../../com.aspose.slides/itheme), aby zwrócić efektywne wartości formatowania z zastosowanym dziedziczeniem.
## Methods

| Metoda | Opis |
| --- | --- |
| [getColorScheme(Integer styleColor)](#getColorScheme-java.lang.Integer-) | Zwraca schemat kolorów. |
| [getFontScheme()](#getFontScheme--) | Zwraca schemat czcionek. |
| [getFormatScheme()](#getFormatScheme--) | Zwraca schemat formatowania kształtów. |
### getColorScheme(Integer styleColor) {#getColorScheme-java.lang.Integer-}
```
public abstract IColorSchemeEffectiveData getColorScheme(Integer styleColor)
```

Zwraca schemat kolorów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| styleColor | java.lang.Integer | Kolor java.lang.Integer |

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