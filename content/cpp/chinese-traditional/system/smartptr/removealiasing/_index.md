---
title: RemoveAliasing()
second_title: Aspose.Slides for C++ API 參考
description: 從指標中移除別名（由別名建構函式建立），確保它管理（若為 shared）或追蹤（若為 weak）它所指向的相同物件。
type: docs
weight: 170
url: /zh-hant/system/smartptr/removealiasing/
---
## SmartPtr::RemoveAliasing() const 方法

從指標中移除別名（由別名建構函式建立），確保它管理（如果為 shared）或追蹤（如果為 weak）它所指向的相同物件。

```cpp
SmartPtr_ System::SmartPtr<T>::RemoveAliasing() const
```

### 傳回值

指向此指標指向之相同物件的指標，負責該物件的生命週期管理。

## 參見

* 型別別名 [SmartPtr_](../smartptr_/)
* 類別 [SmartPtr](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)