---
title: GetName()
second_title: Aspose.Slides for C++ API 參考
description: 傳回具有指定值的列舉常數的名稱。
type: docs
weight: 40
url: /zh-hant/system/enum/getname/
---
## Enum::GetName(T) method

傳回具有指定值的列舉常數的名稱。

```cpp
template<class T> static std::enable_if<std::is_same<T, E>::value||std::is_convertible<T, UnderlyingType>::value, String>::type System::Enum<E, Guard>::GetName(T value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | T | 要回傳其名稱的列舉常數的值 |

### 返回值

指定列舉常數的名稱

## 另見

* Typedef [UnderlyingType](../underlyingtype/)
* Class [String](../../string/)
* Struct [Enum](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)