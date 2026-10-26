---
title: GetCustomAttribute()
second_title: Aspose.Slides C++ API 参考
description: 搜索具有指定类型并应用于当前对象所表示的类型的自定义属性。
type: docs
weight: 573
url: /zh/system/typeinfo/getcustomattribute/
---
## TypeInfo::GetCustomAttribute(const TypeInfo\&) const 方法

搜索具有指定类型并应用于当前对象所表示的类型的自定义属性。

```cpp
ObjectPtr System::TypeInfo::GetCustomAttribute(const TypeInfo &attributeType) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | 对表示要搜索的属性类型的 [TypeInfo](../) 对象的常量引用 |

### 返回值

指向表示找到的属性的对象的指针；如果没有匹配搜索条件的属性，则为空指针

## 另见

* 类 [SmartPtr](../../smartptr/)
* 类 [TypeInfo](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)