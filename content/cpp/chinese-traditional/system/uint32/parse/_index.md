---
title: Parse()
second_title: Aspose.Slides for C++ API 參考文件
description: 將指定的字串（其內容為數字的字串表示）轉換為等價的 32 位元無號整數。
type: docs
weight: 1
url: /zh-hant/system/uint32/parse/
---
## UInt32::Parse(const String\&) 方法

將指定的字串（其內容為數字的字串表示）轉換為等價的 32 位元無號整數。

```cpp
static uint32_t System::UInt32::Parse(const String &value)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串。 |

### 回傳值

等於由指定字串所表示之數字的 32 位元無號整數。

## UInt32::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) 方法

將指定的字串（其內容為數字的字串表示）轉換為等價的 32 位元無號整數，使用提供的格式資訊。

```cpp
static uint32_t System::UInt32::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 指向包含字串格式資訊之物件的指標。 |

### 回傳值

等於由指定字串所表示之數字的 32 位元無號整數。

## UInt32::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) 方法

```cpp
static uint32_t System::UInt32::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt32::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 方法

```cpp
static uint32_t System::UInt32::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt32::Parse(const String\&, std::nullptr_t) 方法

```cpp
static uint32_t System::UInt32::Parse(const String &value, std::nullptr_t)
```

## UInt32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) 方法

將指定的字串（其內容為數字的字串表示）轉換為等價的 32 位元無號整數，使用提供的格式資訊與數字樣式。

```cpp
static uint32_t System::UInt32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串。 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles 列舉值的位元組合，用以指定字串表示之數字允許的樣式。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 指向包含字串格式資訊之物件的指標。 |

### 回傳值

等於由指定字串所表示之數字的 32 位元無號整數。

## UInt32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) 方法

```cpp
static uint32_t System::UInt32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 方法

```cpp
static uint32_t System::UInt32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt32::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) 方法

```cpp
static uint32_t System::UInt32::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## 另見

* 列舉 [NumberStyles](../../../system.globalization/numberstyles/)
* 型別別名 [SharedPtr](../../sharedptr/)
* 類別 [String](../../string/)
* 類別 [IFormatProvider](../../iformatprovider/)
* 類別 [CultureInfo](../../../system.globalization/cultureinfo/)
* 類別 [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* 結構 [UInt32](../)
* 名稱空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)