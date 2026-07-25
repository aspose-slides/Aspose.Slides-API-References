---
title: WriteFont()
second_title: Aspose.Slides for C++ API リファレンス
description: データを base64 で HTML ドキュメント自体に書き込みます
type: docs
weight: 105
url: /ja/aspose.slides.export/embedallfontshtmlcontroller/writefont/
---
## EmbedAllFontsHtmlController::WriteFont(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IFontData\>, System::SharedPtr\<IFontData\>, System::String, System::String, System::ArrayPtr\<uint8_t\>) メソッド


HTML ドキュメント自体にデータを base64 エンコードで書き込みます

```cpp
virtual void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteFont(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IFontData> originalFont, System::SharedPtr<IFontData> substitutedFont, System::String fontStyle, System::String fontWeight, System::ArrayPtr<uint8_t> fontData)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | HTML ジェネレーター |
| originalFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../../aspose.slides/ifontdata/)\> | シリアライズされるフォント |
| substitutedFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../../aspose.slides/ifontdata/)\> | 置換されたフォント (フォント置換が発生した場合)、それ以外は null |
| fontStyle | [System::String](../../../system/string/) | フォントスタイル |
| fontWeight | [System::String](../../../system/string/) | フォントウェイト |
| fontData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | フォントデータ |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [IHtmlGenerator](../../ihtmlgenerator/)
* クラス [IFontData](../../../aspose.slides/ifontdata/)
* クラス [String](../../../system/string/)
* クラス [EmbedAllFontsHtmlController](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)