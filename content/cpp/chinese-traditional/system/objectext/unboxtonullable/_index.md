---
title: UnboxToNullable()
second_title: Aspose.Slides for C++ API 參考文件
description: 將物件解箱為可空類型。
type: docs
weight: 79
url: /zh-hant/system/objectext/unboxtonullable/
---
## ObjectExt::UnboxToNullable(const SmartPtr\<Object\>\&, bool) 方法

將物件解箱為可空類型。

```cpp
template<class T> static Nullable<T> System::ObjectExt::UnboxToNullable(const SmartPtr<Object> &obj, bool safe=1)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 目標類型。 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) 以解箱。 |
| safe | **bool** | 如果為 true，失敗時返回 nullptr，否則拋出 InvalidCastException。 |

### 返回值

已解箱的可空值（可能為 null）。

## 另見

* 類別 [Nullable](../../nullable/)
* 類別 [SmartPtr](../../smartptr/)
* 類別 [Object](../../object/)
* 類別 [ObjectExt](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)