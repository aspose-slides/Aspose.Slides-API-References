---
title: TryGetLast()
second_title: Aspose.Slides for C++ APIリファレンス
description: コレクションの最後の要素を取得しようとします。
type: docs
weight: 261
url: /ja/system.collections.generic.details/trygetlast/
---
## System::Collections::Generic::Details::TryGetLast(IEnumerable\<T\>\&, bool\&) 関数


コレクションの最後の要素を取得しようとします。

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetLast(IEnumerable<T> &enumerable, bool &found)
```


### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T | The type of the collection elements. |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | 要素を取得するコレクション。 |
| found | **bool**\& | 出力パラメーター。コレクションに要素が含まれる場合は true を返します。それ以外の場合は false が返されます。 |

### 戻り値

コレクションの最後の要素を返します。コレクションが空の場合、型の既定値が返されます。

## 参照

* クラス [IEnumerable](../../system.collections.generic/ienumerable/)
* 名前空間 [System::Collections::Generic::Details](../)
* ライブラリ [Aspose.Slides](../../)