---
title: ToDecimal()
second_title: Aspose.Slides for C++ API 參考
description: 將指定的布林值轉換為等效的十進位數字。
type: docs
weight: 235
url: /zh-hant/system/convert/todecimal/
---
## Convert::ToDecimal(bool) 方法

將指定的布林值轉換為等效的十進位數字。

```cpp
static Decimal System::Convert::ToDecimal(bool value)
```

## Convert::ToDecimal(uint8_t) 方法

將指定的 8 位元無號整數 轉換為等效的十進位數字。

```cpp
static Decimal System::Convert::ToDecimal(uint8_t value)
```

## Convert::ToDecimal(int8_t) 方法

將指定的 8 位元有號整數 轉換為等效的十進位數字。

```cpp
static Decimal System::Convert::ToDecimal(int8_t value)
```

## Convert::ToDecimal(uint16_t) 方法

將指定的 16 位元無號整數 轉換為等效的十進位數字。

```cpp
static Decimal System::Convert::ToDecimal(uint16_t value)
```

## Convert::ToDecimal(int16_t) 方法

將指定的 16 位元有號整數 轉換為等效的十進位數字。

```cpp
static Decimal System::Convert::ToDecimal(int16_t value)
```

## Convert::ToDecimal(uint32_t) 方法

將指定的 32 位元無號整數 轉換為等效的十進位數字。

```cpp
static Decimal System::Convert::ToDecimal(uint32_t value)
```

## Convert::ToDecimal(int32_t) 方法

將指定的 32 位元有號整數 轉換為等效的十進位數字。

```cpp
static Decimal System::Convert::ToDecimal(int32_t value)
```

## Convert::ToDecimal(uint64_t) 方法

將指定的 64 位元無號整數 轉換為等效的十進位數字。

```cpp
static Decimal System::Convert::ToDecimal(uint64_t value)
```

## Convert::ToDecimal(int64_t) 方法

將指定的 64 位元有號整數 轉換為等效的十進位數字。

```cpp
static Decimal System::Convert::ToDecimal(int64_t value)
```

## Convert::ToDecimal(float) 方法

將指定的 float 數字轉換為等效的十進位數字。

```cpp
static Decimal System::Convert::ToDecimal(float value)
```

## Convert::ToDecimal(double) 方法

將指定的 double 數字轉換為等效的十進位數字。

```cpp
static Decimal System::Convert::ToDecimal(double value)
```

## Convert::ToDecimal(const Decimal\&) 方法

傳回指定的十進位數字。

```cpp
static Decimal System::Convert::ToDecimal(const Decimal &value)
```

## Convert::ToDecimal(char_t) 方法

不支援此轉換。總是拋出 InvalidCastException。

```cpp
static Decimal System::Convert::ToDecimal(char_t value)
```

## Convert::ToDecimal(DateTime) 方法

不支援此轉換。總是拋出 InvalidCastException。

```cpp
static Decimal System::Convert::ToDecimal(DateTime value)
```

## Convert::ToDecimal(std::nullptr_t) 方法

將指定的 null-string 轉換為等效的 [Decimal](../../decimal/) 值。

```cpp
static Decimal System::Convert::ToDecimal(std::nullptr_t)
```

### 傳回值

零。

## Convert::ToDecimal(const char_t *) 方法

將指定的、包含數字字串表示的 C 字串轉換為等效的 [Decimal](../../decimal/) 值。

```cpp
static Decimal System::Convert::ToDecimal(const char_t *value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const char_t * | 要轉換的 C 字串 |

### 傳回值

等於由指定 C 字串表示之數字的 [Decimal](../../decimal/) 值

## Convert::ToDecimal(const String\&) 方法

將包含數字字串表示的指定字串轉換為等效的 [Decimal](../../decimal/) 值。

```cpp
static Decimal System::Convert::ToDecimal(const String &value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串 |

### 傳回值

等於由指定字串表示之數字的 [Decimal](../../decimal/) 值

## Convert::ToDecimal(const String\&, const SharedPtr\<IFormatProvider\>\&) 方法

使用提供的格式資訊，將包含數字字串表示的指定字串轉換為等效的 [Decimal](../../decimal/) 值。

```cpp
static Decimal System::Convert::ToDecimal(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 指向包含字串格式資訊之物件的指標 |

### 傳回值

等於由指定字串表示之數字的 [Decimal](../../decimal/) 值

## Convert::ToDecimal(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) 方法

使用指定的數字樣式與格式資訊，將包含數字字串表示的指定字串轉換為等效的 [Decimal](../../decimal/) 值。

```cpp
static Decimal System::Convert::ToDecimal(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles 列舉值的逐位組合，指定允許的數字字串表示樣式 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 指向包含字串格式資訊之物件的指標 |

### 傳回值

等於由指定字串表示之數字的 [Decimal](../../decimal/) 值

## Convert::ToDecimal(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) 方法

將指定的已封裝值轉換為等效的 [Decimal](../../decimal/) 值。

```cpp
static Decimal System::Convert::ToDecimal(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 指向封裝要轉換之值之物件的 shared_ptr |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 若已封裝值的類型為 [String](../../string/) 時所使用的字串格式 |

### 傳回值

等同於指定已封裝值的 [Decimal](../../decimal/) 值

## 另請參閱

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)