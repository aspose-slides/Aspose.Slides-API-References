---
title: GetImage()
second_title: Aspose.Slides for C++ API 參考
description: 傳回帶有自訂縮放的 Thumbnail Image 物件。
type: docs
weight: 144
url: /zh-hant/aspose.slides/slide/getimage/
---
## Slide::GetImage(float, float) 方法

返回帶有自訂縮放的 Thumbnail Image 物件。

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(float scaleX, float scaleY) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| scaleX | **float** | 在 x 軸方向上縮放此 Thumbnail 的值。 |
| scaleY | **float** | 在 y 軸方向上縮放此 Thumbnail 的值。 |

### 返回值

[IImage](../../iimage/) 物件。

## 備註

以下範例說明如何從 PowerPoint [Presentation](../../presentation/) 生成縮圖：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"ThumbnailFromSlide.pptx");

// Access the first slide
System::SharedPtr<ISlide> sld = pres->get_Slide(0);
// Create a full scale image
System::SharedPtr<IImage> bmp = sld->GetImage(1.0f, 1.0f);
// Save the image to disk in JPEG format
bmp->Save(u"Thumbnail_out.jpg", Aspose::Slides::ImageFormat::Jpeg);
```
以下範例說明如何將投影片轉換為位圖並以 PNG 格式儲存圖像：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// 將簡報中的第一張投影片轉換為 Bitmap 物件
System::SharedPtr<IImage> bmp = pres->get_Slide(0)->GetImage();
// 將影像以 PNG 格式儲存
bmp->Save(u"Slide_0.png", Aspose::Slides::ImageFormat::Png);
```
以下範例說明如何將 PowerPoint PPT/PPTX 轉換為 JPG：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PowerPoint-Presentation.ppt");

for (auto&& sld : pres->get_Slides())
{
    // 建立完整比例的圖像
    System::SharedPtr<IImage> bmp = sld->GetImage(1.0f, 1.0f);
    // 以 JPEG 格式將圖像儲存至磁碟
    bmp->Save(System::String::Format(u"Slide_{0}.jpg", sld->get_SlideNumber()), Aspose::Slides::ImageFormat::Jpeg);
}
```
以下範例說明如何將 PowerPoint PPT/PPTX 轉換為具有自訂尺寸的 JPG：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PowerPoint-Presentation.pptx");

// 定義尺寸
int32_t desiredX = 1200;
int32_t desiredY = 800;
// 取得 X 與 Y 的縮放值
float scaleX = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Width()) * desiredX;
float scaleY = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Height()) * desiredY;

for (auto&& sld : pres->get_Slides())
{
    // 建立完整比例的圖像
    System::SharedPtr<IImage> bmp = sld->GetImage(scaleX, scaleY);
    // 以 JPEG 格式將圖像儲存至磁碟
    bmp->Save(System::String::Format(u"Slide_{0}.jpg", sld->get_SlideNumber()), Aspose::Slides::ImageFormat::Jpeg);
}
```

## Slide::GetImage() 方法

返回 Thumbnail Image 物件（實際尺寸的 20%）。

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage() override
```

## Slide::GetImage(System::Drawing::Size) 方法

返回具有指定尺寸的 Thumbnail Image 物件。

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::Drawing::Size imageSize) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | 要建立的圖像尺寸。 |

### 返回值

Image 物件。

## 備註

以下範例說明如何使用 C# 將投影片轉換為自訂大小的圖像：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// 將簡報中的第一張投影片轉換為具有指定尺寸的 Bitmap
System::SharedPtr<IImage> bmp = pres->get_Slide(0)->GetImage(System::Drawing::Size(1820, 1040));

// 以 JPEG 格式儲存影像
bmp->Save(u"Slide_0.jpg", Aspose::Slides::ImageFormat::Jpeg);
```

## Slide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) 方法

返回具有指定參數的 Thumbnail tiff 圖像物件。

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::ITiffOptions> options) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Tiff 選項。 |

### 返回值

Image 物件。

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) 方法

返回 Thumbnail Image 物件。

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | 渲染選項。 |

### 返回值

Image 物件。

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) 方法

返回帶有自訂縮放的 Thumbnail Image 物件。

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | 渲染選項。 |
| scaleX | **float** | 在 x 軸方向上縮放此 Thumbnail 的值。 |
| scaleY | **float** | 在 y 軸方向上縮放此 Thumbnail 的值。 |

### 返回值

Bitmap 物件。

## 備註

以下範例說明如何使用 C# 將帶有註解和備註的投影片轉換為 [Images](../../images/)：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PresentationNotesComments.pptx");

// 建立渲染選項
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
// 建立註記與評論版面配置選項
System::SharedPtr<NotesCommentsLayoutingOptions> notesCommentsLayouting = System::MakeObject<NotesCommentsLayoutingOptions>();
// 設定頁面上註記的位置
notesCommentsLayouting->set_NotesPosition(NotesPositions::BottomTruncated);
// 設定頁面上評論的位置
notesCommentsLayouting->set_CommentsPosition(CommentsPositions::Right);
// 設定評論輸出區域的寬度
notesCommentsLayouting->set_CommentsAreaWidth(500);
// 設定評論區域的顏色
notesCommentsLayouting->set_CommentsAreaColor(System::Drawing::Color::get_AntiqueWhite());
// 設定渲染的版面配置選項
options->set_SlidesLayoutOptions(notesCommentsLayouting);
// 將簡報的第一張投影片轉換為 IImage 物件
System::SharedPtr<IImage> image = pres->get_Slide(0)->GetImage(options, 2.0f, 2.0f);
// 以 GIF 格式儲存影像
image->Save(u"Slide_Notes_Comments_0.gif", ImageFormat::Gif);
```

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) 方法

返回具有指定尺寸的 Thumbnail Image 物件。

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | 渲染選項。 |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | 要建立的圖像尺寸。 |

### 返回值

Image 物件。

## 另請參見

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [Slide](../)
* Class [Size](../../../system.drawing/size/)
* Class [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)