---
title: ToByte()
second_title: Aspose.Slides for C++ API 參考文件
description: 將指定的布林值轉換為等效的 8 位元無號整數。
type: docs
weight: 92
url: /zh-hant/system/convert/tobyte/
---
## Convert::ToByte(bool) 方法

將指定的布林值轉換為等效的 8 位元無號整數。

```cpp
static constexpr uint8_t System::Convert::ToByte(bool value)
```

## Convert::ToByte(uint8_t) 方法

返回指定的 8 位元無號整數。

```cpp
static constexpr uint8_t System::Convert::ToByte(uint8_t value)
```

## Convert::ToByte(int8_t) 方法

將指定的 8 位元有號整數轉換為等效的 8 位元無號整數。

```cpp
static uint8_t System::Convert::ToByte(int8_t value)
```

## Convert::ToByte(uint16_t) 方法

將指定的 16 位元無號整數轉換為等效的 8 位元無號整數。

```cpp
static uint8_t System::Convert::ToByte(uint16_t value)
```

## Convert::ToByte(int16_t) 方法

將指定的 16 位元有號整數轉換為等效的 8 位元無號整數。

```cpp
static uint8_t System::Convert::ToByte(int16_t value)
```

## Convert::ToByte(uint32_t) 方法

將指定的 32 位元無號整數轉換為等效的 8 位元無號整數。

```cpp
static uint8_t System::Convert::ToByte(uint32_t value)
```

## Convert::ToByte(int32_t) 方法

將指定的 32 位元有號整數轉換為等效的 8 位元無號整數。

```cpp
static uint8_t System::Convert::ToByte(int32_t value)
```

## Convert::ToByte(uint64_t) 方法

將指定的 64 位元無號整數轉換為等效的 8 位元無號整數。

```cpp
static uint8_t System::Convert::ToByte(uint64_t value)
```

## Convert::ToByte(int64_t) 方法

將指定的 64 位元有號整數轉換為等效的 8 位元無號整數。

```cpp
static uint8_t System::Convert::ToByte(int64_t value)
```

## Convert::ToByte(float) 方法

將指定的 float 數字轉換為等效的 8 位元無號整數。

```cpp
static uint8_t System::Convert::ToByte(float value)
```

## Convert::ToByte(double) 方法

將指定的 double 數字轉換為等效的 8 位元無號整數。

```cpp
static uint8_t System::Convert::ToByte(double value)
```

## Convert::ToByte(const Decimal\&) 方法

將指定的十進位數字轉換為等效的 8 位元無號整數。

```cpp
static uint8_t System::Convert::ToByte(const Decimal &value)
```

## Convert::ToByte(char_t) 方法

將指定的 Unicode 字元轉換為等效的 8 位元無號整數。

```cpp
static uint8_t System::Convert::ToByte(char_t value)
```

## Convert::ToByte(DateTime) 方法

不支援轉換。始終拋出 InvalidCastException。

```cpp
static uint8_t System::Convert::ToByte(DateTime value)
```

## Convert::ToByte(std::nullptr_t) 方法

將指定的空字串轉換為等效的 8 位元無號整數值。

```cpp
static constexpr uint8_t System::Convert::ToByte(std::nullptr_t)
```

### 返回值

Zero.

## Convert::ToByte(const char_t *) 方法

將包含數字字串表示的指定 c-string 轉換為等效的 8 位元無號整數值。

```cpp
static uint8_t System::Convert::ToByte(const char_t *value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const char_t * | 要轉換的 c-string |

### 返回值

等於指定 c-string 所表示數字的 8 位元無號整數值。

## Convert::ToByte(const String\&) 方法

將包含數字字串表示的指定字串轉換為等效的 8 位元無號整數值。

```cpp
static uint8_t System::Convert::ToByte(const String &value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串 |

### 返回值

等於指定字串所表示數字的 8 位元無號整數值。

## Convert::ToByte(const String\&, int) 方法

將包含在指定基數下的數字字串表示的指定字串轉換為等效的 8 位元無號整數值。

```cpp
static uint8_t System::Convert::ToByte(const String &value, int from_base)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串 |
| from_base | int | 字串中數字的基數 |

### 返回值

等於指定字串所表示數字的 8 位元無號整數值。

## Convert::ToByte(const String\&, const SharedPtr\<IFormatProvider\>\&) 方法

將包含數字字串表示的指定字串轉換為等效的 8 位元無號整數值，使用提供的格式資訊。

```cpp
static uint8_t System::Convert::ToByte(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 包含字串格式資訊的物件指標 |

### 返回值

等於指定字串所表示數字的 8 位元無號整數值。

## Convert::ToByte(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) 方法

```cpp
static uint8_t System::Convert::ToByte(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToByte(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 方法

```cpp
static uint8_t System::Convert::ToByte(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToByte(const String\&, std::nullptr_t) 方法

```cpp
static uint8_t System::Convert::ToByte(const String &value, std::nullptr_t)
```

## Convert::ToByte(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) 方法

將包含數字字串表示的指定字串轉換為等效的 8 位元無號整數值，使用提供的格式資訊和數字樣式。

```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles 列舉值的位元組合，指定允許的字串數字樣式 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 包含字串格式資訊的物件指標 |

### 返回值

等於指定字串所表示數字的 8 位元無號整數值。

## Convert::ToByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) 方法

```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 方法

```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToByte(const String\&, Globalization::NumberStyles, std::nullptr_t) 方法

```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToByte(Enum) 方法

```cpp
template<typename Enum,typename> static uint8_t System::Convert::ToByte(Enum value)
```

## Convert::ToByte(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) 方法

將指定的裝箱值轉換為等效的 8 位元無號整數值。

```cpp
static uint8_t System::Convert::ToByte(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 指向將值封裝的物件的 shared pointer |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 若裝箱值的類型為 [String](../../string/)，要使用的字串格式 |

### 返回值

等於指定裝箱值的 8 位元無號整數值。

## See Also

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Struct [Enum](../../enum/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)