---
title: ToString()
second_title: Aspose.Slides for C++ API 參考文件
description: 使用指定的格式和格式提供者將目前物件轉換為字串。
type: docs
weight: 443
url: /zh-hant/system/datetimeoffset/tostring/
---
## DateTimeOffset::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const 方法

將目前物件依指定的格式和格式提供者轉換為字串。

```cpp
String System::DateTimeOffset::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| format | const [String](../../string/)\& | 格式字串。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 格式提供者。 |

### 回傳值

[String](../../string/) 表示目前的 [DateTimeOffset](../) 物件。

## DateTimeOffset::ToString(const SharedPtr\<IFormatProvider\>\&) const 方法

將目前物件依指定的格式提供者轉換為字串。

```cpp
String System::DateTimeOffset::ToString(const SharedPtr<IFormatProvider> &provider) const
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 格式提供者。 |

### 回傳值

[String](../../string/) 表示目前的 [DateTimeOffset](../) 物件。

## DateTimeOffset::ToString(const String\&) const 方法

將目前物件依指定的格式轉換為字串。

```cpp
String System::DateTimeOffset::ToString(const String &format) const
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| format | const [String](../../string/)\& | 格式字串。 |

### 回傳值

[String](../../string/) 表示目前的 [DateTimeOffset](../) 物件。

## DateTimeOffset::ToString() const 方法

將目前物件轉換為字串。

```cpp
String System::DateTimeOffset::ToString() const
```

### 回傳值

[String](../../string/) 表示目前的 [DateTimeOffset](../) 物件。

## 另見

* 型別別名 [SharedPtr](../../sharedptr/)
* 類別 [String](../../string/)
* 類別 [IFormatProvider](../../iformatprovider/)
* 類別 [DateTimeOffset](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)