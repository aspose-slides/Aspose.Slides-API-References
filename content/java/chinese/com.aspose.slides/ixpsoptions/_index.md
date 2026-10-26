---
title: IXpsOptions
second_title: Aspose.Slides for Java API 参考文档
description: 提供控制演示文稿以 XPS 格式保存的选项。
type: docs
url: /zh/com.aspose.slides/ixpsoptions/
---
**所有实现的接口：**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXpsOptions extends ISaveOptions
```

提供控制演示文稿保存为 XPS 格式的选项。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | 若为 true，则将演示文稿中使用的所有元文件转换为 PNG 图像。 |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | 若为 true，则将演示文稿中使用的所有元文件转换为 PNG 图像。 |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | 若为 true，则在每张幻灯片周围绘制黑色框架。 |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | 若为 true，则在每张幻灯片周围绘制黑色框架。 |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 指定生成的文档是否应包含隐藏的幻灯片。 |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 指定生成的文档是否应包含隐藏的幻灯片。 |
### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```

若为 true，则将演示文稿中使用的所有元文件转换为 PNG 图像。可读写的布尔值。

--------------------

默认值为 **true**。

**返回值：**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

若为 true，则将演示文稿中使用的所有元文件转换为 PNG 图像。可读写的布尔值。

--------------------

默认值为 **true**。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

若为 true，则在每张幻灯片周围绘制黑色框架。可读写的布尔值。

--------------------

默认值为 **false**。

**返回值：**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

若为 true，则在每张幻灯片周围绘制黑色框架。可读写的布尔值。

--------------------

默认值为 **false**。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

指定生成的文档是否应包含隐藏的幻灯片。默认值为 false。

**返回值：**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

指定生成的文档是否应包含隐藏的幻灯片。默认值为 false。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |