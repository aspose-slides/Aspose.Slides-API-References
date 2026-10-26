---
title: ToTiff()
second_title: Aspose.Slides for C++ API リファレンス
description: 入力プレゼンテーションを TIFF 形式の画像セットに変換します。出力ファイル名を \"myPath/myFilename.tiff\" と指定した場合、結果は \"myPath/myFilename_N.tiff\" ファイルのセットとして保存されます。ここで N はスライド番号です。
type: docs
weight: 66
url: /ja/aspose.slides.lowcode/convert/totiff/
---
## Convert::ToTiff(System::SharedPtr\<Presentation\>, System::String) メソッド


入力プレゼンテーションを TIFF 形式の画像セットに変換します。 

 出力ファイル名を \"myPath/myFilename.tiff\" と指定した場合、結果は \"myPath/myFilename_N.tiff\" ファイルのセットとして保存されます。ここで N はスライド番号です。

```cpp
static void Aspose::Slides::LowCode::Convert::ToTiff(System::SharedPtr<Presentation> pres, System::String outputFileName)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 入力プレゼンテーション。 |
| outputFileName | [System::String](../../../system/string/) | 出力ファイル名。 |
## 備考




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToTiff(pres, u"presImage.tiff");
```

## Convert::ToTiff(System::SharedPtr\<Presentation\>, System::String, System::SharedPtr\<Aspose::Slides::Export::ITiffOptions\>, bool) メソッド


入力プレゼンテーションをカスタム オプションで TIFF 形式に変換します。出力ファイル名を \"myPath/myFilename.tiff\" と指定し、*multipage* が **false** の場合、結果は \"myPath/myFilename_N.tiff\" ファイルのセットとして保存されます。*multipage* が **true** の場合、結果はマルチページの \"myPath/myFilename.tiff\" ドキュメントになります。

```cpp
static void Aspose::Slides::LowCode::Convert::ToTiff(System::SharedPtr<Presentation> pres, System::String outputFileName, System::SharedPtr<Aspose::Slides::Export::ITiffOptions> options, bool multipage)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 入力プレゼンテーション。 |
| outputFileName | [System::String](../../../system/string/) | 出力ファイル名。 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | TIFF 保存オプション。 |
| multipage | **bool** | 生成された TIFF ドキュメントがマルチページであるかどうかを指定します。 |
## 備考 




```cpp
System::SharedPtr<ITiffOptions> options = System::MakeObject<TiffOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);
options->set_CompressionType(TiffCompressionTypes::CCITT3);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToTiff(pres, u"pres.tiff", options, false);
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Presentation](../../../aspose.slides/presentation/)
* Class [String](../../../system/string/)
* Class [Convert](../)
* Class [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)