---
title: GetCacheControlLength()
second_title: C++ 用 Aspose.Slides API リファレンス
description: 指定されたインデックスから渡された文字列を CacheControlHeaderValue クラスのインスタンスに変換します。
type: docs
weight: 456
url: /ja/system.net.http.headers/cachecontrolheadervalue/getcachecontrollength/
---
## CacheControlHeaderValue::GetCacheControlLength(String, int32_t, System::SharedPtr\<CacheControlHeaderValue\>, System::SharedPtr\<CacheControlHeaderValue\>\&) メソッド

指定されたインデックスから渡された文字列を [CacheControlHeaderValue](../) クラスのインスタンスに変換します。

```cpp
static int32_t System::Net::Http::Headers::CacheControlHeaderValue::GetCacheControlLength(String input, int32_t startIndex, System::SharedPtr<CacheControlHeaderValue> storeValue, System::SharedPtr<CacheControlHeaderValue> &parsedValue)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | 解析する文字列。 |
| startIndex | **int32_t** | 解析の開始位置。 |
| storeValue | [System::SharedPtr](../../../system/sharedptr/)\<[CacheControlHeaderValue](../)\> | 解析されたオブジェクトに追加する必要がある値。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[CacheControlHeaderValue](../)\>\& | 解析されたオブジェクトが代入されるインスタンス。 |

### 戻り値

解析された部分文字列の長さ、該当しない場合は 0。

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [CacheControlHeaderValue](../)
* 名前空間 [System::Net::Http::Headers](../../)
* ライブラリ [Aspose.Slides](../../../)