---
title: InitObject()
second_title: Aspose.Slides for C++ API 參考
description: 開始對具有共享所有權的物件進行初始化。
type: docs
weight: 2263
url: /zh-hant/system/initobject/
---
## System::InitObject(const SharedPtr\<T\>\&) 函式

開始對具有共享所有權的物件進行初始化。

```cpp
template<typename T> Details::ObjectBuilder<T, SharedPtr<T>> System::InitObject(const SharedPtr<T> &object)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | 要初始化的物件類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<T\>\& | [Object](../object/) 用於初始化 |

### 返回值

為共享指標建構配置的 ObjectBuilder

## 備註

[Object](../object/) 初始化必須以 [Get()](../get/) 呼叫結束

## 另請參閱

* Typedef [SharedPtr](../sharedptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)