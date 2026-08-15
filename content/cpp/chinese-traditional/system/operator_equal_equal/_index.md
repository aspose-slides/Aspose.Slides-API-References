---
title: operator==()
second_title: Aspose.Slides for C++ API 參考
description: 
type: docs
weight: 2042
url: /zh-hant/system/operator_equal_equal/
---
## System::operator==(ArraySegment\<T\>, ArraySegment\<T\>) 函式




```cpp
template<typename T> bool System::operator==(ArraySegment<T> a, ArraySegment<T> b)
```

## System::operator==(std::nullptr_t, DateTime) 函式




```cpp
constexpr bool System::operator==(std::nullptr_t, DateTime)
```

## System::operator==(std::nullptr_t, const DateTimeOffset\&) 函式




```cpp
constexpr bool System::operator==(std::nullptr_t, const DateTimeOffset &)
```

## System::operator==(std::nullptr_t, const Nullable\<T\>\&) 函式


判斷指定的 [Nullable](../nullable/) 物件是否表示等於 null 的值。

```cpp
template<typename T> bool System::operator==(std::nullptr_t, const Nullable<T> &other)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| other | std::nullptr_t | 常量參考，用於測試 [Nullable](../nullable/) 物件 |

### 返回值

如果指定的物件表示 null 值則返回 true，否則返回 false

## System::operator==(const T1\&, const Nullable\<T2\>\&) 函式


判斷指定的值是否與由指定的 [Nullable](../nullable/) 物件所表示的值相等，透過對這些值套用 [operator==()](./) 來比較。

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator==(const T1 &some, const Nullable<T2> &other)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T1 | 第一個比較值的類型 |
| T2 | 表示第二個比較值之 [Nullable](../nullable/) 物件的底層類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| some | const T1\& | 作為第一個比較值使用的常量參考 |
| other | const [Nullable](../nullable/)\<T2\>\& | 表示第二個比較值之 [Nullable](../nullable/) 物件的常量參考 |

### 返回值

如果比較值相等則返回 true，否則返回 false

## System::operator==(const SmartPtr\<X\>\&, const SmartPtr\<Y\>\&) 函式


比較兩個智慧指標是否相等。

```cpp
template<class X,class Y> bool System::operator==(const SmartPtr<X> &x, const SmartPtr<Y> &y)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| X | 第一個指標所指向的類型 |
| Y | 第二個指標所指向的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | 第一個要比較的指標 |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | 第二個要比較的指標 |

### 返回值

如果指標相符則返回 true，否則返回 false。

## System::operator==(std::nullptr_t, SmartPtr\<X\> const\&) 函式


檢查智慧指標是否為 null。

```cpp
template<class X> bool System::operator==(std::nullptr_t, SmartPtr<X> const &x)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| X | 指標所指向的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | std::nullptr_t | 要檢查的指標 |

### 返回值

如果指標為 null 則返回 true，否則返回 false。

## System::operator==(const SmartPtr\<X\>\&, const Y *) 函式


將智慧指標與簡單 (C) 指標進行相等比較。

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, Y>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator==(const SmartPtr<X> &x, const Y *y)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| X | 智慧指標的類型 |
| Y | 簡單指標的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | 要比較的智慧指標（左） |
| y | const Y * | 要比較的指標（右） |

### 返回值

如果指標相符則返回 true，否則返回 false。

## System::operator==(const X *, const SmartPtr\<Y\>\&) 函式


將智慧指標與簡單 (C) 指標進行相等比較。

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, X>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator==(const X *x, const SmartPtr<Y> &y)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| X | 簡單指標的類型 |
| Y | 智慧指標的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | const X * | 要比較的指標（右） |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | 要比較的智慧指標（左） |

### 返回值

如果指標相符則返回 true，否則返回 false。

## System::operator==(T const\&, std::nullptr_t) 函式


檢查值型別物件 (已轉譯的 C# 結構等) 是否為 null。

```cpp
template<class T> std::enable_if<!std::is_scalar<T>::value &&!std::is_pointer<T>::value &&!std::is_array<T>::value &&detail::has_method_is_null<T>::value, bool>::type System::operator==(T const &x, std::nullptr_t)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 值型別 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | T const\& | 要檢查的 [Object](../object/) |

### 返回值

如果物件為 null 則返回 true，否則返回 false。

## System::operator==(std::nullptr_t, T const\&) 函式


檢查值型別物件 (已轉譯的 C# 結構等) 是否為 null。

```cpp
template<class T> std::enable_if<!std::is_scalar<T>::value &&!std::is_pointer<T>::value &&!std::is_array<T>::value &&detail::has_method_is_null<T>::value, bool>::type System::operator==(std::nullptr_t, T const &x)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 值型別 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | std::nullptr_t | 要檢查的 [Object](../object/) |

### 返回值

如果物件為 null 則返回 true，否則返回 false。

## System::operator==(Chars\&, const String\&) 函式


[String](../string/) 比較。

```cpp
template<class Chars,typename std::enable_if< IsStringLiteral< Chars, char_t >::value >::type *> bool System::operator==(Chars &left, const String &right)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| Chars | [String](../string/) 文字常量類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| left | Chars\& | 要比較的 [String](../string/) 文字 |
| right | const [String](../string/)\& | 要比較的 [String](../string/) |

### 返回值

如果字串相符則返回 true，否則返回 false。

## System::operator==(T\&, const String\&) 函式


[String](../string/) 比較。

```cpp
template<class T,typename std::enable_if< IsStringPointer< T, char_t >::value >::type *> bool System::operator==(T &left, const String &right)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | [String](../string/) 指標類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| left | T\& | 要比較的 [String](../string/) 指標 |
| right | const [String](../string/)\& | 要比較的 [String](../string/) |

### 返回值

如果字串相符則返回 true，否則返回 false。

## System::operator==(const SharedPtr\<Object\>\&, const String\&) 函式


[Object](../object/) 與字串比較。

```cpp
bool System::operator==(const SharedPtr<Object> &left, const String &right)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| left | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | 要轉為字串並比較的 [Object](../object/) |
| right | const [String](../string/)\& | 要比較的 [String](../string/) |

### 返回值

如果物件的字串表示等於該字串則返回 true，否則返回 false。

## System::operator==(std::nullptr_t, const String\&) 函式


檢查字串是否為 null。

```cpp
bool System::operator==(std::nullptr_t, const String &str)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | std::nullptr_t | 要檢查的 [String](../string/) |

### 返回值

如果字串為 null 則返回 true，否則返回 false。

## System::operator==(std::nullptr_t, TimeSpan) 函式




```cpp
constexpr bool System::operator==(std::nullptr_t, TimeSpan)
```

## System::operator==(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) 函式


判斷目前物件與指定物件所表示的 URI 是否相等。

```cpp
bool System::operator==(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| uri1 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | 要比較的第一個 [Uri](../uri/) 物件 |
| uri2 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | 要比較的第二個 [Uri](../uri/) 物件 |

### 返回值

如果 URI 相等則返回 true，否則返回 false

## 另請參閱

* Typedef [SharedPtr](../sharedptr/)
* 類別 [ArraySegment](../arraysegment/)
* 類別 [DateTime](../datetime/)
* 類別 [DateTimeOffset](../datetimeoffset/)
* 類別 [Nullable](../nullable/)
* 類別 [SmartPtr](../smartptr/)
* 類別 [Object](../object/)
* 類別 [String](../string/)
* 類別 [TimeSpan](../timespan/)
* 類別 [Uri](../uri/)
* Struct [IsNullable](../isnullable/)
* 命名空間 [System](../)
* Library [Aspose.Slides](../../)