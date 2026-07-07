---
title: GetImage
second_title: Aspose.Sildes for .NET API 參考
description: 傳回具有自訂縮放的 Thumbnail Image 物件。
type: docs
weight: 80
url: /zh-hant/aspose.slides/slide/getimage/
---
## GetImage(float, float) {#getimage_5}

傳回具有自訂縮放的 Thumbnail Image 物件。

```csharp
public IImage GetImage(float scaleX, float scaleY)
```

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| scaleX | Single | 在 x 軸方向上縮放此 Thumbnail 的值。 |
| scaleY | Single | 在 y 軸方向上縮放此 Thumbnail 的值。 |

### 傳回值

IImage 物件。

### 範例

以下範例說明如何從 PowerPoint Presentation 產生縮圖。

```csharp
[C#]
// 實例化一個代表簡報檔案的 Presentation 類別
using (Presentation pres = new Presentation("ThumbnailFromSlide.pptx"))
{
    // 取得第一張投影片
    ISlide sld = pres.Slides[0];
    // 建立完整比例的影像
    IImage bmp = sld.GetImage(1f, 1f);
    // 以 JPEG 格式將影像儲存至磁碟
    bmp.Save("Thumbnail_out.jpg", ImageFormat.Jpeg);
}
```

以下範例說明如何將投影片轉換為 bitmap 並以 PNG 儲存圖像。

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // 將簡報中的第一張投影片轉換為 Bitmap 物件
    using (IImage bmp = pres.Slides[0].GetImage())
    {
        // 以 PNG 格式儲存影像
        bmp.Save("Slide_0.png", ImageFormat.Png);
    }
}
```

以下範例說明如何將 PowerPoint PPT/PPTX 轉換為 JPG。

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.ppt"))
{
	foreach (ISlide sld in pres.Slides)
	{
		// 建立完整比例的影像
		IImage bmp = sld.GetImage(1f, 1f);
		// 以 JPEG 格式將影像儲存至磁碟
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

以下範例說明如何在自訂尺寸下將 PowerPoint PPT/PPTX 轉換為 JPG。

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.pptx"))
{
	// 定義尺寸
	int desiredX = 1200;
	int desiredY = 800;
	// 取得 X 與 Y 的縮放值
	float ScaleX = (float)(1.0 / pres.SlideSize.Size.Width) * desiredX;
	float ScaleY = (float)(1.0 / pres.SlideSize.Size.Height) * desiredY;
	foreach (ISlide sld in pres.Slides)
	{
		// 建立完整比例的影像
		IImage bmp = sld.GetImage(ScaleX, ScaleY);
		// 以 JPEG 格式將影像儲存至磁碟
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

### 另請參閱

* 介面 [IImage](../../iimage)
* 類別 [Slide](../../slide)
* 命名空間 [Aspose.Slides](../../slide)
* 程式集 [Aspose.Slides](../../../)

---

## GetImage() {#getimage}

傳回 Thumbnail Image 物件（實際大小的 20%）。

```csharp
public IImage GetImage()
```

### 另請參閱

* 介面 [IImage](../../iimage)
* 類別 [Slide](../../slide)
* 命名空間 [Aspose.Slides](../../slide)
* 程式集 [Aspose.Slides](../../../)

---

## GetImage(Size) {#getimage_6}

傳回具有指定大小的 Thumbnail Image 物件。

```csharp
public IImage GetImage(Size imageSize)
```

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| imageSize | Size | 要建立的圖像大小。 |

### 傳回值

Image 物件。

### 範例

以下範例說明如何使用 C# 將投影片轉換為具有自訂大小的圖像。

```csharp
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // 將簡報中的第一張投影片轉換為指定尺寸的 Bitmap
    using (IImage bmp = pres.Slides[0].GetImage(new Size(1820, 1040)))
    {
        // 以 JPEG 格式儲存影像
        bmp.Save("Slide_0.jpg", ImageFormat.Jpeg);
    }
}
```

### 另請參閱

* 介面 [IImage](../../iimage)
* 類別 [Slide](../../slide)
* 命名空間 [Aspose.Slides](../../slide)
* 程式集 [Aspose.Slides](../../../)

---

## GetImage(ITiffOptions) {#getimage_4}

傳回具有指定參數的 Thumbnail tiff 圖像物件。

```csharp
public IImage GetImage(ITiffOptions options)
```

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| options | ITiffOptions | tiff 選項。 |

### 傳回值

Image 物件。

### 例外狀況

| 例外 | 條件 |
| --- | --- |
| InvalidOperationException | 當 options.SlideLayoutOption 為 NotesCommentsLayoutingOptions 且其屬性 NotesPosition 取得值 NotesPositions.BottomFull 時拋出。 |

### 另請參閱

* 介面 [IImage](../../iimage)
* 介面 [ITiffOptions](../../../aspose.slides.export/itiffoptions)
* 類別 [Slide](../../slide)
* 命名空間 [Aspose.Slides](../../slide)
* 程式集 [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions) {#getimage_1}

傳回 Thumbnail Image 物件。

```csharp
public IImage GetImage(IRenderingOptions options)
```

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| options | IRenderingOptions | 渲染選項。 |

### 傳回值

Image 物件。

### 例外狀況

| 例外 | 條件 |
| --- | --- |
| InvalidOperationException | 當 notesCommentsLayouting.NotesPosition 取得值 NotesPositions.BottomFull 時拋出。 |

### 另請參閱

* 介面 [IImage](../../iimage)
* 介面 [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* 類別 [Slide](../../slide)
* 命名空間 [Aspose.Slides](../../slide)
* 程式集 [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions, float, float) {#getimage_2}

傳回具有自訂縮放的 Thumbnail Image 物件。

```csharp
public IImage GetImage(IRenderingOptions options, float scaleX, float scaleY)
```

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| options | IRenderingOptions | 渲染選項。 |
| scaleX | Single | 在 x 軸方向上縮放此 Thumbnail 的值。 |
| scaleY | Single | 在 y 軸方向上縮放此 Thumbnail 的值。 |

### 傳回值

Bitmap 物件。

### 例外狀況

| 例外 | 條件 |
| --- | --- |
| InvalidOperationException | 當 notesCommentsLayouting.NotesPosition 取得值 NotesPositions.BottomFull 時拋出。 |

### 範例

以下範例說明如何使用 C# 將含有註解與備註的投影片轉換為圖像。

```csharp
using (Presentation pres = new Presentation("PresentationNotesComments.pptx"))
{
    // 建立渲染選項
    IRenderingOptions options = new RenderingOptions();
    // 建立註解與備註版面配置選項
    NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
    // 設定頁面上註解的位置
    notesCommentsLayouting.NotesPosition = NotesPositions.BottomTruncated;
    // 設定頁面上備註的位置
    notesCommentsLayouting.CommentsPosition = CommentsPositions.Right;
    // 設定備註輸出區域的寬度
    notesCommentsLayouting.CommentsAreaWidth = 500;
    // 設定備註區域的顏色
    notesCommentsLayouting.CommentsAreaColor = Color.AntiqueWhite;
    // 設定渲染的版面配置選項
    options.SlidesLayoutOptions = notesCommentsLayouting;
    // 將簡報的第一張投影片轉換為 IImage 物件
    IImage image = pres.Slides[0].GetImage(options, 2f, 2f);
    // 以 GIF 格式儲存影像
    image.Save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
}
```

### 另請參閱

* 介面 [IImage](../../iimage)
* 介面 [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* 類別 [Slide](../../slide)
* 命名空間 [Aspose.Slides](../../slide)
* 程式集 [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions, Size) {#getimage_3}

傳回具有指定大小的 Thumbnail Image 物件。

```csharp
public IImage GetImage(IRenderingOptions options, Size imageSize)
```

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| options | IRenderingOptions | 渲染選項。 |
| imageSize | Size | 要建立的圖像大小。 |

### 傳回值

Image 物件。

### 例外狀況

| 例外 | 條件 |
| --- | --- |
| InvalidOperationException | 當 options.SlideLayoutOption 為 NotesCommentsLayoutingOptions 且其屬性 NotesPosition 取得值 NotesPositions.BottomFull 時拋出。 |

### 另請參閱

* 介面 [IImage](../../iimage)
* 介面 [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* 類別 [Slide](../../slide)
* 命名空間 [Aspose.Slides](../../slide)
* 程式集 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->