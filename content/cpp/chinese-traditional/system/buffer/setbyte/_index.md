---
title: SetByte()
second_title: Aspose.Slides for C++ API 參考文件
description: 將指定的類型化陣列解釋為原始位元組陣列，並在指定的位元組偏移處設定指定的位元組值。
type: docs
weight: 40
url: /zh-hant/system/buffer/setbyte/
---
## Buffer::SetByte(const SharedPtr<Array<T>>&, int, uint8_t) 方法

將指定的類型化陣列解釋為原始位元組陣列，並在指定的位元組偏移處設定指定的位元組值。

```cpp
template<typename T> static void System::Buffer::SetByte(const SharedPtr<Array<T>> &array, int index, uint8_t value)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | 陣列中元素的類型 |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)<[Array](../../array/)<T>> & | 目標陣列 |
| index | int | 要設定的位元組之零基索引偏移 |
| value | **uint8_t** | 要設定的位元組值 |

## Buffer::SetByte(const System::Details::ArrayView<T>&, int, uint8_t) 方法

將指定的類型化陣列解釋為原始位元組陣列，並在指定的位元組偏移處設定指定的位元組值。

```cpp
template<typename T> static void System::Buffer::SetByte(const System::Details::ArrayView<T> &array, int index, uint8_t value)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | 陣列中元素的類型 |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | const System::Details::ArrayView<T>& | 目標陣列檢視 |
| index | int | 要設定的位元組之零基索引偏移 |
| value | **uint8_t** | 要設定的位元組值 |

## Buffer::SetByte(const System::Details::StackArray<T, N>&, int, uint8_t) 方法

將指定的類型化陣列解釋為原始位元組陣列，並在指定的位元組偏移處設定指定的位元組值。

```cpp
template<typename T,std::size_t> static void System::Buffer::SetByte(const System::Details::StackArray<T, N> &array, int index, uint8_t value)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | 陣列中元素的類型 |
| N | 堆疊陣列的大小 |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | const System::Details::StackArray<T, N>& | 目標堆疊陣列 |
| index | int | 要設定的位元組之零基索引偏移 |
| value | **uint8_t** | 要設定的位元組值 |

## 參見

* 型別別名 [SharedPtr](../../sharedptr/)
* 類別 [Array](../../array/)
* 類別 [Buffer](../)
* 命名空間 [System](../../)
* 程式庫 [Aspose.Slides](../../../)