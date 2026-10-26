---
title: Cast()
second_title: Aspose.Slides for C++ API 參考
description: 對 SmartPtr 物件執行轉型。
type: docs
weight: 2510
url: /zh-hant/system/cast/
---
## System::Cast(SmartPtr\<TFrom\> const\&) 函式

對 [SmartPtr](../smartptr/) 物件執行轉型。

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast(SmartPtr<TFrom> const &obj)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| TTo | 目標指向類型。 |
| TFrom | 來源指向類型。 |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | 來源指標。 |

### 傳回值

如果允許轉型，則傳回轉型結果。

## 另見

* 類別 [SmartPtr](../smartptr/)
* 結構 [IsExceptionWrapper](../isexceptionwrapper/)
* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)