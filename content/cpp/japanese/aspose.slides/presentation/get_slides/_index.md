---
title: get_Slides()
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーションで定義されているすべてのスライドのリストを返します。読み取り専用 ISlideCollection.
type: docs
weight: 53
url: /ja/aspose.slides/presentation/get_slides/
---
## Presentation::get_Slides() メソッド

プレゼンテーションで定義されているすべてのスライドのリストを返します。読み取り専用 [ISlideCollection](../../islidecollection/)。

```cpp
System::SharedPtr<ISlideCollection> Aspose::Slides::Presentation::get_Slides() override
```

## 備考

次の例は、PowerPoint のスライドの背景色を設定する方法を示しています [Presentation](../)。 
```cpp
// プレゼンテーション ファイルを表す Presentation クラスのインスタンスを作成します
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// Set the background color of the first ISlide to Blue
slide->get_Background()->set_Type(BackgroundType::OwnBackground);
slide->get_Background()->get_FillFormat()->set_FillType(FillType::Solid);
slide->get_Background()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Blue());
pres->Save(u"ContentBG_out.pptx", SaveFormat::Pptx);
```
次の例は、PowerPoint のスライドの背景画像を設定する方法を示しています [Presentation](../)。 
```cpp
// プレゼンテーション ファイルを表す Presentation クラスのインスタンスを作成します
auto pres = System::MakeObject<Presentation>(u"SetImageAsBackground.pptx");
auto slide = pres->get_Slides()->idx_get(0);

// 画像で背景を設定します
slide->get_Background()->set_Type(BackgroundType::OwnBackground);
slide->get_Background()->get_FillFormat()->set_FillType(FillType::Picture);
slide->get_Background()->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);
// 画像を設定します
auto img = System::ExplicitCast<System::Drawing::Image>(System::MakeObject<System::Drawing::Bitmap>(dataDir + u"Tulips.jpg"));
// プレゼンテーションの画像コレクションに画像を追加します
auto imgx = pres->get_Images()->AddImage(img);
slide->get_Background()->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(imgx);
// プレゼンテーションを書き出します
pres->Save(u"ContentBG_Img_out.pptx", SaveFormat::Pptx);
```
次の例は、スライド遷移を追加する方法を示しています [Presentation](../)。 
```cpp
// ソース プレゼンテーション ファイルを読み込むために Presentation クラスのインスタンスを作成します
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");

// スライド 1 に円形遷移を適用します
presentation->get_Slides()->idx_get(0)->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Circle);
// スライド 2 にコーム形状遷移を適用します
presentation->get_Slides()->idx_get(1)->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Comb);
// プレゼンテーションを書き出します
presentation->Save(u"SampleTransition_out.pptx", SaveFormat::Pptx);
```
次の例は、高度なスライド遷移を追加する方法を示しています。 
```cpp
// プレゼンテーション ファイルを表す Presentation クラスのインスタンスを作成します
auto pres = System::MakeObject<Presentation>(u"BetterSlideTransitions.pptx");

auto slide1 = pres->get_Slides()->idx_get(0);
auto slide2 = pres->get_Slides()->idx_get(1);
auto slide3 = pres->get_Slides()->idx_get(2);

// スライド 1 に円形遷移を適用します
slide1->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Circle);
// 遷移時間を 3 秒に設定します
slide1->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide1->get_SlideShowTransition()->set_AdvanceAfterTime(3000);
// スライド 2 にコーム形状遷移を適用します
slide2->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Comb);
// 遷移時間を 5 秒に設定します
slide2->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide2->get_SlideShowTransition()->set_AdvanceAfterTime(5000);
// スライド 3 にズーム遷移を適用します
slide3->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Zoom);
// 遷移時間を 7 秒に設定します
slide3->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide3->get_SlideShowTransition()->set_AdvanceAfterTime(7000);
// プレゼンテーションを書き出します
pres->Save(u"SampleTransition_out.pptx", SaveFormat::Pptx);
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [ISlideCollection](../../islidecollection/)
* クラス [Presentation](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)