---
title: ArrayInitializerCast()
second_title: Aspose.Slides for C++ API 參考
description: 將陣列基本值轉換（C# 會隱式執行此操作，但 C++ 顯然不會）。
type: docs
weight: 209
url: /zh-hant/system/objectext/arrayinitializercast/
---
## ObjectExt::ArrayInitializerCast(From ...) 方法

將陣列的基本值轉換（C# 會隱式執行此操作，但 C++ 顯然不會）。

```cpp
template<typename To,typename ...> static std::enable_if<(std::is_fundamental<To>::value), std::array<To, sizeof...(From)>>::type System::ObjectExt::ArrayInitializerCast(From ...args)
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| To | 目標類型。 |
| From | 來源類型。 |

### 引數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| args | From ... | 要轉換並推入目標陣列的值。 |

### 返回值

[Array](../../array/) 包含所有參數的已轉換副本，順序相同。

## 另請參閱

* 類別 [ObjectExt](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)