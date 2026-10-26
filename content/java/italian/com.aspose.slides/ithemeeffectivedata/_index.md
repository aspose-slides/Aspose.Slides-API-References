---
title: IThemeEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective theme properties.
type: docs
url: /it/com.aspose.slides/ithemeeffectivedata/
---```
public interface IThemeEffectiveData
```

Oggetto immutabile che contiene le proprietà del tema effettive.

--------------------

Questa interfaccia è usata insieme all'interfaccia [ITheme](../../com.aspose.slides/itheme) per restituire i valori di formattazione effettivi con l'ereditarietà applicata.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getColorScheme(Color styleColor)](#getColorScheme-java.awt.Color-) | Restituisce lo schema di colore. |
| [getFontScheme()](#getFontScheme--) | Restituisce lo schema di carattere. |
| [getFormatScheme()](#getFormatScheme--) | Restituisce lo schema di formato forma. |
### getColorScheme(Color styleColor) {#getColorScheme-java.awt.Color-}
```
public abstract IColorSchemeEffectiveData getColorScheme(Color styleColor)
```

Restituisce lo schema di colore.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| styleColor | java.awt.Color | Color java.awt.Color |

**Restituisce:**
[IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata) - Schema di colore [IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontSchemeEffectiveData getFontScheme()
```

Restituisce lo schema di carattere. Solo lettura [IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata).

**Restituisce:**
[IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatSchemeEffectiveData getFormatScheme()
```

Restituisce lo schema di formato forma. Solo lettura [IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata).

**Restituisce:**
[IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)