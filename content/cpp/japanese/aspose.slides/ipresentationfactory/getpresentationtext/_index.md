---
title: GetPresentationText()
second_title: Aspose.Slides for C++ API リファレンス
description: スライドから生テキストを取得します
type: docs
weight: 40
url: /ja/aspose.slides/ipresentationfactory/getpresentationtext/
---
## IPresentationFactory::GetPresentationText(System::String, TextExtractionArrangingMode) method


スライドから生テキストを取得します

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::String file, TextExtractionArrangingMode mode)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | 入力ファイル |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | 抽出モード |

### 戻り値

[PresentationText](../../presentationtext/) のインスタンスで、スライドテキスト配列として生スライドテキストを表します

## IPresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode) method


スライドから生テキストを取得します

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 入力ストリーム |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | 抽出モード |

### 戻り値

[PresentationText](../../presentationtext/) のインスタンスで、スライドテキスト配列として生スライドテキストを表します

## IPresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode, System::SharedPtr\<ILoadOptions\>) method


スライドから生テキストを取得します

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode, System::SharedPtr<ILoadOptions> options)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 入力ストリーム |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | 抽出モード |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | ロードオプション |

### 戻り値

[PresentationText](../../presentationtext/) のインスタンスで、スライドテキスト配列として生スライドテキストを表します

## 参照

* 列挙体 [TextExtractionArrangingMode](../../textextractionarrangingmode/)
* タイプ定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IPresentationText](../../ipresentationtext/)
* クラス [String](../../../system/string/)
* クラス [IPresentationFactory](../)
* クラス [Stream](../../../system.io/stream/)
* クラス [ILoadOptions](../../iloadoptions/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)