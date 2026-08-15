---
title: ToUInt32()
second_title: Aspose.Slides for C++ API 參考
description: 將指定的布林值轉換為等效的 32 位元無號整數。
type: docs
weight: 170
url: /zh-hant/system/convert/touint32/
---
## Convert::ToUInt32(bool) 方法

將指定的布林值轉換為等效的 32 位元無號整數。

```cpp
static constexpr uint32_t System::Convert::ToUInt32(bool value)
```
## Convert::ToUInt32(uint8_t) 方法

將指定的 8 位元無號整數轉換為等效的 32 位元無號整數。

```cpp
static constexpr uint32_t System::Convert::ToUInt32(uint8_t value)
```
## Convert::ToUInt32(int8_t) 方法

將指定的 8 位元有號整數轉換為等效的 32 位元無號整數。

```cpp
static uint32_t System::Convert::ToUInt32(int8_t value)
```
## Convert::ToUInt32(uint16_t) 方法

將指定的 16 位元無號整數轉換為等效的 32 位元無號整數。

```cpp
static constexpr uint32_t System::Convert::ToUInt32(uint16_t value)
```
## Convert::ToUInt32(int16_t) 方法

將指定的 16 位元有號整數轉換為等效的 32 位元無號整數。

```cpp
static uint32_t System::Convert::ToUInt32(int16_t value)
```
## Convert::ToUInt32(uint32_t) 方法

傳回指定的 32 位元無號整數。

```cpp
static constexpr uint32_t System::Convert::ToUInt32(uint32_t value)
```
## Convert::ToUInt32(int32_t) 方法

將指定的 32 位元有號整數轉換為等效的 32 位元無號整數。

```cpp
static uint32_t System::Convert::ToUInt32(int32_t value)
```
## Convert::ToUInt32(uint64_t) 方法

將指定的 64 位元無號整數轉換為等效的 32 位元無號整數。

```cpp
static uint32_t System::Convert::ToUInt32(uint64_t value)
```
## Convert::ToUInt32(int64_t) 方法

將指定的 64 位元有號整數轉換為等效的 32 位元無號整數。

```cpp
static uint32_t System::Convert::ToUInt32(int64_t value)
```
## Convert::ToUInt32(float) 方法

將指定的 float 數字轉換為等效的 32 位元無號整數。

```cpp
static uint32_t System::Convert::ToUInt32(float value)
```
## Convert::ToUInt32(double) 方法

將指定的 double 數字轉換為等效的 32 位元無號整數。

```cpp
static uint32_t System::Convert::ToUInt32(double value)
```
## Convert::ToUInt32(const Decimal\&) 方法

將指定的 Decimal 數字轉換為等效的 32 位元無號整數。

```cpp
static uint32_t System::Convert::ToUInt32(const Decimal &value)
```
## Convert::ToUInt32(char_t) 方法

將指定的 Unicode 字元轉換為等效的 32 位元無號整數。

```cpp
static constexpr uint32_t System::Convert::ToUInt32(char_t value)
```
## Convert::ToUInt32(DateTime) 方法

不支援轉換。總是拋出 InvalidCastException。

```cpp
static uint32_t System::Convert::ToUInt32(DateTime value)
```
## Convert::ToUInt32(std::nullptr_t) 方法

將指定的 null-string 轉換為等效的 32 位元無號整數值。

```cpp
static constexpr uint32_t System::Convert::ToUInt32(std::nullptr_t)
```

### 回傳值

0。

## Convert::ToUInt32(const char_t *) 方法

將包含數字字串表示的指定 c-string 轉換為等效的 32 位元無號整數值。

```cpp
static uint32_t System::Convert::ToUInt32(const char_t *value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const char_t * | 要轉換的 c-string |

### 回傳值

等於指定 c-string 所表示數字的 32 位元無號整數值

## Convert::ToUInt32(const String\&) 方法

將包含數字字串表示的指定字串轉換為等效的 32 位元無號整數值。

```cpp
static uint32_t System::Convert::ToUInt32(const String &value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串 |

### 回傳值

等於指定字串所表示數字的 32 位元無號整數值

## Convert::ToUInt32(const String\&, int) 方法

將包含指定基底之數字字串表示的指定字串轉換為等效的 32 位元無號整數值。

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, int from_base)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串 |
| from_base | int | 字串所表示數字的基底 |

### 回傳值

等於指定字串所表示數字的 32 位元無號整數值

## Convert::ToUInt32(const String\&, const SharedPtr\<IFormatProvider\>\&) 方法

使用提供的格式資訊，將包含數字字串表示的指定字串轉換為等效的 32 位元無號整數值。

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 指向包含字串格式資訊之物件的指標 |

### 回傳值

等於指定字串所表示數字的 32 位元無號整數值

## Convert::ToUInt32(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) 方法




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt32(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 方法




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt32(const String\&, std::nullptr_t) 方法




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, std::nullptr_t)
```

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) 方法

使用提供的格式資訊與數字樣式，將包含數字字串表示的指定字串轉換為等效的 32 位元無號整數值。

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | 指定允許之數字字串表示樣式的 NumberStyles 列舉的位元組合 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 指向包含字串格式資訊之物件的指標 |

### 回傳值

等於指定字串所表示數字的 32 位元無號整數值

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) 方法




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 方法




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, std::nullptr_t) 方法




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToUInt32(Enum) 方法




```cpp
template<typename Enum,typename> static uint32_t System::Convert::ToUInt32(Enum value)
```

## Convert::ToUInt32(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) 方法

將指定的裝箱值轉換為等效的 32 位元無號整數值。

```cpp
static uint32_t System::Convert::ToUInt32(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 指向將要轉換之值的箱型物件的 shared pointer |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 如果箱型值的型別為 [String](../../string/) 時所使用的字串格式 |

### 回傳值

等於指定裝箱值的 32 位元無號整數值

## 另請參閱

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