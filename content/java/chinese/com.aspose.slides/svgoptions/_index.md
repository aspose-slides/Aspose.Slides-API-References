---
title: SVGOptions
second_title: Aspose.Slides Java API 参考
description: 表示 SVG 选项。
type: docs
url: /zh/com.aspose.slides/svgoptions/
---
**继承:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**所有实现的接口:**
[com.aspose.slides.ISVGOptions](../../com.aspose.slides/isvgoptions), java.lang.Cloneable
```
public final class SVGOptions extends SaveOptions implements ISVGOptions, Cloneable
```

表示 SVG 选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SVGOptions()](#SVGOptions--) | 初始化 SVGOptions 类的新实例。 |
| [SVGOptions(ILinkEmbedController linkEmbedController)](#SVGOptions-com.aspose.slides.ILinkEmbedController-) | 使用指定的链接嵌入控制器对象初始化 SVGOptions 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | 提供控制导出文档中 Ink 对象外观的选项。 |
| [getUseFrameSize()](#getUseFrameSize--) | 确定文本框是否包含在渲染区域中。 |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | 确定文本框是否包含在渲染区域中。 |
| [getUseFrameRotation()](#getUseFrameRotation--) | 确定在渲染时是否对形状执行指定的旋转。 |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | 确定在渲染时是否对形状执行指定的旋转。 |
| [getVectorizeText()](#getVectorizeText--) | 确定幻灯片上的文本是否保存为图形。 |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | 确定幻灯片上的文本是否保存为图形。 |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | 返回或设置元文件光栅化的最低分辨率限制。 |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | 返回或设置元文件光栅化的最低分辨率限制。 |
| [getDisable3DText()](#getDisable3DText--) | 确定 SVG 中是否禁用 3D 文本。 |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | 确定 SVG 中是否禁用 3D 文本。 |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | 禁用 FromCornerX 和 FromCenter 渐变的拆分。 |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | 禁用 FromCornerX 和 FromCenter 渐变的拆分。 |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 缺乏为标记定义插入的能力。 |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 缺乏为标记定义插入的能力。 |
| [getDefault()](#getDefault--) | 返回默认设置。 |
| [getSimple()](#getSimple--) | 返回用于生成最简洁、最小 SVG 文件的设置。 |
| [getWYSIWYG()](#getWYSIWYG--) | 返回用于生成最精确 SVG 文件的设置。 |
| [getJpegQuality()](#getJpegQuality--) | 确定 JPEG 编码质量。 |
| [setJpegQuality(int value)](#setJpegQuality-int-) | 确定 JPEG 编码质量。 |
| [getShapeFormattingController()](#getShapeFormattingController--) | 返回并设置一个回调接口，允许用户控制形状转换。 |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | 返回并设置一个回调接口，允许用户控制形状转换。 |
| [getPicturesCompression()](#getPicturesCompression--) | 表示图片压缩级别 |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | 表示图片压缩级别 |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | 布尔标志，指示裁剪的部分是否保留在文档中。 |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | 布尔标志，指示裁剪的部分是否保留在文档中。 |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | 确定外部加载字体的处理方式。 |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | 确定外部加载字体的处理方式。 |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | 获取或设置一个值，指示文本是否在渲染时不使用连字。 |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | 获取或设置一个值，指示文本是否在渲染时不使用连字。 |

### SVGOptions() {#SVGOptions--}
```
public SVGOptions()
```

初始化 SVGOptions 类的新实例。

### SVGOptions(ILinkEmbedController linkEmbedController) {#SVGOptions-com.aspose.slides.ILinkEmbedController-}
```
public SVGOptions(ILinkEmbedController linkEmbedController)
```

使用指定的链接嵌入控制器对象初始化 SVGOptions 类的新实例。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | 链接嵌入控制器引用。 |

链接嵌入控制器是一个委托对象，负责决定资源（例如图像）是否需要嵌入或引用为外部资源。

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

提供控制导出文档中 Ink 对象外观的选项。只读 [IInkOptions](../../com.aspose.slides/iinkoptions)

**返回值:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getUseFrameSize() {#getUseFrameSize--}
```
public final boolean getUseFrameSize()
```

确定文本框是否包含在渲染区域中。可读写 boolean。默认值为 false。

**返回值:**
boolean

### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public final void setUseFrameSize(boolean value)
```

确定文本框是否包含在渲染区域中。可读写 boolean。默认值为 false。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public final boolean getUseFrameRotation()
```

确定在渲染时是否对形状执行指定的旋转。可读写 boolean。默认值为 true。

**返回值:**
boolean

### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public final void setUseFrameRotation(boolean value)
```

确定在渲染时是否对形状执行指定的旋转。可读写 boolean。默认值为 true。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getVectorizeText() {#getVectorizeText--}
```
public final boolean getVectorizeText()
```

确定幻灯片上的文本是否保存为图形。可读写 boolean。

**返回值:**
boolean

### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public final void setVectorizeText(boolean value)
```

确定幻灯片上的文本是否保存为图形。可读写 boolean。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public final int getMetafileRasterizationDpi()
```

返回或设置元文件光栅化的最低分辨率限制。可读写 int。

**返回值:**
int

### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public final void setMetafileRasterizationDpi(int value)
```

返回或设置元文件光栅化的最低分辨率限制。可读写 int。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public final boolean getDisable3DText()
```

确定 SVG 中是否禁用 3D 文本。可读写 boolean。

**返回值:**
boolean

### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public final void setDisable3DText(boolean value)
```

确定 SVG 中是否禁用 3D 文本。可读写 boolean。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public final boolean getDisableGradientSplit()
```

禁用 FromCornerX 和 FromCenter 渐变的拆分。可读写 boolean。

**返回值:**
boolean

### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public final void setDisableGradientSplit(boolean value)
```

禁用 FromCornerX 和 FromCenter 渐变的拆分。可读写 boolean。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public final boolean getDisableLineEndCropping()
```

SVG 1.1 缺乏为标记定义插入的能力。Aspose.Slides SVG 写入引擎对该问题有解决办法：它裁剪带箭头的线段末端，使线段不与标记重叠。此选项关闭此行为。可读写 boolean。

**返回值:**
boolean

### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public final void setDisableLineEndCropping(boolean value)
```

SVG 1.1 缺乏为标记定义插入的能力。Aspose.Slides SVG 写入引擎对该问题有解决办法：它裁剪带箭头的线段末端，使线段不与标记重叠。此选项关闭此行为。可读写 boolean。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getDefault() {#getDefault--}
```
public static SVGOptions getDefault()
```

返回默认设置。只读 [SVGOptions](../../com.aspose.slides/svgoptions)。

**返回值:**
[SVGOptions](../../com.aspose.slides/svgoptions)

### getSimple() {#getSimple--}
```
public static SVGOptions getSimple()
```

返回用于生成最简洁、最小 SVG 文件的设置。只读 [SVGOptions](../../com.aspose.slides/svgoptions)。

**返回值:**
[SVGOptions](../../com.aspose.slides/svgoptions)

### getWYSIWYG() {#getWYSIWYG--}
```
public static SVGOptions getWYSIWYG()
```

返回用于生成最精确 SVG 文件的设置。只读 [SVGOptions](../../com.aspose.slides/svgoptions)。

**返回值:**
[SVGOptions](../../com.aspose.slides/svgoptions)

### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

确定 JPEG 编码质量。可读写 int。

**返回值:**
int

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```

确定 JPEG 编码质量。可读写 int。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public final ISvgShapeFormattingController getShapeFormattingController()
```

返回并设置一个回调接口，允许用户控制形状转换。可读写 [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)。

**返回值:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)

### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public final void setShapeFormattingController(ISvgShapeFormattingController value)
```

返回并设置一个回调接口，允许用户控制形状转换。可读写 [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

表示图片压缩级别

**返回值:**
int

### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

表示图片压缩级别

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

布尔标志，指示裁剪的部分是否保留在文档中。如果为 true，则裁剪的部分将被移除；如果为 false，则它们会被序列化到文档中（这可能导致文件更大）。

**返回值:**
boolean

### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

布尔标志，指示裁剪的部分是否保留在文档中。如果为 true，则裁剪的部分将被移除；如果为 false，则它们会被序列化到文档中（这可能导致文件更大）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public final int getExternalFontsHandling()
```

确定外部加载字体的处理方式。可读写 [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling)。

**返回值:**
int

### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public final void setExternalFontsHandling(int value)
```

确定外部加载字体的处理方式。可读写 [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

获取或设置一个值，指示文本是否在渲染时不使用连字。设置为 true 时，渲染输出中将禁用连字。默认情况下，此属性设置为 false。

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SVGOptions options = new SVGOptions();
>      options.setDisableFontLigatures(true);
> 
>      FileOutputStream fileStream = new FileOutputStream("slide-0.svg");
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回值:**
boolean

### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```

获取或设置一个值，指示文本是否在渲染时不使用连字。设置为 true 时，渲染输出中将禁用连字。默认情况下，此属性设置为 false。

> ```
> 示例：
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SVGOptions options = new SVGOptions();
>      options.setDisableFontLigatures(true);
> 
>      FileOutputStream fileStream = new FileOutputStream("slide-0.svg");
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |