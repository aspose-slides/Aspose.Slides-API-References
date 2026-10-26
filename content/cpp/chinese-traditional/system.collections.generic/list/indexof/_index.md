---
title: IndexOf()
second_title: Aspose.Slides for C++ API 參考
description: 取得特定項目的第一個索引。
type: docs
weight: 222
url: /zh-hant/system.collections.generic/list/indexof/
---
## List::IndexOf(const T\&) const 方法


取得特定項目的第一個索引。

```cpp
int System::Collections::Generic::List<T>::IndexOf(const T &item) const override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| item | const T\& | 要查找的項目。 |

### 返回值

[Index](../../../system/index/) 第一次出現指定項目的索引，若未找到則返回 -1。

## List::IndexOf(const T\&, int) const 方法


在列表中搜尋特定項目。

```cpp
int System::Collections::Generic::List<T>::IndexOf(const T &item, int index) const
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| item | const T\& | 要查找的項目。 |
| index | int | [Index](../../../system/index/) 用於設定開始搜尋的索引。 |

### 返回值

[Index](../../../system/index/) 第一次出現指定項目的索引，若未找到則返回 -1。

## 另見

* 類別 [List](../)
* 命名空間 [System::Collections::Generic](../../)
* 函式庫 [Aspose.Slides](../../../)