---
title: IOverrideThemeManager
second_title: Aspose.Slides dla Androida – odwołanie do API Java
description: Umożliwia dostęp do różnych typów nadpisanych motywów.
type: docs
url: /pl/com.aspose.slides/ioverridethememanager/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IThemeManager](../../com.aspose.slides/ithememanager)
```
public interface IOverrideThemeManager extends IThemeManager
```

Umożliwia dostęp do różnych typów nadpisanych motywów.
## Metody

| Metoda | Opis |
| --- | --- |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Określa, czy OverrideTheme nadpisuje dziedziczony efektywny motyw, czy nie. |
| [getOverrideTheme()](#getOverrideTheme--) | Zwraca obiekt nadpisującego motywu. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | Zwraca obiekt nadpisującego motywu. |
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public abstract boolean isOverrideThemeEnabled()
```


Określa, czy OverrideTheme nadpisuje dziedziczony efektywny motyw, czy nie. Aby włączyć OverrideTheme do nadpisywania, użyj metod OverrideTheme.Init\*(). Aby wyłączyć OverrideTheme z nadpisywania, użyj metody OverrideTheme.Clear(). Boolean tylko do odczytu.

**Zwraca:**
boolean
### getOverrideTheme() {#getOverrideTheme--}
```
public abstract IOverrideTheme getOverrideTheme()
```


Zwraca obiekt nadpisującego motywu. Odczyt/zapis [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Zwraca:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public abstract void setOverrideTheme(IOverrideTheme value)
```


Zwraca obiekt nadpisującego motywu. Odczyt/zapis [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |