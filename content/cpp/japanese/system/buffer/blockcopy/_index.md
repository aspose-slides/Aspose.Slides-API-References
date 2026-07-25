---
title: BlockCopy()
second_title: Aspose.Slides for C++ API リファレンス
description: ソースバッファからデスティネーションバッファへ指定されたバイト数をコピーします。
type: docs
weight: 1
url: /ja/system/buffer/blockcopy/
---
## Buffer::BlockCopy(const uint8_t *, int, uint8_t *, int, int) メソッド

指定されたバイト数をソースバッファからデスティネーションバッファへコピーします。

```cpp
static void System::Buffer::BlockCopy(const uint8_t *src, int srcOffset, uint8_t *dst, int dstOffset, int count)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| src | const **uint8_t** * | ソースバッファへのポインタ |
| srcOffset | int | コピー開始位置となるソースバッファ内のバイトオフセット |
| dst | **uint8_t** * | デスティネーションバッファへのポインタ |
| dstOffset | int | データ挿入開始位置となるデスティネーションバッファ内のバイトオフセット |
| count | int | コピーするバイト数 |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) メソッド

指定された2つの型付き配列をバイトの生配列として解釈し、片方からもう片方へデータをコピーします。

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```

### テンプレート パラメーター

| パラメータ | 説明 |
| --- | --- |
| TSrc | ソース配列の要素型 |
| TDst | デスティネーション配列の要素型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | ソース配列 |
| srcOffset | int | コピー開始位置となるソース配列内のバイトオフセット |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | デスティネーション配列 |
| dstOffset | int | デスティネーション配列内のデータ挿入開始位置となるバイトオフセット |
| count | int | コピーするバイト数 |

## Buffer::BlockCopy(const SharedPtr\<ArrayBase\>\&, int, const SharedPtr\<ArrayBase\>\&, int, int) メソッド

指定された2つの配列をバイトの生配列として解釈し、片方からもう片方へデータをコピーします。

```cpp
static void System::Buffer::BlockCopy(const SharedPtr<ArrayBase> &src, int srcOffset, const SharedPtr<ArrayBase> &dst, int dstOffset, int count)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[ArrayBase](../../arraybase/)\>\& | ソース配列 |
| srcOffset | int | コピー開始位置となるソース配列内のバイトオフセット |
| dst | const [SharedPtr](../../sharedptr/)\<[ArrayBase](../../arraybase/)\>\& | デスティネーション配列 |
| dstOffset | int | デスティネーション配列内のデータ挿入開始位置となるバイトオフセット |
| count | int | コピーするバイト数 |

## Buffer::BlockCopy(const System::Details::ArrayView\<TSrc\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) メソッド

指定された2つの型付き配列をバイトの生配列として解釈し、片方からもう片方へデータをコピーします。

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const System::Details::ArrayView<TSrc> &src, int srcOffset, const System::Details::ArrayView<TDst> &dst, int dstOffset, int count)
```

### テンプレート パラメーター

| パラメータ | 説明 |
| --- | --- |
| TSrc | ソース配列ビューの要素型 |
| TDst | デスティネーション配列ビューの要素型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| src | const System::Details::ArrayView\<TSrc\>\& | ソース配列ビュー |
| srcOffset | int | コピー開始位置となるソース配列ビュー内のバイトオフセット |
| dst | const System::Details::ArrayView\<TDst\>\& | デスティネーション配列ビュー |
| dstOffset | int | デスティネーション配列ビュー内のデータ挿入開始位置となるバイトオフセット |
| count | int | コピーするバイト数 |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) メソッド

指定された2つの型付き配列をバイトの生配列として解釈し、片方からもう片方へデータをコピーします。

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const System::Details::ArrayView<TDst> &dst, int dstOffset, int count)
```

### テンプレート パラメーター

| パラメータ | 説明 |
| --- | --- |
| TSrc | ソース配列の要素型 |
| TDst | デスティネーション配列ビューの要素型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | ソース配列 |
| srcOffset | int | コピー開始位置となるソース配列内のバイトオフセット |
| dst | const System::Details::ArrayView\<TDst\>\& | デスティネーション配列ビュー |
| dstOffset | int | デスティネーション配列ビュー内のデータ挿入開始位置となるバイトオフセット |
| count | int | コピーするバイト数 |

## Buffer::BlockCopy(const System::Details::ArrayView\<TSrc\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) メソッド

指定された2つの型付き配列をバイトの生配列として解釈し、片方からもう片方へデータをコピーします。

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const System::Details::ArrayView<TSrc> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```

### テンプレート パラメーター

| パラメータ | 説明 |
| --- | --- |
| TSrc | ソース配列ビューの要素型 |
| TDst | デスティネーション配列の要素型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| src | const System::Details::ArrayView\<TSrc\>\& | ソース配列ビュー |
| srcOffset | int | コピー開始位置となるソース配列ビュー内のバイトオフセット |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | デスティネーション配列 |
| dstOffset | int | デスティネーション配列内のデータ挿入開始位置となるバイトオフセット |
| count | int | コピーするバイト数 |

## Buffer::BlockCopy(const System::Details::StackArray\<TSrc, NS\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) メソッド

指定された2つの型付き配列をバイトの生配列として解釈し、片方からもう片方へデータをコピーします。

```cpp
template<typename TSrc,std::size_t,typename TDst,std::size_t> static void System::Buffer::BlockCopy(const System::Details::StackArray<TSrc, NS> &src, int srcOffset, const System::Details::StackArray<TDst, ND> &dst, int dstOffset, int count)
```

### テンプレート パラメーター

| パラメータ | 説明 |
| --- | --- |
| TSrc | ソーススタック配列の要素型 |
| NS | ソーススタック配列のサイズ |
| TDst | デスティネーションスタック配列の要素型 |
| ND | デスティネーションスタック配列のサイズ |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| src | const System::Details::StackArray\<TSrc, NS\>\& | ソーススタック配列 |
| srcOffset | int | コピー開始位置となるソーススタック配列内のバイトオフセット |
| dst | const System::Details::StackArray\<TDst, ND\>\& | デスティネーションスタック配列 |
| dstOffset | int | デスティネーションスタック配列内のデータ挿入開始位置となるバイトオフセット |
| count | int | コピーするバイト数 |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) メソッド

指定された2つの型付き配列をバイトの生配列として解釈し、片方からもう片方へデータをコピーします。

```cpp
template<typename TSrc,typename TDst,std::size_t> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const System::Details::StackArray<TDst, ND> &dst, int dstOffset, int count)
```

### テンプレート パラメーター

| パラメータ | 説明 |
| --- | --- |
| TSrc | ソース配列の要素型 |
| TDst | デスティネーションスタック配列の要素型 |
| ND | デスティネーションスタック配列のサイズ |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | ソース配列 |
| srcOffset | int | コピー開始位置となるソース配列内のバイトオフセット |
| dst | const System::Details::StackArray\<TDst, ND\>\& | デスティネーションスタック配列 |
| dstOffset | int | デスティネーションスタック配列内のデータ挿入開始位置となるバイトオフセット |
| count | int | コピーするバイト数 |

## Buffer::BlockCopy(const System::Details::StackArray\<TSrc, NS\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) メソッド

指定された2つの型付き配列をバイトの生配列として解釈し、片方からもう片方へデータをコピーします。

```cpp
template<typename TSrc,std::size_t,typename TDst> static void System::Buffer::BlockCopy(const System::Details::StackArray<TSrc, NS> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```

### テンプレート パラメーター

| パラメータ | 説明 |
| --- | --- |
| TSrc | ソーススタック配列の要素型 |
| NS | ソーススタック配列のサイズ |
| TDst | デスティネーション配列の要素型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| src | const System::Details::StackArray\<TSrc, NS\>\& | ソーススタック配列 |
| srcOffset | int | コピー開始位置となるソーススタック配列内のバイトオフセット |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | デスティネーション配列 |
| dstOffset | int | デスティネーション配列内のデータ挿入開始位置となるバイトオフセット |
| count | int | コピーするバイト数 |

## 参照

* Typedef [SharedPtr](../../sharedptr/)
* クラス [Buffer](../)
* クラス [Array](../../array/)
* クラス [ArrayBase](../../arraybase/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)