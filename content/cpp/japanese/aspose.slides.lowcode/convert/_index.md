---
title: Convert
second_title: Aspose.Slides for C++ API リファレンス
description: Presentation を変換することを目的としたメソッドのグループを表します。
type: docs
weight: 27
url: /ja/aspose.slides.lowcode/convert/
---
## Convert クラス

[Presentation](../../aspose.slides/presentation/) を変換することを目的としたメソッドのグループを表します。

```cpp
class Convert
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| static void [AutoByExtension](./autobyextension/)([System::String](../../system/string/), [System::String](../../system/string/)) | 渡された出力パスの拡張子を使用して、必要なエクスポート形式を決定しながら [Presentation](../../aspose.slides/presentation/) を変換します。 |
|  [Convert](./convert/)() |  |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | 入力プレゼンテーションを JPEG 形式の画像セットに変換します。

 出力ファイル名が "myPath/myFilename.jpeg" の場合、結果は "myPath/myFilename_N.jpeg" という名前のファイルセットとして保存され、N はスライド番号です。 |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::Drawing::Size](../../system.drawing/size/)) | 入力プレゼンテーションを JPEG 形式の画像セットに変換します。

 出力ファイル名が "myPath/myFilename.jpeg" の場合、結果は "myPath/myFilename_N.jpeg" という名前のファイルセットとして保存され、N はスライド番号です。 |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), **float**, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) | 入力プレゼンテーションを JPEG 形式の画像セットに変換します。

 出力ファイル名が "myPath/myFilename.jpeg" の場合、結果は "myPath/myFilename_N.jpeg" という名前のファイルセットとして保存され、N はスライド番号です。 |
| static void [ToPdf](./topdf/)([System::String](../../system/string/), [System::String](../../system/string/)) | [Presentation](../../aspose.slides/presentation/) を PDF に変換します。 |
| static void [ToPdf](./topdf/)([System::String](../../system/string/), [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../aspose.slides.export/ipdfoptions/)\>) | [Presentation](../../aspose.slides/presentation/) を PDF に変換します。 |
| static void [ToPdf](./topdf/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | [Presentation](../../aspose.slides/presentation/) を PDF に変換します。 |
| static void [ToPdf](./topdf/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../aspose.slides.export/ipdfoptions/)\>) | [Presentation](../../aspose.slides/presentation/) を PDF に変換します。 |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | 入力プレゼンテーションを PNG 形式の画像セットに変換します。

 出力ファイル名が "myPath/myFilename.png" の場合、結果は "myPath/myFilename_N.png" という名前のファイルセットとして保存され、N はスライド番号です。 |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::Drawing::Size](../../system.drawing/size/)) | 入力プレゼンテーションを PNG 形式の画像セットに変換します。

 出力ファイル名が "myPath/myFilename.png" の場合、結果は "myPath/myFilename_N.png" という名前のファイルセットとして保存され、N はスライド番号です。 |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), **float**, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) | 入力プレゼンテーションを PNG 形式の画像セットに変換します。

 出力ファイル名が "myPath/myFilename.png" の場合、結果は "myPath/myFilename_N.png" という名前のファイルセットとして保存され、N はスライド番号です。 |
| static void [ToSvg](./tosvg/)([System::String](../../system/string/)) | [Presentation](../../aspose.slides/presentation/) を SVG に変換します。 |
| static void [ToSvg](./tosvg/)([System::String](../../system/string/), [Convert::GetOutPathCallback](./getoutpathcallback/)) | [Presentation](../../aspose.slides/presentation/) を SVG に変換します。 |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [Convert::GetOutPathCallback](./getoutpathcallback/)) | [Presentation](../../aspose.slides/presentation/) を SVG に変換します。 |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | [Presentation](../../aspose.slides/presentation/) を SVG に変換します。 |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [Convert::GetOutPathCallback](./getoutpathcallback/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | [Presentation](../../aspose.slides/presentation/) を SVG に変換します。 |
| static void [ToTiff](./totiff/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | 入力プレゼンテーションを TIFF 形式の画像セットに変換します。

 出力ファイル名が "myPath/myFilename.tiff" の場合、結果は "myPath/myFilename_N.tiff" という名前のファイルセットとして保存され、N はスライド番号です。 |
| static void [ToTiff](./totiff/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ITiffOptions](../../aspose.slides.export/itiffoptions/)\>, **bool**) | 入力プレゼンテーションをカスタムオプション付きの TIFF 形式に変換します。出力ファイル名が "myPath/myFilename.tiff" で *multipage* が **false** の場合、結果は "myPath/myFilename_N.tiff" という名前のファイルセットとして保存され、N はスライド番号です。*multipage* が **true** の場合、結果はマルチページの "myPath/myFilename.tiff" ドキュメントになります。 |

## 型定義

| 型定義 | 説明 |
| --- | --- |
| [GetOutPathCallback](./getoutpathcallback/) | 各 [Slide](../../aspose.slides/slide/) に対して呼び出されるコールバックで、出力パスが返されることが期待されます。 |

## 備考

```cpp
Convert::AutoByExtension(u"pres.pptx", u"pres.pdf");
```

## 参照

* 名前空間 [Aspose::Slides::LowCode](../)
* ライブラリ [Aspose.Slides](../../)