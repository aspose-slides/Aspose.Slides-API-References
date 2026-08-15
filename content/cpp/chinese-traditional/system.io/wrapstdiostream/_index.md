---
title: WrapSTDIOStream()
second_title: Aspose.Slides for C++ API 參考
description: "用於 std::basic_istream-like 串流的包裝函式。"
type: docs
weight: 469
url: /zh-hant/system.io/wrapstdiostream/
---
## System::IO::WrapSTDIOStream(std::basic_istream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) function

用於 std::basic_istream-like 串流的包裝函式。

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_istream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | std::basic_istream\<char_type, traits_type\>\& | std::basic_istream-like 串流 |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | 包裝模式 |

### 返回值

[BasicSTDIStreamWrapper](../basicstdistreamwrapper/) wrapper

## System::IO::WrapSTDIOStream(std::basic_ostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) function

用於 std::basic_ostream-like 串流的包裝函式。

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_ostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | std::basic_ostream\<char_type, traits_type\>\& | std::basic_ostream-like 串流 |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | 包裝模式 |

### 返回值

[BasicSTDOStreamWrapper](../basicstdostreamwrapper/) wrapper

## System::IO::WrapSTDIOStream(std::basic_iostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode, STDIOStreamPositionPreference) function

用於 std::basic_iostream-like 串流的包裝函式。

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_iostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary, STDIOStreamPositionPreference pref_pos=STDIOStreamPositionPreference::Zero)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | std::basic_iostream\<char_type, traits_type\>\& | std::basic_iostream-like 串流 |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | 包裝模式 |
| pref_pos | [STDIOStreamPositionPreference](../stdiostreampositionpreference/) | 若讀寫位置不同，將首選的讀寫位置 |

### 返回值

[BasicSTDIOStreamWrapper](../basicstdiostreamwrapper/) wrapper

## 另見

* Enum [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)
* Enum [STDIOStreamPositionPreference](../stdiostreampositionpreference/)
* Typedef [SharedPtr](../../system/sharedptr/)
* 類別 [Stream](../stream/)
* 命名空間 [System::IO](../)
* Library [Aspose.Slides](../../)