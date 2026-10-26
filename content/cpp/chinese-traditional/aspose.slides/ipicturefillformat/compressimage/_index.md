---
title: CompressImage()
second_title: Aspose.Slides C++ API 參考
description: 根據形狀大小和指定的解析度縮減圖像大小以壓縮圖像。可選地，它還會刪除裁剪區域。
type: docs
weight: 443
url: /zh-hant/aspose.slides/ipicturefillformat/compressimage/
---
## IPictureFillFormat::CompressImage(bool, Export::PicturesCompression) 方法

壓縮圖像，根據形狀大小和指定的解析度減少其尺寸。可選地，它還會刪除裁剪區域。

```cpp
virtual bool Aspose::Slides::IPictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, Export::PicturesCompression resolution)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | 如果為 true，該方法將移除圖像的裁剪區域，可能會進一步減小其大小。 |
| resolution | [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) | 壓縮的目標解析度，以 [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) 列舉的值指定。 |

### 傳回值

一個 **bool**，指示圖像是否成功壓縮。返回 ****true****

## 備註

此方法會變更圖像的大小和解析度，類似於 PowerPoint 的「Picture Format -> Compress Pictures」功能。

如果圖像已重新調整大小或裁剪，否則返回 ****false****

. 

以下範例示範如何使用 **CompressImage** 方法，透過設定目標解析度與移除裁剪區域，來減少簡報中圖像的大小：
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));
// 壓縮圖像，目標解析度為 150 DPI（網路解析度），並移除裁剪區域
bool result = picFrame->get_PictureFormat()->CompressImage(true, PicturesCompression::Dpi150);
```

## IPictureFillFormat::CompressImage(bool, float) 方法

壓縮圖像，根據形狀大小和指定的解析度減少其尺寸。可選地，它還會刪除裁剪區域。

```cpp
virtual bool Aspose::Slides::IPictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, float resolution)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | 如果為 true，該方法將移除圖像的裁剪區域，可能會進一步減小其大小。 |
| resolution | **float** | 目標解析度，以 DPI 為單位。此值必須為正，並定義圖像將如何重新調整大小。 |

### 傳回值

一個 **bool**，指示圖像是否成功壓縮。返回 ****true****

## 備註

此方法會變更圖像的大小和解析度，類似於 PowerPoint 的「Picture Format -> Compress Pictures」功能。

如果圖像已重新調整大小或裁剪，否則返回 ****false****

. 

以下範例示範如何使用 **CompressImage** 方法，透過設定目標解析度與移除裁剪區域，來減少簡報中圖像的大小：
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 取得 PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// 壓縮圖像，目標解析度為 150 DPI（Web 解析度），並移除裁剪區域
bool result = picFrame->get_PictureFormat()->CompressImage(true, 150.0f); // Web 解析度
```

## 另請參閱

* 列舉 [PicturesCompression](../../../aspose.slides.export/picturescompression/)
* 類別 [IPictureFillFormat](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)