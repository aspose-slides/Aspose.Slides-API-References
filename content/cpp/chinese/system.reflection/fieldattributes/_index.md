---
title: FieldAttributes
second_title: Aspose.Slides for C++ API 参考
description: 反射字段属性。
type: docs
weight: 170
url: /zh/system.reflection/fieldattributes/
---
## FieldAttributes 枚举

反射字段属性。

```cpp
enum class FieldAttributes
```

### Values

| 名称 | 值 | 描述 |
| --- | --- | --- |
| FieldAccessMask | 7 | 成员访问掩码。使用此掩码检索可访问性信息。 |
| PrivateScope | 0 | 不可引用的成员。 |
| Private | 1 | 私有成员。 |
| FamANDAssem | 2 | 私有且程序集作用域的成员。 |
| Assembly | 3 | 程序集作用域的成员。 |
| Family | 4 | 类型及其子类型可访问的成员。 |
| FamORAssem | 5 | 类型、子类型和程序集可访问的成员。 |
| Public | 6 | 任何人都可访问的成员。 |
| Static | 16 | 静态成员，区别于实例成员。 |
| InitOnly | 32 | 只能初始化且不可更改的常量成员。 |
| Literal | 64 | 编译时常量成员。 |
| NotSerialized | 128 | 未序列化的成员。 |
| SpecialName | 512 | 以下名称之一的特殊字段。 |
| PinvokeImpl | 8192 | 互操作转发实现。 |
| ReservedMask | 38144 | 仅供运行时使用的保留标志。 |
| RTSpecialName | 1024 | 运行时应检查名称编码。 |
| HasFieldMarshal | 4096 | 存在封送信息。 |
| HasDefault | 32768 | 存在默认值。 |
| HasFieldRVA | 256 | 存在RVA。 |

## 参见

* 命名空间 [System::Reflection](../)
* 库 [Aspose.Slides](../../)