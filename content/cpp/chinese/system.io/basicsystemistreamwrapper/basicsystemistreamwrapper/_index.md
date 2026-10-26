---
title: BasicSystemIStreamWrapper()
second_title: Aspose.Slides for C++ API 参考
description: 构造一个新的 BasicSystemIStreamWrapper 实例。
type: docs
weight: 1
url: /zh/system.io/basicsystemistreamwrapper/basicsystemistreamwrapper/
---
## BasicSystemIStreamWrapper::BasicSystemIStreamWrapper(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) 构造函数

构造一个新的 [BasicSystemIStreamWrapper](../) 实例。

```cpp
System::IO::BasicSystemIStreamWrapper<Elem, Traits>::BasicSystemIStreamWrapper(SharedPtr<Stream> str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\> | 指向流的指针 |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | 包装模式 |

## BasicSystemIStreamWrapper::BasicSystemIStreamWrapper(const BasicSystemIStreamWrapper\&) 构造函数

复制构造函数。已删除。

```cpp
System::IO::BasicSystemIStreamWrapper<Elem, Traits>::BasicSystemIStreamWrapper(const BasicSystemIStreamWrapper &)=delete
```

## BasicSystemIStreamWrapper::BasicSystemIStreamWrapper(BasicSystemIStreamWrapper\&&) 构造函数

移动构造函数。

```cpp
System::IO::BasicSystemIStreamWrapper<Elem, Traits>::BasicSystemIStreamWrapper(BasicSystemIStreamWrapper &&right) noexcept
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| right | [BasicSystemIStreamWrapper](../)\&& | [Object](../../../system/object/) 被移动 |

## 另见

* 枚举 [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Stream](../../stream/)
* 类 [BasicSystemIStreamWrapper](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)