---
title: GetPresentationInfo()
second_title: C++ 用 Aspose.Slides API リファレンス
description: ファイルから新しい PresentationInfo オブジェクトを作成し、プレゼンテーションにバインドします。
type: docs
weight: 27
url: /ja/aspose.slides/presentationfactory/getpresentationinfo/
---
## PresentationFactory::GetPresentationInfo(System::String) method


ファイルから新しい[PresentationInfo](../../presentationinfo/)オブジェクトを作成し、プレゼンテーションにバインドします。

```cpp
System::SharedPtr<IPresentationInfo> Aspose::Slides::PresentationFactory::GetPresentationInfo(System::String file) override
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | [Presentation](../../presentation/) ファイル。 |

### 戻り値

[Presentation](../../presentation/) 情報がプレゼンテーションにバインドされます。

## PresentationFactory::GetPresentationInfo(System::SharedPtr\<System::IO::Stream\>) method


ストリームから新しい[PresentationInfo](../../presentationinfo/)オブジェクトを作成し、プレゼンテーションにバインドします。指定されたストリーム内のプレゼンテーションに関する情報を取得します。

```cpp
System::SharedPtr<IPresentationInfo> Aspose::Slides::PresentationFactory::GetPresentationInfo(System::SharedPtr<System::IO::Stream> stream) override
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | [Presentation](../../presentation/) ストリーム。 |

### 戻り値

[Presentation](../../presentation/) 情報がプレゼンテーションにバインドされます。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IPresentationInfo](../../ipresentationinfo/)
* クラス [String](../../../system/string/)
* クラス [PresentationFactory](../)
* クラス [Stream](../../../system.io/stream/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)