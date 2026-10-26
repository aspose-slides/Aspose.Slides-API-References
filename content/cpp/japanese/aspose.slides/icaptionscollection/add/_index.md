---
title: Add()
second_title: Aspose.Slides for C++ API リファレンス
description: コレクションの末尾に WebVTT クローズドキャプションを追加します。
type: docs
weight: 27
url: /ja/aspose.slides/icaptionscollection/add/
---
## ICaptionsCollection::Add(System::String, System::String) メソッド

コレクションの末尾に WebVTT クローズドキャプションを追加します。

```cpp
virtual System::SharedPtr<ICaptions> Aspose::Slides::ICaptionsCollection::Add(System::String label, System::String filePath)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | クローズドキャプションのラベル。 |
| filePath | [System::String](../../../system/string/) | WebVTT ファイルへのパス。 |

### 戻り値

追加された [ICaptions](../../icaptions/) インスタンス。

## ICaptionsCollection::Add(System::String, System::SharedPtr\<System::IO::Stream\>) メソッド

ストリームからコレクションの末尾に WebVTT クローズドキャプションを追加します。

```cpp
virtual System::SharedPtr<ICaptions> Aspose::Slides::ICaptionsCollection::Add(System::String label, System::SharedPtr<System::IO::Stream> stream)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | クローズドキャプションのラベル。 |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | WebVTT 形式のデータを含む入力ストリーム。 |

### 戻り値

追加された [ICaptions](../../icaptions/) インスタンス。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [ICaptions](../../icaptions/)
* クラス [String](../../../system/string/)
* クラス [ICaptionsCollection](../)
* クラス [Stream](../../../system.io/stream/)
* 名前空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)