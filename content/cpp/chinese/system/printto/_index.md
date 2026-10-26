---
title: PrintTo()
second_title: Aspose.Slides C++ API 参考
description: 将值打印到 ostream。主要用于调试。
type: docs
weight: 2120
url: /zh/system/printto/
---
## System::PrintTo(DateTime, std::ostream *) 函数

将值打印到 ostream。主要用于调试。

```cpp
void System::PrintTo(DateTime value, std::ostream *stream)
```

## System::PrintTo(DateTimeOffset, std::ostream *) 函数

将值打印到 ostream。主要用于调试。

```cpp
void System::PrintTo(DateTimeOffset value, std::ostream *stream)
```

## System::PrintTo(const Decimal\&, ::std::ostream *) 函数

将指定对象表示的值写入指定的输出流。

```cpp
void System::PrintTo(const Decimal &d, ::std::ostream *os)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| d | const [Decimal](../decimal/)\& | 将 [Decimal](../decimal/) 对象打印到流 |
| os | ::std::ostream * | 用于打印指定对象的流 |

## System::PrintTo(const Details_Exception\&, std::ostream *) 函数

将值打印到 ostream。主要用于调试。

```cpp
void System::PrintTo(const Details_Exception &exception, std::ostream *stream)
```

## System::PrintTo(const ExceptionWrapper\<T\>\&, std::ostream *) 函数

将值打印到 ostream。主要用于调试。

```cpp
template<typename T> void System::PrintTo(const ExceptionWrapper<T> &exception_wrapper, std::ostream *stream)
```

## System::PrintTo(const Guid\&, std::ostream *) 函数

将值打印到 ostream。主要用于调试。

```cpp
void System::PrintTo(const Guid &value, std::ostream *stream)
```

## System::PrintTo(const Nullable\<T\>\&, std::ostream *) 函数

将值打印到 ostream。主要用于调试。

```cpp
template<typename T> void System::PrintTo(const Nullable<T> &value, std::ostream *stream)
```

## System::PrintTo(const System::Object\&, std::ostream *) 函数

将值打印到 ostream。主要用于调试。

```cpp
void System::PrintTo(const System::Object &value, std::ostream *stream)
```

## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) 函数

将值打印到 ostream。主要用于调试。

```cpp
template<typename T> std::enable_if_t<detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) 函数

将值打印到 ostream。主要用于调试。

```cpp
template<typename T> std::enable_if_t<!detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## System::PrintTo(const System::String\&, std::ostream *) 函数

将字符串打印到 ostream。主要用于调试。

```cpp
void System::PrintTo(const System::String &value, std::ostream *os)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [System::String](../string/)\& | 用于打印。 |
| os | std::ostream * | 目标 ostream。 |

## System::PrintTo(TimeSpan, std::ostream *) 函数

将值打印到 ostream。主要用于调试。

```cpp
void System::PrintTo(TimeSpan value, std::ostream *stream)
```

## System::PrintTo(const WeakPtr\<T\>\&, std::ostream *) 函数

将值打印到 ostream。主要用于调试。

```cpp
template<typename T> void System::PrintTo(const WeakPtr<T> &object_ptr, std::ostream *stream)
```

## 另请参见

* 类 [DateTime](../datetime/)
* 类 [DateTimeOffset](../datetimeoffset/)
* 类 [Decimal](../decimal/)
* 类 [Details_Exception](../details_exception/)
* 类 [ExceptionWrapper](../exceptionwrapper/)
* 类 [Guid](../guid/)
* 类 [Nullable](../nullable/)
* 类 [Object](../object/)
* 类 [SmartPtr](../smartptr/)
* 类 [String](../string/)
* 类 [TimeSpan](../timespan/)
* 类 [WeakPtr](../weakptr/)
* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)