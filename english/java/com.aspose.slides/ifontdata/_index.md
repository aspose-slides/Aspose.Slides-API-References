---
title: IFontData
second_title: Aspose.Slides for Java API Reference
description:  Represents a font definition.
type: docs
weight: 777
url: /java/com.aspose.slides/ifontdata/
---```
public interface IFontData
```

Represents a font definition.
## Methods

| Method | Description |
| --- | --- |
| [getFontName()](#getFontName--) | Returns the font name. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Returns the font name, replacing theme referrence with an actual font used. |
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```


Returns the font name. Read-only String.

**Returns:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public abstract String getFontName(IThemeEffectiveData theme)
```


Returns the font name, replacing theme referrence with an actual font used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Theme from which themed font name should be taken. Its up to caller to provide a correct value. |

**Returns:**
java.lang.String - Font name.
