---
title: XpsOptions
second_title: Aspose.Slides for Java API 参考
description: 提供用于控制演示文稿以 XPS 格式保存方式的选项。
type: docs
url: /zh/com.aspose.slides/xpsoptions/
---
**继承:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**所有实现的接口:**
[com.aspose.slides.IXpsOptions](../../com.aspose.slides/ixpsoptions)
```
public class XpsOptions extends SaveOptions implements IXpsOptions
```

提供控制演示文稿以 XPS 格式保存方式的选项。

--------------------

> ```
> The following example shows how to converting presentations to XPS using default settings.
>  
>  // 实例化一个代表演示文稿文件的 Presentation 对象
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
>  // 实例化一个代表演示文稿文件的 Presentation 对象
>  Presentation pres = new Presentation("Convert_XPS_Options.pptx");
>  try {
>      // 实例化 TiffOptions 类
>      XpsOptions options = new XpsOptions();
>      // 将元文件保存为 PNG
>      options.setSaveMetafilesAsPng(true);
>      // 将演示文稿保存为 XPS 文档
>      pres.save("XPS_With_Options_out.xps", SaveFormat.Xps, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## 构造函数

| 构造函数 | 说明 |
| --- | --- |
| [XpsOptions()](#XpsOptions--) | 默认构造函数。 |
## 方法

| 方法 | 说明 |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 指定生成的文档是否应包含隐藏的幻灯片。 |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 指定生成的文档是否应包含隐藏的幻灯片。 |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | 若为 true，则将演示文稿中使用的所有元文件转换为 PNG 图像。 |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | 若为 true，则将演示文稿中使用的所有元文件转换为 PNG 图像。 |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | 若为 true，则在每个幻灯片周围绘制黑色框架。 |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | 若为 true，则在每个幻灯片周围绘制黑色框架。 |
### XpsOptions() {#XpsOptions--}
```
public XpsOptions()
```

默认构造函数。

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

指定生成的文档是否应包含隐藏的幻灯片。默认值为 false。

**返回值:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

指定生成的文档是否应包含隐藏的幻灯片。默认值为 false。

**参数:**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | boolean |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```

若为 true，则将演示文稿中使用的所有元文件转换为 PNG 图像。可读写布尔。

--------------------

默认值为 **true**。

**返回值:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

若为 true，则将演示文稿中使用的所有元文件转换为 PNG 图像。可读写布尔。

--------------------

默认值为 **true**。

**参数:**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | boolean |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

若为 true，则在每个幻灯片周围绘制黑色框架。可读写布尔。

--------------------

默认值为 **false**。

**返回值:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

若为 true，则在每个幻灯片周围绘制黑色框架。可读写布尔。

--------------------

默认值为 **false**。

**参数:**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | boolean |  |