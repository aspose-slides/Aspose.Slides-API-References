---
title: Get()
second_title: Aspose.Slides for C++ API 參考
description: 取得給定 tuple 的第 N 個元素的函式。針對基底物件的重載。
type: docs
weight: 2406
url: /zh-hant/system/get/
---
## System::Get(const SharedPtr\<Object\>\&) function

取得給定 tuple 的第 N 個元素的函式。針對基底物件的重載。

```cpp
template<std::size_t> auto System::Get(const SharedPtr<Object> &object)
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| N | element index. |

### 參數

| 參數 | Type | 描述 |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | 要檢查的物件。 |

### 返回值

第 N 個 tuple 元素轉型為 object 的值。

## System::Get(const T\&) function

取得給定 tuple 的第 N 個元素的函式。針對具有 Deconstruct 方法的物件的重載。

```cpp
template<std::size_t,typename T> auto System::Get(const T &object)
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| N | element index. |
| T | type of inspected object. |

### 參數

| 參數 | Type | 描述 |
| --- | --- | --- |
| object | const T\& | 要檢查的物件。 |

### 返回值

第 N 個 tuple 元素的值。

## System::Get(const SharedPtr\<T\>\&) function

取得給定 tuple 的第 N 個元素的函式。針對 shared pointers 的重載。

```cpp
template<std::size_t,typename T> auto System::Get(const SharedPtr<T> &pointer)
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| N | element index. |
| T | type of inspected object. |

### 參數

| 參數 | Type | 描述 |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<T\>\& | 要檢查的物件。 |

### 返回值

第 N 個 tuple 元素的值。

## System::Get(T\&, const Index\&) function

collection[index] 表達式的實作。

```cpp
template<typename T> auto & System::Get(T &collection, const Index &index)
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| T | Collection type. |

### 參數

| 參數 | Type | 描述 |
| --- | --- | --- |
| collection | T\& | Collection 物件。 |
| index | const [Index](../index/)\& | 類型為 [System.Index](../index/) 的元素索引。 |

### 返回值

Collection 元素在計算後的偏移位置。

## System::Get(T\&, const Range\&) function

傳回由提供的範圍定義的指定集合的切片。

```cpp
template<typename T> auto System::Get(T &collection, const Range &range)
```

### 參數

| 參數 | Type | 描述 |
| --- | --- | --- |
| collection | T\& | 要切割的集合。 |
| range | const [Range](../range/)\& | 指定切片邊界的範圍。 |

### 返回值

從計算出的起始偏移和長度得到的集合視圖或切片。

## System::Get(const ValueTuple\<Args...\>\&) function

取得值 tuple 的第 N 個元素。

```cpp
template<std::size_t,typename...> auto System::Get(const ValueTuple<Args...> &tuple)
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| N | element index. |
| Args | tuple elements. |

### 參數

| 參數 | Type | 描述 |
| --- | --- | --- |
| tuple | const [ValueTuple](../valuetuple/)\<Args...\>\& | 要取得元素的 tuple。 |

### 返回值

第 N 個 tuple 元素的值。

## 另請參閱

* Typedef [SharedPtr](../sharedptr/)
* 類別 [Object](../object/)
* 類別 [Index](../index/)
* 類別 [Range](../range/)
* 類別 [ValueTuple](../valuetuple/)
* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)