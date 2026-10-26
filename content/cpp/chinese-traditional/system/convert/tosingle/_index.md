---
title: ToSingle()
second_title: Aspose.Slides for C++ API 參考
description: 將指定的布林值轉換為等效的單精度浮點數。
type: docs
weight: 209
url: /zh-hant/system/convert/tosingle/
---
## Convert::ToSingle(bool) 方法

將指定的布林值轉換為等效的單精度浮點數。

```cpp
static constexpr float System::Convert::ToSingle(bool value)
```
## Convert::ToSingle(uint8_t) 方法

將指定的 8 位元無號整數轉換為等效的單精度浮點數。

```cpp
static constexpr float System::Convert::ToSingle(uint8_t value)
```
## Convert::ToSingle(int8_t) 方法

將指定的 8 位元有號整數轉換為等效的單精度浮點數。

```cpp
static constexpr float System::Convert::ToSingle(int8_t value)
```
## Convert::ToSingle(uint16_t) 方法

將指定的 16 位元無號整數轉換為等效的單精度浮點數。

```cpp
static constexpr float System::Convert::ToSingle(uint16_t value)
```
## Convert::ToSingle(int16_t) 方法

將指定的 16 位元有號整數轉換為等效的單精度浮點數。

```cpp
static constexpr float System::Convert::ToSingle(int16_t value)
```
## Convert::ToSingle(uint32_t) 方法

將指定的 32 位元無號整數轉換為等效的單精度浮點數。

```cpp
static constexpr float System::Convert::ToSingle(uint32_t value)
```
## Convert::ToSingle(int32_t) 方法

將指定的 32 位元有號整數轉換為等效的單精度浮點數。

```cpp
static constexpr float System::Convert::ToSingle(int32_t value)
```
## Convert::ToSingle(uint64_t) 方法

將指定的 64 位元無號整數轉換為等效的單精度浮點數。

```cpp
static constexpr float System::Convert::ToSingle(uint64_t value)
```
## Convert::ToSingle(int64_t) 方法

將指定的 64 位元有號整數轉換為等效的單精度浮點數。

```cpp
static constexpr float System::Convert::ToSingle(int64_t value)
```
## Convert::ToSingle(float) 方法

返回指定的 float 數字。

```cpp
static constexpr float System::Convert::ToSingle(float value)
```
## Convert::ToSingle(double) 方法

將指定的雙精度數字轉換為等效的單精度浮點數。

```cpp
static constexpr float System::Convert::ToSingle(double value)
```
## Convert::ToSingle(const Decimal\&) 方法

將指定的十進位數字轉換為等效的單精度浮點數。

```cpp
static float System::Convert::ToSingle(const Decimal &value)
```
## Convert::ToSingle(char_t) 方法

不支援此轉換。永遠拋出 InvalidCastException。

```cpp
static float System::Convert::ToSingle(char_t value)
```
## Convert::ToSingle(DateTime) 方法

不支援此轉換。永遠拋出 InvalidCastException。

```cpp
static float System::Convert::ToSingle(DateTime value)
```
## Convert::ToSingle(std::nullptr_t) 方法

將指定的空字串轉換為等效的單精度浮點值。

```cpp
static constexpr float System::Convert::ToSingle(std::nullptr_t)
```

### 返回值

零。

## Convert::ToSingle(const char_t *) 方法

將包含數字字串表示的 c-string 轉換為等效的單精度浮點值。

```cpp
static float System::Convert::ToSingle(const char_t *value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const char_t * | 要轉換的 c-string |

### 返回值

等於指定 c-string 所表示之數字的單精度浮點值

## Convert::ToSingle(const String\&) 方法

將包含數字字串表示的字串轉換為等效的單精度浮點值。

```cpp
static float System::Convert::ToSingle(const String &value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串 |

### 返回值

等於指定字串所表示之數字的單精度浮點值

## Convert::ToSingle(const String\&, const SharedPtr\<IFormatProvider\>\&) 方法

使用提供的格式資訊，將包含數字字串表示的字串轉換為等效的單精度浮點值。

```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 指向包含字串格式資訊之物件的指標 |

### 返回值

等於指定字串所表示之數字的單精度浮點值

## Convert::ToSingle(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) 方法




```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSingle(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 方法




```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSingle(const String\&, std::nullptr_t) 方法




```cpp
static float System::Convert::ToSingle(const String &value, std::nullptr_t)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) 方法

使用提供的格式資訊與數字樣式，將包含數字字串表示的字串轉換為等效的單精度浮點值。

```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | 指定數字字串表示之許可樣式的 NumberStyles 列舉值的位元組合 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 指向包含字串格式資訊之物件的指標 |

### 返回值

等於指定字串所表示之數字的單精度浮點值

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) 方法




```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 方法




```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, std::nullptr_t) 方法 




```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToSingle(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) 方法

將指定的封裝值轉換為單精度浮點值。

```cpp
static float System::Convert::ToSingle(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 封裝要轉換之值的物件的共享指標 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 若封裝值的類型為 [String](../../string/) 時所使用的字串格式 |

### 返回值

等於指定封裝值的單精度浮點值

## 另見

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
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)