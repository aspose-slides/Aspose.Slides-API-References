---
title: Next()
second_title: Aspose.Slides for C++ API 参考
description: 返回一个非负的随机数，小于 int32 最大值。
type: docs
weight: 27
url: /zh/system/random/next/
---
## Random::Next() 方法

返回一个非负的随机数，小于 int32 最大值。

```cpp
virtual int32_t System::Random::Next()
```

## Random::Next(int32_t) 方法

返回一个非负的随机数，小于指定的最大值。

```cpp
virtual int32_t System::Random::Next(int32_t maxValue)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| maxValue | **int32_t** | 该方法生成的值将小于此值 |

## Random::Next(int32_t, int32_t) 方法

返回一个位于指定范围内的随机数。

```cpp
virtual int32_t System::Random::Next(int32_t minValue, int32_t maxValue)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| minValue | **int32_t** | 该方法生成的值将大于此值 |
| maxValue | **int32_t** | 该方法生成的值将小于此值 |

## 参见

* 类 [Random](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)