---
title: ITheme
second_title: Aspose.Slides dla Androida - odniesienie API Java
description: Reprezentuje motyw.
type: docs
url: /pl/com.aspose.slides/itheme/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
```
public interface ITheme extends IPresentationComponent
```

Reprezentuje motyw.
## Metody

| Metoda | Opis |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Zwraca schemat kolorów. |
| [getFontScheme()](#getFontScheme--) | Zwraca schemat czcionek. |
| [getFormatScheme()](#getFormatScheme--) | Zwraca schemat formatu kształtu. |
| [getEffective()](#getEffective--) | Pobiera efektywne dane motywu z zastosowanym dziedziczeniem. |
### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```

Zwraca schemat kolorów. Tylko do odczytu [IColorScheme](../../com.aspose.slides/icolorscheme).

**Zwraca:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```

Zwraca schemat czcionek. Tylko do odczytu [IFontScheme](../../com.aspose.slides/ifontscheme).

**Zwraca:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```

Zwraca schemat formatu kształtu. Tylko do odczytu [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Zwraca:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getEffective() {#getEffective--}
```
public abstract IThemeEffectiveData getEffective()
```

Pobiera efektywne dane motywu z zastosowanym dziedziczeniem.

**Zwraca:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - A [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).