---
title: TryGetValues()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された名前に対応する値を取得しようとします。
type: docs
weight: 66
url: /ja/system.net.http.headers/httpheaders/trygetvalues/
---
## HttpHeaders::TryGetValues(String, System::SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&) メソッド

指定された名前に対応する値を取得しようとします。

```cpp
bool System::Net::Http::Headers::HttpHeaders::TryGetValues(String name, System::SharedPtr<Collections::Generic::IEnumerable<String>> &values)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | ヘッダー名です。 |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | 対応する値が代入されるインスタンスです。 |

### 戻り値

指定された名前でヘッダー値が見つかった場合は true、そうでない場合は false が返されます。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [IEnumerable](../../../system.collections.generic/ienumerable/)
* クラス [HttpHeaders](../)
* 名前空間 [System::Net::Http::Headers](../../)
* ライブラリ [Aspose.Slides](../../../)