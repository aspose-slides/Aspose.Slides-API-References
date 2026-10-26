---
title: PptxOptions
second_title: Aspose.Slides for Android via Java API 参考
description: 表示用于保存 OpenXml 演示文稿（PPTX、PPSX、POTX、PPTM、PPSM、POTM）的选项。
type: docs
url: /zh/com.aspose.slides/pptxoptions/
---
**继承:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**所有实现的接口:**
[com.aspose.slides.IPptxOptions](../../com.aspose.slides/ipptxoptions), java.lang.Cloneable
```
public final class PptxOptions extends SaveOptions implements IPptxOptions, Cloneable
```

表示用于保存 OpenXml 演示文稿 (PPTX, PPSX, POTX, PPTM, PPSM, POTM) 的选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PptxOptions()](#PptxOptions--) | 创建 PptxOptions 的新实例 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getConformance()](#getConformance--) | 指定演示文稿文档符合的符合性类。 |
| [setConformance(int value)](#setConformance-int-) | 指定演示文稿文档符合的符合性类。 |
| [getZip64Mode()](#getZip64Mode--) | 指定演示文稿文档是否使用 ZIP64 格式。 |
| [setZip64Mode(int value)](#setZip64Mode-int-) | 指定演示文稿文档是否使用 ZIP64 格式。 |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | 指定是否刷新演示文稿缩略图。 |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | 指定是否刷新演示文稿缩略图。 |
| [getCompressionLevel()](#getCompressionLevel--) | 指定保存演示文稿文档时使用的压缩级别。 |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | 指定保存演示文稿文档时使用的压缩级别。 |

### PptxOptions() {#PptxOptions--}
```
public PptxOptions()
```

创建 PptxOptions 的新实例

### getConformance() {#getConformance--}
```
public final int getConformance()
```

指定演示文稿文档符合的符合性类。默认值为 [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**返回值:**
int

### setConformance(int value) {#setConformance-int-}
```
public final void setConformance(int value)
```

指定演示文稿文档符合的符合性类。默认值为 [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getZip64Mode() {#getZip64Mode--}
```
public final int getZip64Mode()
```

指定演示文稿文档是否使用 ZIP64 格式。默认值为 [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setZip64Mode(Zip64Mode.Always);
>      pres.save("demo-zip64.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
int
### setZip64Mode(int value) {#setZip64Mode-int-}
```
public final void setZip64Mode(int value)
```

Specifies whether the ZIP64 format is used for the Presentation document. The default value is [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setZip64Mode(Zip64Mode.Always);
>      pres.save("demo-zip64.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRefreshThumbnail() {#getRefreshThumbnail--}
```
public final boolean getRefreshThumbnail()
```

Specifies whether the presentation thumbnail will be refreshed. Read/write boolean. Default value is **true**.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setRefreshThumbnail(false);
>      pres.save("result_with_old_thumbnail.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

When the option value is **true**, the new thumbnail will be generated.

When the option value is **false**, the current thumbnail will be saved as is.

**Returns:**
boolean
### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public final void setRefreshThumbnail(boolean value)
```

Specifies whether the presentation thumbnail will be refreshed. Read/write boolean. Default value is **true**.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setRefreshThumbnail(false);
>      pres.save("result_with_old_thumbnail.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

When the option value is **true**, the new thumbnail will be generated.

When the option value is **false**, the current thumbnail will be saved as is.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public final int getCompressionLevel()
```

Specifies the compression level used when saving the presentation document. The default value is [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setCompressionLevel(CompressionLevel.Level8);
>      pres.save("demo-level8.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Higher compression levels produce smaller files but require more processing time. The actual compression ratio depends on the content of the presentation.

**Returns:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public final void setCompressionLevel(int value)

指定保存演示文稿文档时使用的压缩级别。默认值为 [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6)。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setCompressionLevel(CompressionLevel.Level8);
>      pres.save("demo-level8.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

更高的压缩级别会生成更小的文件，但需要更多的处理时间。实际的压缩比例取决于演示文稿的内容。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |