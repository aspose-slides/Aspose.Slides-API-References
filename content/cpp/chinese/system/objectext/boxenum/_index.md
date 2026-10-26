---
title: BoxEnum()
second_title: Aspose.Slides for C++ API 参考
description: 将枚举类型装箱以便作为 Object 进行传播。
type: docs
weight: 196
url: /zh/system/objectext/boxenum/
---
## ObjectExt::BoxEnum(T) 方法


将枚举类型装箱以便传播为 [Object](../../object/)。

```cpp
template<typename T> static SmartPtr<System::BoxedValueBase> System::ObjectExt::BoxEnum(T enumValue)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | [Enum](../../enum/) 类型以进行装箱。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| enumValue | T | [Enum](../../enum/) 值以进行装箱。 |

### 返回值

装箱的枚举值。

## 另请参见

* 类 [SmartPtr](../../smartptr/)
* 类 [BoxedValueBase](../../boxedvaluebase/)
* 类 [ObjectExt](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)