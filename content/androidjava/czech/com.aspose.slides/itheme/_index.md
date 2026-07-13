---
title: ITheme
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Reprezentuje motiv.
type: docs
url: /cs/com.aspose.slides/itheme/
---
**Všechna implementovaná rozhraní:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
```
public interface ITheme extends IPresentationComponent
```

Reprezentuje motiv.
## Metody

| Metoda | Popis |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Vrací schéma barev. |
| [getFontScheme()](#getFontScheme--) | Vrací schéma fontů. |
| [getFormatScheme()](#getFormatScheme--) | Vrací schéma formátu tvarů. |
| [getEffective()](#getEffective--) | Získá efektivní data motivu s aplikovaným děděním. |
### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```


Vrací schéma barev. Pouze pro čtení [IColorScheme](../../com.aspose.slides/icolorscheme).

**Vrací:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```


Vrací schéma fontů. Pouze pro čtení [IFontScheme](../../com.aspose.slides/ifontscheme).

**Vrací:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```


Vrací schéma formátu tvarů. Pouze pro čtení [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Vrací:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getEffective() {#getEffective--}
```
public abstract IThemeEffectiveData getEffective()
```


Získá efektivní data motivu s aplikovaným děděním.

**Vrací:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - Typ [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).