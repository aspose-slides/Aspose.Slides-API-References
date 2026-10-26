---
title: GetCustomAttributes()
second_title: Aspose.Slides for C++ API 參考
description: 傳回包含表示套用於該類型的所有自訂屬性的物件陣列。
type: docs
weight: 586
url: /zh-hant/system/typeinfo/getcustomattributes/
---
## TypeInfo::GetCustomAttributes() const 方法

傳回包含表示套用於該類型的所有自訂屬性的物件陣列。

```cpp
ArrayPtr<ObjectPtr> System::TypeInfo::GetCustomAttributes() const
```

## TypeInfo::GetCustomAttributes(const TypeInfo\&, bool) const 方法

傳回包含表示套用於該類型的特定屬性的物件陣列。

```cpp
ArrayPtr<ObjectPtr> System::TypeInfo::GetCustomAttributes(const TypeInfo &attributeType, bool inherit) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | 要搜尋的屬性類型。 |
| inherit | **bool** | 是否同時搜尋繼承的屬性。 |

## 參見

* Typedef [ArrayPtr](../../arrayptr/)
* 類別 [SmartPtr](../../smartptr/)
* 類別 [TypeInfo](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)