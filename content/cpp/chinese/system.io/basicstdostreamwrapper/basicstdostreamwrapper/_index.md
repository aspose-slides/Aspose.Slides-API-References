---
title: BasicSTDOStreamWrapper()
second_title: Aspose.Slides for C++ API 参考
description: 构造 BasicSTDOStreamWrapper 的新实例。
type: docs
weight: 14
url: /zh/system.io/basicstdostreamwrapper/basicstdostreamwrapper/
---
## BasicSTDOStreamWrapper::BasicSTDOStreamWrapper(std::basic_ostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) 构造函数

构造 [BasicSTDOStreamWrapper](../) 的新实例。

```cpp
System::IO::BasicSTDOStreamWrapper<T, typename>::BasicSTDOStreamWrapper(std::basic_ostream<char_type, traits_type> &str, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | std::basic_ostream\<[char_type](../../stdiostreamwrapperbase/char_type/), [traits_type](../../stdiostreamwrapperbase/traits_type/)\>\& | 流的引用 |
| mode | [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/) | 包装模式 |

## BasicSTDOStreamWrapper::BasicSTDOStreamWrapper(const BasicSTDOStreamWrapper\&) 构造函数

拷贝构造函数。已删除。

```cpp
System::IO::BasicSTDOStreamWrapper<T, typename>::BasicSTDOStreamWrapper(const BasicSTDOStreamWrapper &)=delete
```

## 另请参阅

* Enum [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/)
* Typedef [char_type](../../stdiostreamwrapperbase/char_type/)
* Typedef [traits_type](../../stdiostreamwrapperbase/traits_type/)
* Class [BasicSTDOStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)