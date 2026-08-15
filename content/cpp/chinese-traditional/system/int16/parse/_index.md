---
title: Parse()
second_title: Aspose.Slides for C++ API 參考
description: 將包含數字字串表示形式的指定字串轉換為等效的 16 位元有號整數。
type: docs
weight: 1
url: /zh-hant/system/int16/parse/
---
## Int16::Parse(const String\&) 方法

將包含數字字串表示形式的指定字串轉換為等效的 16 位元有號整數。

```cpp
static int16_t System::Int16::Parse(const String &value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串。 |

### 返回值

等於由指定字串所表示之數字的 16 位元有號整數。

## Int16::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) 方法

使用提供的格式資訊，將包含數字字串表示形式的指定字串轉換為等效的 16 位元有號整數。

```cpp
static int16_t System::Int16::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 包含字串格式資訊的物件指標。 |

### 返回值

等於由指定字串所表示之數字的 16 位元有號整數。

## Int16::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) 方法




```cpp
static int16_t System::Int16::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int16::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 方法




```cpp
static int16_t System::Int16::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int16::Parse(const String\&, std::nullptr_t) 方法




```cpp
static int16_t System::Int16::Parse(const String &value, std::nullptr_t)
```

## Int16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) 方法

使用提供的格式資訊與數字樣式，將包含數字字串表示形式的指定字串轉換為等效的 16 位元有號整數。

```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串。 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | 指定允許的數字字串表示樣式之 NumberStyles 列舉值的位元組合。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 包含字串格式資訊的物件指標。 |

### 返回值

等於由指定字串所表示之數字的 16 位元有號整數。

## Int16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) 方法 




```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 方法 




```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int16::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) 方法 




```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## 另請參閱

* 列舉 [NumberStyles](../../../system.globalization/numberstyles/)
* 型別別名 [SharedPtr](../../sharedptr/)
* 類別 [String](../../string/)
* 類別 [Int16](../)
* 類別 [IFormatProvider](../../iformatprovider/)
* 類別 [CultureInfo](../../../system.globalization/cultureinfo/)
* 類別 [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)