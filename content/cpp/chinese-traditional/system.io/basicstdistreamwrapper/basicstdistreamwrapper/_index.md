---
title: BasicSTDIStreamWrapper()
second_title: Aspose.Slides C++ API 參考
description: 建立 BasicSTDIStreamWrapper 的新實例。
type: docs
weight: 14
url: /zh-hant/system.io/basicstdistreamwrapper/basicstdistreamwrapper/
---
## BasicSTDIStreamWrapper::BasicSTDIStreamWrapper(std::basic_istream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) 建構子

建立 [BasicSTDIStreamWrapper](../) 的新實例。

```cpp
System::IO::BasicSTDIStreamWrapper<T, typename>::BasicSTDIStreamWrapper(std::basic_istream<char_type, traits_type> &str, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | std::basic_istream\<[char_type](../../stdiostreamwrapperbase/char_type/), [traits_type](../../stdiostreamwrapperbase/traits_type/)\>\& | 串流的參考 |
| mode | [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/) | 包裝模式 |

## BasicSTDIStreamWrapper::BasicSTDIStreamWrapper(const BasicSTDIStreamWrapper\&) 建構子

複製建構子。已刪除。

```cpp
System::IO::BasicSTDIStreamWrapper<T, typename>::BasicSTDIStreamWrapper(const BasicSTDIStreamWrapper &)=delete
```

## 另請參閱

* 列舉 [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/)
* 類型別名 [char_type](../../stdiostreamwrapperbase/char_type/)
* 類型別名 [traits_type](../../stdiostreamwrapperbase/traits_type/)
* 類別 [BasicSTDIStreamWrapper](../)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)