---
title: get_SlideSize()
second_title: Aspose.Slides for C++ API 參考
description: 傳回投影片尺寸物件。唯讀 ISlideSize.
type: docs
weight: 79
url: /zh-hant/aspose.slides/presentation/get_slidesize/
---
## Presentation::get_SlideSize() 方法

傳回投影片尺寸物件。唯讀 [ISlideSize](../../islidesize/)。

```cpp
System::SharedPtr<ISlideSize> Aspose::Slides::Presentation::get_SlideSize() override
```

## 備註

以下範例說明如何在 PowerPoint [Presentation](../) 中變更投影片尺寸。
```cpp
auto pres = System::MakeObject<Presentation>(u"pres-4x3-aspect-ratio.pptx");

pres->get_SlideSize()->SetSize(SlideSizeType::OnScreen16x9, SlideSizeScaleType::DoNotScale);
pres->Save(u"pres-4x3-aspect-ratio.pptx", SaveFormat::Pptx);
```
以下範例說明如何在 PowerPoint [Presentation](../) 中依內容縮放設定投影片尺寸。
```cpp
// 實例化一個代表簡報檔的 Presentation 物件
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");
auto auxPresentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);

// 將產生的簡報投影片尺寸設定為來源的尺寸
presentation->get_SlideSize()->SetSize(540.0f, 720.0f, SlideSizeScaleType::EnsureFit);

// SetSize 方法用於設定投影片尺寸，並縮放內容以確保適合
presentation->get_SlideSize()->SetSize(SlideSizeType::A4Paper, SlideSizeScaleType::Maximize);

// SetSize 方法用於設定投影片尺寸，並將內容大小最大化
// 將簡報儲存至磁碟
auxPresentation->Save(u"Set_Size_Type_out.pptx", SaveFormat::Pptx);
```
以下範例說明如何在 PowerPoint [Presentation](../) 中指定自訂投影片尺寸。
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
pres->get_SlideSize()->SetSize(780.0f, 540.0f, SlideSizeScaleType::DoNotScale);

// A4 紙張尺寸
pres->Save(u"pres-a4-slide-size.pptx", SaveFormat::Pptx);
```

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [ISlideSize](../../islidesize/)
* 類別 [Presentation](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)