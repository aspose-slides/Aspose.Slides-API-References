---
title: IOverrideThemeManager
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: Hozzáférést biztosít a felülírt témák különböző típusaihoz.
type: docs
url: /hu/com.aspose.slides/ioverridethememanager/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IThemeManager](../../com.aspose.slides/ithememanager)
```
public interface IOverrideThemeManager extends IThemeManager
```

Hozzáférést biztosít a felülírt témák különböző típusaihoz.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Meghatározza, hogy az OverrideTheme felülírja-e a örökölt hatékony témát vagy sem. |
| [getOverrideTheme()](#getOverrideTheme--) | Visszaadja a felülíró témaobjektumot. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | Visszaadja a felülíró témaobjektumot. |
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public abstract boolean isOverrideThemeEnabled()
```

Meghatározza, hogy az OverrideTheme felülírja-e a örökölt hatékony témát vagy sem. Az OverrideTheme felülírásának engedélyezéséhez használja az OverrideTheme.Init\*() metódusokat. Az OverrideTheme felülírásának letiltásához használja az OverrideTheme.Clear() metódust. Csak olvasható boolean.

**Visszatér:**
boolean
### getOverrideTheme() {#getOverrideTheme--}
```
public abstract IOverrideTheme getOverrideTheme()
```

Visszaadja a felülíró témaobjektumot. Olvasás/írás [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Visszatér:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public abstract void setOverrideTheme(IOverrideTheme value)
```

Visszaadja a felülíró témaobjektumot. Olvasás/írás [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |