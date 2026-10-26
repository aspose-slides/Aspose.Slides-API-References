---
title: BasicSystemIOStreamWrapper()
second_title: Aspose.Slides C++ API 参考
description: 构造一个新的 BasicSystemIOStreamWrapper 实例。
type: docs
weight: 1
url: /zh/system.io/basicsystemiostreamwrapper/basicsystemiostreamwrapper/
---
## BasicSystemIOStreamWrapper::BasicSystemIOStreamWrapper(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) 构造函数

构造一个新的 [BasicSystemIOStreamWrapper](../) 实例。

```cpp
System::IO::BasicSystemIOStreamWrapper<Elem, Traits>::BasicSystemIOStreamWrapper(SharedPtr<Stream> str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\> | 指向流的指针 |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | 包装模式 |

## BasicSystemIOStreamWrapper::BasicSystemIOStreamWrapper(const BasicSystemIOStreamWrapper\&) 构造函数

复制构造函数。已删除。

```cpp
System::IO::BasicSystemIOStreamWrapper<Elem, Traits>::BasicSystemIOStreamWrapper(const BasicSystemIOStreamWrapper &)=delete
```

## BasicSystemIOStreamWrapper::BasicSystemIOStreamWrapper(BasicSystemIOStreamWrapper\&&) 构造函数

移动构造函数。

```cpp
System::IO::BasicSystemIOStreamWrapper<Elem, Traits>::BasicSystemIOStreamWrapper(BasicSystemIOStreamWrapper &&right) noexcept
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| right | [BasicSystemIOStreamWrapper](../)\&& | 要移动的 [Object](../../../system/object/) |

## 另请参见

* 枚举 [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* 类型别名 [SharedPtr](../../../system/sharedptr/)
* 类 [Stream](../../stream/)
* 类 [BasicSystemIOStreamWrapper](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)