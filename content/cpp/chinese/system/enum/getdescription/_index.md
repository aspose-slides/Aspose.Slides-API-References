---
title: GetDescription()
second_title: Aspose.Slides C++ API 参考
description: 返回具有指定值的枚举常量的名称。
type: docs
weight: 53
url: /zh/system/enum/getdescription/
---
## Enum::GetDescription(T) 方法

返回具有指定值的枚举常量的名称。

```cpp
template<class T> static std::enable_if<std::is_same<T, E>::value||std::is_convertible<T, UnderlyingType>::value, String>::type System::Enum<E, Guard>::GetDescription(T value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | T | 要返回其名称的枚举常量的值 |

### 返回值

指定枚举常量的名称

## 参见

* 类型定义 [UnderlyingType](../underlyingtype/)
* 类 [String](../../string/)
* 结构体 [Enum](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)