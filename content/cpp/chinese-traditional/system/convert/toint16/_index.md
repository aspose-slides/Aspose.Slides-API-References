---
title: ToInt16()
second_title: Aspose.Slides C++ API 參考
description: 將指定的布林值轉換為等效的 16 位元有號整數。
type: docs
weight: 131
url: /zh-hant/system/convert/toint16/
---
## Convert::ToInt16(bool) 方法


將指定的布林值轉換為等效的 16 位元有號整數。

```cpp
static constexpr int16_t System::Convert::ToInt16(bool value)
```

## Convert::ToInt16(uint8_t) 方法


將指定的 8 位元無號整數轉換為等效的 16 位元有號整數。

```cpp
static constexpr int16_t System::Convert::ToInt16(uint8_t value)
```

## Convert::ToInt16(int8_t) 方法


將指定的 8 位元有號整數轉換為等效的 16 位元有號整數。

```cpp
static constexpr int16_t System::Convert::ToInt16(int8_t value)
```

## Convert::ToInt16(uint16_t) 方法


將指定的 16 位元無號整數轉換為等效的 16 位元有號整數。

```cpp
static int16_t System::Convert::ToInt16(uint16_t value)
```

## Convert::ToInt16(int16_t) 方法


傳回指定的 16 位元有號整數。

```cpp
static constexpr int16_t System::Convert::ToInt16(int16_t value)
```

## Convert::ToInt16(uint32_t) 方法


將指定的 32 位元無號整數轉換為等效的 16 位元有號整數。

```cpp
static int16_t System::Convert::ToInt16(uint32_t value)
```

## Convert::ToInt16(int32_t) 方法


將指定的 32 位元有號整數轉換為等效的 16 位元有號整數。

```cpp
static int16_t System::Convert::ToInt16(int32_t value)
```

## Convert::ToInt16(uint64_t) 方法


將指定的 64 位元無號整數轉換為等效的 16 位元有號整數。

```cpp
static int16_t System::Convert::ToInt16(uint64_t value)
```

## Convert::ToInt16(int64_t) 方法


將指定的 64 位元有號整數轉換為等效的 16 位元有號整數。

```cpp
static int16_t System::Convert::ToInt16(int64_t value)
```

## Convert::ToInt16(float) 方法


將指定的 float 數字轉換為等效的 16 位元有號整數。

```cpp
static int16_t System::Convert::ToInt16(float value)
```

## Convert::ToInt16(double) 方法


將指定的 double 數字轉換為等效的 16 位元有號整數。

```cpp
static int16_t System::Convert::ToInt16(double value)
```

## Convert::ToInt16(const Decimal\&) 方法


將指定的 decimal 數字轉換為等效的 16 位元有號整數。

```cpp
static int16_t System::Convert::ToInt16(const Decimal &value)
```

## Convert::ToInt16(char_t) 方法


將指定的 Unicode 字元轉換為等效的 16 位元有號整數。

```cpp
static int16_t System::Convert::ToInt16(char_t value)
```

## Convert::ToInt16(DateTime) 方法


不支援轉換。總是拋出 InvalidCastException。

```cpp
static int16_t System::Convert::ToInt16(DateTime value)
```

## Convert::ToInt16(std::nullptr_t) 方法


將指定的 null 字串轉換為等效的 16 位元整數值。

```cpp
static constexpr int16_t System::Convert::ToInt16(std::nullptr_t)
```


### 返回值

零。

## Convert::ToInt16(const char_t *) 方法


將包含數字字串表示的指定 C 字串轉換為等效的 16 位元整數值。

```cpp
static int16_t System::Convert::ToInt16(const char_t *value)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const char_t * | 要轉換的 C 字串 |

### 返回值

等於指定 C 字串所表示之數字的 16 位元整數值

## Convert::ToInt16(const String\&) 方法


將包含數字字串表示的指定字串轉換為等效的 16 位元整數值。

```cpp
static int16_t System::Convert::ToInt16(const String &value)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串 |

### 返回值

等於指定字串所表示之數字的 16 位元整數值

## Convert::ToInt16(const String\&, int) 方法


將包含指定基底之數字字串表示的指定字串轉換為等效的 16 位元整數值。

```cpp
static int16_t System::Convert::ToInt16(const String &value, int from_base)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串 |
| from_base | int | 字串所表示之數字的基底 |

### 返回值

等於指定字串所表示之數字的 16 位元整數值

## Convert::ToInt16(const String\&, const SharedPtr\<IFormatProvider\>\&) 方法


使用提供的格式資訊將包含數字字串表示的指定字串轉換為等效的 16 位元整數值。

```cpp
static int16_t System::Convert::ToInt16(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 指向包含字串格式資訊之物件的指標 |

### 返回值

等於指定字串所表示之數字的 16 位元整數值

## Convert::ToInt16(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) 方法




```cpp
static int16_t System::Convert::ToInt16(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt16(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 方法




```cpp
static int16_t System::Convert::ToInt16(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt16(const String\&, std::nullptr_t) 方法




```cpp
static int16_t System::Convert::ToInt16(const String &value, std::nullptr_t)
```

## Convert::ToInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) 方法


使用提供的格式資訊和數字樣式將包含數字字串表示的指定字串轉換為等效的 16 位元整數值。

```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | 指定數字字串表示之允許樣式的 NumberStyles 列舉值的位元組合 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 指向包含字串格式資訊之物件的指標 |

### 返回值

等於指定字串所表示之數字的 16 位元整數值

## Convert::ToInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) 方法




```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 方法




```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt16(const String\&, Globalization::NumberStyles, std::nullptr_t) 方法




```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToInt16(Enum) 方法




```cpp
template<typename Enum,typename> static int16_t System::Convert::ToInt16(Enum value)
```

## Convert::ToInt16(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) 方法


將指定的裝箱值轉換為等效的 16 位元整數值。

```cpp
static int16_t System::Convert::ToInt16(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 指向裝箱值所在物件的共享指標 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 若裝箱值的類型為 [String](../../string/) 時要使用的字串格式 |

### 返回值

等於指定裝箱值的 16 位元整數值

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