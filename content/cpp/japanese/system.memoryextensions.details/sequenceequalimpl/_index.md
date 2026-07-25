---
title: SequenceEqualImpl()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された位置から、2つのスパンが等しいかどうかを確認します。
type: docs
weight: 27
url: /ja/system.memoryextensions.details/sequenceequalimpl/
---
## System::MemoryExtensions::Details::SequenceEqualImpl(const ReadOnlySpan\<T\>\&, const int32_t, int32_t, const ReadOnlySpan\<T\>\&) 関数


指定された位置から、2つのスパンが等しいかどうかを確認します。

```cpp
template<typename T> bool System::MemoryExtensions::Details::SequenceEqualImpl(const ReadOnlySpan<T> &first, const int32_t start, int32_t length, const ReadOnlySpan<T> &second)
```


### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| first | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 最初のスパン |
| start | const **int32_t** | 最初のスパンの開始インデックス |
| length | **int32_t** | 比較する要素数 |
| second | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 2番目のスパン |

### 戻り値

指定された範囲が等しい場合は true、そうでない場合は false

## 関連項目

* クラス [ReadOnlySpan](../../system/readonlyspan/)
* 名前空間 [System::MemoryExtensions::Details](../)
* ライブラリ [Aspose.Slides](../../)