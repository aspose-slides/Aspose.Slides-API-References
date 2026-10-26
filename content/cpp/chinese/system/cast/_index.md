---
title: Cast()
second_title: Aspose.Slides for C++ API 参考
description: 对 SmartPtr 对象执行转换。
type: docs
weight: 2471
url: /zh/system/cast/
---
## System::Cast(SmartPtr\<TFrom\> const\&) 函数


对 [SmartPtr](../smartptr/) 对象执行转换。

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast(SmartPtr<TFrom> const &obj)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| TTo | Target pointee type. |
| TFrom | Source pointee type. |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | 源指针。 |

### 返回值

如果允许转换，则返回转换结果。

## 另见

* 类 [SmartPtr](../smartptr/)
* 结构体 [IsExceptionWrapper](../isexceptionwrapper/)
* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)