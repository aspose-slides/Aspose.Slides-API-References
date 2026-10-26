---
title: MasterThemeManager
second_title: Aspose.Slides dla Androida przy użyciu dokumentacji API Java
description: Zapewnia dostęp do motywu głównego prezentacji.
type: docs
url: /pl/com.aspose.slides/masterthememanager/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**All Implemented Interfaces:**
[com.aspose.slides.IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
```
public class MasterThemeManager extends BaseThemeManager implements IMasterThemeManager
```

Provides access to presentation master theme.
## Metody

| Metoda | Opis |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | Zwraca obiekt nadpisującego motywu. |
| [setOverrideTheme(IMasterTheme value)](#setOverrideTheme-com.aspose.slides.IMasterTheme-) | Zwraca obiekt nadpisującego motywu. |
| [createThemeEffective()](#createThemeEffective--) | Zwraca obiekt motywu. |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Określa, czy OverrideTheme nadpisuje odziedziczony efektywny motyw (Presentation.MasterTheme), czy nie. |
| [setOverrideThemeEnabled(boolean value)](#setOverrideThemeEnabled-boolean-) | Określa, czy OverrideTheme nadpisuje odziedziczony efektywny motyw (Presentation.MasterTheme), czy nie. |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | Stosuje dodatkowy schemat kolorów do slajdu. |
### getOverrideTheme() {#getOverrideTheme--}
```
public final IMasterTheme getOverrideTheme()
```

Zwraca obiekt nadpisującego motywu. Odczyt/zapis [IMasterTheme](../../com.aspose.slides/imastertheme).

**Zwraca:**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### setOverrideTheme(IMasterTheme value) {#setOverrideTheme-com.aspose.slides.IMasterTheme-}
```
public final void setOverrideTheme(IMasterTheme value)
```

Zwraca obiekt nadpisującego motywu. Odczyt/zapis [IMasterTheme](../../com.aspose.slides/imastertheme).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IMasterTheme](../../com.aspose.slides/imastertheme) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Zwraca obiekt motywu.

**Zwraca:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public final boolean isOverrideThemeEnabled()
```

Określa, czy OverrideTheme nadpisuje odziedziczony efektywny motyw (Presentation.MasterTheme), czy nie. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setOverrideThemeEnabled(boolean value) {#setOverrideThemeEnabled-boolean-}
```
public final void setOverrideThemeEnabled(boolean value)
```

Określa, czy OverrideTheme nadpisuje odziedziczony efektywny motyw (Presentation.MasterTheme), czy nie. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```

Stosuje dodatkowy schemat kolorów do slajdu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) object. |