---
title: IOverrideTheme
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta un tema di sovrascrittura.
type: docs
url: /it/com.aspose.slides/ioverridetheme/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IOverrideTheme extends ITheme
```

Rappresenta un tema di sovrascrittura.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [isEmpty()](#isEmpty--) | Valore true indica che ColorScheme, FontScheme, FormatScheme è null e qualsiasi sovrascrittura con questo oggetto tema è disabilitata. |
| [initColorScheme()](#initColorScheme--) | Inizializza ColorScheme con un nuovo oggetto per sovrascrivere ColorScheme di InheritedTheme. |
| [initColorSchemeFrom(IColorScheme colorScheme)](#initColorSchemeFrom-com.aspose.slides.IColorScheme-) | Inizializza ColorScheme con un nuovo oggetto per sovrascrivere ColorScheme di InheritedTheme. |
| [initColorSchemeFromInherited()](#initColorSchemeFromInherited--) | Inizializza ColorScheme con un nuovo oggetto per sovrascrivere ColorScheme di InheritedTheme. |
| [initFontScheme()](#initFontScheme--) | Inizializza FontScheme con un nuovo oggetto per sovrascrivere FontScheme di InheritedTheme. |
| [initFontSchemeFrom(IFontScheme fontScheme)](#initFontSchemeFrom-com.aspose.slides.IFontScheme-) | Inizializza FontScheme con un nuovo oggetto per sovrascrivere FontScheme di InheritedTheme. |
| [initFontSchemeFromInherited()](#initFontSchemeFromInherited--) | Inizializza FontScheme con un nuovo oggetto per sovrascrivere FontScheme di InheritedTheme. |
| [initFormatScheme()](#initFormatScheme--) | Inizializza FormatScheme con un nuovo oggetto per sovrascrivere FormatScheme di InheritedTheme. |
| [initFormatSchemeFrom(IFormatScheme formatScheme)](#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-) | Inizializza FormatScheme con un nuovo oggetto per sovrascrivere FormatScheme di InheritedTheme. |
| [initFormatSchemeFromInherited()](#initFormatSchemeFromInherited--) | Inizializza FormatScheme con un nuovo oggetto per sovrascrivere FormatScheme di InheritedTheme. |
| [clear()](#clear--) | Imposta ColorScheme, FontScheme, FormatScheme su null per disabilitare qualsiasi sovrascrittura con questo oggetto tema. |
### isEmpty() {#isEmpty--}
```
public abstract boolean isEmpty()
```

Valore true indica che ColorScheme, FontScheme, FormatScheme è null e qualsiasi sovrascrittura con questo oggetto tema è disabilitata. Boolean di sola lettura.

**Restituisce:**  
boolean
### initColorScheme() {#initColorScheme--}
```
public abstract void initColorScheme()
```

Inizializza ColorScheme con un nuovo oggetto per sovrascrivere ColorScheme di InheritedTheme.

### initColorSchemeFrom(IColorScheme colorScheme) {#initColorSchemeFrom-com.aspose.slides.IColorScheme-}
```
public abstract void initColorSchemeFrom(IColorScheme colorScheme)
```

Inizializza ColorScheme con un nuovo oggetto per sovrascrivere ColorScheme di InheritedTheme.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| colorScheme | [IColorScheme](../../com.aspose.slides/icolorscheme) | Dati da cui inizializzare. |

### initColorSchemeFromInherited() {#initColorSchemeFromInherited--}
```
public abstract void initColorSchemeFromInherited()
```

Inizializza ColorScheme con un nuovo oggetto per sovrascrivere ColorScheme di InheritedTheme. E inizializza i dati di questo nuovo oggetto con i dati del ColorScheme di InheritedTheme.

### initFontScheme() {#initFontScheme--}
```
public abstract void initFontScheme()
```

Inizializza FontScheme con un nuovo oggetto per sovrascrivere FontScheme di InheritedTheme.

### initFontSchemeFrom(IFontScheme fontScheme) {#initFontSchemeFrom-com.aspose.slides.IFontScheme-}
```
public abstract void initFontSchemeFrom(IFontScheme fontScheme)
```

Inizializza FontScheme con un nuovo oggetto per sovrascrivere FontScheme di InheritedTheme.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontScheme | [IFontScheme](../../com.aspose.slides/ifontscheme) | Dati da cui inizializzare. |

### initFontSchemeFromInherited() {#initFontSchemeFromInherited--}
```
public abstract void initFontSchemeFromInherited()
```

Inizializza FontScheme con un nuovo oggetto per sovrascrivere FontScheme di InheritedTheme. E inizializza i dati di questo nuovo oggetto con i dati del FontScheme di InheritedTheme.

### initFormatScheme() {#initFormatScheme--}
```
public abstract void initFormatScheme()
```

Inizializza FormatScheme con un nuovo oggetto per sovrascrivere FormatScheme di InheritedTheme.

### initFormatSchemeFrom(IFormatScheme formatScheme) {#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-}
```
public abstract void initFormatSchemeFrom(IFormatScheme formatScheme)
```

Inizializza FormatScheme con un nuovo oggetto per sovrascrivere FormatScheme di InheritedTheme.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| formatScheme | [IFormatScheme](../../com.aspose.slides/iformatscheme) | Dati da cui inizializzare. |

### initFormatSchemeFromInherited() {#initFormatSchemeFromInherited--}
```
public abstract void initFormatSchemeFromInherited()
```

Inizializza FormatScheme con un nuovo oggetto per sovrascrivere FormatScheme di InheritedTheme. E inizializza i dati di questo nuovo oggetto con i dati del FormatScheme di InheritedTheme.

### clear() {#clear--}
```
public abstract void clear()
```

Imposta ColorScheme, FontScheme, FormatScheme su null per disabilitare qualsiasi sovrascrittura con questo oggetto tema.