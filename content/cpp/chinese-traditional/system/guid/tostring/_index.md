---
title: ToString()
second_title: Aspose.Slides for C++ API 參考文件
description: 將目前物件所代表的 GUID 轉換為其字串表示形式。
type: docs
weight: 79
url: /zh-hant/system/guid/tostring/
---
## Guid::ToString() const 方法

將目前物件所代表的 GUID 轉換為其字串表示形式。

```cpp
String System::Guid::ToString() const
```

## Guid::ToString(const String\&) const 方法

將目前物件所代表的 GUID 轉換為其字串表示形式，使用指定的字串格式。

```cpp
String System::Guid::ToString(const String &format) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| format | const [String](../../string/)\& | 要使用的格式 |

### 回傳值

GUID 值的字串表示形式

## Guid::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const 方法

將目前物件所代表的 GUID 轉換為其字串表示形式，使用指定的字串格式與文化。

```cpp
String System::Guid::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| format | const [String](../../string/)\& | 要使用的格式 |
| culture | const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | 要使用的文化 |

### 回傳值

GUID 值的字串表示形式

## 另見

* Typedef [SharedPtr](../../sharedptr/)
* 類別 [String](../../string/)
* 類別 [Guid](../)
* 類別 [CultureInfo](../../../system.globalization/cultureinfo/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)