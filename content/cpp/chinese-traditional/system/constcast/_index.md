---
title: ConstCast()
second_title: Aspose.Slides for C++ API 參考
description: 已棄用的轉型已結束。
type: docs
weight: 2575
url: /zh-hant/system/constcast/
---
## System::ConstCast(const SmartPtr\<TFrom\>\&) 函數

已棄用的轉型已結束。

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ConstCast(const SmartPtr<TFrom> &obj)
```

### 模板參數

| Parameter | Description |
| --- | --- |
| TTo | 目標指向類型。 |
| TFrom | 來源指向類型。 |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SmartPtr](../smartptr/)\<TFrom\>\& | 來源指標。 |

### 返回值

如果允許轉型，則返回轉型結果；否則返回 nullptr。

## 備註

對 [SmartPtr](../smartptr/) 物件執行 const cast。

## 另請參閱

* 類別 [SmartPtr](../smartptr/)
* 結構 [CastResult](../castresult/)
* 命名空間 [System](../)
* 程式庫 [Aspose.Slides](../../)