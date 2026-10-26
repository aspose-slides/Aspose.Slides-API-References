---
title: BoxEnum()
second_title: Aspose.Slides for C++ API 參考
description: 將列舉類型包裝，以便作為 Object 進行傳播。
type: docs
weight: 196
url: /zh-hant/system/objectext/boxenum/
---
## ObjectExt::BoxEnum(T) 方法

將列舉類型包裝，以便作為 [Object](../../object/) 傳播。

```cpp
template<typename T> static SmartPtr<System::BoxedValueBase> System::ObjectExt::BoxEnum(T enumValue)
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| T | [Enum](../../enum/) 類型以進行包裝。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| enumValue | T | [Enum](../../enum/) 值以進行包裝。 |

### 返回值

已包裝的 enum 值。

## 另請參閱

* 類別 [SmartPtr](../../smartptr/)
* 類別 [BoxedValueBase](../../boxedvaluebase/)
* 類別 [ObjectExt](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)