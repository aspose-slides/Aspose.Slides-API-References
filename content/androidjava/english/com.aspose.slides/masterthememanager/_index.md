---
title: MasterThemeManager
second_title: Aspose.Slides for Android via Java API Reference
description: Provides access to presentation master theme.
type: docs
url: /com.aspose.slides/masterthememanager/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**All Implemented Interfaces:**
[com.aspose.slides.IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
```
public class MasterThemeManager extends BaseThemeManager implements IMasterThemeManager
```

Provides access to presentation master theme.
## Methods

| Method | Description |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | Returns the overriding theme object. |
| [setOverrideTheme(IMasterTheme value)](#setOverrideTheme-com.aspose.slides.IMasterTheme-) | Returns the overriding theme object. |
| [createThemeEffective()](#createThemeEffective--) | Returns the theme object. |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Determines whether OverrideTheme overrides inherited effective theme (Presentation.MasterTheme) or not. |
| [setOverrideThemeEnabled(boolean value)](#setOverrideThemeEnabled-boolean-) | Determines whether OverrideTheme overrides inherited effective theme (Presentation.MasterTheme) or not. |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | Applies extra color scheme to a slide. |
### getOverrideTheme() {#getOverrideTheme--}
```
public final IMasterTheme getOverrideTheme()
```


Returns the overriding theme object. Read/write [IMasterTheme](../../com.aspose.slides/imastertheme).

**Returns:**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### setOverrideTheme(IMasterTheme value) {#setOverrideTheme-com.aspose.slides.IMasterTheme-}
```
public final void setOverrideTheme(IMasterTheme value)
```


Returns the overriding theme object. Read/write [IMasterTheme](../../com.aspose.slides/imastertheme).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IMasterTheme](../../com.aspose.slides/imastertheme) |  |

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


Determines whether OverrideTheme overrides inherited effective theme (Presentation.MasterTheme) or not. Read/write boolean.

**Returns:**
boolean
### setOverrideThemeEnabled(boolean value) {#setOverrideThemeEnabled-boolean-}
```
public final void setOverrideThemeEnabled(boolean value)
```


Determines whether OverrideTheme overrides inherited effective theme (Presentation.MasterTheme) or not. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```


Applies extra color scheme to a slide.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) object. |

