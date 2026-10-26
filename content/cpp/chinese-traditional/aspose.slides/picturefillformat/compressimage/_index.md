---
title: CompressImage()
second_title: Aspose.Slides for C++ API 參考文件
description: 根據形狀大小和指定的解析度減少圖像的尺寸以壓縮圖像。亦可選擇刪除裁剪區域。
type: docs
weight: 443
url: /zh-hant/aspose.slides/picturefillformat/compressimage/
---
## PictureFillFormat::CompressImage(bool, Export::PicturesCompression) method

壓縮圖像，根據形狀大小和指定的解析度減少其尺寸。亦可選擇刪除裁剪區域。

```cpp
bool Aspose::Slides::PictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, Export::PicturesCompression resolution) override
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | 若為 true，方法會移除圖像的裁剪區域，可能進一步減少其大小。 |
| resolution | [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) | 壓縮的目標解析度，指定為 [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) enum 的值。 |

### 傳回值

一個 **bool**，表示圖像是否成功壓縮。傳回 ****true****

## 備註

此方法會改變圖像的大小和解析度，類似於 PowerPoint 的「Picture Format -> Compress Pictures」功能。

如果圖像已重新調整大小或被裁剪，則傳回 ****false****
.

以下範例示範如何使用 **CompressImage** 方法，透過設定目標解析度並移除裁剪區域，以減少簡報中圖像的大小：
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));
// 壓縮圖像，目標解析度為 150 DPI（Web 解析度），並移除裁剪區域
bool result = picFrame->get_PictureFormat()->CompressImage(true, PicturesCompression::Dpi150);
```

## PictureFillFormat::CompressImage(bool, float) method

壓縮圖像，根據形狀大小和指定的解析度減少其尺寸。亦可選擇刪除裁剪區域。

```cpp
bool Aspose::Slides::PictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, float resolution) override
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | 若為 true，方法會移除圖像的裁剪區域，可能進一步減少其大小。 |
| resolution | **float** | 目標解析度（單位 DPI）。此值必須為正數，決定圖像的重新縮放方式。 |

### 傳回值

一個 **bool**，表示圖像是否成功壓縮。傳回 ****true****

## 備註

此方法會改變圖像的大小和解析度，類似於 PowerPoint 的「Picture Format -> Compress Pictures」功能。

如果圖像已重新調整大小或被裁剪，則傳回 ****false****
.

以下範例示範如何使用 **CompressImage** 方法，透過設定目標解析度並移除裁剪區域，以減少簡報中圖像的大小：
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 取得 PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// 壓縮圖像，目標解析度為 150 DPI（Web 解析度），並移除裁剪區域
bool result = picFrame->get_PictureFormat()->CompressImage(true, 150.0f); // Web 解析度
```

## 另請參閱

* Enum [PicturesCompression](../../../aspose.slides.export/picturescompression/)
* Class [PictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)