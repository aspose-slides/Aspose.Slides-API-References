---
title: ArrayInitializerCast()
second_title: Aspose.Slides C++ API 参考
description: 转换数组基本值（C# 会隐式完成，但 C++ 显然不会）。
type: docs
weight: 209
url: /zh/system/objectext/arrayinitializercast/
---
## ObjectExt::ArrayInitializerCast(From ...) 方法

将数组基本值进行转换（C# 会隐式完成，但 C++ 显然不会）。

```cpp
template<typename To,typename ...> static std::enable_if<(std::is_fundamental<To>::value), std::array<To, sizeof...(From)>>::type System::ObjectExt::ArrayInitializerCast(From ...args)
```

### 模板参数

| Parameter | Description |
| --- | --- |
| To | 目标类型。 |
| From | 源类型。 |

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| args | From ... | 将值转换并推入目标数组。 |

### 返回值

[Array](../../array/) 包含所有参数按相同顺序转换后的副本。

## 另见

* 类 [ObjectExt](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)