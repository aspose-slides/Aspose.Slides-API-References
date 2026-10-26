---
title: ToString()
second_title: Aspose.Slides for C++ API 參考文件
description: 傳回目前物件所代表之日期與時間值的字串表示形式，使用目前文化所定義的格式慣例。
type: docs
weight: 482
url: /zh-hant/system/datetime/tostring/
---
## DateTime::ToString() const 方法


傳回目前物件所代表之日期與時間值的字串表示形式，使用目前文化所定義的格式慣例。

```cpp
String System::DateTime::ToString() const
```


### 返回值

目前物件所代表之值的字串表示形式

## DateTime::ToString(const String\&) const 方法


傳回目前物件所代表之日期與時間值的字串表示形式，使用指定的格式以及目前文化所定義的格式慣例。

```cpp
String System::DateTime::ToString(const String &format) const
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| format | const [String](../../string/)\& | 格式字串 |

### 返回值

目前物件所代表之值的字串表示形式，依 **format** 與目前文化定義的格式進行格式化。

## DateTime::ToString(const SharedPtr\<IFormatProvider\>\&) const 方法


傳回目前物件所代表之日期與時間值的字串表示形式，使用指定的格式資訊。

```cpp
String System::DateTime::ToString(const SharedPtr<IFormatProvider> &provider) const
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 表示格式資訊的物件 |

### 返回值

目前物件所代表之值的字串表示形式，依 **formatProvider** 提供的格式資訊進行格式化。

## DateTime::ToString(const SharedPtr\<Globalization::CultureInfo\>\&) const 方法




```cpp
String System::DateTime::ToString(const SharedPtr<Globalization::CultureInfo> &culture) const
```

## DateTime::ToString(const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const 方法




```cpp
String System::DateTime::ToString(const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## DateTime::ToString(std::nullptr_t) const 方法




```cpp
String System::DateTime::ToString(std::nullptr_t) const
```

## DateTime::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const 方法


傳回目前物件所代表之日期與時間值的字串表示形式，使用指定的格式資訊。

```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| format | const [String](../../string/)\& | 格式字串 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 表示格式資訊的物件 |

### 返回值

目前物件所代表之值的字串表示形式，依 **provider** 提供的格式資訊以及 **format** 格式字串進行格式化。

## DateTime::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const 方法




```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## DateTime::ToString(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const 方法




```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## DateTime::ToString(const String\&, std::nullptr_t) const 方法




```cpp
String System::DateTime::ToString(const String &format, std::nullptr_t) const
```

## 另請參閱

* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [DateTime](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)