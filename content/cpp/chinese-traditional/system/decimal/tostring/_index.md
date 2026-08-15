---
title: ToString()
second_title: Aspose.Slides for C++ API 參考文件
description: 傳回由物件所代表之值的字串表示形式。
type: docs
weight: 352
url: /zh-hant/system/decimal/tostring/
---
## Decimal::ToString() const 方法

傳回此物件所代表之值的字串表示形式。

```cpp
String System::Decimal::ToString() const
```

## Decimal::ToString(const SharedPtr\<IFormatProvider\>\&) const 方法

使用文化特定的格式資訊將目前物件轉換為字串。

```cpp
String System::Decimal::ToString(const SharedPtr<IFormatProvider> &provider) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 提供文化特定格式資訊的 [IFormatProvider](../../iformatprovider/) 物件。 |

### 傳回值

目前物件的字串表示形式。

## Decimal::ToString(const SharedPtr\<Globalization::CultureInfo\>\&) const 方法

```cpp
String System::Decimal::ToString(const SharedPtr<Globalization::CultureInfo> &culture) const
```

## Decimal::ToString(const SharedPtr\<Globalization::NumberFormatInfo\>\&) const 方法

```cpp
String System::Decimal::ToString(const SharedPtr<Globalization::NumberFormatInfo> &nfi) const
```

## Decimal::ToString(const Decimal\&, std::nullptr_t) const 方法

```cpp
String System::Decimal::ToString(const Decimal &value, std::nullptr_t) const
```

## Decimal::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const 方法

使用指定的字串格式以及由指定的 [IFormatProvider](../../iformatprovider/) 物件提供的文化特定格式資訊，將目前物件轉換為其字串表示形式。

```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| format | const [String](../../string/)\& | 字串格式。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 提供文化特定格式資訊的 [IFormatProvider](../../iformatprovider/) 物件。 |

### 傳回值

目前物件的字串表示形式。

## Decimal::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const 方法

```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## Decimal::ToString(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) const 方法

```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<Globalization::NumberFormatInfo> &nfi) const
```

## Decimal::ToString(const String\&, std::nullptr_t) const 方法

```cpp
String System::Decimal::ToString(const String &format, std::nullptr_t=nullptr) const
```

## 另請參閱

* 類型定義 [SharedPtr](../../sharedptr/)
* 類別 [String](../../string/)
* 類別 [Decimal](../)
* 類別 [IFormatProvider](../../iformatprovider/)
* 類別 [CultureInfo](../../../system.globalization/cultureinfo/)
* 類別 [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)