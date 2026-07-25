---
title: GetPresentationText()
second_title: Aspose.Slides for C++ API リファレンス
description: スライドから生テキストを取得します
type: docs
weight: 53
url: /ja/aspose.slides/presentationfactory/getpresentationtext/
---
## PresentationFactory::GetPresentationText(System::String, TextExtractionArrangingMode) メソッド

スライドから生テキストを取得します

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::String file, TextExtractionArrangingMode mode) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | 入力ファイル |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | 抽出モード |

### 戻り値

生スライドテキストを表す SlideText 配列を含む [PresentationText](../../presentationtext/) のインスタンス

## PresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode) メソッド

スライドから生テキストを取得します

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 入力ストリーム |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | 抽出モード |

### 戻り値

生スライドテキストを表す SlideText 配列を含む [PresentationText](../../presentationtext/) のインスタンス

## PresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode, System::SharedPtr\<ILoadOptions\>) メソッド

スライドから生テキストを取得します

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode, System::SharedPtr<ILoadOptions> options) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 入力ストリーム |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | 抽出モード |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | ロードオプション |

### 戻り値

生スライドテキストを表す SlideText 配列を含む [PresentationText](../../presentationtext/) のインスタンス

## 関連項目

* 列挙型 [TextExtractionArrangingMode](../../textextractionarrangingmode/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IPresentationText](../../ipresentationtext/)
* クラス [String](../../../system/string/)
* クラス [PresentationFactory](../)
* クラス [Stream](../../../system.io/stream/)
* クラス [ILoadOptions](../../iloadoptions/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)