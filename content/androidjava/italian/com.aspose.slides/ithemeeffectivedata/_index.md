---
title: IThemeEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Oggetto immutabile che contiene le proprietà del tema effettivo.
type: docs
url: /it/com.aspose.slides/ithemeeffectivedata/
---```
public interface IThemeEffectiveData
```

Oggetto immutabile che contiene le proprietà del tema effettivo.

--------------------

Questa interfaccia è usata insieme all'interfaccia [ITheme](../../com.aspose.slides/itheme) per restituire i valori di formattazione effettiva con l'ereditarietà applicata.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getColorScheme(Integer styleColor)](#getColorScheme-java.lang.Integer-) | Restituisce lo schema dei colori. |
| [getFontScheme()](#getFontScheme--) | Restituisce lo schema dei caratteri. |
| [getFormatScheme()](#getFormatScheme--) | Restituisce lo schema del formato della forma. |
### getColorScheme(Integer styleColor) {#getColorScheme-java.lang.Integer-}
```
public abstract IColorSchemeEffectiveData getColorScheme(Integer styleColor)
```


Restituisce lo schema dei colori.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| styleColor | java.lang.Integer | Color java.lang.Integer |

**Restituisce:**
[IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata) - Color scheme [IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontSchemeEffectiveData getFontScheme()
```


Restituisce lo schema dei caratteri. Solo lettura [IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata).

**Restituisce:**
[IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatSchemeEffectiveData getFormatScheme()
```


Restituisce lo schema del formato della forma. Solo lettura [IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata).

**Restituisce:**
[IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)