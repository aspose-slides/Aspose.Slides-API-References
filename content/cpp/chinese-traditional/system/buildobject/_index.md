---
title: BuildObject()
second_title: Aspose.Slides for C++ API 參考
description: 以共享所有權建立物件。
type: docs
weight: 2250
url: /zh-hant/system/buildobject/
---
## System::BuildObject(Args\&&...) 函式

建立具有共享所有權的物件。

```cpp
template<typename T,typename...> Details::ObjectBuilder<T, SharedPtr<T>> System::BuildObject(Args &&... args)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | Type of object to build |
| Args | Argument types for object construction |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| args | Args\&&... | Arguments to forward to object constructor |

### 傳回值

ObjectBuilder 已配置用於共享指標建構

## 備註

建立 SharedPtr<T> 並回傳其建構器
[Object](../object/) 建構必須以 [Get()](../get/) 呼叫完成

## 另見

* 型別別名 [SharedPtr](../sharedptr/)
* 名稱空間 [System](../)
* 函式庫 [Aspose.Slides](../../)