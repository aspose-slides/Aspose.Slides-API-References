---
title: ForceStaticCast()
second_title: Aspose.Slides for C++ API 参考
description: 对 SmartPtr 对象执行真实的静态转换。
type: docs
weight: 2549
url: /zh/system/forcestaticcast/
---
## System::ForceStaticCast(SmartPtr\<TFrom\> const\&) 函数

对 [SmartPtr](../smartptr/) 对象执行真实的静态转换。

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ForceStaticCast(SmartPtr<TFrom> const &obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| TTo | 目标指向类型。 |
| TFrom | 源指向类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | 源指针。 |

### 返回值

如果允许转换，则返回转换结果；否则行为未定义。

## 另见

* 类 [SmartPtr](../smartptr/)
* 结构体 [CastResult](../castresult/)
* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)