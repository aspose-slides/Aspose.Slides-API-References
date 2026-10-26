---
title: IThemeEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Oföränderligt objekt som innehåller effektiva temaegenskaper.
type: docs
url: /sv/com.aspose.slides/ithemeeffectivedata/
---```
public interface IThemeEffectiveData
```

Oföränderligt objekt som innehåller effektiva temaegenskaper.

--------------------

Detta gränssnitt används tillsammans med [ITheme](../../com.aspose.slides/itheme)-gränssnittet för att returnera effektiva formatteringsvärden med arv tillämpat.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getColorScheme(Color styleColor)](#getColorScheme-java.awt.Color-) | Returnerar färgschemat. |
| [getFontScheme()](#getFontScheme--) | Returnerar typsnittsschemat. |
| [getFormatScheme()](#getFormatScheme--) | Returnerar formformatmallen. |
### getColorScheme(Color styleColor) {#getColorScheme-java.awt.Color-}
```
public abstract IColorSchemeEffectiveData getColorScheme(Color styleColor)
```


Returnerar färgschemat.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| styleColor | java.awt.Color | Color java.awt.Color |

**Returnerar:**
[IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata) - Color scheme [IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontSchemeEffectiveData getFontScheme()
```


Returnerar typsnittsschemat. Skrivskyddad [IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata).

**Returnerar:**
[IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatSchemeEffectiveData getFormatScheme()
```


Returnerar formformatmallen. Skrivskyddad [IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata).

**Returnerar:**
[IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)