---
title: Handle()
second_title: Aspose.Slides for C++ API 參考
description: 在每個內部例外上呼叫處理函式，並重新拋出任何未處理的例外。
type: docs
weight: 66
url: /zh-hant/system/details_aggregateexception/handle/
---
## 詳細_AggregateException::Handle(const Func\<Exception, bool\>\&) 方法

對每個內部例外呼叫處理函式，並重新拋出任何未處理的例外。

```cpp
void System::Details_AggregateException::Handle(const Func<Exception, bool> &predicate)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| predicate | const [Func](../../func/)\<[Exception](../../exception/), **bool**\>\& | 一個接受 Exception 並在已處理時回傳 true 的函式。 |

## 備註

如果所有例外都已處理，方法會正常返回；否則，會拋出包含未處理例外的新 AggregateException。

## 另見

* 型別別名 [Exception](../../exception/)
* 類別 [Func](../../func/)
* 類別 [Details_AggregateException](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)