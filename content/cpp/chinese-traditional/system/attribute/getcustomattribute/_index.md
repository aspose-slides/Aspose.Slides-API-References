---
title: GetCustomAttribute()
second_title: Aspose.Slides for C++ API 參考文件
description: 返回套用於指定類型的指定類型的自訂屬性。
type: docs
weight: 1
url: /zh-hant/system/attribute/getcustomattribute/
---
## Attribute::GetCustomAttribute(const TypeInfo\&, const TypeInfo\&) 方法

返回套用於指定類型的指定類型的自訂屬性。

```cpp
static Object::ptr System::Attribute::GetCustomAttribute(const TypeInfo &type, const TypeInfo &attributeType)
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | 要檢索的類型屬性 |
| attributeType | const [TypeInfo](../../typeinfo/)\& | 要檢索的屬性類型 |

### 返回值

取得的屬性，若指定類型沒有指定類型的屬性則返回 null。

## 另請參閱

* Typedef [ptr](../../object/ptr/)
* 類別 [TypeInfo](../../typeinfo/)
* 類別 [Attribute](../)
* 命名空間 [System](../../)
* Library [Aspose.Slides](../../../)