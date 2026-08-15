---
title: Join()
second_title: Aspose.Slides for C++ API 參考
description: 使用字串作為分隔符號來連接陣列。
type: docs
weight: 846
url: /zh-hant/system/string/join/
---
## String::Join(const String\&, const ArrayPtr\<String\>\&, int, int) 方法

使用字串作為分隔符號來連接陣列。

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<String> &parts, int startIndex=0, int count=-1)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) 用於在連接時放置於陣列元素之間。 |
| parts | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) 要連接的部分。 |
| startIndex | int | 要開始連接的陣列之第一個索引。 |
| count | int | 要連接的陣列元素數量。-1 代表「直到陣列結束」。 |

### 傳回值

[String](../) 代表聯結的陣列元素。

## String::Join(const String\&, const System::Details::ArrayView\<String\>\&, int, int) 方法

使用字串作為分隔符號來連接陣列。

```cpp
static String System::String::Join(const String &separator, const System::Details::ArrayView<String> &parts, int startIndex=0, int count=-1)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) 用於在連接時放置於陣列元素之間。 |
| parts | const System::Details::ArrayView\<[String](../)\>\& | ArrayView of parts to join. |
| startIndex | int | 要開始連接的陣列之第一個索引。 |
| count | int | 要連接的陣列元素數量。-1 代表「直到陣列結束」。 |

### 傳回值

[String](../) 代表聯結的陣列元素。

## String::Join(const String\&, const SharedPtr\<System::Collections::Generic::IEnumerable\<String\>\>\&) 方法

使用字串作為分隔符號來連接陣列。

```cpp
static String System::String::Join(const String &separator, const SharedPtr<System::Collections::Generic::IEnumerable<String>> &parts)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) 用於在連接時放置於陣列元素之間。 |
| parts | const [SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../)\>\>\& | - parts enumerable object |

### 傳回值

[String](../) 代表聯結的元素。

## String::Join(const String\&, const ArrayPtr\<SharedPtr\<Object\>\>\&) 方法

使用字串作為分隔符號來連接陣列。

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<SharedPtr<Object>> &parts)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) 用於在連接時放置於陣列元素之間。 |
| parts | const [ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\>\& | [Array](../../array/) 要連接的部分。 |

### 傳回值

[String](../) 代表聯結的元素。

## 另請參閱

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [Object](../../object/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)