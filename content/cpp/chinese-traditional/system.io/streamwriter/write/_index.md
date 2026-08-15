---
title: Write()
second_title: Aspose.Slides for C++ API 參考文件
description: 將指定的字元寫入串流。
type: docs
weight: 79
url: /zh-hant/system.io/streamwriter/write/
---
## StreamWriter::Write(char_t) 方法


將指定的字元寫入串流。

```cpp
void System::IO::StreamWriter::Write(char_t value) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | char_t | 要寫入的字元 |

## StreamWriter::Write(const String\&) 方法


將指定的字串寫入串流。

```cpp
void System::IO::StreamWriter::Write(const String &value) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | 要寫入的字串 |

## StreamWriter::Write(const SharedPtr\<Object\>\&) 方法


將指定物件的字串表示寫入串流。

```cpp
void System::IO::StreamWriter::Write(const SharedPtr<Object> &obj) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 要寫入的物件 |

## StreamWriter::Write(const ArrayPtr\<char_t\>\&) 方法


將指定陣列中的所有字元寫入串流。

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | 包含要寫入之字元的陣列 |

## StreamWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) 方法


將指定字元陣列中指定的 UTF-16 子範圍寫入串流。

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | 包含要寫入之字元的陣列 |
| index | **int32_t** | **buffer** 中子範圍開始的 0 基索引 |
| count | **int32_t** | 要寫入之子範圍的字元數；-1 表示子範圍延伸至 **buffer** 陣列結尾 |

## StreamWriter::Write(const char_t *) 方法


將指定的 C 字串寫入串流。

```cpp
void System::IO::StreamWriter::Write(const char_t *buffer) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const char_t * | 要寫入的 C 字串 |

## StreamWriter::Write(const System::SharedPtr\<T\>\&) 方法


將指定物件的字串表示寫入串流。

```cpp
template<typename T> void System::IO::StreamWriter::Write(const System::SharedPtr<T> &obj)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 物件的型別 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const [System::SharedPtr](../../../system/sharedptr/)\<T\>\& | 要寫入的物件 |

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 類別 [StreamWriter](../)
* 類別 [String](../../../system/string/)
* 類別 [Object](../../../system/object/)
* 命名空間 [System::IO](../../)
* Library [Aspose.Slides](../../../)