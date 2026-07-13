---
title: MasterThemeManager
second_title: Aspose.Slides pro Android prostřednictvím referenčního Java API
description: Poskytuje přístup k hlavnímu tématu prezentace.
type: docs
url: /cs/com.aspose.slides/masterthememanager/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**Všechny implementované rozhraní:**
[com.aspose.slides.IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
```
public class MasterThemeManager extends BaseThemeManager implements IMasterThemeManager
```

Poskytuje přístup k hlavnímu tématu prezentace.
## Metody

| Metoda | Popis |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | Vrací objekt přepisující téma. |
| [setOverrideTheme(IMasterTheme value)](#setOverrideTheme-com.aspose.slides.IMasterTheme-) | Vrací objekt přepisující téma. |
| [createThemeEffective()](#createThemeEffective--) | Vrací objekt tématu. |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Určuje, zda OverrideTheme přepisuje zděděné účinné téma (Presentation.MasterTheme), nebo ne. |
| [setOverrideThemeEnabled(boolean value)](#setOverrideThemeEnabled-boolean-) | Určuje, zda OverrideTheme přepisuje zděděné účinné téma (Presentation.MasterTheme), nebo ne. |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | Aplikuje dodatečnou barevnou schému na snímek. |
### getOverrideTheme() {#getOverrideTheme--}
```
public final IMasterTheme getOverrideTheme()
```

Vrací objekt přepisující téma. Čtení/Zápis [IMasterTheme](../../com.aspose.slides/imastertheme).

**Vrací:**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### setOverrideTheme(IMasterTheme value) {#setOverrideTheme-com.aspose.slides.IMasterTheme-}
```
public final void setOverrideTheme(IMasterTheme value)
```

Vrací objekt přepisující téma. Čtení/Zápis [IMasterTheme](../../com.aspose.slides/imastertheme).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IMasterTheme](../../com.aspose.slides/imastertheme) |  |
### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Vrací objekt tématu.

**Vrací:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public final boolean isOverrideThemeEnabled()
```

Určuje, zda OverrideTheme přepisuje zděděné účinné téma (Presentation.MasterTheme), nebo ne. Čtení/Zápis boolean.

**Vrací:**
boolean
### setOverrideThemeEnabled(boolean value) {#setOverrideThemeEnabled-boolean-}
```
public final void setOverrideThemeEnabled(boolean value)
```

Určuje, zda OverrideTheme přepisuje zděděné účinné téma (Presentation.MasterTheme), nebo ne. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```

Aplikuje dodatečnou barevnou schému na snímek.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) objekt. |