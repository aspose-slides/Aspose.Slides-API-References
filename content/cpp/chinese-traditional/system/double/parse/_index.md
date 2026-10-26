---
title: Parse()
second_title: Aspose.Slides for C++ API 參考
description: 將包含數字字串表示形式的指定字串轉換為等效的雙精度浮點值。
type: docs
weight: 1
url: /zh-hant/system/double/parse/
---
## Double::Parse(const String\&) method

將包含數字字串表示形式的指定字串轉換為等效的雙精度浮點值。

```cpp
static double System::Double::Parse(const String &value)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串。 |

### 返回值

等於由指定字串所表示的數字的雙精度浮點值。

## Double::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) method

將包含數字字串表示形式的指定字串，使用提供的格式資訊，轉換為等效的雙精度浮點值。

```cpp
static double System::Double::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 指向包含字串格式資訊之物件的指標。 |

### 返回值

等於由指定字串所表示的數字的雙精度浮點值。

## Double::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) method




```cpp
static double System::Double::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Double::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) method




```cpp
static double System::Double::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Double::Parse(const String\&, std::nullptr_t) method




```cpp
static double System::Double::Parse(const String &value, std::nullptr_t)
```

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) method

將包含數字字串表示形式的指定字串，使用提供的格式資訊與數字樣式，轉換為等效的雙精度浮點值。

```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串。 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | 指定允許的字串表示形式之樣式的 NumberStyles 列舉值的位元組合。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 指向包含字串格式資訊之物件的指標。 |

### 返回值

等於由指定字串所表示的數字的雙精度浮點值。

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) method




```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) method




```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Double::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) method




```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## 另請參閱

* 列舉 [NumberStyles](../../../system.globalization/numberstyles/)
* 類型別名 [SharedPtr](../../sharedptr/)
* 類別 [String](../../string/)
* 類別 [IFormatProvider](../../iformatprovider/)
* 類別 [CultureInfo](../../../system.globalization/cultureinfo/)
* 類別 [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* 結構 [Double](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)