---
title: GetCustomAttributes()
second_title: Aspose.Slides for C++ API 参考
description: 返回一个数组，包含表示当前对象所代表的类型上应用的所有自定义属性的对象。
type: docs
weight: 66
url: /zh/system.reflection/memberinfo/getcustomattributes/
---
## MemberInfo::GetCustomAttributes(const TypeInfo\&, bool) const 方法

返回一个数组，包含表示当前对象所代表的类型上应用的所有自定义属性的对象。

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(const TypeInfo &attributeType, bool inherit=false) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| attributeType | const [TypeInfo](../../../system/typeinfo/)\& | 要查找的属性类型。 |
| inherit | **bool** | 是否也检查继承的属性。 |

## MemberInfo::GetCustomAttributes(bool) const 方法

返回一个数组，包含表示当前对象所代表的类型上应用的所有自定义属性的对象。

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(bool inherit=false) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inherit | **bool** | 是否也检查继承的属性。 |

## 另见

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [MemberInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.Slides](../../../)