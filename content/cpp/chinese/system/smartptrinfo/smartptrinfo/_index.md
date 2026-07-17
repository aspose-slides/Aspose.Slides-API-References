---
title: SmartPtrInfo()
second_title: Aspose.Slides for C++ API 参考
description: 创建空的 SmartPtrInfo 对象。
type: docs
weight: 1
url: /zh/system/smartptrinfo/smartptrinfo/
---
## SmartPtrInfo::SmartPtrInfo() 构造函数

创建空的 [SmartPtrInfo](../) 对象。

```cpp
System::SmartPtrInfo::SmartPtrInfo()
```

## SmartPtrInfo::SmartPtrInfo(const SmartPtr\<T\>\&) 构造函数

创建 [SmartPtrInfo](../) 对象，并包含特定智能指针的信息。

```cpp
template<typename T> System::SmartPtrInfo::SmartPtrInfo(const SmartPtr<T> &ptr)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | Pointee type. |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ptr | const [SmartPtr](../../smartptr/)\<T\>\& | Smart pointer to create info for. |

## 另见

* 类 [SmartPtrInfo](../)
* 类 [SmartPtr](../../smartptr/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)