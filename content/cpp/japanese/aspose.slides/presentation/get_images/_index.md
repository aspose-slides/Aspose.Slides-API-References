---
title: get_Images()
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーション内のすべての画像のコレクションを返します。読み取り専用 IImageCollection。
type: docs
weight: 209
url: /ja/aspose.slides/presentation/get_images/
---
## Presentation::get_Images() メソッド


プレゼンテーション内のすべての画像のコレクションを返します。読み取り専用 [IImageCollection](../../iimagecollection/).

```cpp
System::SharedPtr<IImageCollection> Aspose::Slides::Presentation::get_Images() override
```

## 備考


以下の例は、PowerPoint [Presentation](../) に画像を BLOB として追加する方法を示します。 
```cpp
System::String pathToLargeImage = u"large_image.jpg";
// 新しいプレゼンテーションを作成し、画像を追加します。
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto fileStream = System::MakeObject<System::IO::FileStream>(pathToLargeImage, System::IO::FileMode::Open);

// 画像をプレゼンテーションに追加します - KeepLocked 動作を選択します、なぜなら
// 「largeImage.png」ファイルにアクセスする意図がないためです。
auto img = pres->get_Images()->AddImage(fileStream, LoadingStreamBehavior::KeepLocked);
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 300.0f, 200.0f, img);
// プレゼンテーションを保存します。大きなプレゼンテーションが出力されても、メモリ使用量は
// pres オブジェクトのライフサイクルを通じて低く保たれます。
pres->Save(u"presentationWithLargeImage.pptx", SaveFormat::Pptx);
```
 以下の例は、PowerPoint [Presentation](../) の画像にハイパーリンクを追加します。 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// プレゼンテーションに画像を追加します
auto image = pres->get_Images()->AddImage(System::IO::File::ReadAllBytes(u"image.png"));
// 以前に追加した画像に基づいてスライド 1 に画像フレームを作成します
auto pictureFrame = slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pictureFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
pictureFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IImageCollection](../../iimagecollection/)
* クラス [Presentation](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)