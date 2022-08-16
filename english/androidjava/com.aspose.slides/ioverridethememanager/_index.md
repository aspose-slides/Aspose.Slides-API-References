---
title: IOverrideThemeManager
second_title: Aspose.Slides for Android via Java API Reference
description:  Provides access to different types of overriden themes.
type: docs
weight: 947
url: /androidjava/com.aspose.slides/ioverridethememanager/
---
**All Implemented Interfaces:**
[com.aspose.slides.IThemeManager](../../com.aspose.slides/ithememanager)
```
public interface IOverrideThemeManager extends IThemeManager
```

Provides access to different types of overriden themes.
## Methods

| Method | Description |
| --- | --- |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Determines whether OverrideTheme overrides inherited effective theme or not. |
| [getOverrideTheme()](#getOverrideTheme--) | Returns the overriding theme object. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | Returns the overriding theme object. |
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public abstract boolean isOverrideThemeEnabled()
```


Determines whether OverrideTheme overrides inherited effective theme or not. To enable OverrideTheme for overriding use OverrideTheme.Init\*() methods. To disable OverrideTheme from overriding use OverrideTheme.Clear() method. Read-only boolean.

**Returns:**
boolean
### getOverrideTheme() {#getOverrideTheme--}
```
public abstract IOverrideTheme getOverrideTheme()
```


Returns the overriding theme object. Read/write [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Returns:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public abstract void setOverrideTheme(IOverrideTheme value)
```


Returns the overriding theme object. Read/write [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |

