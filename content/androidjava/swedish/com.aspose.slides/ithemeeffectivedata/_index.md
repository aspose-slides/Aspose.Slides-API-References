---
title: IThemeEffectiveData
second_title: Aspose.Slides för Android via Java API Reference
description: Oföränderligt objekt som innehåller effektiva temaegenskaper.
type: docs
url: /sv/com.aspose.slides/ithemeeffectivedata/
---```
public interface IThemeEffectiveData
```

Oföränderligt objekt som innehåller effektiva temaegenskaper.

--------------------

Det här gränssnittet används tillsammans med [ITheme](../../com.aspose.slides/itheme)-gränssnittet för att returnera effektiva formateringsvärden med arv tillämpat.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getColorScheme(Integer styleColor)](#getColorScheme-java.lang.Integer-) | Returnerar färgschemat. |
| [getFontScheme()](#getFontScheme--) | Returnerar typsnittsschemat. |
| [getFormatScheme()](#getFormatScheme--) | Returnerar formateringsschemat för former. |
### getColorScheme(Integer styleColor) {#getColorScheme-java.lang.Integer-}
```
public abstract IColorSchemeEffectiveData getColorScheme(Integer styleColor)
```


Returnerar färgschemat.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| styleColor | java.lang.Integer | Color java.lang.Integer |

**Returnerar:**
[IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata) - Färgschema [IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata)
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


Returnerar formateringsschemat för former. Skrivskyddad [IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata).

**Returnerar:**
[IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)