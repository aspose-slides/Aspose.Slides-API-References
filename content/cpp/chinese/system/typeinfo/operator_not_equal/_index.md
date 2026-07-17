---
title: operator!=()
second_title: Aspose.Slides C++ API 参考
description: 确定当前对象和指定的 TypeInfo 对象是否不相等。
type: docs
weight: 456
url: /zh/system/typeinfo/operator_not_equal/
---
## TypeInfo::operator!=(const TypeInfo\&) const 方法

确定当前对象和指定的 [TypeInfo](../) 对象是否不相等。

```cpp
bool System::TypeInfo::operator!=(const TypeInfo &info) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| info | const [TypeInfo](../)\& | 要比较的 [TypeInfo](../) 对象 |

### 返回值

如果对象的哈希值不相等，则返回 true，否则 - false

## TypeInfo::operator!=(std::nullptr_t) const 方法

确定当前 [TypeInfo](../) 对象不是空对象，即它表示某种类型。

```cpp
bool System::TypeInfo::operator!=(std::nullptr_t) const
```

### 返回值

如果当前 [TypeInfo](../) 对象不是空对象，则返回 true，否则 - false

## 另请参阅

* 类 [TypeInfo](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)