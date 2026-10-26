---
title: ITheme
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta un tema.
type: docs
url: /it/com.aspose.slides/itheme/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
```
public interface ITheme extends IPresentationComponent
```

Rappresenta un tema.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Restituisce lo schema di colore. |
| [getFontScheme()](#getFontScheme--) | Restituisce lo schema di caratteri. |
| [getFormatScheme()](#getFormatScheme--) | Restituisce lo schema di formato della forma. |
| [getEffective()](#getEffective--) | Ottiene i dati del tema effettivo con l'ereditarietà applicata. |
### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```


Restituisce lo schema di colore. Solo lettura [IColorScheme](../../com.aspose.slides/icolorscheme).

**Restituisce:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```


Restituisce lo schema di caratteri. Solo lettura [IFontScheme](../../com.aspose.slides/ifontscheme).

**Restituisce:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```


Restituisce lo schema di formato della forma. Solo lettura [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Restituisce:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getEffective() {#getEffective--}
```
public abstract IThemeEffectiveData getEffective()
```


Ottiene i dati del tema effettivo con l'ereditarietà applicata.

**Restituisce:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - A [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).