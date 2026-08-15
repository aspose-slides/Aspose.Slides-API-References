---
title: ToInt32()
second_title: Aspose.Slides for C++ API 參考文件
description: 將指定的布林值轉換為等效的 32 位帶符號整數。
type: docs
weight: 157
url: /zh-hant/system/convert/toint32/
---
## Convert::ToInt32(bool) 方法

將指定的布林值轉換為等效的 32 位帶符號整數。

```cpp
static constexpr int System::Convert::ToInt32(bool value)
```

## Convert::ToInt32(uint8_t) 方法

將指定的 8 位元無號整數轉換為等效的 32 位帶符號整數。

```cpp
static constexpr int System::Convert::ToInt32(uint8_t value)
```

## Convert::ToInt32(int8_t) 方法

將指定的 8 位元有號整數轉換為等效的 32 位帶符號整數。

```cpp
static constexpr int System::Convert::ToInt32(int8_t value)
```

## Convert::ToInt32(uint16_t) 方法

將指定的 16 位元無號整數轉換為等效的 32 位帶符號整數。

```cpp
static constexpr int System::Convert::ToInt32(uint16_t value)
```

## Convert::ToInt32(int16_t) 方法

將指定的 16 位元有號整數轉換為等效的 32 位帶符號整數。

```cpp
static constexpr int System::Convert::ToInt32(int16_t value)
```

## Convert::ToInt32(uint32_t) 方法

將指定的 32 位元無號整數轉換為等效的 32 位帶符號整數。

```cpp
static int System::Convert::ToInt32(uint32_t value)
```

## Convert::ToInt32(int32_t) 方法

傳回指定的 32 位帶符號整數。

```cpp
static constexpr int System::Convert::ToInt32(int32_t value)
```

## Convert::ToInt32(uint64_t) 方法

將指定的 64 位元無號整數轉換為等效的 32 位帶符號整數。

```cpp
static int System::Convert::ToInt32(uint64_t value)
```

## Convert::ToInt32(int64_t) 方法

將指定的 64 位元有號整數轉換為等效的 32 位帶符號整數。

```cpp
static int System::Convert::ToInt32(int64_t value)
```

## Convert::ToInt32(float) 方法

將指定的 float 數字轉換為等效的 32 位帶符號整數。

```cpp
static int System::Convert::ToInt32(float value)
```

## Convert::ToInt32(double) 方法

將指定的 double 數字轉換為等效的 32 位帶符號整數。

```cpp
static int System::Convert::ToInt32(double value)
```

## Convert::ToInt32(const Decimal\&) 方法

將指定的 Decimal 數字轉換為等效的 32 位帶符號整數。

```cpp
static int System::Convert::ToInt32(const Decimal &value)
```

## Convert::ToInt32(char_t) 方法

將指定的 Unicode 字元轉換為等效的 32 位帶符號整數。

```cpp
static constexpr int System::Convert::ToInt32(char_t value)
```

## Convert::ToInt32(DateTime) 方法

不支援此類型的轉換。始終拋出 InvalidCastException。

```cpp
static int System::Convert::ToInt32(DateTime value)
```

## Convert::ToInt32(std::nullptr_t) 方法

將指定的 null 索引字串轉換為等效的 32 位整數值。

```cpp
static constexpr int System::Convert::ToInt32(std::nullptr_t)
```

### 返回值

零。

## Convert::ToInt32(const char_t *) 方法

將包含數字字串表示的指定 c-string 轉換為等效的 32 位整數值。

```cpp
static int System::Convert::ToInt32(const char_t *value)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const char_t * | 要轉換的 c-string |

### 返回值

等於指定 c-string 所表示數字的 32 位整數值

## Convert::ToInt32(const String\&) 方法

將包含數字字串表示的指定字串轉換為等效的 32 位整數值。

```cpp
static int System::Convert::ToInt32(const String &value)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串 |

### 返回值

等於指定字串所表示數字的 32 位整數值

## Convert::ToInt32(const String\&, int) 方法

將包含指定基數下數字字串表示的指定字串轉換為等效的 32 位整數值。

```cpp
static int System::Convert::ToInt32(const String &value, int from_base)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串 |
| from_base | int | 字串所表示數字的基數 |

### 返回值

等於指定字串所表示數字的 32 位整數值

## Convert::ToInt32(const String\&, const SharedPtr\<IFormatProvider\>\&) 方法

將包含數字字串表示的指定字串轉換為等效的 32 位整數值，使用提供的格式資訊。

```cpp
static int System::Convert::ToInt32(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 指向包含字串格式資訊之物件的指標 |

### 返回值

等於指定字串所表示數字的 32 位整數值

## Convert::ToInt32(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) 方法

```cpp
static int System::Convert::ToInt32(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt32(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 方法

```cpp
static int System::Convert::ToInt32(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt32(const String\&, std::nullptr_t) 方法

```cpp
static int System::Convert::ToInt32(const String &value, std::nullptr_t)
```

## Convert::ToInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) 方法

將包含數字字串表示的指定字串轉換為等效的 32 位整數值，使用提供的格式資訊與數字樣式。

```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles 列舉值的位元組合，指定字串表示之數字的允許樣式 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 指向包含字串格式資訊之物件的指標 |

### 返回值

等於指定字串所表示數字的 32 位整數值

## Convert::ToInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) 方法

```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 方法

```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt32(const String\&, Globalization::NumberStyles, std::nullptr_t) 方法

```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToInt32(Enum) 方法

```cpp
template<typename Enum,typename> static int32_t System::Convert::ToInt32(Enum value)
```

## Convert::ToInt32(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) 方法

將指定的已封裝值轉換為等效的 32 位整數值。

```cpp
static int System::Convert::ToInt32(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 指向封裝欲轉換之值的物件的 shared pointer |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 若已封裝值的類型為 [String](../../string/)，則使用的字串格式 |

### 返回值

等同於指定已封裝值的 32 位整數值

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