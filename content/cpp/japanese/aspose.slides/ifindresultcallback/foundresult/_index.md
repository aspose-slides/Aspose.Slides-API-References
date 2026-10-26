---
title: FoundResult()
second_title: Aspose.Slides for C++ API リファレンス
description: 見つかったテキストに関するデータを受け取るコールバックメソッド。
type: docs
weight: 1
url: /ja/aspose.slides/ifindresultcallback/foundresult/
---
## IFindResultCallback::FoundResult(System::SharedPtr\<ITextFrame\>, System::String, System::String, int32_t) メソッド

見つかったテキストに関するデータを受け取るコールバックメソッド。

```cpp
virtual void Aspose::Slides::IFindResultCallback::FoundResult(System::SharedPtr<ITextFrame> textFrame, System::String sourceText, System::String foundText, int32_t textPosition)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| textFrame | [System::SharedPtr](../../../system/sharedptr/)\<[ITextFrame](../../itextframe/)\> | テキストが見つかった[ITextFrame](../../itextframe/)。 |
| sourceText | [System::String](../../../system/string/) | テキストが見つかったソーステキスト。 |
| foundText | [System::String](../../../system/string/) | 見つかったテキスト。 |
| textPosition | **int32_t** | 見つかったテキストの位置。 |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [ITextFrame](../../itextframe/)
* クラス [String](../../../system/string/)
* クラス [IFindResultCallback](../)
* 名前空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)