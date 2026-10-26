---
title: IOverrideThemeManager
second_title: Aspose.Slides Java API referencia
description: Hozzáférést biztosít a különböző felülbíráló témák típusaihoz.
type: docs
url: /hu/com.aspose.slides/ioverridethememanager/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IThemeManager](../../com.aspose.slides/ithememanager)
```
public interface IOverrideThemeManager extends IThemeManager
```

Hozzáférést biztosít a különböző felülbíráló témák típusaihoz.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Meghatározza, hogy az OverrideTheme felülbírálja-e a öröklött hatékony témát vagy sem. |
| [getOverrideTheme()](#getOverrideTheme--) | Visszaadja a felülbíráló téma objektumát. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | Visszaadja a felülbíráló téma objektumát. |
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public abstract boolean isOverrideThemeEnabled()
```


Meghatározza, hogy az OverrideTheme felülbírálja-e a öröklött hatékony témát vagy sem. Az OverrideTheme engedélyezéséhez a felülbíráláshoz használja az OverrideTheme.Init*() metódusokat. Az OverrideTheme letiltásához a felülbírálásból használja az OverrideTheme.Clear() metódust. Csak olvasható boolean.

**Visszatérési érték:**
boolean
### getOverrideTheme() {#getOverrideTheme--}
```
public abstract IOverrideTheme getOverrideTheme()
```


Visszaadja a felülbíráló téma objektumát. Olvasás/írás [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Visszatérési érték:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public abstract void setOverrideTheme(IOverrideTheme value)
```


Visszaadja a felülbíráló téma objektumát. Olvasás/írás [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |