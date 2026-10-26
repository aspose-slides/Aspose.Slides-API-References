---
title: ToSByte()
second_title: Aspose.Slides for C++ API 參考
description: 將指定的布林值轉換為等效的 8 位元有號整數。
type: docs
weight: 105
url: /zh-hant/system/convert/tosbyte/
---
## Convert::ToSByte(bool) 方法


將指定的布林值轉換為等效的 8 位元有號整數。

```cpp
static constexpr int8_t System::Convert::ToSByte(bool value)
```

## Convert::ToSByte(uint8_t) 方法


將指定的 8 位元無號整數轉換為等效的 8 位元有號整數。

```cpp
static int8_t System::Convert::ToSByte(uint8_t value)
```

## Convert::ToSByte(int8_t) 方法


返回指定的 8 位元有號整數。

```cpp
static constexpr int8_t System::Convert::ToSByte(int8_t value)
```

## Convert::ToSByte(uint16_t) 方法


將指定的 16 位元無號整數轉換為等效的 8 位元有號整數。

```cpp
static int8_t System::Convert::ToSByte(uint16_t value)
```

## Convert::ToSByte(int16_t) 方法


將指定的 16 位元有號整數轉換為等效的 8 位元有號整數。

```cpp
static int8_t System::Convert::ToSByte(int16_t value)
```

## Convert::ToSByte(uint32_t) 方法


將指定的 32 位元無號整數轉換為等效的 8 位元有號整數。

```cpp
static int8_t System::Convert::ToSByte(uint32_t value)
```

## Convert::ToSByte(int32_t) 方法


將指定的 32 位元有號整數轉換為等效的 8 位元有號整數。

```cpp
static int8_t System::Convert::ToSByte(int32_t value)
```

## Convert::ToSByte(uint64_t) 方法


將指定的 64 位元無號整數轉換為等效的 8 位元有號整數。

```cpp
static int8_t System::Convert::ToSByte(uint64_t value)
```

## Convert::ToSByte(int64_t) 方法


將指定的 64 位元有號整數轉換為等效的 8 位元有號整數。

```cpp
static int8_t System::Convert::ToSByte(int64_t value)
```

## Convert::ToSByte(float) 方法


將指定的 float 數字轉換為等效的 8 位元有號整數。

```cpp
static int8_t System::Convert::ToSByte(float value)
```

## Convert::ToSByte(double) 方法


將指定的 double 數字轉換為等效的 8 位元有號整數。

```cpp
static int8_t System::Convert::ToSByte(double value)
```

## Convert::ToSByte(const Decimal\&) 方法


將指定的 decimal 數字轉換為等效的 8 位元有號整數。

```cpp
static int8_t System::Convert::ToSByte(const Decimal &value)
```

## Convert::ToSByte(char_t) 方法


將指定的 unicode 字元轉換為等效的 8 位元有號整數。

```cpp
static int8_t System::Convert::ToSByte(char_t value)
```

## Convert::ToSByte(DateTime) 方法


不支援此轉換。總是拋出 InvalidCastException。

```cpp
static int8_t System::Convert::ToSByte(DateTime value)
```

## Convert::ToSByte(std::nullptr_t) 方法


將指定的 null 字串轉換為等效的 8 位元整數值。

```cpp
static constexpr int8_t System::Convert::ToSByte(std::nullptr_t)
```


### 返回值

零。

## Convert::ToSByte(const char_t *) 方法


將包含數字字串表示法的 c 字串轉換為等效的 8 位元整數值。

```cpp
static int8_t System::Convert::ToSByte(const char_t *value)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | const char_t * | 要轉換的 c 字串 |

### 返回值

等於指定 c 字串所表示之數字的 8 位元整數值

## Convert::ToSByte(const String\&) 方法


將包含數字字串表示法的字串轉換為等效的 8 位元整數值。

```cpp
static int8_t System::Convert::ToSByte(const String &value)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串 |

### 返回值

等於指定字串所表示之數字的 8 位元整數值

## Convert::ToSByte(const String\&, int) 方法


將指定基礎中數字字串表示法的字串轉換為等效的 8 位元整數值。

```cpp
static int8_t System::Convert::ToSByte(const String &value, int from_base)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串 |
| from_base | int | 字串所表示之數字的基礎 |

### 返回值

等於指定字串所表示之數字的 8 位元整數值

## Convert::ToSByte(const String\&, const SharedPtr\<IFormatProvider\>\&) 方法


使用提供的格式資訊，將包含數字字串表示法的字串轉換為等效的無號 8 位元整數值。

```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 指向包含字串格式資訊之物件的指標 |

### 返回值

等於指定字串所表示之數字的無號 8 位元整數值

## Convert::ToSByte(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) 方法




```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSByte(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 方法




```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSByte(const String\&, std::nullptr_t) 方法




```cpp
static int8_t System::Convert::ToSByte(const String &value, std::nullptr_t)
```

## Convert::ToSByte(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) 方法


使用提供的格式資訊與數字樣式，將包含數字字串表示法的字串轉換為等效的 8 位元整數值。

```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles 列舉值的位元組合，指定允許的字串表示數字的樣式 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 指向包含字串格式資訊之物件的指標 |

### 返回值

等於指定字串所表示之數字的無號 8 位元整數值

## Convert::ToSByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) 方法




```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 方法




```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSByte(const String\&, Globalization::NumberStyles, std::nullptr_t) 方法




```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToSByte(Enum) 方法




```cpp
template<typename Enum,typename> static int8_t System::Convert::ToSByte(Enum value)
```

## Convert::ToSByte(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) 方法


將指定的裝箱值轉換為等效的 8 位元整數值。

```cpp
static int8_t System::Convert::ToSByte(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 指向裝箱要轉換之值之物件的 shared pointer |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 如果裝箱值的類型是 [String](../../string/)，則使用的字串格式 |

### 返回值

等效於指定裝箱值的 8 位元整數值

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