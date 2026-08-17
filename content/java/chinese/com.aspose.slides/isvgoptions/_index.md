---
title: ISVGOptions
second_title: Aspose.Slides for Java API 参考
description: 表示 SVG 选项。
type: docs
url: /zh/com.aspose.slides/isvgoptions/
---
**所有实现的接口:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISVGOptions extends ISaveOptions
```

表示 SVG 选项。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getVectorizeText()](#getVectorizeText--) | 确定是否将幻灯片上的文本保存为图形。 |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | 确定是否将幻灯片上的文本保存为图形。 |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | 返回或设置元文件光栅化的最低分辨率限制。 |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | 返回或设置元文件光栅化的最低分辨率限制。 |
| [getDisable3DText()](#getDisable3DText--) | 确定是否在 SVG 中禁用 3D 文本。 |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | 确定是否在 SVG 中禁用 3D 文本。 |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | 禁用 FromCornerX 和 FromCenter 渐变的拆分。 |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | 禁用 FromCornerX 和 FromCenter 渐变的拆分。 |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 缺乏为标记定义内边距的能力。 |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 缺乏为标记定义内边距的能力。 |
| [getJpegQuality()](#getJpegQuality--) | 确定 JPEG 编码质量。 |
| [setJpegQuality(int value)](#setJpegQuality-int-) | 确定 JPEG 编码质量。 |
| [getShapeFormattingController()](#getShapeFormattingController--) | 返回并设置一个回调接口，允许用户控制形状转换。 |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | 返回并设置一个回调接口，允许用户控制形状转换。 |
| [getPicturesCompression()](#getPicturesCompression--) | 表示图片压缩级别 读/写 \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | 表示图片压缩级别 读/写 \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | 一个布尔标志指示裁剪的部分是否仍然是文档的一部分。 |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | 一个布尔标志指示裁剪的部分是否仍然是文档的一部分。 |
| [getUseFrameSize()](#getUseFrameSize--) | 确定是否将文本框包含在渲染区域中。 |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | 确定是否将文本框包含在渲染区域中。 |
| [getUseFrameRotation()](#getUseFrameRotation--) | 确定在渲染时是否执行形状的指定旋转。 |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | 确定在渲染时是否执行形状的指定旋转。 |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | 确定外部加载字体的处理方式。 |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | 确定外部加载字体的处理方式。 |
| [getInkOptions()](#getInkOptions--) | 提供控制导出文档中 Ink 对象外观的选项。 |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | 获取或设置一个值，指示文本是否在渲染时不使用 ligatures。 |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | 获取或设置一个值，指示文本是否在渲染时不使用 ligatures。 |

### getVectorizeText() {#getVectorizeText--}
```
public abstract boolean getVectorizeText()
```

确定是否将幻灯片上的文本保存为图形。读/写 boolean。

**返回:**
boolean

### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public abstract void setVectorizeText(boolean value)
```

确定是否将幻灯片上的文本保存为图形。读/写 boolean。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public abstract int getMetafileRasterizationDpi()
```

返回或设置元文件光栅化的最低分辨率限制。读/写 int。

**返回:**
int

### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public abstract void setMetafileRasterizationDpi(int value)
```

返回或设置元文件光栅化的最低分辨率限制。读/写 int。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public abstract boolean getDisable3DText()
```

确定是否在 SVG 中禁用 3D 文本。读/写 boolean。

**返回:**
boolean

### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public abstract void setDisable3DText(boolean value)
```

确定是否在 SVG 中禁用 3D 文本。读/写 boolean。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public abstract boolean getDisableGradientSplit()
```

禁用 FromCornerX 和 FromCenter 渐变的拆分。读/写 boolean。

**返回:**
boolean

### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public abstract void setDisableGradientSplit(boolean value)
```

禁用 FromCornerX 和 FromCenter 渐变的拆分。读/写 boolean。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public abstract boolean getDisableLineEndCropping()
```

SVG 1.1 缺乏为标记定义内边距的能力。Aspose.Slides SVG 写入引擎为此问题提供了变通方案：它会裁剪带箭头的线段末端，使线段不与标记重叠。此选项关闭该行为。读/写 boolean。

**返回:**
boolean

### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public abstract void setDisableLineEndCropping(boolean value)
```

SVG 1.1 缺乏为标记定义内边距的能力。Aspose.Slides SVG 写入引擎为此问题提供了变通方案：它会裁剪带箭头的线段末端，使线段不与标记重叠。此选项关闭该行为。读/写 boolean。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

确定 JPEG 编码质量。读/写 int。

**返回:**
int

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

确定 JPEG 编码质量。读/写 int。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public abstract ISvgShapeFormattingController getShapeFormattingController()
```

返回并设置一个回调接口，允许用户控制形状转换。读/写 [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)。

**返回:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)

### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public abstract void setShapeFormattingController(ISvgShapeFormattingController value)
```

返回并设置一个回调接口，允许用户控制形状转换。读/写 [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

表示图片压缩级别 读/写 \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)。

**返回:**
int

### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

表示图片压缩级别 读/写 \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

一个布尔标志指示裁剪的部分是否仍然是文档的一部分。如果为 true，则裁剪的部分将被移除；如果为 false，则它们将序列化到文档中（这可能导致文件更大）。读/写 boolean。

**返回:**
boolean

### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

一个布尔标志指示裁剪的部分是否仍然是文档的一部分。如果为 true，则裁剪的部分将被移除；如果为 false，则它们将序列化到文档中（这可能导致文件更大）。读/写 boolean。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameSize() {#getUseFrameSize--}
```
public abstract boolean getUseFrameSize()
```

确定是否将文本框包含在渲染区域中。读/写 boolean。默认值为 false。

**返回:**
boolean

### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public abstract void setUseFrameSize(boolean value)
```

确定是否将文本框包含在渲染区域中。读/写 boolean。默认值为 false。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public abstract boolean getUseFrameRotation()
```

确定在渲染时是否执行形状的指定旋转。读/写 boolean。默认值为 true。

**返回:**
boolean

### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public abstract void setUseFrameRotation(boolean value)
```

确定在渲染时是否执行形状的指定旋转。读/写 boolean。默认值为 true。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public abstract int getExternalFontsHandling()
```

确定外部加载字体的处理方式。读/写 [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling)。

**返回:**
int

### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public abstract void setExternalFontsHandling(int value)
```

确定外部加载字体的处理方式。读/写 [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

提供控制导出文档中 Ink 对象外观的选项。只读 [IInkOptions](../../com.aspose.slides/iinkoptions)

**返回:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

获取或设置一个值，指示文本是否在渲染时不使用 ligatures。当设置为 true 时，渲染输出中将禁用连字。默认情况下，此属性为 false。

--------------------

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

**返回:**
boolean

### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public abstract void setDisableFontLigatures(boolean value)
```

获取或设置一个值，指示文本是否在渲染时不使用 ligatures。当设置为 true 时，渲染输出中将禁用连字。默认情况下，此属性为 false。

--------------------

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

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |