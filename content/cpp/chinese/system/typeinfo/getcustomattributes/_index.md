---
title: GetCustomAttributes()
second_title: Aspose.Slides for C++ API 参考
description: 返回一个数组，其中包含表示已应用于该类型的所有自定义属性的对象。
type: docs
weight: 586
url: /zh/system/typeinfo/getcustomattributes/
---
## TypeInfo::GetCustomAttributes() const 方法

返回一个数组，其中包含表示已应用于该类型的所有自定义属性的对象。

```cpp
ArrayPtr<ObjectPtr> System::TypeInfo::GetCustomAttributes() const
```

## TypeInfo::GetCustomAttributes(const TypeInfo\&, bool) const 方法

返回一个数组，其中包含表示已应用于该类型的特定属性的对象。

```cpp
ArrayPtr<ObjectPtr> System::TypeInfo::GetCustomAttributes(const TypeInfo &attributeType, bool inherit) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | 要查找的属性的类型。 |
| inherit | **bool** | 是否同时查找继承的属性。 |

## 参见

* Typedef [ArrayPtr](../../arrayptr/)
* 类 [SmartPtr](../../smartptr/)
* 类 [TypeInfo](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)