---
title: TryParse()
second_title: Aspose.Slides for C++ API リファレンス
description: 渡された文字列を ContentDispositionHeaderValue クラスのインスタンスに変換しようとします。
type: docs
weight: 287
url: /ja/system.net.http.headers/contentdispositionheadervalue/tryparse/
---
## ContentDispositionHeaderValue::TryParse(String, System::SharedPtr\<ContentDispositionHeaderValue\>\&) メソッド

渡された文字列を[ContentDispositionHeaderValue](../)クラスのインスタンスに変換しようとします。

```cpp
static bool System::Net::Http::Headers::ContentDispositionHeaderValue::TryParse(String input, System::SharedPtr<ContentDispositionHeaderValue> &parsedValue)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 解析する文字列。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[ContentDispositionHeaderValue](../)\>\& | 解析されたオブジェクトが割り当てられるインスタンス。 |

### 戻り値

解析が正常に完了した場合は true、そうでない場合は false が返されます。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [ContentDispositionHeaderValue](../)
* 名前空間 [System::Net::Http::Headers](../../)
* ライブラリ [Aspose.Slides](../../../)