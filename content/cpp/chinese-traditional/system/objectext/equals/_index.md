---
title: Equals()
second_title: Aspose.Slides for C++ API 參考
description: 
type: docs
weight: 14
url: /zh-hant/system/objectext/equals/
---
## ObjectExt::Equals(const T\&, const T2\&) 方法

```cpp
template<typename T,typename T2> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```

## ObjectExt::Equals(const T\&, const T2\&) 方法

替代 C# [Object.Equals](../../object/equals/) 呼叫，可在 C++ 中適用於任何型別。支援智慧指標類型的重載。

```cpp
template<typename T,typename T2> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | 第一個物件類型。 |
| T2 | 第二個物件類型。 |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const T\& | 第一個物件。 |
| another | const T2\& | 第二個物件。 |

### 傳回值

若物件被視為相等則傳回 true，否則傳回 false。

## ObjectExt::Equals(T, const T2\&) 方法

替代 C# [Object.Equals](../../object/equals/) 呼叫，可在 C++ 中適用於任何型別。支援結構類型的重載。

```cpp
template<typename T,typename T2> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(T obj, const T2 &another)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | 第一個物件類型。 |
| T2 | 第二個物件類型。 |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | T | 第一個物件。 |
| another | const T2\& | 第二個物件。 |

### 傳回值

若物件被視為相等則傳回 true，否則傳回 false。

## ObjectExt::Equals(const T\&, const T2\&) 方法

替代 C# [Object.Equals](../../object/equals/) 呼叫，可在 C++ 中適用於任何型別。支援純量類型的重載。

```cpp
template<typename T,typename T2> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | 第一個物件類型。 |
| T2 | 第二個物件類型。 |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const T\& | 第一個物件。 |
| another | const T2\& | 第二個物件。 |

### 傳回值

若物件被視為相等則傳回 true，否則傳回 false。

## ObjectExt::Equals(const char_t(&), String) 方法

替代 C# [Object.Equals](../../object/equals/) 呼叫，可在 C++ 中適用於任何型別。支援字串常值與字串比較的重載。

```cpp
template<size_t> static bool System::ObjectExt::Equals(const char_t(&obj)[N], String another)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| N | [String](../../string/) 文字大小。 |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const char_t(&) | [String](../../string/) 文字常值。 |
| another | [String](../../string/) | [String](../../string/)。 |

### 傳回值

若字串相符則傳回 true，否則傳回 false。

## ObjectExt::Equals(const float\&, const float\&) 方法

模擬 C# 風格的浮點比較，即使根據 IEC 60559:1989，NaN 不等於任何值（包括 NaN），兩個 NaN 仍被視為相等。

```cpp
bool System::ObjectExt::Equals(const float &obj, const float &another)
```

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const **float**\& | 左側浮點值。 |
| another | const **float**\& | 右側浮點值。 |

### 傳回值

若 **obj** 和 **another** 均為 NaN 或相等則傳回 true，否則傳回 false。

## ObjectExt::Equals(const double\&, const double\&) 方法

模擬 C# 風格的浮點比較，即使根據 IEC 60559:1989，NaN 不等於任何值（包括 NaN），兩個 NaN 仍被視為相等。

```cpp
bool System::ObjectExt::Equals(const double &obj, const double &another)
```

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const **double**\& | 左側浮點值。 |
| another | const **double**\& | 右側浮點值。 |

### 傳回值

若 **obj** 和 **another** 均為 NaN 或相等則傳回 true，否則傳回 false。

## 另見

* 類別 [ObjectExt](../)
* 類別 [String](../../string/)
* 結構 [IsExceptionWrapper](../../isexceptionwrapper/)
* 結構 [IsSmartPtr](../../issmartptr/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)