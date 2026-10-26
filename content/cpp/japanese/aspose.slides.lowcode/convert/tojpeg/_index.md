---
title: ToJpeg()
second_title: Aspose.Slides for C++ API リファレンス
description: 入力プレゼンテーションを JPEG 形式の画像セットに変換します。 出力ファイル名が \"myPath/myFilename.jpeg\" と指定された場合、結果は \"myPath/myFilename_N.jpeg\" という名前のファイルセットとして保存されます。ここで N はスライド番号です。
type: docs
weight: 40
url: /ja/aspose.slides.lowcode/convert/tojpeg/
---
## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String) メソッド

入力プレゼンテーションを JPEG 形式の画像セットに変換します。

出力ファイル名が "myPath/myFilename.jpeg" と指定された場合、結果は "myPath/myFilename_N.jpeg" という名前のファイルセットとして保存されます。ここで N はスライド番号です。

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 入力プレゼンテーション。 |
| outputFileName | [System::String](../../../system/string/) | 出力ファイル名。 |
## 備考

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg");
```

## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String, System::Drawing::Size) メソッド

入力プレゼンテーションを JPEG 形式の画像セットに変換します。

出力ファイル名が "myPath/myFilename.jpeg" と指定された場合、結果は "myPath/myFilename_N.jpeg" という名前のファイルセットとして保存されます。ここで N はスライド番号です。

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName, System::Drawing::Size imageSize)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 入力プレゼンテーション |
| outputFileName | [System::String](../../../system/string/) | 出力ファイル名。 |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | 生成される各画像のサイズ。 |
## 備考

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg", System::Drawing::Size(720, 540));
```

## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String, float, System::SharedPtr\<Aspose::Slides::Export::IRenderingOptions\>) メソッド

入力プレゼンテーションを JPEG 形式の画像セットに変換します。

出力ファイル名が "myPath/myFilename.jpeg" と指定された場合、結果は "myPath/myFilename_N.jpeg" という名前のファイルセットとして保存されます。ここで N はスライド番号です。

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName, float scale, System::SharedPtr<Aspose::Slides::Export::IRenderingOptions> options)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 入力プレゼンテーション。 |
| outputFileName | [System::String](../../../system/string/) | 出力ファイル名。 |
| scale | **float** | 元のスライドサイズに対する出力画像のスケーリング係数。 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | レンダリング オプション。 |
## 備考

```cpp
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg", 2.0f, options);
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