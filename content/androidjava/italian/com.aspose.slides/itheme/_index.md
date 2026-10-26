---
title: ITheme
second_title: Aspose.Slides per Android tramite Riferimento API Java
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
| [getColorScheme()](#getColorScheme--) | Restituisce il color scheme. |
| [getFontScheme()](#getFontScheme--) | Restituisce il font scheme. |
| [getFormatScheme()](#getFormatScheme--) | Restituisce il shape format scheme. |
| [getEffective()](#getEffective--) | Ottiene i dati effective del tema con l'ereditarietà applicata. |
### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```


Restituisce il color scheme. Solo lettura [IColorScheme](../../com.aspose.slides/icolorscheme).

**Restituisce:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```


Restituisce il font scheme. Solo lettura [IFontScheme](../../com.aspose.slides/ifontscheme).

**Restituisce:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```


Restituisce il shape format scheme. Solo lettura [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Restituisce:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getEffective() {#getEffective--}
```
public abstract IThemeEffectiveData getEffective()
```


Ottiene i dati effective del tema con l'ereditarietà applicata.

**Restituisce:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - A [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).