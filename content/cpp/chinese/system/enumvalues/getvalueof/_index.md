---
title: GetValueOf()
second_title: Aspose.Slides C++ API 参考文档
description: 返回具有指定名称的枚举常量的装箱值。
type: docs
weight: 53
url: /zh/system/enumvalues/getvalueof/
---
## EnumValues::GetValueOf(const String\&, bool) const 方法

返回具有指定名称的枚举常量的装箱值。

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(const String &str, bool ignoreCase) const override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const [String](../../string/)\& | 枚举常量的名称 |
| ignoreCase | **bool** | 指定在解释枚举常量名称时是否应忽略大小写 |

### 返回值

一个装箱值，其对应的枚举常量名称在 **str** 中指定。

## EnumValues::GetValueOf(long) const 方法

返回具有指定值的枚举常量的装箱值。

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(long val) const override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| val | long | 枚举常量的值 |

### 返回值

一个装箱值，其对应的枚举常量值在 **str** 中指定。

## 参见

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [String](../../string/)
* Class [EnumValues](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)