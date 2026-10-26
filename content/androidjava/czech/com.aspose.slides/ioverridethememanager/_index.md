---
title: IOverrideThemeManager
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Poskytuje přístup k různým typům přepsaných motivů.
type: docs
url: /cs/com.aspose.slides/ioverridethememanager/
---
**Všechna implementovaná rozhraní:**
[com.aspose.slides.IThemeManager](../../com.aspose.slides/ithememanager)
```
public interface IOverrideThemeManager extends IThemeManager
```

Poskytuje přístup k různým typům přepsaných motivů.
## Metody

| Metoda | Popis |
| --- | --- |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Určuje, zda OverrideTheme přepisuje zděděný efektivní motiv, nebo ne. |
| [getOverrideTheme()](#getOverrideTheme--) | Vrací objekt přepisující motiv. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | Vrací objekt přepisující motiv. |
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public abstract boolean isOverrideThemeEnabled()
```


Určuje, zda OverrideTheme přepisuje zděděný efektivní motiv, nebo ne. Pro povolení OverrideTheme pro přepisování použijte metody OverrideTheme.Init\*(). Pro zakázání OverrideTheme od přepisování použijte metodu OverrideTheme.Clear(). Pouze pro čtení boolean.

**Vrací:**
boolean
### getOverrideTheme() {#getOverrideTheme--}
```
public abstract IOverrideTheme getOverrideTheme()
```


Vrací objekt přepisující motiv. Čtení/zápis [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Vrací:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public abstract void setOverrideTheme(IOverrideTheme value)
```


Vrací objekt přepisující motiv. Čtení/zápis [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |