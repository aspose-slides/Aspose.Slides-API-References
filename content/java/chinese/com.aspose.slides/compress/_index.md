---
title: Compress
second_title: Aspose.Slides for Java API 参考
description: 表示一组旨在压缩的 方法。
type: docs
url: /zh/com.aspose.slides/compress/
---
**Inheritance:**
java.lang.Object
```
public class Compress
```

表示一组旨在压缩 [Presentation](../../com.aspose.slides/presentation) 的方法。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.removeUnusedMasterSlides(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Compress()](#Compress--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [compressPresentation(Presentation presentation)](#compressPresentation-com.aspose.slides.Presentation-) | 通过应用所有可用的压缩步骤来减小演示文稿的大小：

 *  删除未使用的母版幻灯片 \#removeUnusedMasterSlides(Presentation).removeUnusedMasterSlides(Presentation).
 *  删除未使用的版式幻灯片 \#removeUnusedLayoutSlides(Presentation).removeUnusedLayoutSlides(Presentation).
 *  仅保留嵌入字体中实际使用的字形 \#compressEmbeddedFonts(Presentation).compressEmbeddedFonts(Presentation).
 *  将图片分辨率降低至 150 DPI 并删除图片的裁剪区域 \#compressImages(IPresentation,int).compressImages(IPresentation,int). |
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | 通过删除未使用的母版幻灯片来压缩 [Presentation](../../com.aspose.slides/presentation)。 |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | 通过删除未使用的版式幻灯片来压缩 [Presentation](../../com.aspose.slides/presentation)。 |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | 通过删除嵌入字体中未使用的字符来压缩 [Presentation](../../com.aspose.slides/presentation)。 |
| [compressImages(IPresentation presentation, int resolution)](#compressImages-com.aspose.slides.IPresentation-int-) | 降低演示文稿中图片的分辨率并删除其裁剪区域，类似于对所有图片应用 PowerPoint 的“压缩图片”。 |
### Compress() {#Compress--}
```
public Compress()
```

### compressPresentation(Presentation presentation) {#compressPresentation-com.aspose.slides.Presentation-}
```
public static void compressPresentation(Presentation presentation)
```

通过应用所有可用的压缩步骤来减小演示文稿的大小：

 *  删除未使用的母版幻灯片 \#removeUnusedMasterSlides(Presentation).removeUnusedMasterSlides(Presentation).
 *  删除未使用的版式幻灯片 \#removeUnusedLayoutSlides(Presentation).removeUnusedLayoutSlides(Presentation).
 *  仅保留嵌入字体中实际使用的字形 \#compressEmbeddedFonts(Presentation).compressEmbeddedFonts(Presentation).
 *  将图片分辨率降低至 150 DPI 并删除图片的裁剪区域 \#compressImages(IPresentation,int).compressImages(IPresentation,int).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.compressPresentation(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| presentation | [Presentation](../../com.aspose.slides/presentation) | 要压缩的演示文稿。

若要自定义压缩，例如使用不同的图片分辨率或跳过某个步骤，请单独调用上面列出的方法，而不是调用此方法。图片的裁剪区域会被永久删除，且在 PowerPoint 中无法恢复。

### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```

通过删除未使用的母版幻灯片来压缩 [Presentation](../../com.aspose.slides/presentation)。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.removeUnusedMasterSlides(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 演示文稿实例 |

### removeUnusedLayoutSlides(Presentation pres) {#removeUnusedLayoutSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedLayoutSlides(Presentation pres)
```

通过删除未使用的版式幻灯片来压缩 [Presentation](../../com.aspose.slides/presentation)。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.removeUnusedLayoutSlides(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 演示文稿实例 |

### compressEmbeddedFonts(Presentation pres) {#compressEmbeddedFonts-com.aspose.slides.Presentation-}
```
public static void compressEmbeddedFonts(Presentation pres)
```

通过删除嵌入字体中未使用的字符来压缩 [Presentation](../../com.aspose.slides/presentation)。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.compressEmbeddedFonts(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 演示文稿实例 |

### compressImages(IPresentation presentation, int resolution) {#compressImages-com.aspose.slides.IPresentation-int-}
```
public static void compressImages(IPresentation presentation, int resolution)
```

降低演示文稿中图片的分辨率并删除其裁剪区域，类似于对所有图片应用 PowerPoint 的“压缩图片”。会处理幻灯片、版式幻灯片和母版幻灯片上的图片，包括组形状内的图片以及形状的图片填充。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.compressImages(pres, PicturesCompression.Dpi150);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | 要处理的演示文稿。 |
| resolution | int | 相对于每张图片显示大小的目标分辨率。[PicturesCompression.DocumentResolution](../../com.aspose.slides/picturescompression\#DocumentResolution) 保持图片不变。

已达到或低于目标分辨率的图片保持不变；图片永不放大。

未处理的包括：幻灯片背景、表格单元格填充、图表、SmartArt、GIF 图像（以保留动画）、SVG 和元文件（EMF/WMF）图像。

裁剪区域会被永久删除，且在 PowerPoint 中无法恢复。