---
title: MasterTheme
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta un tema master.
type: docs
url: /it/com.aspose.slides/mastertheme/
---
**Ereditarietà:**
java.lang.Object, [com.aspose.slides.Theme](../../com.aspose.slides/theme)

**Tutte le interfacce implementate:**
[com.aspose.slides.IMasterTheme](../../com.aspose.slides/imastertheme)
```
public final class MasterTheme extends Theme implements IMasterTheme
```

Rappresenta un tema master.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Restituisce lo schema dei colori. |
| [getFontScheme()](#getFontScheme--) | Restituisce lo schema dei caratteri. |
| [getFormatScheme()](#getFormatScheme--) | Restituisce lo schema di formattazione delle forme. |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | Restituisce la collezione di schemi di colore aggiuntivi. |
| [getName()](#getName--) | Restituisce il nome di un tema. |
| [setName(String value)](#setName-java.lang.String-) | Restituisce il nome di un tema. |
| [getVersion()](#getVersion--) |  |
### getColorScheme() {#getColorScheme--}
```
public IColorScheme getColorScheme()
```


Restituisce lo schema dei colori. Solo lettura [IColorScheme](../../com.aspose.slides/icolorscheme).

**Restituisce:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public IFontScheme getFontScheme()
```


Restituisce lo schema dei caratteri. Solo lettura [IFontScheme](../../com.aspose.slides/ifontscheme).

**Restituisce:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public IFormatScheme getFormatScheme()
```


Restituisce lo schema di formattazione delle forme. Solo lettura [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Restituisce:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public final IExtraColorSchemeCollection getExtraColorSchemes()
```


Restituisce la collezione di schemi di colore aggiuntivi. Questi schemi non influenzano l'aspetto della presentazione, possono essere selezionati come schema di colore principale per una diapositiva. Solo lettura [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**Restituisce:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public final String getName()
```


Restituisce il nome di un tema. Lettura/scrittura String.

**Restituisce:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Restituisce il nome di un tema. Lettura/scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getVersion() {#getVersion--}
```
public long getVersion()
```


Versione. Solo lettura long.

**Restituisce:**
long