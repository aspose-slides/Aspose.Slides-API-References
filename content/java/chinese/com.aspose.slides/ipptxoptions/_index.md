---
title: IPptxOptions
second_title: Aspose.Slides for Java API 参考
description: 表示用于保存 OpenXml 演示文稿 PPTX、PPSX、POTX、PPTM、PPSM、POTM 的选项。
type: docs
url: /zh/com.aspose.slides/ipptxoptions/
---
**所有已实现的接口:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptxOptions extends ISaveOptions
```

表示用于保存 OpenXml 演示文稿 (PPTX, PPSX, POTX, PPTM, PPSM, POTM) 的选项。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getConformance()](#getConformance--) | 指定 Presentation 文档符合的兼容级别。 |
| [setConformance(int value)](#setConformance-int-) | 指定 Presentation 文档符合的兼容级别。 |
| [getZip64Mode()](#getZip64Mode--) | 指定是否对 Presentation 文档使用 ZIP64 格式。 |
| [setZip64Mode(int value)](#setZip64Mode-int-) | 指定是否对 Presentation 文档使用 ZIP64 格式。 |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | 指定是否刷新演示文稿缩略图。 |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | 指定是否刷新演示文稿缩略图。 |
| [getCompressionLevel()](#getCompressionLevel--) | 指定在保存演示文稿时使用的压缩级别。 |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | 指定在保存演示文稿时使用的压缩级别。 |
### getConformance() {#getConformance--}
```
public abstract int getConformance()
```

指定 Presentation 文档符合的兼容级别。默认值为 [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**返回:**
int
### setConformance(int value) {#setConformance-int-}
```
public abstract void setConformance(int value)
```

指定 Presentation 文档符合的兼容级别。默认值为 [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getZip64Mode() {#getZip64Mode--}
```
public abstract int getZip64Mode()
```

指定是否对 Presentation 文档使用 ZIP64 格式。默认值为 [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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

**返回:**
int
### setZip64Mode(int value) {#setZip64Mode-int-}
```
public abstract void setZip64Mode(int value)
```

指定是否对 Presentation 文档使用 ZIP64 格式。默认值为 [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getRefreshThumbnail() {#getRefreshThumbnail--}
```
public abstract boolean getRefreshThumbnail()
```

指定是否刷新演示文稿缩略图。读/写 布尔值。默认值为 **true**。

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

当选项值为 **true** 时，将生成新的缩略图。

当选项值为 **false** 时，当前缩略图将保持不变并保存。

**返回:**
boolean
### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public abstract void setRefreshThumbnail(boolean value)
```

指定是否刷新演示文稿缩略图。读/写 布尔值。默认值为 **true**。

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

当选项值为 **true** 时，将生成新的缩略图。

当选项值为 **false** 时，当前缩略图将保持不变并保存。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public abstract int getCompressionLevel()
```

指定在保存演示文稿时使用的压缩级别。默认值为 [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6)。

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

更高的压缩级别会生成更小的文件，但需要更多的处理时间。实际的压缩比取决于 presentation 的内容。

**返回:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public abstract void setCompressionLevel(int value)
```

指定在保存演示文稿时使用的压缩级别。默认值为 [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6)。

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

更高的压缩级别会生成更小的文件，但需要更多的处理时间。实际的压缩比取决于 presentation 的内容。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |