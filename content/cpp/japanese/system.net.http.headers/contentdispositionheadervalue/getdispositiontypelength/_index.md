---
title: GetDispositionTypeLength()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたインデックスから渡された文字列を ContentDispositionHeaderValue クラスのインスタンスに変換します。
type: docs
weight: 300
url: /ja/system.net.http.headers/contentdispositionheadervalue/getdispositiontypelength/
---
## ContentDispositionHeaderValue::GetDispositionTypeLength(String, int32_t, System::SharedPtr\<Object\>\&) メソッド

指定されたインデックスから渡された文字列を [ContentDispositionHeaderValue](../) クラスのインスタンスに変換します。

```cpp
static int32_t System::Net::Http::Headers::ContentDispositionHeaderValue::GetDispositionTypeLength(String input, int32_t startIndex, System::SharedPtr<Object> &parsedValue)
```

### 引数

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 解析する文字列です。 |
| startIndex | **int32_t** | 解析の開始位置です。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 解析されたオブジェクトが割り当てられるインスタンスです。 |

### 戻り値

解析されたサブ文字列の長さです。解析できなければ 0 が返されます。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [Object](../../../system/object/)
* クラス [ContentDispositionHeaderValue](../)
* 名前空間 [System::Net::Http::Headers](../../)
* ライブラリ [Aspose.Slides](../../../)