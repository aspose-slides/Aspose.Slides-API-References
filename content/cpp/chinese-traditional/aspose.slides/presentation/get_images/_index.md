---
title: get_Images()
second_title: Aspose.Slides for C++ API 參考
description: 傳回簡報中所有影像的集合。唯讀 IImageCollection.
type: docs
weight: 209
url: /zh-hant/aspose.slides/presentation/get_images/
---
## Presentation::get_Images() 方法

傳回簡報中所有影像的集合。唯讀 [IImageCollection](../../iimagecollection/)。

```cpp
System::SharedPtr<IImageCollection> Aspose::Slides::Presentation::get_Images() override
```

## 備註

以下範例說明如何在 PowerPoint 中將影像作為 BLOB 新增。[Presentation](../)
```cpp
System::String pathToLargeImage = u"large_image.jpg";
// 建立一個新簡報，將加入影像。
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto fileStream = System::MakeObject<System::IO::FileStream>(pathToLargeImage, System::IO::FileMode::Open);

// 讓我們將影像加入簡報 - 我們選擇 KeepLocked 行為，因為我們
// 不打算存取 "largeImage.png" 檔案。
auto img = pres->get_Images()->AddImage(fileStream, LoadingStreamBehavior::KeepLocked);
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 300.0f, 200.0f, img);
// 儲存簡報。雖然輸出大型簡報，記憶體使用量
// 在 pres 物件生命週期中保持低量
pres->Save(u"presentationWithLargeImage.pptx", SaveFormat::Pptx);
```
以下範例在 PowerPoint 中為影像新增超連結。[Presentation](../)
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// Adds image to presentation
auto image = pres->get_Images()->AddImage(System::IO::File::ReadAllBytes(u"image.png"));
// Creates picture frame on slide 1 based on previously added image
auto pictureFrame = slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pictureFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
pictureFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IImageCollection](../../iimagecollection/)
* 類別 [Presentation](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)