---
title: operator+()
second_title: Aspose.Slides C++ API 參考
description: 返回一個新的 Decimal 類別實例，該實例表示指定值與指定 Decimal 物件所代表的值的總和。
type: docs
weight: 2185
url: /zh-hant/system/operator_plus/
---
## System::operator+(const T\&, const Decimal\&) 函式

返回一個新的 [Decimal](../decimal/) 類別實例，該實例表示指定值與指定 [Decimal](../decimal/) 物件所代表的值的總和。

```cpp
template<typename T,typename _> Decimal System::operator+(const T &x, const Decimal &d)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | const T\& | 第一個加數 |
| d | const [Decimal](../decimal/)\& | 對 [Decimal](../decimal/) 物件的常量參考，該物件代表第二個加數 |

### 回傳值

一個新的 [Decimal](../decimal/) 類別實例，表示 **x** 與 **d** 所代表的值之總和。

## System::operator+(MulticastDelegate\<T\>, MulticastDelegate\<T\>) 函式

將右側委派的所有回呼連接至左側委派回呼清單的末端。

```cpp
template<typename T> MulticastDelegate<T> System::operator+(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | 將要新增回呼的委派。 |
| rhv | MulticastDelegate\<T\> | 正在新增回呼的委派。 |

### 回傳值

返回一個委派，其包含左側值的回呼，然後是右側的回呼。

## System::operator+(const T1\&, const Nullable\<T2\>\&) 函式

將不可為 null 與可為 null 的值相加。

```cpp
template<typename T1,typename T2,typename> auto System::operator+(const T1 &some, const Nullable<T2> &other) -> System::Nullable<decltype(some+other.get_Value())>
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T1 | 左運算元類型。 |
| T2 | 右運算元類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| some | const T1\& | 左運算元。 |
| other | const [Nullable](../nullable/)\<T2\>\& | 右運算元。 |

### 回傳值

加總結果。

## System::operator+(T\&, const String\&) 函式

[String](../string/) 串接。

```cpp
template<typename T> std::enable_if<IsStringLiteral<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | [String](../string/) 文字型別。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| left | T\& | 要串接至字串的文字。 |
| right | const [String](../string/)\& | [String](../string/) 以進行串接。 |

### 回傳值

串接後的字串。

## System::operator+(T\&, const String\&) 函式

[String](../string/) 串接。

```cpp
template<typename T> std::enable_if<IsStringPointer<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | [String](../string/) 指標類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| left | T\& | [String](../string/) 指標以串接至字串。 |
| right | const [String](../string/)\& | [String](../string/) 以進行串接。 |

### 回傳值

串接後的字串。

## System::operator+(const char_t, const String\&) 函式

[String](../string/) 串接。

```cpp
String System::operator+(const char_t left, const String &right)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| left | const char_t | 要串接至字串的字元。 |
| right | const [String](../string/)\& | [String](../string/) 以進行串接。 |

### 回傳值

串接後的字串。

## 另見

* 類別 [Decimal](../decimal/)
* 類別 [Nullable](../nullable/)
* 類別 [String](../string/)
* 結構 [IsStringLiteral](../isstringliteral/)
* 結構 [IsStringPointer](../isstringpointer/)
* 命名空間 [System](../)
* 程式庫 [Aspose.Slides](../../)