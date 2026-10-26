---
title: GetPresentationInfo()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたファイルのプレゼンテーションに関する情報を取得します。
type: docs
weight: 14
url: /ja/aspose.slides/ipresentationfactory/getpresentationinfo/
---
## IPresentationFactory::GetPresentationInfo(System::String) メソッド


指定されたファイルのプレゼンテーションに関する情報を取得します。

```cpp
virtual System::SharedPtr<IPresentationInfo> Aspose::Slides::IPresentationFactory::GetPresentationInfo(System::String file)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | [Presentation](../../presentation/) ファイル。 |

### 戻り値

[Presentation](../../presentation/) 情報

## IPresentationFactory::GetPresentationInfo(System::SharedPtr\<System::IO::Stream\>) メソッド


指定されたストリームのプレゼンテーションに関する情報を取得します。

```cpp
virtual System::SharedPtr<IPresentationInfo> Aspose::Slides::IPresentationFactory::GetPresentationInfo(System::SharedPtr<System::IO::Stream> stream)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | [Presentation](../../presentation/) ストリーム。 |

### 戻り値

[Presentation](../../presentation/) 情報。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IPresentationInfo](../../ipresentationinfo/)
* クラス [String](../../../system/string/)
* クラス [IPresentationFactory](../)
* クラス [Stream](../../../system.io/stream/)
* 名前空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)