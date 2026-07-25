---
title: TryParse()
second_title: Aspose.Slides for C++ API リファレンス
description: 渡された文字列を MediaTypeHeaderValue クラスのインスタンスに変換しようとします。
type: docs
weight: 131
url: /ja/system.net.http.headers/mediatypeheadervalue/tryparse/
---
## MediaTypeHeaderValue::TryParse(String, System::SharedPtr\<MediaTypeHeaderValue\>\&) メソッド

渡された文字列を [MediaTypeHeaderValue](../) クラスのインスタンスに変換しようとします。

```cpp
static bool System::Net::Http::Headers::MediaTypeHeaderValue::TryParse(String input, System::SharedPtr<MediaTypeHeaderValue> &parsedValue)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 解析する文字列。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[MediaTypeHeaderValue](../)\>\& | 解析されたオブジェクトが割り当てられるインスタンス。 |

### 戻り値

解析が正常に完了した場合は True、そうでない場合は false です。

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [MediaTypeHeaderValue](../)
* 名前空間 [System::Net::Http::Headers](../../)
* ライブラリ [Aspose.Slides](../../../)