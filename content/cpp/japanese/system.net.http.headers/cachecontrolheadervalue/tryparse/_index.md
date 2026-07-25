---
title: TryParse()
second_title: Aspose.Slides for C++ API リファレンス
description: 渡された文字列を CacheControlHeaderValue クラスのインスタンスに変換しようとします。
type: docs
weight: 443
url: /ja/system.net.http.headers/cachecontrolheadervalue/tryparse/
---
## CacheControlHeaderValue::TryParse(String, System::SharedPtr\<CacheControlHeaderValue\>\&) メソッド

渡された文字列を [CacheControlHeaderValue](../) クラスのインスタンスに変換しようとします。

```cpp
static bool System::Net::Http::Headers::CacheControlHeaderValue::TryParse(String input, System::SharedPtr<CacheControlHeaderValue> &parsedValue)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 解析する文字列。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[CacheControlHeaderValue](../)\>\& | 解析されたオブジェクトが代入されるインスタンス。 |

### 戻り値

解析が正常に完了した場合は true、それ以外の場合は false。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [CacheControlHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)