---
title: TryParse()
second_title: Aspose.Slides for C++ API リファレンス
description: 渡された文字列を ProductInfoHeaderValue クラスのインスタンスに変換しようとします。
type: docs
weight: 92
url: /ja/system.net.http.headers/productinfoheadervalue/tryparse/
---
## ProductInfoHeaderValue::TryParse(String, System::SharedPtr\<ProductInfoHeaderValue\>\&) メソッド

渡された文字列を [ProductInfoHeaderValue](../) クラスのインスタンスに変換しようとします。

```cpp
static bool System::Net::Http::Headers::ProductInfoHeaderValue::TryParse(String input, System::SharedPtr<ProductInfoHeaderValue> &parsedValue)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 解析対象の文字列。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[ProductInfoHeaderValue](../)\>\& | 解析されたオブジェクトが割り当てられるインスタンス。 |

### 戻り値

解析が正常に完了した場合は true、そうでない場合は false が返されます。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [ProductInfoHeaderValue](../)
* 名前空間 [System::Net::Http::Headers](../../)
* ライブラリ [Aspose.Slides](../../../)