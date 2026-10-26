---
title: get_SlideSize()
second_title: Aspose.Slides for C++ API リファレンス
description: スライドサイズオブジェクトを返します。Read-only ISlideSize.
type: docs
weight: 79
url: /ja/aspose.slides/presentation/get_slidesize/
---
## Presentation::get_SlideSize() メソッド

スライド サイズオブジェクトを返します。読み取り専用 [ISlideSize](../../islidesize/).

```cpp
System::SharedPtr<ISlideSize> Aspose::Slides::Presentation::get_SlideSize() override
```

## 備考

次の例は、PowerPoint [Presentation](../) でスライドサイズを変更する方法を示します。
```cpp
auto pres = System::MakeObject<Presentation>(u"pres-4x3-aspect-ratio.pptx");

pres->get_SlideSize()->SetSize(SlideSizeType::OnScreen16x9, SlideSizeScaleType::DoNotScale);
pres->Save(u"pres-4x3-aspect-ratio.pptx", SaveFormat::Pptx);
```
 次の例は、PowerPoint [Presentation](../) のコンテンツスケーリングに合わせてスライドサイズを設定する方法を示します。
```cpp
// プレゼンテーションファイルを表す Presentation オブジェクトをインスタンス化します
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");
auto auxPresentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);

// 生成されたプレゼンテーションのスライドサイズを元のものと同じに設定します
presentation->get_SlideSize()->SetSize(540.0f, 720.0f, SlideSizeScaleType::EnsureFit);

// Method SetSize は、コンテンツをスケールしてフィットさせるためにスライドサイズを設定する際に使用します
presentation->get_SlideSize()->SetSize(SlideSizeType::A4Paper, SlideSizeScaleType::Maximize);

// Method SetSize は、コンテンツのサイズを最大化してスライドサイズを設定する際に使用します
// プレゼンテーションをディスクに保存します
auxPresentation->Save(u"Set_Size_Type_out.pptx", SaveFormat::Pptx);
```
 次の例は、PowerPoint [Presentation](../) でカスタムスライドサイズを指定する方法を示します。
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
pres->get_SlideSize()->SetSize(780.0f, 540.0f, SlideSizeScaleType::DoNotScale);

// A4 用紙サイズ
pres->Save(u"pres-a4-slide-size.pptx", SaveFormat::Pptx);
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [ISlideSize](../../islidesize/)
* クラス [Presentation](../)
* 名前空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)