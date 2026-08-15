---
title: CopyTo()
second_title: Aspose.Slides for C++ API 參考
description: 將清單元素複製到現有的陣列元素中。
type: docs
weight: 209
url: /zh-hant/system.collections.generic/list/copyto/
---
## List::CopyTo(System::ArrayPtr\<T\>, int) 方法

將清單元素複製到現有的陣列元素中。

```cpp
void System::Collections::Generic::List<T>::CopyTo(System::ArrayPtr<T> array, int arrayIndex) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<T\> | 目標陣列。 |
| arrayIndex | int | 目標陣列的起始索引。 |

## List::CopyTo(const System::ArrayPtr\<T\>\&) 方法

將所有元素複製到現有的陣列元素中。

```cpp
void System::Collections::Generic::List<T>::CopyTo(const System::ArrayPtr<T> &array)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| array | const [System::ArrayPtr](../../../system/arrayptr/)\<T\>\& | 將元素複製到[Array](../../../system/array/)。 |

## List::CopyTo(int, const System::ArrayPtr\<T\>\&, int, int) 方法

將元素從指定的索引開始複製到現有的陣列元素中。

```cpp
void System::Collections::Generic::List<T>::CopyTo(int index, const System::ArrayPtr<T> &array, int arrayIndex, int count)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 以 0 為基礎的索引，表示由目前物件所代表的清單中要開始複製的元素所在位置 |
| array | const [System::ArrayPtr](../../../system/arrayptr/)\<T\>\& | 將元素複製到[Array](../../../system/array/)。 |
| arrayIndex | int | 目標陣列的起始位置。 |
| count | int | 要複製的元素數量。 |

## 另請參閱

* 型別定義 [ArrayPtr](../../../system/arrayptr/)
* 類別 [List](../)
* 命名空間 [System::Collections::Generic](../../)
* 函式庫 [Aspose.Slides](../../../)