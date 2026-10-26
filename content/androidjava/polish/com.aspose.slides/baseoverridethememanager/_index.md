---
title: BaseOverrideThemeManager
second_title: Aspose.Slides dla Androida poprzez odniesienie do API Java
description: Klasa bazowa dla klas, które zapewniają dostęp do różnych typów nadpisanych motywów.
type: docs
url: /pl/com.aspose.slides/baseoverridethememanager/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**All Implemented Interfaces:**
[com.aspose.slides.IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
```
public abstract class BaseOverrideThemeManager extends BaseThemeManager implements IOverrideThemeManager
```

Klasa bazowa dla klas, które zapewniają dostęp do różnych typów nadpisanych motywów.
## Metody

| Metoda | Opis |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | Zwraca obiekt nadpisującego motywu. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | Zwraca obiekt nadpisującego motywu. |
| [createThemeEffective()](#createThemeEffective--) | Zwraca obiekt motywu. |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Określa, czy OverrideTheme nadpisuje odziedziczony efektywny motyw, czy nie. |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | Stosuje dodatkowy schemat kolorów do slajdu. |
### getOverrideTheme() {#getOverrideTheme--}
```
public final IOverrideTheme getOverrideTheme()
```


Zwraca obiekt nadpisującego motywu. Odczyt/zapis [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Zwraca:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public final void setOverrideTheme(IOverrideTheme value)
```


Zwraca obiekt nadpisującego motywu. Odczyt/zapis [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |

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


Określa, czy OverrideTheme nadpisuje odziedziczony efektywny motyw, czy nie. Aby włączyć OverrideTheme do nadpisywania, użyj metod OverrideTheme.Init\*(). Aby wyłączyć OverrideTheme z nadpisywania, użyj metody OverrideTheme.Clear(). Tylko do odczytu boolean.

**Zwraca:**
boolean
### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```


Stosuje dodatkowy schemat kolorów do slajdu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | Obiekt [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme). |