---
title: BasicSystemOStreamWrapper()
second_title: Aspose.Slides C++ API 参考
description: 构造一个新的 BasicSystemOStreamWrapper 实例。
type: docs
weight: 1
url: /zh/system.io/basicsystemostreamwrapper/basicsystemostreamwrapper/
---
## BasicSystemOStreamWrapper::BasicSystemOStreamWrapper(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) 构造函数


构造一个新的 [BasicSystemOStreamWrapper](../) 实例。

```cpp
System::IO::BasicSystemOStreamWrapper<Elem, Traits>::BasicSystemOStreamWrapper(SharedPtr<Stream> str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\> | 流的指针 |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | 包装模式 |

## BasicSystemOStreamWrapper::BasicSystemOStreamWrapper(const BasicSystemOStreamWrapper\&) 构造函数


复制构造函数。已删除。

```cpp
System::IO::BasicSystemOStreamWrapper<Elem, Traits>::BasicSystemOStreamWrapper(const BasicSystemOStreamWrapper &)=delete
```

## BasicSystemOStreamWrapper::BasicSystemOStreamWrapper(BasicSystemOStreamWrapper\&&) 构造函数


移动构造函数。

```cpp
System::IO::BasicSystemOStreamWrapper<Elem, Traits>::BasicSystemOStreamWrapper(BasicSystemOStreamWrapper &&right) noexcept
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| right | [BasicSystemOStreamWrapper](../)\&& | 要移动的[Object](../../../system/object/) |

## See Also

* Enum [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [Stream](../../stream/)
* 类 [BasicSystemOStreamWrapper](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)