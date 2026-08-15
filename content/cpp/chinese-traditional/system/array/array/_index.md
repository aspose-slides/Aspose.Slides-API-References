---
title: Array()
second_title: Aspose.Slides for C++ API 參考
description: 建構一個空的陣列。
type: docs
weight: 1
url: /zh-hant/system/array/array/
---
## Array::Array() 建構子

建構一個空的陣列。

```cpp
System::Array<T>::Array()
```

## Array::Array(int, const T\&) 建構子

填充建構子。

```cpp
System::Array<T>::Array(int count, const T &init=T())
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| count | int | 陣列的初始大小 |
| init | const T\& | 用於填充陣列的初始值 |

## Array::Array(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<ValueType\>::value\&&std::is_convertible\<ValueType, T\>::value, int\>::type, ValueType) 建構子

填充建構子。

```cpp
template<typename ValueType> System::Array<T>::Array(typename std::enable_if<std::is_arithmetic<T>::value &&std::is_arithmetic<ValueType>::value &&std::is_convertible<ValueType, T>::value, int>::type count, ValueType init)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| ValueType | 初始值的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| count | typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<[ValueType](../valuetype/)\>::value\&&std::is_convertible\<[ValueType](../valuetype/), T\>::value, int\>::type | 陣列的初始大小 |
| init | [ValueType](../valuetype/) | 用於填充陣列的初始值 |

## Array::Array(int, const T) 建構子

填充建構子。

```cpp
System::Array<T>::Array(int count, const T inits[])
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| count | int | 陣列的初始大小 |
| inits | const T | 用於填充陣列的值 |

## Array::Array(vector_t\&&) 建構子

移動建構子。

```cpp
System::Array<T>::Array(vector_t &&value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **vector_t**\&& | std::vector，其元素被陣列取得 |

## Array::Array(const vector_t\&) 建構子

複製建構子。

```cpp
System::Array<T>::Array(const vector_t &assgn)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| assgn | const **vector_t**\& | 從中複製值的 std::vector |

## Array::Array(const std::vector\<Q\>\&) 建構子

建構一個 [Array](../) 物件，並用從 std::vector 物件複製的值填充，其中該物件的值類型與 **T** 相同但與 **UnderlyingType** 不同。

```cpp
template<typename Q,typename> System::Array<T>::Array(const std::vector<Q> &value)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| Q | 用於從 std::vector 物件複製元素的元素類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const std::vector\<Q\>\& | 用於複製值的 std::vector |

## Array::Array(std::vector\<Q\>\&&) 建構子

建構一個 [Array](../) 物件，並用從 std::vector 物件移動的值填充，其中該物件的值類型與 **T** 相同但與 **UnderlyingType** 不同。

```cpp
template<typename Q,typename> System::Array<T>::Array(std::vector<Q> &&value)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| Q | 用於從 std::vector 物件移動元素的元素類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | std::vector\<Q\>\&& | 用於移動值的 std::vector |

## Array::Array(std::initializer_list\<UnderlyingType\>) 建構子

建構一個 [Array](../) 物件，並用指定的 initializer list（其中包含 **UnderlyingType** 類型的元素）填充其值。

```cpp
System::Array<T>::Array(std::initializer_list<UnderlyingType> init)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| init | std::initializer_list\<[UnderlyingType](../underlyingtype/)\> | 包含用於填充陣列的元素的 initializer list |

## Array::Array(const std::array\<UnderlyingType, InitArraySize\>\&) 建構子

建構一個 [Array](../) 物件，並用指定的陣列（其中包含 **UnderlyingType** 類型的元素）填充其值。

```cpp
template<std::size_t> System::Array<T>::Array(const std::array<UnderlyingType, InitArraySize> &init)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| InitArraySize | **init** 陣列的元素數量。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| init | const std::array\<[UnderlyingType](../underlyingtype/), InitArraySize\>\& | [Array](../) 用於複製到正在建構的陣列中。 |

## Array::Array(std::initializer_list\<bool\>, int) 建構子

建構一個 [Array](../) 物件，並用指定的 initializer list（其中包含 bool 類型的元素）填充其值。

```cpp
System::Array<T>::Array(std::initializer_list<bool> init, int=0)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| init | std::initializer_list\<**bool**\> | 包含用於填充陣列的元素的 initializer list |

## 另見

* 型別定義 [ValueType](../valuetype/)
* 型別定義 [UnderlyingType](../underlyingtype/)
* 類別 [Array](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)