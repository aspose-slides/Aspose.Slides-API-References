---
title: BasicSystemIOStreamBuf()
second_title: Aspose.Slides for C++ API 参考
description: 构造一个新的 BasicSystemIOStreamBuf 实例。
type: docs
weight: 14
url: /zh/system.io/basicsystemiostreambuf/basicsystemiostreambuf/
---
## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf() 构造函数

构造一个新的 [BasicSystemIOStreamBuf](../) 实例。

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf()
```

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(const SharedPtr\<Stream\>\&, SystemIOStreamWrappingMode, const std::locale\&) 构造函数

构造一个新的 [BasicSystemIOStreamBuf](../) 实例。

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(const SharedPtr<Stream> &str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary, const std::locale &locale=std::locale())
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 指向流的智能指针 |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | 包装模式 |
| locale | const std::locale\& | [Stream](../../stream/) 的区域设置 |

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(const BasicSystemIOStreamBuf\&) 构造函数

复制构造函数。已删除。

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(const BasicSystemIOStreamBuf &)=delete
```

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(BasicSystemIOStreamBuf\&&) 构造函数

移动构造函数。

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(BasicSystemIOStreamBuf &&right) noexcept
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| right | [BasicSystemIOStreamBuf](../)\&& | [Object](../../../system/object/) 将被移动 |

## 另请参见

* 枚举 [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [BasicSystemIOStreamBuf](../)
* 类 [Stream](../../stream/)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)