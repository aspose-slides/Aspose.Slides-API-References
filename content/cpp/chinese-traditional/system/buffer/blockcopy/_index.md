---
title: BlockCopy()
second_title: Aspose.Slides for C++ API 參考文件
description: 從來源緩衝區複製指定數量的位元組到目標緩衝區。
type: docs
weight: 1
url: /zh-hant/system/buffer/blockcopy/
---
## Buffer::BlockCopy(const uint8_t *, int, uint8_t *, int, int) 方法

將指定數量的位元組從來源緩衝區複製到目標緩衝區。

```cpp
static void System::Buffer::BlockCopy(const uint8_t *src, int srcOffset, uint8_t *dst, int dstOffset, int count)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| src | const **uint8_t** * | 指向來源緩衝區的指標 |
| srcOffset | int | 來源緩衝區中開始複製的位元組偏移量 |
| dst | **uint8_t** * | 指向目標緩衝區的指標 |
| dstOffset | int | 目標緩衝區中開始插入資料的位元組偏移量 |
| count | int | 要複製的位元組數量 |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) 方法

將兩個指定型別的陣列視為原始位元組陣列，並將資料從其中一個複製到另一個。

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| TSrc | 來源陣列元素的型別 |
| TDst | 目標陣列元素的型別 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | 來源陣列 |
| srcOffset | int | 來源陣列中開始複製的位元組偏移量 |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | 目標陣列 |
| dstOffset | int | 目標陣列中開始插入資料的位元組偏移量 |
| count | int | 要複製的位元組數量 |

## Buffer::BlockCopy(const SharedPtr\<ArrayBase\>\&, int, const SharedPtr\<ArrayBase\>\&, int, int) 方法

將兩個指定的陣列視為原始位元組陣列，並將資料從其中一個複製到另一個。

```cpp
static void System::Buffer::BlockCopy(const SharedPtr<ArrayBase> &src, int srcOffset, const SharedPtr<ArrayBase> &dst, int dstOffset, int count)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[ArrayBase](../../arraybase/)\>\& | 來源陣列 |
| srcOffset | int | 來源陣列中開始複製的位元組偏移量 |
| dst | const [SharedPtr](../../sharedptr/)\<[ArrayBase](../../arraybase/)\>\& | 目標陣列 |
| dstOffset | int | 目標陣列中開始插入資料的位元組偏移量 |
| count | int | 要複製的位元組數量 |

## Buffer::BlockCopy(const System::Details::ArrayView\<TSrc\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) 方法

將兩個指定型別的陣列視為原始位元組陣列，並將資料從其中一個複製到另一個。

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const System::Details::ArrayView<TSrc> &src, int srcOffset, const System::Details::ArrayView<TDst> &dst, int dstOffset, int count)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| TSrc | 來源陣列視圖元素的型別 |
| TDst | 目標陣列視圖元素的型別 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| src | const System::Details::ArrayView\<TSrc\>\& | 來源陣列視圖 |
| srcOffset | int | 來源陣列視圖中開始複製的位元組偏移量 |
| dst | const System::Details::ArrayView\<TDst\>\& | 目標陣列視圖 |
| dstOffset | int | 目標陣列視圖中開始插入資料的位元組偏移量 |
| count | int | 要複製的位元組數量 |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) 方法

將兩個指定型別的陣列視為原始位元組陣列，並將資料從其中一個複製到另一個。

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const System::Details::ArrayView<TDst> &dst, int dstOffset, int count)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| TSrc | 來源陣列元素的型別 |
| TDst | 目標陣列視圖元素的型別 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | 來源陣列 |
| srcOffset | int | 來源陣列中開始複製的位元組偏移量 |
| dst | const System::Details::ArrayView\<TDst\>\& | 目標陣列視圖 |
| dstOffset | int | 目標陣列視圖中開始插入資料的位元組偏移量 |
| count | int | 要複製的位元組數量 |

## Buffer::BlockCopy(const System::Details::ArrayView\<TSrc\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) 方法

將兩個指定型別的陣列視為原始位元組陣列，並將資料從其中一個複製到另一個。

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const System::Details::ArrayView<TSrc> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| TSrc | 來源陣列視圖元素的型別 |
| TDst | 目標陣列元素的型別 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| src | const System::Details::ArrayView\<TSrc\>\& | 來源陣列視圖 |
| srcOffset | int | 來源陣列視圖中開始複製的位元組偏移量 |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | 目標陣列 |
| dstOffset | int | 目標陣列中開始插入資料的位元組偏移量 |
| count | int | 要複製的位元組數量 |

## Buffer::BlockCopy(const System::Details::StackArray\<TSrc, NS\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) 方法

將兩個指定型別的陣列視為原始位元組陣列，並將資料從其中一個複製到另一個。

```cpp
template<typename TSrc,std::size_t,typename TDst,std::size_t> static void System::Buffer::BlockCopy(const System::Details::StackArray<TSrc, NS> &src, int srcOffset, const System::Details::StackArray<TDst, ND> &dst, int dstOffset, int count)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| TSrc | 來源堆疊陣列元素的型別 |
| NS | 來源堆疊陣列的大小 |
| TDst | 目標堆疊陣列元素的型別 |
| ND | 目標堆疊陣列的大小 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| src | const System::Details::StackArray\<TSrc, NS\>\& | 來源堆疊陣列 |
| srcOffset | int | 來源堆疊陣列中開始複製的位元組偏移量 |
| dst | const System::Details::StackArray\<TDst, ND\>\& | 目標堆疊陣列 |
| dstOffset | int | 目標堆疊陣列中開始插入資料的位元組偏移量 |
| count | int | 要複製的位元組數量 |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) 方法

將兩個指定型別的陣列視為原始位元組陣列，並將資料從其中一個複製到另一個。

```cpp
template<typename TSrc,typename TDst,std::size_t> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const System::Details::StackArray<TDst, ND> &dst, int dstOffset, int count)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| TSrc | 來源陣列元素的型別 |
| TDst | 目標堆疊陣列元素的型別 |
| ND | 目標堆疊陣列的大小 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | 來源陣列 |
| srcOffset | int | 來源陣列中開始複製的位元組偏移量 |
| dst | const System::Details::StackArray\<TDst, ND\>\& | 目標堆疊陣列 |
| dstOffset | int | 目標堆疊陣列中開始插入資料的位元組偏移量 |
| count | int | 要複製的位元組數量 |

## Buffer::BlockCopy(const System::Details::StackArray\<TSrc, NS\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) 方法

將兩個指定型別的陣列視為原始位元組陣列，並將資料從其中一個複製到另一個。

```cpp
template<typename TSrc,std::size_t,typename TDst> static void System::Buffer::BlockCopy(const System::Details::StackArray<TSrc, NS> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| TSrc | 來源堆疊陣列元素的型別 |
| NS | 來源堆疊陣列的大小 |
| TDst | 目標陣列元素的型別 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| src | const System::Details::StackArray\<TSrc, NS\>\& | 來源堆疊陣列 |
| srcOffset | int | 來源堆疊陣列中開始複製的位元組偏移量 |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | 目標陣列 |
| dstOffset | int | 目標陣列中開始插入資料的位元組偏移量 |
| count | int | 要複製的位元組數量 |

## 另請參閱

* 型別定義 [SharedPtr](../../sharedptr/)
* 類別 [Buffer](../)
* 類別 [Array](../../array/)
* 類別 [ArrayBase](../../arraybase/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)