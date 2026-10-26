---
title: Build()
second_title: Aspose.Slides for C++ API 參考
description: 以直接所有權建立物件。
type: docs
weight: 2289
url: /zh-hant/system/build/
---
## System::Build(Args\&&...) 函式


以直接所有權建立物件。

```cpp
template<typename T,typename...> Details::ObjectBuilder<T> System::Build(Args &&... args)
```


### 範本參數

| Parameter | Description |
| --- | --- |
| T | 要建立之物件的類型 |
| Args | 物件建構的引數類型 |

### 引數

| Parameter | Type | Description |
| --- | --- | --- |
| args | Args\&&... | 傳遞給物件建構函式的引數 |

### 傳回值

ObjectBuilder 已配置為直接物件建構

## 備註



[Object](../object/) 建構必須以 [Get()](../get/) 呼叫結束 

## 另見

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)