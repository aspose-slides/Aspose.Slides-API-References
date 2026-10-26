---
title: operator==()
second_title: Aspose.Slides for C++ API 参考
description: 确定当前对象和指定的 TypeInfo 对象是否相等。
type: docs
weight: 443
url: /zh/system/typeinfo/operator_equal_equal/
---
## TypeInfo::operator==(const TypeInfo\&) const 方法


确定当前对象和指定的 [TypeInfo](../) 对象是否相等。

```cpp
bool System::TypeInfo::operator==(const TypeInfo &info) const
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| info | const [TypeInfo](../)\& | 用于比较的 [TypeInfo](../) 对象 |

### 返回值

如果对象的哈希相等则返回 true，否则返回 false

## TypeInfo::operator==(std::nullptr_t) const 方法


确定当前的 [TypeInfo](../) 对象是否为空对象，即不代表任何类型。

```cpp
bool System::TypeInfo::operator==(std::nullptr_t) const
```


### 返回值

如果当前的 [TypeInfo](../) 对象为空对象则返回 true，否则返回 false

## 另请参见

* 类 [TypeInfo](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)