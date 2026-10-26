---
title: GetHashCode()
second_title: Aspose.Slides for C++ API 參考
description: 返回指定標量值的雜湊碼。
type: docs
weight: 2484
url: /zh-hant/system/gethashcode/
---
## System::GetHashCode(const T\&) 函式

返回指定標量值的雜湊碼。

```cpp
template<typename T> std::enable_if<std::is_scalar<T>::value, int>::type System::GetHashCode(const T &obj)
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| T | 函式產生雜湊碼之值的類型 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| obj | const T\& | 要產生雜湊碼的值 |

### 返回值

為指定值產生的雜湊碼

## System::GetHashCode(const T\&) 函式

返回指定物件的雜湊碼。

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&System::IsSmartPtr<T>::value, int>::type System::GetHashCode(const T &obj)
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| T | 函式產生雜湊碼之物件的類型 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| obj | const T\& | 指向要產生雜湊碼之物件的[SmartPtr](../smartptr/) |

### 返回值

為指定物件產生的雜湊碼

## System::GetHashCode(const T\&) 函式

返回指定例外物件的雜湊碼。

```cpp
template<typename T> std::enable_if<System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| T | 函式產生雜湊碼之物件的類型 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| obj | const T\& | 包含要產生雜湊碼之物件的Exception Wrapper |

### 返回值

為指定物件產生的雜湊碼

## System::GetHashCode(const T\&) 函式

返回指定非智慧指標也非例外之物件的雜湊碼。

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&!System::IsSmartPtr<T>::value &&!System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| T | 函式產生雜湊碼之物件的類型 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| obj | const T\& | 指向要產生雜湊碼之物件的 const 參考 |

### 返回值

為指定物件產生的雜湊碼

## System::GetHashCode(const std::thread::id\&) 函式

對 std::thread::id 的特化；返回指定執行緒物件的雜湊碼。

```cpp
int System::GetHashCode(const std::thread::id &id)
```

## 另請參閱

* 結構 [IsSmartPtr](../issmartptr/)
* 結構 [IsExceptionWrapper](../isexceptionwrapper/)
* 命名空間 [System](../)
* 程式庫 [Aspose.Slides](../../)