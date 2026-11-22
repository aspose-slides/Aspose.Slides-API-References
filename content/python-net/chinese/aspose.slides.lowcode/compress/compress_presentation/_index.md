---
title: compress_presentation method
second_title: Aspose.Slides 用于 Python 的 .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.lowcode/compress/compress_presentation/
weight: 30
---
## compress_presentation(presentation) {#presentation}
通过应用所有可用的压缩步骤来减小演示文稿的大小：

* 删除未使用的母版幻灯片 **Aspose.Slides.LowCode.Compress.RemoveUnusedMasterSlides(Aspose.Slide**.
* 删除未使用的布局幻灯片 **Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(Aspose.Slide**.
* 仅保留嵌入字体中实际使用的字形 **Aspose.Slides.LowCode.Compress.CompressEmbeddedFonts(Aspose.Slide**.
* 将图片分辨率降低至 150 DPI 并删除图片的裁剪区域 **Aspose.Slides.LowCode.Compress.CompressImages(Aspose.Slides.IPresentation,Aspose.Slides.Expor**.

```python
@staticmethod
def compress_presentation(presentation):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| presentation | [`Presentation`](/slides/python-net/zh/aspose.slides/presentation) | 要压缩的演示文稿。 |

### 备注

要自定义压缩，例如使用不同的图片分辨率或跳过某一步，  
请单独调用上面列出的方法，而不是此方法。  
图片的裁剪区域会被永久删除，且在 PowerPoint 中无法恢复。

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `presentation` 为 `None`。 |

### 另请参见
* 类 [`Compress`](/slides/python-net/zh/aspose.slides.lowcode/compress)
* 类 [`Presentation`](/slides/python-net/zh/aspose.slides/presentation)
* 模块 [`aspose.slides.lowcode`](/slides/python-net/zh/aspose.slides.lowcode)
* 库 [`Aspose.Slides`](/slides/python-net)