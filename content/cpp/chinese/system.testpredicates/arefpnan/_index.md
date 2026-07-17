---
title: AreFPNaN()
second_title: Aspose.Slides for C++ API 参考
description: 命名空间详情
type: docs
weight: 1
url: /zh/system.testpredicates/arefpnan/
---
## System::TestPredicates::AreFPNaN(T1, T2) 函数

命名空间 [Details](../../system.testpredicates.details/)

```cpp
template<typename T1,typename T2> std::enable_if<std::numeric_limits<T1>::has_quiet_NaN &&std::numeric_limits<T2>::has_quiet_NaN, bool>::type System::TestPredicates::AreFPNaN(T1 lhs, T2 rhs)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T1 | 第一个浮点类型。 |
| T2 | 第二个浮点类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs | T1 | 第一个浮点值。 |
| rhs | T2 | 第二个浮点值。 |

### 返回值

如果 **lhs** 和 **rhs** 都是浮点值则返回 true，否则返回 false。

## 备注

检查两个浮点值是否均为 NaN。处理支持非信号 NaN 的情况。

## System::TestPredicates::AreFPNaN(T1, T2) 函数

检查两个浮点值是否均为 NaN。处理不支持非信号 NaN 的情况。

```cpp
template<typename T1,typename T2> std::enable_if<!std::numeric_limits<T1>::has_quiet_NaN||!std::numeric_limits<T2>::has_quiet_NaN, bool>::type System::TestPredicates::AreFPNaN(T1 lhs, T2 rhs)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T1 | 第一个浮点类型。 |
| T2 | 第二个浮点类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs | T1 | 第一个浮点值。 |
| rhs | T2 | 第二个浮点值。 |

### 返回值

始终返回 false，因为不支持 NaN 值。

## 另请参阅

* 命名空间 [System::TestPredicates](../)
* 库 [Aspose.Slides](../../)