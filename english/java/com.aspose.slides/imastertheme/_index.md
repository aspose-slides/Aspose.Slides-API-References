---
title: IMasterTheme
second_title: Aspose.Slides for Java API Reference
description: Represents a master theme.
type: docs
weight: 884
url: /java/com.aspose.slides/imastertheme/
---
**All Implemented Interfaces:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IMasterTheme extends ITheme
```

Represents a master theme.
## Methods

| Method | Description |
| --- | --- |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | Returns the collection of additional color schemes. |
| [getName()](#getName--) | Returns the name of a theme. |
| [setName(String value)](#setName-java.lang.String-) | Returns the name of a theme. |
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public abstract IExtraColorSchemeCollection getExtraColorSchemes()
```


Returns the collection of additional color schemes. These schemes don't affect presentation's look, they can be selected as main color scheme for a slide. Read-only [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**Returns:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public abstract String getName()
```


Returns the name of a theme. Read/write String.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Returns the name of a theme. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

