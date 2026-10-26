---
title: ToInt64()
second_title: Aspose.Slides for C++ API 參考文件
description: 將指定的布林值轉換為等效的 64 位元帶符號整數。
type: docs
weight: 183
url: /zh-hant/system/convert/toint64/
---
## Convert::ToInt64(bool) 方法

將指定的布林值轉換為等效的 64 位元帶符號整數。

```cpp
static constexpr int64_t System::Convert::ToInt64(bool value)
```

## Convert::ToInt64(uint8_t) 方法

將指定的 8 位元無符號整數轉換為等效的 64 位元帶符號整數。

```cpp
static constexpr int64_t System::Convert::ToInt64(uint8_t value)
```

## Convert::ToInt64(int8_t) 方法

將指定的 8 位元帶符號整數轉換為等效的 64 位元帶符號整數。

```cpp
static constexpr int64_t System::Convert::ToInt64(int8_t value)
```

## Convert::ToInt64(uint16_t) 方法

將指定的 16 位元無符號整數轉換為等效的 64 位元帶符號整數。

```cpp
static constexpr int64_t System::Convert::ToInt64(uint16_t value)
```

## Convert::ToInt64(int16_t) 方法

將指定的 16 位元帶符號整數轉換為等效的 64 位元帶符號整數。

```cpp
static constexpr int64_t System::Convert::ToInt64(int16_t value)
```

## Convert::ToInt64(uint32_t) 方法

將指定的 32 位元無符號整數轉換為等效的 64 位元帶符號整數。

```cpp
static constexpr int64_t System::Convert::ToInt64(uint32_t value)
```

## Convert::ToInt64(int32_t) 方法

將指定的 32 位元帶符號整數轉換為等效的 64 位元帶符號整數。

```cpp
static constexpr int64_t System::Convert::ToInt64(int32_t value)
```

## Convert::ToInt64(uint64_t) 方法

將指定的 64 位元無符號整數轉換為等效的 64 位元帶符號整數。

```cpp
static int64_t System::Convert::ToInt64(uint64_t value)
```

## Convert::ToInt64(int64_t) 方法

返回指定的 64 位元帶符號整數。

```cpp
static constexpr int64_t System::Convert::ToInt64(int64_t value)
```

## Convert::ToInt64(float) 方法

將指定的浮點數轉換為等效的 64 位元帶符號整數。

```cpp
static int64_t System::Convert::ToInt64(float value)
```

## Convert::ToInt64(double) 方法

將指定的雙精度浮點數轉換為等效的 64 位元帶符號整數。

```cpp
static int64_t System::Convert::ToInt64(double value)
```

## Convert::ToInt64(const Decimal\&) 方法

將指定的十進位數字轉換為等效的 64 位元帶符號整數。

```cpp
static int64_t System::Convert::ToInt64(const Decimal &value)
```

## Convert::ToInt64(char_t) 方法

將指定的 Unicode 字元轉換為等效的 64 位元帶符號整數。

```cpp
static constexpr int64_t System::Convert::ToInt64(char_t value)
```

## Convert::ToInt64(DateTime) 方法

不支援此轉換。始終拋出 InvalidCastException。

```cpp
static int64_t System::Convert::ToInt64(DateTime value)
```

## Convert::ToInt64(std::nullptr_t) 方法

將指定的空字串轉換為等效的 64 位元整數值。

```cpp
static constexpr int64_t System::Convert::ToInt64(std::nullptr_t)
```

### 返回值

零。

## Convert::ToInt64(const char_t *) 方法

將指定的包含數字字串表示的 c-string 轉換為等效的 64 位元整數值。

```cpp
static int64_t System::Convert::ToInt64(const char_t *value)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const char_t * | 要轉換的 c-string |

### 返回值

等同於指定 c-string 所表示之數字的 64 位元整數值

## Convert::ToInt64(const String\&) 方法

將指定的包含數字字串表示的字串轉換為等效的 64 位元整數值。

```cpp
static int64_t System::Convert::ToInt64(const String &value)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串 |

### 返回值

等同於指定字串所表示之數字的 64 位元整數值

## Convert::ToInt64(const String\&, int) 方法

將指定的包含在指定基數下的數字字串表示的字串轉換為等效的 64 位元整數值。

```cpp
static int64_t System::Convert::ToInt64(const String &value, int from_base)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串 |
| from_base | int | 字串所表示之數字的基數 |

### 返回值

等同於指定字串所表示之數字的 64 位元整數值

## Convert::ToInt64(const String\&, const SharedPtr\<IFormatProvider\>\&) 方法

將指定的包含數字字串表示的字串轉換為等效的 64 位元整數值，使用提供的格式資訊。

```cpp
static int64_t System::Convert::ToInt64(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 包含字串格式資訊的物件指標 |

### 返回值

等同於指定字串所表示之數字的 64 位元整數值

## Convert::ToInt64(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) 方法

```cpp
static int64_t System::Convert::ToInt64(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt64(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 方法

```cpp
static int64_t System::Convert::ToInt64(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt64(const String\&, std::nullptr_t) 方法

```cpp
static int64_t System::Convert::ToInt64(const String &value, std::nullptr_t)
```

## Convert::ToInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) 方法

將指定的包含數字字串表示的字串轉換為等效的 64 位元整數值，使用提供的格式資訊與數字樣式。

```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles 列舉值的逐位組合，指定允許的字串表示樣式 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 包含字串格式資訊的物件指標 |

### 返回值

等同於指定字串所表示之數字的 64 位元整數值

## Convert::ToInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) 方法

```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 方法

```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt64(const String\&, Globalization::NumberStyles, std::nullptr_t) 方法

```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToInt64(Enum) 方法

```cpp
template<typename Enum,typename> static int64_t System::Convert::ToInt64(Enum value)
```

## Convert::ToInt64(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) 方法

將指定的已裝箱值轉換為等效的 64 位元整數值。

```cpp
static int64_t System::Convert::ToInt64(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 包含要轉換之值的物件之共享指標 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 如果已裝箱值的型別為 [String](../../string/) 時使用的字串格式 |

### 返回值

等同於指定已裝箱值的 64 位元整數值

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