---
title: GetProductInfoLength()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたインデックスから渡された文字列を ProductInfoHeaderValue クラスのインスタンスに変換します。
type: docs
weight: 105
url: /ja/system.net.http.headers/productinfoheadervalue/getproductinfolength/
---
## ProductInfoHeaderValue::GetProductInfoLength(String, int32_t, System::SharedPtr\<ProductInfoHeaderValue\>\&) メソッド

指定されたインデックスから渡された文字列を [ProductInfoHeaderValue](../) クラスのインスタンスに変換します。

```cpp
static int32_t System::Net::Http::Headers::ProductInfoHeaderValue::GetProductInfoLength(String input, int32_t startIndex, System::SharedPtr<ProductInfoHeaderValue> &parsedValue)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 解析する文字列。 |
| startIndex | **int32_t** | 解析の開始位置。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[ProductInfoHeaderValue](../)\>\& | 解析されたオブジェクトが代入されるインスタンス。 |

### 戻り値

解析されたサブ文字列の長さを返し、そうでない場合は 0 を返します。

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [ProductInfoHeaderValue](../)
* 名前空間 [System::Net::Http::Headers](../../)
* ライブラリ [Aspose.Slides](../../../)