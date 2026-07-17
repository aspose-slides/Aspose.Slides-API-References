---
title: GetImage()
second_title: Aspose.Slides for C++ API 参考
description: 返回具有自定义缩放的 Thumbnail Image 对象。
type: docs
weight: 144
url: /zh/aspose.slides/slide/getimage/
---
## Slide::GetImage(float, float) 方法

返回一个具有自定义缩放的 Thumbnail Image 对象。

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(float scaleX, float scaleY) override
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| scaleX | **float** | 在 x 轴方向上用于缩放此 Thumbnail 的值。 |
| scaleY | **float** | 在 y 轴方向上用于缩放此 Thumbnail 的值。 |

### 返回值

[IImage](../../iimage/) 对象。

## 备注

以下示例演示如何从 PowerPoint [Presentation](../../presentation/) 生成缩略图：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"ThumbnailFromSlide.pptx");

// Access the first slide
System::SharedPtr<ISlide> sld = pres->get_Slide(0);
// Create a full scale image
System::SharedPtr<IImage> bmp = sld->GetImage(1.0f, 1.0f);
// Save the image to disk in JPEG format
bmp->Save(u"Thumbnail_out.jpg", Aspose::Slides::ImageFormat::Jpeg);
```
以下示例演示如何将幻灯片转换为位图并以 PNG 格式保存图像：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// 将演示文稿中的第一张幻灯片转换为 Bitmap 对象
System::SharedPtr<IImage> bmp = pres->get_Slide(0)->GetImage();
// 以 PNG 格式保存图像
bmp->Save(u"Slide_0.png", Aspose::Slides::ImageFormat::Png);
```
以下示例演示如何将 PowerPoint PPT/PPTX 转换为 JPG：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PowerPoint-Presentation.ppt");

for (auto&& sld : pres->get_Slides())
{
    // 创建全尺寸图像
    System::SharedPtr<IImage> bmp = sld->GetImage(1.0f, 1.0f);
    // 将图像以 JPEG 格式保存到磁盘
    bmp->Save(System::String::Format(u"Slide_{0}.jpg", sld->get_SlideNumber()), Aspose::Slides::ImageFormat::Jpeg);
}
```
以下示例演示如何在自定义尺寸下将 PowerPoint PPT/PPTX 转换为 JPG：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PowerPoint-Presentation.pptx");

// 定义尺寸
int32_t desiredX = 1200;
int32_t desiredY = 800;
// 获取 X 和 Y 的缩放值
float scaleX = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Width()) * desiredX;
float scaleY = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Height()) * desiredY;

for (auto&& sld : pres->get_Slides())
{
    // 创建全尺寸图像
    System::SharedPtr<IImage> bmp = sld->GetImage(scaleX, scaleY);
    // 将图像以 JPEG 格式保存到磁盘
    bmp->Save(System::String::Format(u"Slide_{0}.jpg", sld->get_SlideNumber()), Aspose::Slides::ImageFormat::Jpeg);
}
```

## Slide::GetImage() 方法

返回一个 Thumbnail Image 对象（实际大小的 20%）。

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage() override
```

## Slide::GetImage(System::Drawing::Size) 方法

返回一个具有指定尺寸的 Thumbnail Image 对象。

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::Drawing::Size imageSize) override
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | 要创建的图像的尺寸。 |

### 返回值

Image 对象。

## 备注

以下示例演示如何使用 C# 将幻灯片转换为自定义尺寸的图像：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// 将演示文稿中的第一张幻灯片转换为指定尺寸的 Bitmap
System::SharedPtr<IImage> bmp = pres->get_Slide(0)->GetImage(System::Drawing::Size(1820, 1040));

// 以 JPEG 格式保存图像
bmp->Save(u"Slide_0.jpg", Aspose::Slides::ImageFormat::Jpeg);
```

## Slide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) 方法

返回具有指定参数的 Thumbnail tiff 图像对象。

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::ITiffOptions> options) override
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Tiff 选项。 |

### 返回值

Image 对象。

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) 方法

返回一个 Thumbnail Image 对象。

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options) override
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | 渲染选项。 |

### 返回值

Image 对象。

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) 方法

返回一个具有自定义缩放的 Thumbnail Image 对象。

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY) override
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | 渲染选项。 |
| scaleX | **float** | 在 x 轴方向上用于缩放此 Thumbnail 的值。 |
| scaleY | **float** | 在 y 轴方向上用于缩放此 Thumbnail 的值。 |

### 返回值

Bitmap 对象。

## 备注

以下示例演示如何使用 C# 将带有备注和评论的幻灯片转换为 [Images](../../images/)：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PresentationNotesComments.pptx");

// 创建渲染选项
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
// 创建备注和评论布局选项
System::SharedPtr<NotesCommentsLayoutingOptions> notesCommentsLayouting = System::MakeObject<NotesCommentsLayoutingOptions>();
// 设置页面上备注的位置
notesCommentsLayouting->set_NotesPosition(NotesPositions::BottomTruncated);
// 设置页面上评论的位置
notesCommentsLayouting->set_CommentsPosition(CommentsPositions::Right);
// 设置评论输出区域的宽度
notesCommentsLayouting->set_CommentsAreaWidth(500);
// 设置评论区域的颜色
notesCommentsLayouting->set_CommentsAreaColor(System::Drawing::Color::get_AntiqueWhite());
// 设置渲染的布局选项
options->set_SlidesLayoutOptions(notesCommentsLayouting);
// 将演示文稿的第一张幻灯片转换为 IImage 对象
System::SharedPtr<IImage> image = pres->get_Slide(0)->GetImage(options, 2.0f, 2.0f);
// 以 GIF 格式保存图像
image->Save(u"Slide_Notes_Comments_0.gif", ImageFormat::Gif);
```

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) 方法

返回一个具有指定尺寸的 Thumbnail Image 对象。

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize) override
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | 渲染选项。 |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | 要创建的图像的尺寸。 |

### 返回值

Image 对象。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IImage](../../iimage/)
* 类 [Slide](../)
* 类 [Size](../../../system.drawing/size/)
* 类 [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* 类 [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)