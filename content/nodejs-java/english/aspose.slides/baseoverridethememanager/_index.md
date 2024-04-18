---
title: BaseOverrideThemeManager
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/baseoverridethememanager/
---

## BaseOverrideThemeManager class

 Base class for classes that provide access to different types of overriden themes.
 
### applyColorScheme {#applyColorScheme}

| Name | Description |
| --- | --- |
| applyColorScheme ([ExtraColorScheme](../extracolorscheme)) | Applies extra color scheme to a slide. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| scheme | [ExtraColorScheme](../extracolorscheme) | The IExtraColorScheme object. |


---


### createThemeEffective {#createThemeEffective}

| Name | Description |
| --- | --- |
| createThemeEffective () | Returns the theme object. |

 **Returns:**
ThemeEffectiveData


---


### getOverrideTheme {#getOverrideTheme}

| Name | Description |
| --- | --- |
| getOverrideTheme () | Returns the overriding theme object. Read/write IOverrideTheme. |

 **Returns:**
[OverrideTheme](../overridetheme)


---


### isOverrideThemeEnabled {#isOverrideThemeEnabled}

| Name | Description |
| --- | --- |
| isOverrideThemeEnabled () | Determines whether OverrideTheme overrides inherited effective theme or not. To enable OverrideTheme for overriding use OverrideTheme.Init*() functions. To disable OverrideTheme from overriding use OverrideTheme.Clear() function. Read-only boolean. |

 **Returns:**
boolean


---


### setOverrideTheme {#setOverrideTheme}

| Name | Description |
| --- | --- |
| setOverrideTheme ([OverrideTheme](../overridetheme)) | Returns the overriding theme object. Read/write IOverrideTheme. |


---


