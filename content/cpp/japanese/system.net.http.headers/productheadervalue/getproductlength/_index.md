---
title: GetProductLength()
second_title: Aspose.Slides の C++ API リファレンス
description: 指定されたインデックスから渡された文字列を ProductHeaderValue クラスのインスタンスに変換します。
type: docs
weight: 105
url: /ja/system.net.http.headers/productheadervalue/getproductlength/
---
## ProductHeaderValue::GetProductLength(String, int32_t, System::SharedPtr\<ProductHeaderValue\>\&) メソッド

指定されたインデックスから渡された文字列を[ProductHeaderValue](../) クラスのインスタンスに変換します。

```cpp
static int32_t System::Net::Http::Headers::ProductHeaderValue::GetProductLength(String input, int32_t startIndex, System::SharedPtr<ProductHeaderValue> &parsedValue)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 解析対象の文字列。 |
| startIndex | **int32_t** | パースの開始位置。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[ProductHeaderValue](../)\>\& | 解析されたオブジェクトが割り当てられるインスタンス。 |

### 戻り値

解析された部分文字列の長さを返します。該当しない場合は 0 を返します。

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [ProductHeaderValue](../)
* 名前空間 [System::Net::Http::Headers](../../)
* ライブラリ [Aspose.Slides](../../../)