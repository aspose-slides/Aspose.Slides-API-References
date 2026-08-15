---
title: get_Slides()
second_title: Aspose.Slides C++ API 參考
description: 傳回在簡報中定義的所有投影片的清單。唯讀 ISlideCollection.
type: docs
weight: 53
url: /zh-hant/aspose.slides/presentation/get_slides/
---
## Presentation::get_Slides() 方法

傳回在簡報中定義的所有投影片的清單。唯讀 [ISlideCollection](../../islidecollection/)。

```cpp
System::SharedPtr<ISlideCollection> Aspose::Slides::Presentation::get_Slides() override
```

## 備註

以下範例示範如何設定 PowerPoint 投影片的背景顏色 [Presentation](../)。 
```cpp
// 實例化代表簡報檔案的 Presentation 類別
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// Set the background color of the first ISlide to Blue
slide->get_Background()->set_Type(BackgroundType::OwnBackground);
slide->get_Background()->get_FillFormat()->set_FillType(FillType::Solid);
slide->get_Background()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Blue());
pres->Save(u"ContentBG_out.pptx", SaveFormat::Pptx);
```
以下範例示範如何設定 PowerPoint 投影片的背景圖像 [Presentation](../)。 
```cpp
// 實例化代表簡報檔案的 Presentation 類別
auto pres = System::MakeObject<Presentation>(u"SetImageAsBackground.pptx");
auto slide = pres->get_Slides()->idx_get(0);

// 使用圖像設定背景
slide->get_Background()->set_Type(BackgroundType::OwnBackground);
slide->get_Background()->get_FillFormat()->set_FillType(FillType::Picture);
slide->get_Background()->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);
// 設定圖片
auto img = System::ExplicitCast<System::Drawing::Image>(System::MakeObject<System::Drawing::Bitmap>(dataDir + u"Tulips.jpg"));
// 將圖像加入簡報的圖片集合
auto imgx = pres->get_Images()->AddImage(img);
slide->get_Background()->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(imgx);
// 將簡報寫入磁碟
pres->Save(u"ContentBG_Img_out.pptx", SaveFormat::Pptx);
```
以下範例示範如何新增投影片轉場效果 [Presentation](../)。 
```cpp
// 實例化 Presentation 類別以載入來源簡報檔案
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");

// 在第 1 張投影片套用圓形類型的轉場
presentation->get_Slides()->idx_get(0)->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Circle);
// 在第 2 張投影片套用梳狀類型的轉場
presentation->get_Slides()->idx_get(1)->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Comb);
// 將簡報寫入磁碟
presentation->Save(u"SampleTransition_out.pptx", SaveFormat::Pptx);
```
以下範例示範如何新增進階投影片轉場效果 ```cpp
// 實例化代表簡報檔案的 Presentation 類別
auto pres = System::MakeObject<Presentation>(u"BetterSlideTransitions.pptx");

auto slide1 = pres->get_Slides()->idx_get(0);
auto slide2 = pres->get_Slides()->idx_get(1);
auto slide3 = pres->get_Slides()->idx_get(2);

// 在第 1 張投影片套用圓形類型的轉場
slide1->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Circle);
// 設定 3 秒的轉場時間
slide1->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide1->get_SlideShowTransition()->set_AdvanceAfterTime(3000);
// 在第 2 張投影片套用梳狀類型的轉場
slide2->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Comb);
// 設定 5 秒的轉場時間
slide2->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide2->get_SlideShowTransition()->set_AdvanceAfterTime(5000);
// 在第 3 張投影片套用縮放類型的轉場
slide3->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Zoom);
// 設定 7 秒的轉場時間
slide3->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide3->get_SlideShowTransition()->set_AdvanceAfterTime(7000);
// 將簡報寫入磁碟
pres->Save(u"SampleTransition_out.pptx", SaveFormat::Pptx);
```。

## 另請參閱

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [ISlideCollection](../../islidecollection/)
* 類別 [Presentation](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)