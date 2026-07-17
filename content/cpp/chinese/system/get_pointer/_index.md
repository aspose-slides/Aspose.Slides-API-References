---
title: get_pointer()
second_title: Aspose.Slides for C++ API 参考
description: 获取智能指针引用的对象。
type: docs
weight: 2913
url: /zh/system/get_pointer/
---
## System::get_pointer(System::SmartPtr\<T\> const\&) function

获取智能指针引用的对象。

```cpp
template<class T> T * System::get_pointer(System::SmartPtr<T> const &x)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 被指对象的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | [System::SmartPtr](../smartptr/)\<T\> const\& | 源智能指针。 |

### 返回值

返回传入的智能指针所引用对象的原始指针。

## 另请参阅

* 类 [SmartPtr](../smartptr/)
* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)