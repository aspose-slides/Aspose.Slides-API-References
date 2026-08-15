---
title: const_pointer_cast()
second_title: Aspose.Slides for C++ API 參考
description: 使用 const_cast 轉換智慧指標。
type: docs
weight: 2939
url: /zh-hant/system/const_pointer_cast/
---
## System::const_pointer_cast(SmartPtr\<X\> const\&) 函式


使用 const_cast 轉換智能指標。

```cpp
template<class Y,class X> SmartPtr<Y> System::const_pointer_cast(SmartPtr<X> const &x)
```


### 範本參數

| 參數 | 說明 |
| --- | --- |
| X | 來源指標的被指向類型。 |
| Y | 目標指標的被指向類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | [SmartPtr](../smartptr/)\<X\> const\& | 來源指標。 |

### 回傳值

轉型後的指標。

## 另見

* 類別 [SmartPtr](../smartptr/)
* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)