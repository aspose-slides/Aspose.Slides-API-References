---
title: ForceStaticCast()
second_title: Aspose.Slides for C++ API 參考
description: 對 SmartPtr 物件執行真實的靜態轉換。
type: docs
weight: 2588
url: /zh-hant/system/forcestaticcast/
---
## System::ForceStaticCast(SmartPtr\<TFrom\> const\&) 函式


對 [SmartPtr](../smartptr/) 物件執行真實的靜態轉換。

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ForceStaticCast(SmartPtr<TFrom> const &obj)
```


### 模板參數

| 參數 | 描述 |
| --- | --- |
| TTo | 目標指向類型。 |
| TFrom | 來源指向類型。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | 來源指標。 |

### 返回值

如果允許轉換則回傳轉換結果，否則行為未定義。

## 另請參閱

* 類別 [SmartPtr](../smartptr/)
* 結構 [CastResult](../castresult/)
* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)