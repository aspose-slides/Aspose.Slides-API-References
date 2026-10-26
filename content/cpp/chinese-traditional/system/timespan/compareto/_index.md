---
title: CompareTo()
second_title: Aspose.Slides for C++ API 參考
description: 比較目前的物件與指定的物件。
type: docs
weight: 27
url: /zh-hant/system/timespan/compareto/
---
## TimeSpan::CompareTo(TimeSpan) const 方法

比較目前的物件與指定的物件。

```cpp
constexpr int System::TimeSpan::CompareTo(TimeSpan value) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [TimeSpan](../) | 與目前的物件比較的 [TimeSpan](../) 物件 |

### 傳回值

- 1，若目前的物件代表的時間間隔短於 **value**；0，若目前的物件代表的時間間隔等於 **value**；1，若目前的物件代表的時間間隔長於 **value**

## TimeSpan::CompareTo(const SharedPtr\<Object\>\&) const 方法

比較目前的物件與指定的物件。

```cpp
int System::TimeSpan::CompareTo(const SharedPtr<Object> &obj) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 與目前的物件比較的 [TimeSpan](../) 物件 |

### 傳回值

- 1，若目前的物件代表的時間間隔短於 **value**；0，若目前的物件代表的時間間隔等於 **value**；1，若目前的物件代表的時間間隔長於 **value**

## 參見

* 型別定義 [SharedPtr](../../sharedptr/)
* 類別 [TimeSpan](../)
* 類別 [Object](../../object/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)