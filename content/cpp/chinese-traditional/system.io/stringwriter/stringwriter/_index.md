---
title: StringWriter()
second_title: Aspose.Slides for C++ API 參考
description: 使用指定的 StringBuilder 和 IFormatProvider 建構 StringWriter 的新實例。
type: docs
weight: 1
url: /zh-hant/system.io/stringwriter/stringwriter/
---
## StringWriter::StringWriter(const System::SharedPtr\<Text::StringBuilder\>\&, const IFormatProviderPtr\&) 建構子

使用指定的 StringBuilder 與 [IFormatProvider](../../../system/iformatprovider/) 建構 [StringWriter](../) 的新實例。

```cpp
System::IO::StringWriter::StringWriter(const System::SharedPtr<Text::StringBuilder> &sb, const IFormatProviderPtr &formatProvider)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sb | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | 在建構的 [StringWriter](../) 中使用的 StringBuilder 物件 |
| formatProvider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | 用於正在建構的物件的 [IFormatProvider](../../../system/iformatprovider/) 物件 |

## StringWriter::StringWriter(const System::SharedPtr\<Text::StringBuilder\>\&) 建構子

使用指定的 StringBuilder 與來自目前文化的 [IFormatProvider](../../../system/iformatprovider/) 建構 [StringWriter](../) 的新實例。

```cpp
System::IO::StringWriter::StringWriter(const System::SharedPtr<Text::StringBuilder> &sb)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sb | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | 在建構的 [StringWriter](../) 中使用的 StringBuilder 物件 |

## StringWriter::StringWriter(const IFormatProviderPtr\&) 建構子

使用指定的 [IFormatProvider](../../../system/iformatprovider/) 建構 [StringWriter](../) 的新實例。

```cpp
System::IO::StringWriter::StringWriter(const IFormatProviderPtr &formatProvider)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| formatProvider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | 用於正在建構的物件的 [IFormatProvider](../../../system/iformatprovider/) 物件 |

## StringWriter::StringWriter() 建構子

使用來自目前文化的 [IFormatProvider](../../../system/iformatprovider/) 建構 [StringWriter](../) 的新實例。

```cpp
System::IO::StringWriter::StringWriter()
```

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 型別定義 [IFormatProviderPtr](../../../system/iformatproviderptr/)
* 類別 [StringBuilder](../../../system.text/stringbuilder/)
* 類別 [StringWriter](../)
* 命名空間 [System::IO](../../)
* 程式庫 [Aspose.Slides](../../../)