---
title: PrintTo()
second_title: Aspose.Slides for C++ API 參考文件
description: 將值印至 ostream。主要用於除錯。
type: docs
weight: 2146
url: /zh-hant/system/printto/
---
## System::PrintTo(DateTime, std::ostream *) 函式

將值印至 ostream。主要用於除錯。

```cpp
void System::PrintTo(DateTime value, std::ostream *stream)
```
## System::PrintTo(DateTimeOffset, std::ostream *) 函式

將值印至 ostream。主要用於除錯。

```cpp
void System::PrintTo(DateTimeOffset value, std::ostream *stream)
```
## System::PrintTo(const Decimal\&, ::std::ostream *) 函式

將指定物件所表示的值寫入指定的輸出串流。

```cpp
void System::PrintTo(const Decimal &d, ::std::ostream *os)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| d | const [Decimal](../decimal/)\& | 要印入串流的 [Decimal](../decimal/) 物件 |
| os | ::std::ostream * | 用來印出指定物件的串流 |

## System::PrintTo(const Details_Exception\&, std::ostream *) 函式

將值印至 ostream。主要用於除錯。

```cpp
void System::PrintTo(const Details_Exception &exception, std::ostream *stream)
```

## System::PrintTo(const ExceptionWrapper\<T\>\&, std::ostream *) 函式

將值印至 ostream。主要用於除錯。

```cpp
template<typename T> void System::PrintTo(const ExceptionWrapper<T> &exception_wrapper, std::ostream *stream)
```

## System::PrintTo(const Guid\&, std::ostream *) 函式

將值印至 ostream。主要用於除錯。

```cpp
void System::PrintTo(const Guid &value, std::ostream *stream)
```

## System::PrintTo(const Nullable\<T\>\&, std::ostream *) 函式

將值印至 ostream。主要用於除錯。

```cpp
template<typename T> void System::PrintTo(const Nullable<T> &value, std::ostream *stream)
```

## System::PrintTo(const System::Object\&, std::ostream *) 函式

將值印至 ostream。主要用於除錯。

```cpp
void System::PrintTo(const System::Object &value, std::ostream *stream)
```

## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) 函式

將值印至 ostream。主要用於除錯。

```cpp
template<typename T> std::enable_if_t<detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) 函式

將值印至 ostream。主要用於除錯。

```cpp
template<typename T> std::enable_if_t<!detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## System::PrintTo(const System::String\&, std::ostream *) 函式

將字串印至 ostream。主要用於除錯。

```cpp
void System::PrintTo(const System::String &value, std::ostream *os)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [System::String](../string/)\& | 要印出的值。 |
| os | std::ostream * | 目標 ostream。 |

## System::PrintTo(TimeSpan, std::ostream *) 函式

將值印至 ostream。主要用於除錯。

```cpp
void System::PrintTo(TimeSpan value, std::ostream *stream)
```

## System::PrintTo(const WeakPtr\<T\>\&, std::ostream *) 函式

將值印至 ostream。主要用於除錯。

```cpp
template<typename T> void System::PrintTo(const WeakPtr<T> &object_ptr, std::ostream *stream)
```

## 參見

* 類別 [DateTime](../datetime/)
* 類別 [DateTimeOffset](../datetimeoffset/)
* 類別 [Decimal](../decimal/)
* 類別 [Details_Exception](../details_exception/)
* 類別 [ExceptionWrapper](../exceptionwrapper/)
* 類別 [Guid](../guid/)
* 類別 [Nullable](../nullable/)
* 類別 [Object](../object/)
* 類別 [SmartPtr](../smartptr/)
* 類別 [String](../string/)
* 類別 [TimeSpan](../timespan/)
* 類別 [WeakPtr](../weakptr/)
* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)