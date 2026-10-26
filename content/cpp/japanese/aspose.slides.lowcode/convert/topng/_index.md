---
title: ToPng()
second_title: Aspose.Slides for C++ API リファレンス
description: 入力されたプレゼンテーションを PNG 形式の画像セットに変換します。 出力ファイル名が \"myPath/myFilename.png\" の場合、結果は \"myPath/myFilename_N.png\" という形式のファイルセットとして保存されます。N はスライド番号です。
type: docs
weight: 53
url: /ja/aspose.slides.lowcode/convert/topng/
---
## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String) メソッド


入力されたプレゼンテーションを PNG 形式の画像セットに変換します。 

 出力ファイル名が "myPath/myFilename.png" と指定された場合、結果は "myPath/myFilename_N.png" という形式のファイルセットとして保存されます。N はスライド番号です。

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 入力プレゼンテーション。 |
| outputFileName | [System::String](../../../system/string/) | 出力ファイル名。 |
## 備考




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png");
```

## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String, System::Drawing::Size) メソッド


入力されたプレゼンテーションを PNG 形式の画像セットに変換します。 

 出力ファイル名が "myPath/myFilename.png" と指定された場合、結果は "myPath/myFilename_N.png" という形式のファイルセットとして保存されます。N はスライド番号です。

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName, System::Drawing::Size imageSize)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 入力プレゼンテーション |
| outputFileName | [System::String](../../../system/string/) | 出力ファイル名。 |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | 生成される各画像のサイズ。 |
## 備考




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png", System::Drawing::Size(720, 540));
```

## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String, float, System::SharedPtr\<Aspose::Slides::Export::IRenderingOptions\>) メソッド


入力されたプレゼンテーションを PNG 形式の画像セットに変換します。 

 出力ファイル名が "myPath/myFilename.png" と指定された場合、結果は "myPath/myFilename_N.png" という形式のファイルセットとして保存されます。N はスライド番号です。

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName, float scale, System::SharedPtr<Aspose::Slides::Export::IRenderingOptions> options)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 入力プレゼンテーション。 |
| outputFileName | [System::String](../../../system/string/) | 出力ファイル名。 |
| scale | **float** | 元のスライドサイズに対して出力画像に適用されるスケーリング係数です。 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | レンダリングオプションです。 |
## 備考




```cpp
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png", 2.0f, options);
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Presentation](../../../aspose.slides/presentation/)
* クラス [String](../../../system/string/)
* クラス [Convert](../)
* クラス [Size](../../../system.drawing/size/)
* クラス [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* 名前空間 [Aspose::Slides::LowCode](../../)
* ライブラリ [Aspose.Slides](../../../)