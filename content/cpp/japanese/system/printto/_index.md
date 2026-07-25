---
title: PrintTo()
second_title: Aspose.Slides for C++ API リファレンス
description: ostream に値を出力します。主にデバッグに使用されます。
type: docs
weight: 2146
url: /ja/system/printto/
---
## System::PrintTo(DateTime, std::ostream *) 関数

ostream に値を出力します。主にデバッグに使用されます。

```cpp
void System::PrintTo(DateTime value, std::ostream *stream)
```

## System::PrintTo(DateTimeOffset, std::ostream *) 関数

ostream に値を出力します。主にデバッグに使用されます。

```cpp
void System::PrintTo(DateTimeOffset value, std::ostream *stream)
```

## System::PrintTo(const Decimal\&, ::std::ostream *) 関数

指定されたオブジェクトが表す値を指定された出力ストリームに書き込みます。

```cpp
void System::PrintTo(const Decimal &d, ::std::ostream *os)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| d | const [Decimal](../decimal/)\& | ストリームに出力する[Decimal](../decimal/)オブジェクト |
| os | ::std::ostream * | 指定されたオブジェクトを出力するストリーム |

## System::PrintTo(const Details_Exception\&, std::ostream *) 関数

ostream に値を出力します。主にデバッグに使用されます。

```cpp
void System::PrintTo(const Details_Exception &exception, std::ostream *stream)
```

## System::PrintTo(const ExceptionWrapper\<T\>\&, std::ostream *) 関数

ostream に値を出力します。主にデバッグに使用されます。

```cpp
template<typename T> void System::PrintTo(const ExceptionWrapper<T> &exception_wrapper, std::ostream *stream)
```

## System::PrintTo(const Guid\&, std::ostream *) 関数

ostream に値を出力します。主にデバッグに使用されます。

```cpp
void System::PrintTo(const Guid &value, std::ostream *stream)
```

## System::PrintTo(const Nullable\<T\>\&, std::ostream *) 関数

ostream に値を出力します。主にデバッグに使用されます。

```cpp
template<typename T> void System::PrintTo(const Nullable<T> &value, std::ostream *stream)
```

## System::PrintTo(const System::Object\&, std::ostream *) 関数

ostream に値を出力します。主にデバッグに使用されます。

```cpp
void System::PrintTo(const System::Object &value, std::ostream *stream)
```

## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) 関数

ostream に値を出力します。主にデバッグに使用されます。

```cpp
template<typename T> std::enable_if_t<detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) 関数

ostream に値を出力します。主にデバッグに使用されます。

```cpp
template<typename T> std::enable_if_t<!detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## System::PrintTo(const System::String\&, std::ostream *) 関数

ostream に文字列を出力します。主にデバッグに使用されます。

```cpp
void System::PrintTo(const System::String &value, std::ostream *os)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [System::String](../string/)\& | 出力する値。 |
| os | std::ostream * | 対象のostream。 |

## System::PrintTo(TimeSpan, std::ostream *) 関数

ostream に値を出力します。主にデバッグに使用されます。

```cpp
void System::PrintTo(TimeSpan value, std::ostream *stream)
```

## System::PrintTo(const WeakPtr\<T\>\&, std::ostream *) 関数

ostream に値を出力します。主にデバッグに使用されます。

```cpp
template<typename T> void System::PrintTo(const WeakPtr<T> &object_ptr, std::ostream *stream)
```

## 参照

* クラス [DateTime](../datetime/)
* クラス [DateTimeOffset](../datetimeoffset/)
* クラス [Decimal](../decimal/)
* クラス [Details_Exception](../details_exception/)
* クラス [ExceptionWrapper](../exceptionwrapper/)
* クラス [Guid](../guid/)
* クラス [Nullable](../nullable/)
* クラス [Object](../object/)
* クラス [SmartPtr](../smartptr/)
* クラス [String](../string/)
* クラス [TimeSpan](../timespan/)
* クラス [WeakPtr](../weakptr/)
* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)