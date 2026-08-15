---
title: TryParse()
second_title: Aspose.Slides for C++ API 參考
description: 將指定的包含數字字串表示形式的字串轉換為等效的雙精度浮點值。
type: docs
weight: 14
url: /zh-hant/system/double/tryparse/
---
## Double::TryParse(const String\&, double\&) method

將指定的包含數字字串表示形式的字串轉換為等效的雙精度浮點值。

```cpp
static bool System::Double::TryParse(const String &value, double &result)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串。 |
| result | **double**\& | 指向雙精度浮點變數的參考，該變數用於存放轉換結果。 |

### 返回值

如果轉換成功則返回 true，否則 - false。

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, double\&) method

將指定的包含數字字串表示形式的字串，使用提供的格式資訊與數字樣式，轉換為等效的雙精度浮點值。

```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, double &result)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串。 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles 列舉值的位元組合，用於指定允許的數字字串表示樣式。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 指向包含字串格式資訊的物件的指標。 |
| result | **double**\& | 指向雙精度浮點變數的參考，該變數用於存放轉換結果。 |

### 返回值

如果轉換成功則返回 true，否則 - false。

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, double\&) method




```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, double &result)
```

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, double\&) method




```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, double &result)
```

## Double::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, double\&) method




```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, double &result)
```

## 另見

* 列舉 [NumberStyles](../../../system.globalization/numberstyles/)
* 型別別名 [SharedPtr](../../sharedptr/)
* 類別 [String](../../string/)
* 類別 [IFormatProvider](../../iformatprovider/)
* 類別 [CultureInfo](../../../system.globalization/cultureinfo/)
* 類別 [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* 結構 [Double](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)