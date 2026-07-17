---
title: CoalesceInternal()
second_title: Aspose.Slides C++ API 参考
description: 实现对非可空类型的 '??' 运算符的翻译。针对 RT2 可转换为 RT1 的情况的重载。
type: docs
weight: 157
url: /zh/system/objectext/coalesceinternal/
---
## ObjectExt::CoalesceInternal(RT1, F) 方法


实现对非可空类型的“??”运算符的翻译。针对 RT2 可转换为 RT1 的情况的重载。

```cpp
template<typename RT1,typename RT2,typename F> static std::conditional<std::is_convertible<RT2, RT1>::value, RT1, RT2>::type System::ObjectExt::CoalesceInternal(RT1 value, F func)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T0 | 左侧值类型。 |
| T1 | 包含右侧表达式的 lambda 类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | RT1 | 左侧值。 |
| func | F | 右侧表达式。 |

### 返回值

如果左侧值不为 null，返回左侧值；否则计算右侧表达式并返回结果。

## 参见

* 类 [ObjectExt](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)