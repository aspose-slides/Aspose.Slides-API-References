---
title: BindingFlags
second_title: Aspose.Slides C++ API 参考
description: 定义成员和类型的查找模式和绑定。
type: docs
weight: 157
url: /zh/system.reflection/bindingflags/
---
## BindingFlags 枚举

定义成员和类型的查找模式和绑定。

```cpp
enum class BindingFlags
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Default | 0 | 没有特殊选项。 |
| IgnoreCase | 1 | 在查找项时忽略名称的大小写。 |
| DeclaredOnly | 2 | 仅查找在类型中声明而非基类型中声明的成员。 |
| Instance | 4 | 查找实例成员。 |
| Static | 8 | 查找静态成员。 |
| Public | 16 | 查找公共成员。 |
| NonPublic | 32 | 查找非公共成员。 |
| FlattenHierarchy | 64 | 查找基类型的公共和受保护的静态成员。 |
| InvokeMethod | 256 | 调用方法。 |
| CreateInstance | 512 | 创建反射类型的实例。 |
| GetField | 1024 | 获取字段值。 |
| SetField | 2048 | 设置字段值。 |
| GetProperty | 4096 | 获取属性值。 |
| SetProperty | 8192 | 设置属性值。 |
| PutDispProperty | 16384 | 设置 COM 属性。 |
| PutRefDispProperty | 32768 | 设置 COM 引用属性。 |
| ExactBinding | 65536 | 类型绑定必须完全匹配，不能进行任何类型更改。 |
| SuppressChangeType | 131072 | 不受支持。 |
| OptionalParamBinding | 262144 | 根据参数数量选择重载。 |
| IgnoreReturn | 16777216 | 忽略 COM 互操作返回值。 |

## 另请参见

* 命名空间 [System::Reflection](../)
* 库 [Aspose.Slides](../../)