---
title: Append()
second_title: Aspose.Slides for C++ API 參考手冊
description: 將字元新增至建構器。
type: docs
weight: 118
url: /zh-hant/system.text/stringbuilder/append/
---
## StringBuilder::Append(char_t) 方法

將字元新增至建構器。

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| c | char_t | 字元值。 |

### 返回值

此指標。

## StringBuilder::Append(char_t, int) 方法

將字元新增至建構器。

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c, int count)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| c | char_t | 字元值。 |
| count | int | 要重複插入字元的次數。 |

### 返回值

此指標。

## StringBuilder::Append(const ArrayPtr\<char_t\>\&) 方法

將字元陣列新增至建構器。

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | 要新增的字元。 |

### 返回值

此指標。

## StringBuilder::Append(const ArrayPtr\<char_t\>\&, int, int) 方法

將字元陣列切片新增至建構器。

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr, int startIndex, int charCount)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | 要新增的字元。 |
| startIndex | int | 切片的起始索引。 |
| charCount | int | 切片長度。 |

### 返回值

此指標。

## StringBuilder::Append(const String\&) 方法

將字串新增至建構器。

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) 要新增。 |

### 返回值

此指標。

## StringBuilder::Append(const String\&, int, int) 方法

將字串切片新增至建構器。

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str, int startIndex, int charCount)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) 要新增。 |
| startIndex | int | 切片的起始索引。 |
| charCount | int | 切片長度。 |

### 返回值

此指標。

## StringBuilder::Append(const SharedPtr\<T\>\&) 方法

將物件的字串表示新增至建構器。

```cpp
template<class T> StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<T> &obj)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | [Object](../../../system/object/) 類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<T\>\& | [Object](../../../system/object/) 要序列化並新增。 |

### 返回值

此指標。

## StringBuilder::Append(const SharedPtr\<StringBuilder\>\&) 方法

將建構器的內容新增至建構器。

```cpp
StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<StringBuilder> &builder)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| builder | const [SharedPtr](../../../system/sharedptr/)\<[StringBuilder](../)\>\& | 要從中新增內容的建構器。 |

### 返回值

此指標。

## StringBuilder::Append(float) 方法

將浮點值新增至建構器。

```cpp
StringBuilder * System::Text::StringBuilder::Append(float f)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| f | **float** | 要序列化並新增的值。 |

### 返回值

此指標。

## StringBuilder::Append(double) 方法

將浮點值新增至建構器。

```cpp
StringBuilder * System::Text::StringBuilder::Append(double df)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| df | **double** | 要序列化並新增的值。 |

### 返回值

此指標。

## StringBuilder::Append(int) 方法

將整數值新增至建構器。

```cpp
StringBuilder * System::Text::StringBuilder::Append(int i)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| i | int | 要序列化並新增的值。 |

### 返回值

此指標。

## StringBuilder::Append(T) 方法

將算術值新增至建構器。

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Append(T value)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 算術類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | T | 要序列化並新增的值。 |

### 返回值

此指標。

## StringBuilder::Append(E) 方法

將列舉值的字串表示新增至建構器。

```cpp
template<class E> std::enable_if<std::is_enum<E>::value, StringBuilder *>::type System::Text::StringBuilder::Append(E e)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| E | [Enum](../../../system/enum/) 類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| e | E | 要序列化並新增的值。 |

### 返回值

此指標。

## 參見

* 類型別名 [ArrayPtr](../../../system/arrayptr/)
* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [StringBuilder](../)
* 類別 [String](../../../system/string/)
* 命名空間 [System::Text](../../)
* 函式庫 [Aspose.Slides](../../../)