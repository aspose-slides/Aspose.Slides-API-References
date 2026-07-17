---
title: CompressImage()
second_title: Aspose.Slides C++ API 参考
description: 根据形状大小和指定的分辨率通过减小图像尺寸来压缩图像。可选地，它还会删除裁剪区域。
type: docs
weight: 443
url: /zh/aspose.slides/picturefillformat/compressimage/
---
## PictureFillFormat::CompressImage(bool, Export::PicturesCompression) 方法

根据形状大小和指定的分辨率压缩图像以减小其尺寸。可选地，它还会删除裁剪区域。

```cpp
bool Aspose::Slides::PictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, Export::PicturesCompression resolution) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | 如果为 true，方法将删除图像的裁剪区域，可能进一步减小其尺寸。 |
| resolution | [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) | 压缩的目标分辨率，以 [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) 枚举的值指定。 |

### 返回值

一个 **bool**，指示图像是否成功压缩。返回 ****true****

## 备注

此方法会更改图像的尺寸和分辨率，类似于 PowerPoint 的 “Picture Format -> Compress Pictures” 功能。

如果图像已被调整大小或裁剪，则为 ****true****，否则为 ****false****

. 

下面的示例演示了如何使用 **CompressImage** 方法通过设置目标分辨率并删除裁剪区域来减小演示文稿中图像的大小： 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));
// 使用目标分辨率 150 DPI（网页分辨率）压缩图像并删除裁剪区域
bool result = picFrame->get_PictureFormat()->CompressImage(true, PicturesCompression::Dpi150);
```

## PictureFillFormat::CompressImage(bool, float) 方法

根据形状大小和指定的分辨率压缩图像以减小其尺寸。可选地，它还会删除裁剪区域。

```cpp
bool Aspose::Slides::PictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, float resolution) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | 如果为 true，方法将删除图像的裁剪区域，可能进一步减小其尺寸。 |
| resolution | **float** | 目标分辨率（单位 DPI）。该值必须为正数，并定义图像的调整大小方式。 |

### 返回值

一个 **bool**，指示图像是否成功压缩。返回 ****true****

## 备注

此方法会更改图像的尺寸和分辨率，类似于 PowerPoint 的 “Picture Format -> Compress Pictures” 功能。

如果图像已被调整大小或裁剪，则为 ****true****，否则为 ****false****

. 

下面的示例演示了如何使用 **CompressImage** 方法通过设置目标分辨率并删除裁剪区域来减小演示文稿中图像的大小： 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 获取 PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// 使用目标分辨率 150 DPI（网页分辨率）压缩图像并删除裁剪区域
bool result = picFrame->get_PictureFormat()->CompressImage(true, 150.0f); // 网页分辨率
```

## 另请参见

* 枚举 [PicturesCompression](../../../aspose.slides.export/picturescompression/)
* 类 [PictureFillFormat](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)