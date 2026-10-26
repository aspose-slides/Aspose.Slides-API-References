---
title: IsEmpty()
second_title: Aspose.Slides for C++ API 參考
description: 檢查字串是否為空。
type: docs
weight: 14
url: /zh-hant/system/testtools/isempty/
---
## TestTools::IsEmpty(const System::String\&) 方法

檢查字串是否為空。

```cpp
static bool System::TestTools::IsEmpty(const System::String &str)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) 用於檢查是否為空。 |

### 返回值

若字串為空（null-length），則回傳 True，否則回傳 false。

## TestTools::IsEmpty(const SharedPtr\<T\>\&) 方法

檢查集合是否為空。

```cpp
template<typename T> static bool System::TestTools::IsEmpty(const SharedPtr<T> &collection)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 集合型別。 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| collection | const [SharedPtr](../../sharedptr/)\<T\>\& | 用於檢查的集合。 |

### 返回值

若集合的元素數量為零，則回傳 True，否則回傳 false。

## 另請參閱

* 型別別名 [SharedPtr](../../sharedptr/)
* 類別 [String](../../string/)
* 結構 [TestTools](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)