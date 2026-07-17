---
title: ConstCast()
second_title: Aspose.Slides C++ API 参考
description: 已弃用的转换结束。
type: docs
weight: 2536
url: /zh/system/constcast/
---
## System::ConstCast(const SmartPtr\<TFrom\>\&) function

已弃用的转换结束。

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ConstCast(const SmartPtr<TFrom> &obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| TTo | 目标指向类型。 |
| TFrom | 源指向类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const [SmartPtr](../smartptr/)\<TFrom\>\& | 源指针。 |

### 返回值

如果允许转换则返回转换结果，否则返回 nullptr。

## 备注

对 [SmartPtr](../smartptr/) 对象执行 const 转换。

## 另见

* 类 [SmartPtr](../smartptr/)
* 结构体 [CastResult](../castresult/)
* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)