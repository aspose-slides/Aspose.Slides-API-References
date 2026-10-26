---
title: const_pointer_cast()
second_title: Aspose.Slides C++ API 参考
description: 使用 const_cast 对智能指针进行转换。
type: docs
weight: 2900
url: /zh/system/const_pointer_cast/
---
## System::const_pointer_cast(SmartPtr\<X\> const\&) 函数

使用 const_cast 对智能指针进行转换。

```cpp
template<class Y,class X> SmartPtr<Y> System::const_pointer_cast(SmartPtr<X> const &x)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| X | 源指针所指向的类型。 |
| Y | 目标指针所指向的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | [SmartPtr](../smartptr/)\<X\> const\& | 源指针。 |

### 返回值

转换后的指针。

## 另见

* 类 [SmartPtr](../smartptr/)
* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)