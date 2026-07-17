---
title: GetCustomAttribute()
second_title: Aspose.Slides C++ API 参考
description: 返回指定类型上应用的指定类型的自定义属性。
type: docs
weight: 1
url: /zh/system/attribute/getcustomattribute/
---
## Attribute::GetCustomAttribute(const TypeInfo\&, const TypeInfo\&) 方法


返回指定类型上应用的指定类型的自定义属性。

```cpp
static Object::ptr System::Attribute::GetCustomAttribute(const TypeInfo &type, const TypeInfo &attributeType)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | 检索的属性所属的类型 |
| attributeType | const [TypeInfo](../../typeinfo/)\& | 要检索的属性的类型 |

### 返回值

检索到的属性，如果指定的类型没有指定类型的属性，则为 null。

## 另见

* 类型定义 [ptr](../../object/ptr/)
* 类 [TypeInfo](../../typeinfo/)
* 类 [Attribute](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)