---
title: XpsOptions
second_title: Aspose.Slides for Android via Java API 参考
description: 提供用于控制演示文稿以 XPS 格式保存的选项。
type: docs
url: /zh/com.aspose.slides/xpsoptions/
---
**继承：**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**所有实现的接口：**
[com.aspose.slides.IXpsOptions](../../com.aspose.slides/ixpsoptions)
```
public class XpsOptions extends SaveOptions implements IXpsOptions
```

提供用于控制演示文稿以 XPS 格式保存的选项。

--------------------

> ```
> The following example shows how to converting presentations to XPS using default settings.
>  
>  // 实例化一个表示演示文稿文件的 Presentation 对象
>  Presentation pres = new Presentation("Convert_XPS.pptx");
>  try {
>      // 将演示文稿保存为 XPS 文档
>      pres.save("XPS_Output_Without_XPSOption_out.xps", SaveFormat.Xps);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to converting presentations to XPS using custom settings.
>  
>  // 实例化一个表示演示文稿文件的 Presentation 对象
>  Presentation pres = new Presentation("Convert_XPS_Options.pptx");
>  try {
>      // 实例化 TiffOptions 类
>      XpsOptions options = new XpsOptions();
>      // 将 MetaFiles 保存为 PNG
>      options.setSaveMetafilesAsPng(true);
>      // 将演示文稿保存为 XPS 文档
>      pres.save("XPS_With_Options_out.xps", SaveFormat.Xps, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [XpsOptions()](#XpsOptions--) | Default constructor. |
## Methods

| Method | Description |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Specifies whether the generated document should include hidden slides or not. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Specifies whether the generated document should include hidden slides or not. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True to convert all metafiles used in a presentation to the PNG images. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True to convert all metafiles used in a presentation to the PNG images. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True to draw black frame around each slide. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True to draw black frame around each slide. |
### XpsOptions() {#XpsOptions--}
```
public XpsOptions()
```

Default constructor.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Specifies whether the generated document should include hidden slides or not. Default is false.

**Returns:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Specifies whether the generated document should include hidden slides or not. Default is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```

True to convert all metafiles used in a presentation to the PNG images. Read/write boolean.

--------------------

Default is **true**.

**Returns:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

True to convert all metafiles used in a presentation to the PNG images. Read/write boolean.

--------------------

Default is **true**.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

True to draw black frame around each slide. Read/write boolean.

--------------------

Default is **false**.

**Returns:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)


为 true 时在每个幻灯片周围绘制黑色框。读/写 布尔值。

--------------------

默认是 **false**。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |