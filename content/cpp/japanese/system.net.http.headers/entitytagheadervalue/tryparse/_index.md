---
title: TryParse()
second_title: Aspose.Slides for C++ API リファレンス
description: 渡された文字列を EntityTagHeaderValue クラスのインスタンスに変換しようとします。
type: docs
weight: 105
url: /ja/system.net.http.headers/entitytagheadervalue/tryparse/
---
## EntityTagHeaderValue::TryParse(String, System::SharedPtr\<EntityTagHeaderValue\>\&) メソッド


渡された文字列を [EntityTagHeaderValue](../) クラスのインスタンスに変換しようとします。

```cpp
static bool System::Net::Http::Headers::EntityTagHeaderValue::TryParse(String input, System::SharedPtr<EntityTagHeaderValue> &parsedValue)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 解析する文字列。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[EntityTagHeaderValue](../)\>\& | 解析されたオブジェクトが割り当てられるインスタンス。 |

### 戻り値

解析が正常に完了した場合は true、そうでない場合は false。

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [EntityTagHeaderValue](../)
* 名前空間 [System::Net::Http::Headers](../../)
* ライブラリ [Aspose.Slides](../../../)