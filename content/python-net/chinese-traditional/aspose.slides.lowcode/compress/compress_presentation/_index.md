---
title: compress_presentation method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.lowcode/compress/compress_presentation/
weight: 30
---
## compress_presentation(presentation) {#presentation}
透過套用所有可用的壓縮步驟，減少簡報的大小：

* 移除未使用的母片投影片 **Aspose.Slides.LowCode.Compress.RemoveUnusedMasterSlides(Aspose.Slide**.
* 移除未使用的版面配置投影片 **Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(Aspose.Slide**.
* 只保留嵌入字型中實際使用的字形 **Aspose.Slides.LowCode.Compress.CompressEmbeddedFonts(Aspose.Slide**.
* 將圖片解析度降低至 150 DPI 並刪除圖片的裁切區域 **Aspose.Slides.LowCode.Compress.CompressImages(Aspose.Slides.IPresentation,Aspose.Slides.Expor**.

```python
@staticmethod
def compress_presentation(presentation):
    ...
```

| 參數 | 型別 | 說明 |
| :- | :- | :- |
| presentation | [`Presentation`](/slides/python-net/zh-hant/aspose.slides/presentation) | 要壓縮的簡報。 |

### 備註

若要自訂壓縮，例如使用不同的圖片解析度或跳過某個步驟，請個別呼叫上述方法，而非使用此方法。圖片的裁切區域會被永久移除，無法在 PowerPoint 中復原。

### 例外狀況

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `presentation` 為 `None`。 |

### 另請參閱
* 類別 [`Compress`](/slides/python-net/zh-hant/aspose.slides.lowcode/compress)
* 類別 [`Presentation`](/slides/python-net/zh-hant/aspose.slides/presentation)
* 模組 [`aspose.slides.lowcode`](/slides/python-net/zh-hant/aspose.slides.lowcode)
* 函式庫 [`Aspose.Slides`](/slides/python-net)