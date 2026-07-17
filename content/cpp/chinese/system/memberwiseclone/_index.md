---
title: MemberwiseClone()
second_title: Aspose.Slides C++ API 参考
description: 使用拷贝构造函数执行成员逐个克隆。
type: docs
weight: 2562
url: /zh/system/memberwiseclone/
---
## System::MemberwiseClone(T *) 函数

使用拷贝构造函数执行成员逐个克隆。

```cpp
template<typename T> SmartPtr<Object> System::MemberwiseClone(T *ptr)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 要使用拷贝构造函数构造的类。子类信息将丢失。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ptr | T * | 指向要克隆的对象的指针。 |

### 返回值

指向克隆对象的指针。

## 另请参见

* 类 [SmartPtr](../smartptr/)
* 类 [Object](../object/)
* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)