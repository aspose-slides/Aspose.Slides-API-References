---
title: Add()
second_title: Aspose.Slides for C++ API リファレンス
description: コレクションの末尾に WebVTT のクローズドキャプションを追加します。
type: docs
weight: 27
url: /ja/aspose.slides/captionscollection/add/
---
## CaptionsCollection::Add(System::String, System::String) メソッド

Adds WebVTT closed captions to the end of the collection.

```cpp
System::SharedPtr<ICaptions> Aspose::Slides::CaptionsCollection::Add(System::String label, System::String filePath) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | クローズドキャプションのラベルです。 |
| filePath | [System::String](../../../system/string/) | WebVTT ファイルへのパスです。 |

### 戻り値

追加された [ICaptions](../../icaptions/) インスタンス。

## CaptionsCollection::Add(System::String, System::SharedPtr\<System::IO::Stream\>) メソッド

Adds WebVTT closed captions to the end of the collection from a stream.

```cpp
System::SharedPtr<ICaptions> Aspose::Slides::CaptionsCollection::Add(System::String label, System::SharedPtr<System::IO::Stream> stream) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | クローズドキャプションのラベルです。 |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | WebVTT 形式のデータを含む入力ストリームです。 |

### 戻り値

追加された [ICaptions](../../icaptions/) インスタンス。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [ICaptions](../../icaptions/)
* クラス [String](../../../system/string/)
* クラス [CaptionsCollection](../)
* クラス [Stream](../../../system.io/stream/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)