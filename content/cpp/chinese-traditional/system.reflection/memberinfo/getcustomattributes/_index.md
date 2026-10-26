---
title: GetCustomAttributes()
second_title: Aspose.Slides for C++ API 參考
description: 返回一個陣列，其中包含表示套用於目前物件所代表類型的所有自訂屬性的物件。
type: docs
weight: 66
url: /zh-hant/system.reflection/memberinfo/getcustomattributes/
---
## MemberInfo::GetCustomAttributes(const TypeInfo\&, bool) const 方法

返回一個陣列，其中包含表示套用於目前物件所代表類型的所有自訂屬性的物件。

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(const TypeInfo &attributeType, bool inherit=false) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| attributeType | const [TypeInfo](../../../system/typeinfo/)\& | 要查找的屬性類型。 |
| inherit | **bool** | 是否也檢查繼承的屬性。 |

## MemberInfo::GetCustomAttributes(bool) const 方法

返回一個陣列，其中包含表示套用於目前物件所代表類型的所有自訂屬性的物件。

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(bool inherit=false) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| inherit | **bool** | 是否也檢查繼承的屬性。 |

## 另請參閱

* 類型別名 [ArrayPtr](../../../system/arrayptr/)
* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [Object](../../../system/object/)
* 類別 [TypeInfo](../../../system/typeinfo/)
* 類別 [MemberInfo](../)
* 命名空間 [System::Reflection](../../)
* 函式庫 [Aspose.Slides](../../../)