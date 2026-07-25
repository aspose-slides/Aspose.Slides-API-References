---
title: TryParse()
second_title: Aspose.Slides for C++ APIリファレンス
description: 渡された文字列を ViaHeaderValue クラスのインスタンスに変換しようとします。
type: docs
weight: 118
url: /ja/system.net.http.headers/viaheadervalue/tryparse/
---
## ViaHeaderValue::TryParse(String, System::SharedPtr\<ViaHeaderValue\>\&) メソッド


渡された文字列を [ViaHeaderValue](../) クラスのインスタンスに変換しようとします。

```cpp
static bool System::Net::Http::Headers::ViaHeaderValue::TryParse(String input, System::SharedPtr<ViaHeaderValue> &parsedValue)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | 解析対象の文字列。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[ViaHeaderValue](../)\>\& | 解析されたオブジェクトが割り当てられるインスタンス。 |

### 戻り値

解析が正常に完了した場合は true、そうでない場合は false。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [ViaHeaderValue](../)
* 名前空間 [System::Net::Http::Headers](../../)
* ライブラリ [Aspose.Slides](../../../)