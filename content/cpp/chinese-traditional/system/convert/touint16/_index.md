---
title: ToUInt16()
second_title: Aspose.Slides for C++ API 參考文件
description: 將指定的布林值轉換為等效的 16 位元無號整數。
type: docs
weight: 144
url: /zh-hant/system/convert/touint16/
---
## Convert::ToUInt16(bool) 方法

將指定的布林值轉換為等效的 16 位元無號整數。

```cpp
static constexpr uint16_t System::Convert::ToUInt16(bool value)
```

## Convert::ToUInt16(uint8_t) 方法

將指定的 8 位元無號整數轉換為等效的 16 位元無號整數。

```cpp
static constexpr uint16_t System::Convert::ToUInt16(uint8_t value)
```

## Convert::ToUInt16(int8_t) 方法

將指定的 8 位元有號整數轉換為等效的 16 位元無號整數。

```cpp
static uint16_t System::Convert::ToUInt16(int8_t value)
```

## Convert::ToUInt16(uint16_t) 方法

傳回指定的 16 位元無號整數。

```cpp
static constexpr uint16_t System::Convert::ToUInt16(uint16_t value)
```

## Convert::ToUInt16(int16_t) 方法

將指定的 16 位元有號整數轉換為等效的 16 位元無號整數。

```cpp
static uint16_t System::Convert::ToUInt16(int16_t value)
```

## Convert::ToUInt16(uint32_t) 方法

將指定的 32 位元無號整數轉換為等效的 16 位元無號整數。

```cpp
static uint16_t System::Convert::ToUInt16(uint32_t value)
```

## Convert::ToUInt16(int32_t) 方法

將指定的 32 位元有號整數轉換為等效的 16 位元無號整數。

```cpp
static uint16_t System::Convert::ToUInt16(int32_t value)
```

## Convert::ToUInt16(uint64_t) 方法

將指定的 64 位元無號整數轉換為等效的 16 位元無號整數。

```cpp
static uint16_t System::Convert::ToUInt16(uint64_t value)
```

## Convert::ToUInt16(int64_t) 方法

將指定的 64 位元有號整數轉換為等效的 16 位元無號整數。

```cpp
static uint16_t System::Convert::ToUInt16(int64_t value)
```

## Convert::ToUInt16(float) 方法

將指定的 float 數值轉換為等效的 16 位元無號整數。

```cpp
static uint16_t System::Convert::ToUInt16(float value)
```

## Convert::ToUInt16(double) 方法

將指定的 double 數值轉換為等效的 16 位元無號整數。

```cpp
static uint16_t System::Convert::ToUInt16(double value)
```

## Convert::ToUInt16(const Decimal\&) 方法

將指定的十進位數字轉換為等效的 16 位元無號整數。

```cpp
static uint16_t System::Convert::ToUInt16(const Decimal &value)
```

## Convert::ToUInt16(char_t) 方法

將指定的 Unicode 字元轉換為等效的 16 位元無號整數。

```cpp
static constexpr uint16_t System::Convert::ToUInt16(char_t value)
```

## Convert::ToUInt16(DateTime) 方法

不支援轉換。永遠會拋出 InvalidCastException。

```cpp
static uint16_t System::Convert::ToUInt16(DateTime value)
```

## Convert::ToUInt16(std::nullptr_t) 方法

將指定的 null 字串轉換為等效的 16 位元無號整數值。

```cpp
static constexpr uint16_t System::Convert::ToUInt16(std::nullptr_t)
```

### 返回值

零。

## Convert::ToUInt16(const char_t *) 方法

將包含數字字串表示的指定 c 字串轉換為等效的 16 位元無號整數值。

```cpp
static uint16_t System::Convert::ToUInt16(const char_t *value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const char_t * | 要轉換的 c 字串 |

### 返回值

等於指定 c 字串所表示之數字的 16 位元無號整數值

## Convert::ToUInt16(const String\&) 方法

將包含數字字串表示的指定字串轉換為等效的 16 位元無號整數值。

```cpp
static uint16_t System::Convert::ToUInt16(const String &value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串 |

### 返回值

等於指定字串所表示之數字的 16 位元無號整數值

## Convert::ToUInt16(const String\&, int) 方法

將包含以指定基數表示之數字字串的指定字串轉換為等效的 16 位元無號整數值。

```cpp
static uint16_t System::Convert::ToUInt16(const String &value, int from_base)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串 |
| from_base | int | 字串所表示之數字的基數 |

### 返回值

等於指定字串所表示之數字的 16 位元無號整數值

## Convert::ToUInt16(const String\&, const SharedPtr\<IFormatProvider\>\&) 方法

使用提供的格式化資訊，將包含數字字串表示的指定字串轉換為等效的 16 位元無號整數值。

```cpp
static uint16_t System::Convert::ToUInt16(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 指向包含字串格式資訊之物件的指標 |

### 返回值

等於指定字串所表示之數字的 16 位元無號整數值

## Convert::ToUInt16(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) 方法




```cpp
static uint16_t System::Convert::ToUInt16(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt16(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 方法




```cpp
static uint16_t System::Convert::ToUInt16(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt16(const String\&, std::nullptr_t) 方法




```cpp
static uint16_t System::Convert::ToUInt16(const String &value, std::nullptr_t)
```

## Convert::ToUInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) 方法

使用提供的格式化資訊與數字樣式，將包含數字字串表示的指定字串轉換為等效的 16 位元無號整數值。

```cpp
static uint16_t System::Convert::ToUInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles 列舉值的逐位組合，用於指定數字字串表示允許的樣式 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 指向包含字串格式資訊之物件的指標 |

### 返回值

等於指定字串所表示之數字的 16 位元無號整數值

## Convert::ToUInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) 方法




```cpp
static uint16_t System::Convert::ToUInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 方法




```cpp
static uint16_t System::Convert::ToUInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt16(const String\&, Globalization::NumberStyles, std::nullptr_t) 方法




```cpp
static uint16_t System::Convert::ToUInt16(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToUInt16(Enum) 方法




```cpp
template<typename Enum,typename> static uint16_t System::Convert::ToUInt16(Enum value)
```

## Convert::ToUInt16(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) 方法

將指定的封裝值轉換為等效的 16 位元無號整數值。

```cpp
static uint16_t System::Convert::ToUInt16(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 封裝要轉換之值的物件之共享指標 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 如果封裝值的類型為 [String](../../string/)，則使用的字串格式 |

### 返回值

等於指定封裝值的 16 位元無號整數值

## 另請參閱

* 列舉 [NumberStyles](../../../system.globalization/numberstyles/)
* 型別定義 [SharedPtr](../../sharedptr/)
* 類別 [Decimal](../../decimal/)
* 類別 [DateTime](../../datetime/)
* 類別 [String](../../string/)
* 類別 [IFormatProvider](../../iformatprovider/)
* 類別 [CultureInfo](../../../system.globalization/cultureinfo/)
* 類別 [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* 類別 [Object](../../object/)
* 結構 [Convert](../)
* 結構 [Enum](../../enum/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)