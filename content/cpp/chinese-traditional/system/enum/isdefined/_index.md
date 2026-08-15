---
title: IsDefined()
second_title: Aspose.Slides for C++ API 參考
description: 判斷指定的值是否為列舉類型 E 的成員。
type: docs
weight: 27
url: /zh-hant/system/enum/isdefined/
---
## Enum::IsDefined(E) 方法


判斷指定的值是否為列舉類型 **E** 的成員。

```cpp
static bool System::Enum<E, Guard>::IsDefined(E value)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | E | 要檢查的值 |

### 傳回值

True 如果 **value** 為列舉 **E** 的成員，否則返回 false

## Enum::IsDefined(T) 方法


判斷指定的值是否為列舉類型 **T** 的成員。

```cpp
template<class T> static std::enable_if<std::is_convertible<T, UnderlyingType>::value, bool>::type System::Enum<E, Guard>::IsDefined(T value)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | T | 要檢查的值 |

### 傳回值

True 如果 **value** 為列舉 **T** 的成員，否則返回 false

## Enum::IsDefined(const String\&) 方法


判斷具有指定名稱的值是否為列舉 **E** 的成員之一。

```cpp
static bool System::Enum<E, Guard>::IsDefined(const String &name)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | const [String](../../string/)\& | 要檢查的名稱 |

### 傳回值

True 如果存在具有指定名稱的列舉 **E** 成員則返回 True。

## 參見

* 型別定義 [UnderlyingType](../underlyingtype/)
* 類別 [String](../../string/)
* 結構 [Enum](../)
* 名稱空間 [System](../../)
* 程式庫 [Aspose.Slides](../../../)