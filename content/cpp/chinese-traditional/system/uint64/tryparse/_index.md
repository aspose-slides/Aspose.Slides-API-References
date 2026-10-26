---
title: TryParse()
second_title: Aspose.Slides for C++ API 參考文件
description: 將指定的字串（其內容為數字的字串表示形式）轉換為等效的 64 位元無號整數。
type: docs
weight: 14
url: /zh-hant/system/uint64/tryparse/
---
## UInt64::TryParse(const String\&, uint64_t\&) 方法

將指定的字串（其內容為數字的字串表示形式）轉換為等效的 64 位元無號整數。

```cpp
static bool System::UInt64::TryParse(const String &value, uint64_t &result)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串。 |
| result | **uint64_t**\& | 指向 64 位元無號整數變數的參考，儲存轉換結果。 |

### 傳回值

若轉換成功則傳回 True，否則傳回 False。

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint64_t\&) 方法

將指定的字串（其內容為數字的字串表示形式）使用提供的格式資訊和數字樣式轉換為等效的 64 位元無號整數。

```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint64_t &result)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串。 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles 列舉值的位元組合，用以指定允許的數字字串表示樣式。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 指向包含字串格式資訊之物件的指標。 |
| result | **uint64_t**\& | 指向 64 位元無號整數變數的參考，儲存轉換結果。 |

### 傳回值

若轉換成功則傳回 True，否則傳回 False。

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint64_t\&) 方法

```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint64_t &result)
```

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint64_t\&) 方法

```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint64_t &result)
```

## UInt64::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint64_t\&) 方法

```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint64_t &result)
```

## 另見

* 列舉 [NumberStyles](../../../system.globalization/numberstyles/)
* 型別定義 [SharedPtr](../../sharedptr/)
* 類別 [String](../../string/)
* 類別 [IFormatProvider](../../iformatprovider/)
* 類別 [CultureInfo](../../../system.globalization/cultureinfo/)
* 類別 [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* 結構 [UInt64](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)