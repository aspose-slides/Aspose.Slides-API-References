---
title: GetImage()
second_title: Aspose.Slides for C++ API リファレンス
description: カスタムスケーリングでサムネイル画像オブジェクトを返します。
type: docs
weight: 144
url: /ja/aspose.slides/slide/getimage/
---
## Slide::GetImage(float, float) メソッド

カスタムスケーリングで Thumbnail Image オブジェクトを返します。

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(float scaleX, float scaleY) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| scaleX | **float** | x 軸方向にこの Thumbnail を拡大縮小する値。 |
| scaleY | **float** | y 軸方向にこの Thumbnail を拡大縮小する値。 |

### 戻り値

[IImage](../../iimage/) オブジェクト。

## 備考

次の例は PowerPoint [Presentation](../../presentation/) からサムネイルを生成する方法を示しています:  
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"ThumbnailFromSlide.pptx");

// Access the first slide
System::SharedPtr<ISlide> sld = pres->get_Slide(0);
// Create a full scale image
System::SharedPtr<IImage> bmp = sld->GetImage(1.0f, 1.0f);
// Save the image to disk in JPEG format
bmp->Save(u"Thumbnail_out.jpg", Aspose::Slides::ImageFormat::Jpeg);
```

次の例はスライドをビットマップに変換し、画像を PNG で保存する方法を示しています:  
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// プレゼンテーションの最初のスライドを Bitmap オブジェクトに変換します
System::SharedPtr<IImage> bmp = pres->get_Slide(0)->GetImage();
// 画像を PNG 形式で保存します
bmp->Save(u"Slide_0.png", Aspose::Slides::ImageFormat::Png);
```

次の例は PowerPoint PPT/PPTX を JPG に変換する方法を示しています:  
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PowerPoint-Presentation.ppt");

for (auto&& sld : pres->get_Slides())
{
    // フルスケールの画像を作成する
    System::SharedPtr<IImage> bmp = sld->GetImage(1.0f, 1.0f);
    // 画像を JPEG 形式でディスクに保存する
    bmp->Save(System::String::Format(u"Slide_{0}.jpg", sld->get_SlideNumber()), Aspose::Slides::ImageFormat::Jpeg);
}
```

次の例はカスタマイズされたサイズで PowerPoint PPT/PPTX を JPG に変換する方法を示しています:  
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PowerPoint-Presentation.pptx");

// 寸法を定義する
int32_t desiredX = 1200;
int32_t desiredY = 800;
// X と Y のスケール済み値を取得する
float scaleX = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Width()) * desiredX;
float scaleY = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Height()) * desiredY;

for (auto&& sld : pres->get_Slides())
{
    // フルスケールの画像を作成する
    System::SharedPtr<IImage> bmp = sld->GetImage(scaleX, scaleY);
    // 画像を JPEG 形式でディスクに保存する
    bmp->Save(System::String::Format(u"Slide_{0}.jpg", sld->get_SlideNumber()), Aspose::Slides::ImageFormat::Jpeg);
}
```

## Slide::GetImage() メソッド

実際のサイズの 20% の Thumbnail Image オブジェクトを返します。

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage() override
```

## Slide::GetImage(System::Drawing::Size) メソッド

指定されたサイズの Thumbnail Image オブジェクトを返します。

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::Drawing::Size imageSize) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | 作成する画像のサイズ。 |

### 戻り値

Image オブジェクト。

## 備考

次の例は C# を使用してカスタムサイズでスライドを画像に変換する方法を示しています。  
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// プレゼンテーションの最初のスライドを指定されたサイズのビットマップに変換します
System::SharedPtr<IImage> bmp = pres->get_Slide(0)->GetImage(System::Drawing::Size(1820, 1040));

// 画像を JPEG 形式で保存します
bmp->Save(u"Slide_0.jpg", Aspose::Slides::ImageFormat::Jpeg);
```

## Slide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) メソッド

指定されたパラメータで Thumbnail tiff 画像オブジェクトを返します。

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::ITiffOptions> options) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Tiff オプション。 |

### 戻り値

Image オブジェクト。

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) メソッド

Thumbnail Image オブジェクトを返します。

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | レンダリングオプション。 |

### 戻り値

Image オブジェクト。

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) メソッド

カスタムスケーリングで Thumbnail Image オブジェクトを返します。

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | レンダリングオプション。 |
| scaleX | **float** | x 軸方向にこの Thumbnail を拡大縮小する値。 |
| scaleY | **float** | y 軸方向にこの Thumbnail を拡大縮小する値。 |

### 戻り値

Bitmap オブジェクト。

## 備考

次の例は C# を使用してノートとコメント付きのスライドを [Images](../../images/) に変換する方法を示しています。  
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PresentationNotesComments.pptx");

// レンダリングオプションを作成する
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
// ノートとコメントのレイアウトオプションを作成する
System::SharedPtr<NotesCommentsLayoutingOptions> notesCommentsLayouting = System::MakeObject<NotesCommentsLayoutingOptions>();
// ページ上のノートの位置を設定する
notesCommentsLayouting->set_NotesPosition(NotesPositions::BottomTruncated);
// ページ上のコメントの位置を設定する
notesCommentsLayouting->set_CommentsPosition(CommentsPositions::Right);
// コメント出力領域の幅を設定する
notesCommentsLayouting->set_CommentsAreaWidth(500);
// コメント領域の色を設定する
notesCommentsLayouting->set_CommentsAreaColor(System::Drawing::Color::get_AntiqueWhite());
// レンダリング用のレイアウトオプションを設定する
options->set_SlidesLayoutOptions(notesCommentsLayouting);
// プレゼンテーションの最初のスライドを IImage オブジェクトに変換する
System::SharedPtr<IImage> image = pres->get_Slide(0)->GetImage(options, 2.0f, 2.0f);
// 画像を GIF 形式で保存する
image->Save(u"Slide_Notes_Comments_0.gif", ImageFormat::Gif);
```

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) メソッド

指定されたサイズの Thumbnail Image オブジェクトを返します。

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | レンダリングオプション。 |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | 作成する画像のサイズ。 |

### 戻り値

Image オブジェクト。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IImage](../../iimage/)
* クラス [Slide](../)
* クラス [Size](../../../system.drawing/size/)
* クラス [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* クラス [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)