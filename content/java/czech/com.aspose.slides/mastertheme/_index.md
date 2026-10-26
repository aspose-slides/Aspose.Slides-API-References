---
title: MasterTheme
second_title: Aspose.Slides pro Java API Reference
description: Reprezentuje hlavní motiv.
type: docs
url: /cs/com.aspose.slides/mastertheme/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.Theme](../../com.aspose.slides/theme)

**Všechny implementované rozhraní:**
[com.aspose.slides.IMasterTheme](../../com.aspose.slides/imastertheme)
```
public final class MasterTheme extends Theme implements IMasterTheme
```

Reprezentuje hlavní motiv.
## Metody

| Metoda | Popis |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Vrací barevné schéma. |
| [getFontScheme()](#getFontScheme--) | Vrací schéma písma. |
| [getFormatScheme()](#getFormatScheme--) | Vrací schéma formátu tvarů. |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | Vrací kolekci dalších barevných schémat. |
| [getName()](#getName--) | Vrací název motivu. |
| [setName(String value)](#setName-java.lang.String-) | Vrací název motivu. |
| [getVersion()](#getVersion--) |  |
### getColorScheme() {#getColorScheme--}
```
public IColorScheme getColorScheme()
```


Vrací barevné schéma. Pouze pro čtení [IColorScheme](../../com.aspose.slides/icolorscheme).

**Vrací:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public IFontScheme getFontScheme()
```


Vrací schéma písma. Pouze pro čtení [IFontScheme](../../com.aspose.slides/ifontscheme).

**Vrací:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public IFormatScheme getFormatScheme()
```


Vrací schéma formátu tvarů. Pouze pro čtení [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Vrací:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public final IExtraColorSchemeCollection getExtraColorSchemes()
```


Vrací kolekci dalších barevných schémat. Tato schémata neovlivňují vzhled prezentace, mohou být vybrána jako hlavní barevné schéma pro snímek. Pouze pro čtení [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**Vrací:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public final String getName()
```


Vrací název motivu. Čtení/Zápis String.

**Vrací:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Vrací název motivu. Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Verze. Pouze pro čtení long.

**Vrací:**
long