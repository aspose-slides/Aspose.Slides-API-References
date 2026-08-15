---
title: operator!=()
second_title: Aspose.Slides for C++ API 參考文件
description: 
type: docs
weight: 2055
url: /zh-hant/system/operator_not_equal/
---
## System::operator!=(ArraySegment\<T\>, ArraySegment\<T\>) 函式




```cpp
template<typename T> bool System::operator!=(ArraySegment<T> a, ArraySegment<T> b)
```

## System::operator!=(std::nullptr_t, DateTime) 函式




```cpp
constexpr bool System::operator!=(std::nullptr_t, DateTime)
```

## System::operator!=(std::nullptr_t, const DateTimeOffset\&) 函式




```cpp
constexpr bool System::operator!=(std::nullptr_t, const DateTimeOffset &)
```

## System::operator!=(std::nullptr_t, const Nullable\<T\>\&) 函式


判斷指定的 [Nullable](../nullable/) 物件是否表示不等於 null 的值。

```cpp
template<typename T> bool System::operator!=(std::nullptr_t, const Nullable<T> &other)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| other | std::nullptr_t | A constant reference to an [Nullable](../nullable/) object to test |

### 傳回值

如果指定的物件表示非 null 值則回傳 true，否則回傳 false

## System::operator!=(const T1\&, const Nullable\<T2\>\&) 函式


判斷指定的值是否不等於由指定的 [Nullable](../nullable/) 物件所表示的值，方法是對這些值套用 [operator!=()](./)。

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator!=(const T1 &some, const Nullable<T2> &other)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T1 | 第一個比較值的類型 |
| T2 | 代表第二個比較值的 [Nullable](../nullable/) 物件的底層類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| some | const T1\& | 作為第一個比較值使用的值的常量參考 |
| other | const [Nullable](../nullable/)\<T2\>\& | 作為第二個比較值使用的 [Nullable](../nullable/) 物件的常量參考 |

### 傳回值

如果比較值不相等則回傳 true，否則回傳 false

## System::operator!=(const SmartPtr\<X\>\&, const SmartPtr\<Y\>\&) 函式


比較兩個智慧指標是否不相等。

```cpp
template<class X,class Y> bool System::operator!=(const SmartPtr<X> &x, const SmartPtr<Y> &y)
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

### 傳回值

如果指標相等則回傳 false，否則回傳 true

## System::operator!=(SmartPtr\<X\> const\&, std::nullptr_t) 函式


檢查智慧指標是否非 null。

```cpp
template<class X> bool System::operator!=(SmartPtr<X> const &x, std::nullptr_t)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| X | 指標所指向的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | [SmartPtr](../smartptr/)\<X\> const\& | 要檢查的指標 |

### 傳回值

如果指標為 null 則回傳 false，否則回傳 true

## System::operator!=(std::nullptr_t, SmartPtr\<X\> const\&) 函式


檢查智慧指標是否非 null。

```cpp
template<class X> bool System::operator!=(std::nullptr_t, SmartPtr<X> const &x)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| X | 指標所指向的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | std::nullptr_t | 要檢查的指標 |

### 傳回值

如果指標為 null 則回傳 false，否則回傳 true

## System::operator!=(const SmartPtr\<X\>\&, const Y *) 函式


將智慧指標與一般 (C) 指標進行不等比較。

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, Y>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator!=(const SmartPtr<X> &x, const Y *y)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| X | 智慧指標的類型 |
| Y | 一般指標的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | 要比較的智慧指標（左） |
| y | const Y * | 要比較的一般指標（右） |

### 傳回值

如果指標相等則回傳 false，否則回傳 true

## System::operator!=(const X *, const SmartPtr\<Y\>\&) 函式


將一般 (C) 指標與智慧指標進行不等比較。

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, X>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator!=(const X *x, const SmartPtr<Y> &y)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| X | 一般指標的類型 |
| Y | 智慧指標的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | const X * | 要比較的一般指標（右） |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | 要比較的智慧指標（左） |

### 傳回值

如果指標相等則回傳 false，否則回傳 true

## System::operator!=(Chars\&, const String\&) 函式


[String](../string/) 比較。

```cpp
template<class Chars,typename std::enable_if< IsStringLiteral< Chars, char_t >::value >::type *> bool System::operator!=(Chars &left, const String &right)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| Chars | [String](../string/) 字面值類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| left | Chars\& | [String](../string/) 字面值以供比較 |
| right | const [String](../string/)\& | [String](../string/) 以供比較 |

### 傳回值

如果字串相等則回傳 false，否則回傳 true

## System::operator!=(T\&, const String\&) 函式


[String](../string/) 比較。

```cpp
template<class T,typename std::enable_if< IsStringPointer< T, char_t >::value >::type *> bool System::operator!=(T &left, const String &right)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | [String](../string/) 指標類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| left | T\& | [String](../string/) 指標以供比較 |
| right | const [String](../string/)\& | [String](../string/) 以供比較 |

### 傳回值

如果字串相等則回傳 false，否則回傳 true

## System::operator!=(const SharedPtr\<Object\>\&, const String\&) 函式


[Object](../object/) 與字串比較。

```cpp
bool System::operator!=(const SharedPtr<Object> &left, const String &right)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| left | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | [Object](../object/) 轉換為字串並比較 |
| right | const [String](../string/)\& | [String](../string/) 以供比較 |

### 傳回值

如果物件的字串表示等於字串則回傳 false，否則回傳 true

## System::operator!=(std::nullptr_t, const String\&) 函式


檢查字串是否為 null。

```cpp
bool System::operator!=(std::nullptr_t, const String &str)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | std::nullptr_t | [String](../string/) 以供檢查 |

### 傳回值

如果字串為 null 則回傳 false，否則回傳 true

## System::operator!=(std::nullptr_t, TimeSpan) 函式




```cpp
constexpr bool System::operator!=(std::nullptr_t, TimeSpan)
```

## System::operator!=(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) 函式


判斷目前與指定物件所表示的 URI 是否不相等。

```cpp
bool System::operator!=(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| uri1 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | 第一個用於比較的 [Uri](../uri/) 物件 |
| uri2 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | 第二個用於比較的 [Uri](../uri/) 物件 |

### 傳回值

如果 URI 不相等則回傳 true，否則回傳 false

## 另請參閱

* 型別別名 [SharedPtr](../sharedptr/)
* 類別 [ArraySegment](../arraysegment/)
* 類別 [DateTime](../datetime/)
* 類別 [DateTimeOffset](../datetimeoffset/)
* 類別 [Nullable](../nullable/)
* 類別 [SmartPtr](../smartptr/)
* 類別 [Object](../object/)
* 類別 [String](../string/)
* 類別 [TimeSpan](../timespan/)
* 類別 [Uri](../uri/)
* 結構 [IsNullable](../isnullable/)
* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)