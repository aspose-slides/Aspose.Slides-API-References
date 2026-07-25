---
title: TryParse()
second_title: Aspose.Slides for C++ API リファレンス
description: 渡された文字列を ProductHeaderValue クラスのインスタンスに変換しようとします。
type: docs
weight: 92
url: /ja/system.net.http.headers/productheadervalue/tryparse/
---
## ProductHeaderValue::TryParse(String, System::SharedPtr\<ProductHeaderValue\>\&) メソッド

渡された文字列を [ProductHeaderValue](../) クラスのインスタンスに変換しようとします。

```cpp
static bool System::Net::Http::Headers::ProductHeaderValue::TryParse(String input, System::SharedPtr<ProductHeaderValue> &parsedValue)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 解析対象の文字列。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[ProductHeaderValue](../)\>\& | 解析されたオブジェクトが割り当てられるインスタンス。 |

### 戻り値

解析が正常に完了した場合は true、そうでない場合は false です。

## 参照

* typedef [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [ProductHeaderValue](../)
* 名前空間 [System::Net::Http::Headers](../../)
* ライブラリ [Aspose.Slides](../../../)