---
title: ReplaceImage()
second_title: Aspose.Slides for C++ API 参考
description: 替换图像数据。
type: docs
weight: 118
url: /zh/aspose.slides/ppimage/replaceimage/
---
## PPImage::ReplaceImage(System::ArrayPtr\<uint8_t\>) 方法

替换图像数据。

```cpp
void Aspose::Slides::PPImage::ReplaceImage(System::ArrayPtr<uint8_t> newImageData) override
```

## PPImage::ReplaceImage(System::SharedPtr\<Aspose::Slides::IImage\>) 方法

替换图像数据。注意：当 Image 为元文件时，它将被光栅化。请使用 ReplaceImage(byte[]) 代替

```cpp
void Aspose::Slides::PPImage::ReplaceImage(System::SharedPtr<Aspose::Slides::IImage> newImage) override
```

## PPImage::ReplaceImage(System::SharedPtr\<Aspose::Slides::IPPImage\>) 方法

替换图像数据。

```cpp
void Aspose::Slides::PPImage::ReplaceImage(System::SharedPtr<Aspose::Slides::IPPImage> newImage) override
```

## 另见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [PPImage](../)
* 类 [IImage](../../iimage/)
* 类 [IPPImage](../../ippimage/)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)