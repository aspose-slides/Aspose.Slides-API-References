---
title: BaseOverrideThemeManager
second_title: Aspose.Slides for Java API Reference
description: Base class for classes that provide access to different types of overriden themes.
type: docs
weight: 41
url: /java/com.aspose.slides/baseoverridethememanager/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**All Implemented Interfaces:**
[com.aspose.slides.IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
```
public abstract class BaseOverrideThemeManager extends BaseThemeManager implements IOverrideThemeManager
```

Base class for classes that provide access to different types of overriden themes.
## Methods

| Method | Description |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | Returns the overriding theme object. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | Returns the overriding theme object. |
| [createThemeEffective()](#createThemeEffective--) | Returns the theme object. |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Determines whether OverrideTheme overrides inherited effective theme or not. |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | Applies extra color scheme to a slide. |
### getOverrideTheme() {#getOverrideTheme--}
```
public final IOverrideTheme getOverrideTheme()
```


Returns the overriding theme object. Read/write [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Returns:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public final void setOverrideTheme(IOverrideTheme value)
```


Returns the overriding theme object. Read/write [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```


Returns the theme object.

**Returns:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public final boolean isOverrideThemeEnabled()
```


Determines whether OverrideTheme overrides inherited effective theme or not. To enable OverrideTheme for overriding use OverrideTheme.Init\*() methods. To disable OverrideTheme from overriding use OverrideTheme.Clear() method. Read-only boolean.

**Returns:**
boolean
### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```


Applies extra color scheme to a slide.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | The [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) object. |

