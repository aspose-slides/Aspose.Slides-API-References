---
title: get_Images()
second_title: Aspose.Slides C++ API 参考
description: 返回演示文稿中所有图像的集合。只读 IImageCollection.
type: docs
weight: 209
url: /zh/aspose.slides/presentation/get_images/
---
## Presentation::get_Images() 方法

返回演示文稿中所有图像的集合。只读 [IImageCollection](../../iimagecollection/)。

```cpp
System::SharedPtr<IImageCollection> Aspose::Slides::Presentation::get_Images() override
```

## 备注

以下示例展示了如何在 PowerPoint 中将图像添加为 BLOB [Presentation](../)。
```cpp
System::String pathToLargeImage = u"large_image.jpg";
// 创建一个新的演示文稿，将向其添加图像。
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto fileStream = System::MakeObject<System::IO::FileStream>(pathToLargeImage, System::IO::FileMode::Open);

// 让我们将图像添加到演示文稿中 - 我们选择 KeepLocked 行为，因为我们
// 不打算访问 "largeImage.png" 文件。
auto img = pres->get_Images()->AddImage(fileStream, LoadingStreamBehavior::KeepLocked);
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 300.0f, 200.0f, img);
// 保存演示文稿。虽然输出的是大型演示文稿，但在 pres 对象的生命周期内
// 内存消耗保持较低
pres->Save(u"presentationWithLargeImage.pptx", SaveFormat::Pptx);
```
以下示例向 PowerPoint 中的图像添加超链接 [Presentation](../)。
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// 将图像添加到演示文稿
auto image = pres->get_Images()->AddImage(System::IO::File::ReadAllBytes(u"image.png"));
// 在第 1 张幻灯片上创建图片框，基于之前添加的图像
auto pictureFrame = slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pictureFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
pictureFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IImageCollection](../../iimagecollection/)
* 类 [Presentation](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)