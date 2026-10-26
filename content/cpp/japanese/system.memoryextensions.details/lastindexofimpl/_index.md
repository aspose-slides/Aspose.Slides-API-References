---
title: LastIndexOfImpl()
second_title: Aspose.Slides for C++ API リファレンス
description: スパン内の値の最後のインデックスを検索します。
type: docs
weight: 14
url: /ja/system.memoryextensions.details/lastindexofimpl/
---
## System::MemoryExtensions::Details::LastIndexOfImpl(const ReadOnlySpan\<T\>\&, int32_t, const T\&) function

スパン内の値の最後のインデックスを検索します。

```cpp
template<typename T> int32_t System::MemoryExtensions::Details::LastIndexOfImpl(const ReadOnlySpan<T> &searchSpace, int32_t length, const T &value)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T | スパン内の要素の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| searchSpace | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [Span](../../system/span/) を検索 |
| length | **int32_t** | 検索する範囲の長さ |
| value | const T\& | 検索する値 |

### 戻り値

値の最後のインデックス、または見つからない場合は -1

## 参照

* クラス [ReadOnlySpan](../../system/readonlyspan/)
* 名前空間 [System::MemoryExtensions::Details](../)
* ライブラリ [Aspose.Slides](../../)