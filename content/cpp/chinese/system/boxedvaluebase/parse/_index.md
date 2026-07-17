---
title: Parse()
second_title: Aspose.Slides for C++ API 参考
description: 将指定枚举中具有指定名称的枚举常量的值装箱。一个参数指定在解释表示枚举常量名称的字符串时是否应忽略大小写。
type: docs
weight: 53
url: /zh/system/boxedvaluebase/parse/
---
## BoxedValueBase::Parse(const TypeInfo\&, const String\&, bool) 方法

将指定枚举中具有指定名称的枚举常量的值装箱。一个参数指定在解释表示枚举常量名称的字符串时是否应忽略大小写。

```cpp
static SharedPtr<Object> System::BoxedValueBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | 指定枚举的类型 |
| str | const [String](../../string/)\& | 要装箱的枚举常量的名称 |
| ignoreCase | **bool** | 指定在解释表示枚举常量名称的字符串时是否应忽略大小写 |

### 返回值

一个指向表示指定枚举常量装箱值的对象的共享指针

## BoxedValueBase::Parse(const TypeInfo\&, const String\&) 方法

将指定枚举中具有指定名称的枚举常量的值装箱。

```cpp
static SharedPtr<Object> System::BoxedValueBase::Parse(const TypeInfo &type, const String &str)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | 指定枚举的类型 |
| str | const [String](../../string/)\& | 要装箱的枚举常量的名称 |

### 返回值

一个指向表示指定枚举常量装箱值的对象的共享指针

## 另请参阅

* 类型定义 [SharedPtr](../../sharedptr/)
* 类 [Object](../../object/)
* 类 [TypeInfo](../../typeinfo/)
* 类 [String](../../string/)
* 类 [BoxedValueBase](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)