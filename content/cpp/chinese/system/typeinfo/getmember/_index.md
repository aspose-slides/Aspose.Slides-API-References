---
title: GetMember()
second_title: Aspose.Slides for C++ API 参考
description: 获取具有指定名称的成员列表。
type: docs
weight: 495
url: /zh/system/typeinfo/getmember/
---
## TypeInfo::GetMember(const String\&) const 方法

获取具有指定名称的成员列表。

```cpp
ArrayPtr<SharedPtr<System::Reflection::MemberInfo>> System::TypeInfo::GetMember(const String &name) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | const [String](../../string/)\& | 要获取的成员的名称。 |

### 返回值

[Array](../../array/) 的成员描述符（如果未找到成员则为空）。

## 另见

* 类型定义 [ArrayPtr](../../arrayptr/)
* 类型定义 [SharedPtr](../../sharedptr/)
* 类 [MemberInfo](../../../system.reflection/memberinfo/)
* 类 [String](../../string/)
* 类 [TypeInfo](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)