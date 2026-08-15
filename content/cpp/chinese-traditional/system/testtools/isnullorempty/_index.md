---
title: IsNullOrEmpty()
second_title: Aspose.Slides for C++ API 參考文件
description: 檢查集合是否為 null 或為空。
type: docs
weight: 27
url: /zh-hant/system/testtools/isnullorempty/
---
## TestTools::IsNullOrEmpty(const SharedPtr\<T\>\&) 方法

檢查集合是否為 null 或為空。

```cpp
template<typename T> static bool System::TestTools::IsNullOrEmpty(const SharedPtr<T> &collection)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | 集合類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| collection | const [SharedPtr](../../sharedptr/)\<T\>\& | 要檢查的集合。 |

### 回傳值

若集合為 null 或元素計數為零則回傳 true，否則回傳 false。

## TestTools::IsNullOrEmpty(const System::String\&) 方法

檢查字串是否為 null 或為空。

```cpp
static bool System::TestTools::IsNullOrEmpty(const System::String &str)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) 以檢查。 |

### 回傳值

若字串為 null 或長度為零則回傳 true，否則回傳 false。

## 另請參閱

* 型別別名 [SharedPtr](../../sharedptr/)
* 類別 [String](../../string/)
* 結構 [TestTools](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)