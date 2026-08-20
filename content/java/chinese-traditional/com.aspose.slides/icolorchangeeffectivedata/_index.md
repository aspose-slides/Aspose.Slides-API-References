---
title: IColorChangeEffectiveData
second_title: Aspose.Slides for Java API 參考文件
description: 表示顏色變換效果的不可變物件。
type: docs
url: /zh-hant/com.aspose.slides/icolorchangeeffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IColorChangeEffectiveData extends IEffectEffectiveData
```

不可變物件，表示 Color Change 效果。FromColor 的實例會被 ToColor 的實例取代。
## Methods

| Method | Description |
| --- | --- |
| [getFromColor()](#getFromColor--) | Color which will be replaced. |
| [getToColor()](#getToColor--) | Color which will replace. |
| [getUseAlpha()](#getUseAlpha--) | Returns a boolean value which determines if alpha component should be used. |
### getFromColor() {#getFromColor--}
```
public abstract Color getFromColor()
```


Color which will be replaced. Read-only java.awt.Color.

**Returns:**
java.awt.Color
### getToColor() {#getToColor--}
```
public abstract Color getToColor()
```


Color which will replace. Read-only java.awt.Color.

**Returns:**
java.awt.Color
### getUseAlpha() {#getUseAlpha--}
```
public abstract boolean getUseAlpha()
```


Returns a boolean value which determines if alpha component should be used. Read-only boolean.

**Returns:**
boolean