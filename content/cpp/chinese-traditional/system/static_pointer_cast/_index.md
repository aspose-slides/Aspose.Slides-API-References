---
title: static_pointer_cast()
second_title: Aspose.Slides for C++ API 參考
description: 使用 static_cast 轉換智慧指標。
type: docs
weight: 2913
url: /zh-hant/system/static_pointer_cast/
---
## System::static_pointer_cast(SmartPtr\<X\> const\&) function

使用 static_cast 轉換智慧指標。

```cpp
template<class Y,class X> SmartPtr<Y> System::static_pointer_cast(SmartPtr<X> const &x)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| X | 來源指標指向的類型。 |
| Y | 目標指標指向的類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | [SmartPtr](../smartptr/)\<X\> const\& | 來源指標。 |

### 返回值

轉換後的指標。

## 另請參閱

* 類別 [SmartPtr](../smartptr/)
* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)