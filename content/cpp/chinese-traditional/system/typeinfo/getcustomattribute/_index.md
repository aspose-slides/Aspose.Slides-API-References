---
title: GetCustomAttribute()
second_title: Aspose.Slides for C++ API 參考
description: 搜尋具有指定類型且套用於目前物件所表示類型的自訂屬性。
type: docs
weight: 573
url: /zh-hant/system/typeinfo/getcustomattribute/
---
## TypeInfo::GetCustomAttribute(const TypeInfo\&) const method

搜尋具有指定類型且套用於目前物件所表示類型的自訂屬性。

```cpp
ObjectPtr System::TypeInfo::GetCustomAttribute(const TypeInfo &attributeType) const
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | 指向表示屬性類型的 [TypeInfo](../) 物件的常量參考 |

### Return Value

指向代表找到的屬性的物件的指標；如果沒有符合搜尋條件的屬性，則為空指標

## See Also

* 類別 [SmartPtr](../../smartptr/)
* 類別 [TypeInfo](../)
* 命名空間 [System](../../)
* 程式庫 [Aspose.Slides](../../../)