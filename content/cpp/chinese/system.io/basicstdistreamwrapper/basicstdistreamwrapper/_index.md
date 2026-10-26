---
title: BasicSTDIStreamWrapper()
second_title: Aspose.Slides for C++ API 参考
description: 构造一个新的 BasicSTDIStreamWrapper 实例。
type: docs
weight: 14
url: /zh/system.io/basicstdistreamwrapper/basicstdistreamwrapper/
---
## BasicSTDIStreamWrapper::BasicSTDIStreamWrapper(std::basic_istream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) 构造函数

构造一个新的 [BasicSTDIStreamWrapper](../) 实例。

```cpp
System::IO::BasicSTDIStreamWrapper<T, typename>::BasicSTDIStreamWrapper(std::basic_istream<char_type, traits_type> &str, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | std::basic_istream\<[char_type](../../stdiostreamwrapperbase/char_type/), [traits_type](../../stdiostreamwrapperbase/traits_type/)\>\& | The reference to the stream |
| mode | [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/) | Wrapping mode |

## BasicSTDIStreamWrapper::BasicSTDIStreamWrapper(const BasicSTDIStreamWrapper\&) 构造函数

拷贝构造函数。已删除。

```cpp
System::IO::BasicSTDIStreamWrapper<T, typename>::BasicSTDIStreamWrapper(const BasicSTDIStreamWrapper &)=delete
```

## 另请参见

* 枚举 [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/)
* 类型别名 [char_type](../../stdiostreamwrapperbase/char_type/)
* 类型别名 [traits_type](../../stdiostreamwrapperbase/traits_type/)
* 类 [BasicSTDIStreamWrapper](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)