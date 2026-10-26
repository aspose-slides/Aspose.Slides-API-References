---
title: GetDescription()
second_title: Aspose.Slides for C++ API 參考
description: 傳回具有指定值的列舉常數的名稱。
type: docs
weight: 53
url: /zh-hant/system/enum/getdescription/
---
## Enum::GetDescription(T) 方法

返回具有指定值的列舉常數的名稱。

```cpp
template<class T> static std::enable_if<std::is_same<T, E>::value||std::is_convertible<T, UnderlyingType>::value, String>::type System::Enum<E, Guard>::GetDescription(T value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | T | 要返回其名稱的列舉常數的值 |

### 傳回值

指定列舉常數的名稱

## 另見

* Typedef [UnderlyingType](../underlyingtype/)
* 類別 [String](../../string/)
* 結構 [Enum](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)