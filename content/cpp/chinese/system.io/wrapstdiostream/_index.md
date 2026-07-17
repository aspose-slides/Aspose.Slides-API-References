---
title: WrapSTDIOStream()
second_title: Aspose.Slides C++ API 参考
description: "用于 std::basic_istream 类流的包装函数。"
type: docs
weight: 469
url: /zh/system.io/wrapstdiostream/
---
## System::IO::WrapSTDIOStream(std::basic_istream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) function

用于 std::basic_istream 类流的包装函数。

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_istream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | std::basic_istream\<char_type, traits_type\>\& | std::basic_istream 类流 |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | 包装模式 |

### 返回值

[BasicSTDIStreamWrapper](../basicstdistreamwrapper/) 包装器

## System::IO::WrapSTDIOStream(std::basic_ostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) function

用于 std::basic_ostream 类流的包装函数。

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_ostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | std::basic_ostream\<char_type, traits_type\>\& | std::basic_ostream 类流 |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | 包装模式 |

### 返回值

[BasicSTDOStreamWrapper](../basicstdostreamwrapper/) 包装器

## System::IO::WrapSTDIOStream(std::basic_iostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode, STDIOStreamPositionPreference) function

用于 std::basic_iostream 类流的包装函数。

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_iostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary, STDIOStreamPositionPreference pref_pos=STDIOStreamPositionPreference::Zero)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | std::basic_iostream\<char_type, traits_type\>\& | std::basic_iostream 类流 |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | 包装模式 |
| pref_pos | [STDIOStreamPositionPreference](../stdiostreampositionpreference/) | 如果读写位置不同，则首选的读写位置 |

### 返回值

[BasicSTDIOStreamWrapper](../basicstdiostreamwrapper/) 包装器

## 另请参阅

* 枚举 [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)
* 枚举 [STDIOStreamPositionPreference](../stdiostreampositionpreference/)
* 类型定义 [SharedPtr](../../system/sharedptr/)
* 类 [Stream](../stream/)
* 命名空间 [System::IO](../)
* 库 [Aspose.Slides](../../)