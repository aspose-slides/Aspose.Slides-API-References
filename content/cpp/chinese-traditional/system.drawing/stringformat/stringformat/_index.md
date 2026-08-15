---
title: StringFormat()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立 StringFormat 類別的新實例。
type: docs
weight: 1
url: /zh-hant/system.drawing/stringformat/stringformat/
---
## StringFormat::StringFormat() 建構函式

建立 [StringFormat](../) 類別的新實例。

```cpp
System::Drawing::StringFormat::StringFormat()
```

## StringFormat::StringFormat(StringFormatFlags, int32_t) 建構函式

建立 [StringFormat](../) 類別的新實例，並使用指定的格式旗標與語言。

```cpp
System::Drawing::StringFormat::StringFormat(StringFormatFlags options, int32_t language=0)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| options | [StringFormatFlags](../../stringformatflags/) | 一個由 StringFormatFlags 列舉值組成的位元組合，用於指定所建立物件所代表的字串格式 |
| language | **int32_t** | 文字的語言 |

## StringFormat::StringFormat(const SharedPtr\<StringFormat\>\&) 建構函式

複製建構函式。

```cpp
System::Drawing::StringFormat::StringFormat(const SharedPtr<StringFormat> &format)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| format | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../)\>\& | 用於複製的 [StringFormat](../) 物件 |

## 另見

* 列舉 [StringFormatFlags](../../stringformatflags/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [StringFormat](../)
* 命名空間 [System::Drawing](../../)
* 程式庫 [Aspose.Slides](../../../)