---
title: BasicSTDOStreamWrapper()
second_title: Aspose.Slides for C++ API 參考
description: 建構 BasicSTDOStreamWrapper 的新實例。
type: docs
weight: 14
url: /zh-hant/system.io/basicstdostreamwrapper/basicstdostreamwrapper/
---
## BasicSTDOStreamWrapper::BasicSTDOStreamWrapper(std::basic_ostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) 建構子

建構 [BasicSTDOStreamWrapper](../) 的新實例。

```cpp
System::IO::BasicSTDOStreamWrapper<T, typename>::BasicSTDOStreamWrapper(std::basic_ostream<char_type, traits_type> &str, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | std::basic_ostream\<[char_type](../../stdiostreamwrapperbase/char_type/), [traits_type](../../stdiostreamwrapperbase/traits_type/)\>\& | 對串流的參照 |
| mode | [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/) | 包裝模式 |

## BasicSTDOStreamWrapper::BasicSTDOStreamWrapper(const BasicSTDOStreamWrapper\&) 建構子

拷貝建構子。已刪除。

```cpp
System::IO::BasicSTDOStreamWrapper<T, typename>::BasicSTDOStreamWrapper(const BasicSTDOStreamWrapper &)=delete
```

## 相關參考

* 列舉 [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/)
* 型別定義 [char_type](../../stdiostreamwrapperbase/char_type/)
* 型別定義 [traits_type](../../stdiostreamwrapperbase/traits_type/)
* 類別 [BasicSTDOStreamWrapper](../)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)