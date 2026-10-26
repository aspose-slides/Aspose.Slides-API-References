---
title: WriteLine()
second_title: Aspose.Slides for C++ API 參考
description: 將換行終止字元寫入串流。
type: docs
weight: 92
url: /zh-hant/system.io/streamwriter/writeline/
---
## StreamWriter::WriteLine() 方法

將換行終止字元寫入串流。

```cpp
void System::IO::StreamWriter::WriteLine() override
```

## StreamWriter::WriteLine(const String\&) 方法

將指定的字串寫入串流，並在其後加入換行終止字元。

```cpp
void System::IO::StreamWriter::WriteLine(const String &value) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | 要寫入的字串 |

## StreamWriter::WriteLine(const SharedPtr\<Object\>\&) 方法

將指定物件的字串表示寫入串流，並在其後加入換行終止字元。

```cpp
void System::IO::StreamWriter::WriteLine(const SharedPtr<Object> &obj) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 要寫入的物件 |

## StreamWriter::WriteLine(const ArrayPtr\<char_t\>\&) 方法

將指定陣列中的所有字元寫入串流，並在其後加入換行終止字元。

```cpp
void System::IO::StreamWriter::WriteLine(const ArrayPtr<char_t> &buffer) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | 包含要寫入字元的陣列 |

## StreamWriter::WriteLine(const ArrayPtr\<char_t\>\&, int32_t, int32_t) 方法

將指定字符陣列中指定子範圍的 UTF-16 字元寫入串流，並在其後加入換行終止字元。

```cpp
void System::IO::StreamWriter::WriteLine(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | 包含要寫入字元的陣列 |
| index | **int32_t** | 在 **buffer** 中寫入子範圍開始位置的 0 基索引 |
| count | **int32_t** | 要寫入之子範圍的字元數；-1 表示子範圍結束於 **buffer** 陣列的末端 |

## StreamWriter::WriteLine(const char_t *) 方法

將指定的 C 字串寫入串流，並在其後加入換行終止字元。

```cpp
void System::IO::StreamWriter::WriteLine(const char_t *buffer) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const char_t * | 要寫入的 C 字串 |

## StreamWriter::WriteLine(const System::SharedPtr\<T\>\&) 方法

將指定物件的字串表示寫入串流，並在其後加入換行終止字元。

```cpp
template<typename T> void System::IO::StreamWriter::WriteLine(const System::SharedPtr<T> &obj)
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
* Class [StreamWriter](../)
* Class [String](../../../system/string/)
* Class [Object](../../../system/object/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)