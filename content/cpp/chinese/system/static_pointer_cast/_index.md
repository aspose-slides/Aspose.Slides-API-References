---
title: static_pointer_cast()
second_title: Aspose.Slides for C++ API 参考
description: 使用 static_cast 将智能指针进行强制转换。
type: docs
weight: 2874
url: /zh/system/static_pointer_cast/
---
## System::static_pointer_cast(SmartPtr\<X\> const\&) 函数

使用 static_cast 将智能指针进行强制转换。

```cpp
template<class Y,class X> SmartPtr<Y> System::static_pointer_cast(SmartPtr<X> const &x)
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