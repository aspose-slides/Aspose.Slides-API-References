---
title: ToDouble()
second_title: Aspose.Slides for C++ API 參考
description: 將指定的布林值轉換為等效的雙精度浮點數。
type: docs
weight: 222
url: /zh-hant/system/convert/todouble/
---
## Convert::ToDouble(bool) 方法

將指定的布林值轉換為等效的雙精度浮點數。

```cpp
static constexpr double System::Convert::ToDouble(bool value)
```
## Convert::ToDouble(uint8_t) 方法

將指定的 8 位元無號整數轉換為等效的雙精度浮點數。

```cpp
static constexpr double System::Convert::ToDouble(uint8_t value)
```
## Convert::ToDouble(int8_t) 方法

將指定的 8 位元有號整數轉換為等效的雙精度浮點數。

```cpp
static constexpr double System::Convert::ToDouble(int8_t value)
```
## Convert::ToDouble(uint16_t) 方法

將指定的 16 位元無號整數轉換為等效的雙精度浮點數。

```cpp
static constexpr double System::Convert::ToDouble(uint16_t value)
```
## Convert::ToDouble(int16_t) 方法

將指定的 16 位元有號整數轉換為等效的雙精度浮點數。

```cpp
static constexpr double System::Convert::ToDouble(int16_t value)
```
## Convert::ToDouble(uint32_t) 方法

將指定的 32 位元無號整數轉換為等效的雙精度浮點數。

```cpp
static constexpr double System::Convert::ToDouble(uint32_t value)
```
## Convert::ToDouble(int32_t) 方法

將指定的 32 位元有號整數轉換為等效的雙精度浮點數。

```cpp
static constexpr double System::Convert::ToDouble(int32_t value)
```
## Convert::ToDouble(uint64_t) 方法

將指定的 64 位元無號整數轉換為等效的雙精度浮點數。

```cpp
static constexpr double System::Convert::ToDouble(uint64_t value)
```
## Convert::ToDouble(int64_t) 方法

將指定的 64 位元有號整數轉換為等效的雙精度浮點數。

```cpp
static constexpr double System::Convert::ToDouble(int64_t value)
```
## Convert::ToDouble(float) 方法

將指定的單精度數字轉換為等效的雙精度浮點數。

```cpp
static constexpr double System::Convert::ToDouble(float value)
```
## Convert::ToDouble(double) 方法

傳回指定的 double 數字。

```cpp
static constexpr double System::Convert::ToDouble(double value)
```
## Convert::ToDouble(const Decimal\&) 方法

將指定的十進位數字轉換為等效的雙精度浮點數。

```cpp
static double System::Convert::ToDouble(const Decimal &value)
```
## Convert::ToDouble(char_t) 方法

不支援此轉換。永遠拋出 InvalidCastException。

```cpp
static double System::Convert::ToDouble(char_t value)
```
## Convert::ToDouble(DateTime) 方法

不支援此轉換。永遠拋出 InvalidCastException。

```cpp
static double System::Convert::ToDouble(DateTime value)
```
## Convert::ToDouble(std::nullptr_t) 方法

將指定的 null 字串轉換為等效的雙精度浮點值。

```cpp
static constexpr double System::Convert::ToDouble(std::nullptr_t)
```


### 傳回值

0。

## Convert::ToDouble(const char_t *) 方法


將包含數字字串表示的 c 字串轉換為等效的雙精度浮點值。

```cpp
static double System::Convert::ToDouble(const char_t *value)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const char_t * | 要轉換的 c 字串 |

### 傳回值

等同於指定 c 字串所表示之數字的雙精度浮點值

## Convert::ToDouble(const String\&) 方法


將包含數字字串表示之字串轉換為等效的雙精度浮點值。

```cpp
static double System::Convert::ToDouble(const String &value)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串 |

### 傳回值

等同於指定字串所表示之數字的雙精度浮點值

## Convert::ToDouble(const String\&, const SharedPtr\<IFormatProvider\>\&) 方法


使用提供的格式資訊，將包含數字字串表示之字串轉換為等效的雙精度浮點值。

```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 指向包含字串格式資訊之物件的指標 |

### 傳回值

等同於指定字串所表示之數字的雙精度浮點值

## Convert::ToDouble(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) 方法




```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDouble(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 方法




```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToDouble(const String\&, std::nullptr_t) 方法




```cpp
static double System::Convert::ToDouble(const String &value, std::nullptr_t)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) 方法


使用提供的格式資訊與數字樣式，將包含數字字串表示之字串轉換為等效的雙精度浮點值。

```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles 列舉值的位元組合，用以指定允許的數字字串表示樣式 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 指向包含字串格式資訊之物件的指標 |

### 傳回值

等同於指定字串所表示之數字的雙精度浮點值

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) 方法




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 方法




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, std::nullptr_t) 方法




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToDouble(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) 方法


將指定的箱裝值轉換為雙精度浮點值。若箱裝值的類型為 [String](../../string/)，則在轉換期間使用指定的字串格式。

```cpp
static double System::Convert::ToDouble(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 指向箱裝該值的物件之 shared pointer |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 若箱裝值的類型為 [String](../../string/)，將使用的字串格式 |

### 傳回值

等同於指定箱裝值的雙精度浮點值

## 另請參閱

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* 類別 [Decimal](../../decimal/)
* 類別 [DateTime](../../datetime/)
* 類別 [String](../../string/)
* 類別 [IFormatProvider](../../iformatprovider/)
* 類別 [CultureInfo](../../../system.globalization/cultureinfo/)
* 類別 [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* 類別 [Object](../../object/)
* Struct [Convert](../)
* 命名空間 [System](../../)
* Library [Aspose.Slides](../../../)