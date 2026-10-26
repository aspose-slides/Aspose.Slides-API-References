---
title: dynamic_pointer_cast()
second_title: Aspose.Slides C++ API 参考
description: 使用 dynamic_cast 对智能指针进行转换。
type: docs
weight: 2887
url: /zh/system/dynamic_pointer_cast/
---
## System::dynamic_pointer_cast(SmartPtr\<X\> const\&) 函数

使用 dynamic_cast 将智能指针进行转换。

```cpp
template<class Y,class X> SmartPtr<Y> System::dynamic_pointer_cast(SmartPtr<X> const &x)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| X | 源指针所指对象的类型。 |
| Y | 目标指针所指对象的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | [SmartPtr](../smartptr/)\<X\> const\& | 源指针。 |

### 返回值

转换后的指针。

## 另请参见

* 类 [SmartPtr](../smartptr/)
* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)