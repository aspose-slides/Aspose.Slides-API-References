---
title: Parse()
second_title: Aspose.Slides for C++ API 參考
description: 將十進位數字的字串表示轉換為等效的 Decimal 類別實例。
type: docs
weight: 469
url: /zh-hant/system/decimal/parse/
---
## Decimal::Parse(const String\&) 方法


將十進位數字的字串表示轉換為等效的 [Decimal](../) 類別 實例。

```cpp
static Decimal System::Decimal::Parse(const String &s)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | 數字的字串表示 |

### 返回值

[Decimal](../) 類別 的新實例，表示與指定字串所表示的值等價的值。

## Decimal::Parse(const String\&, Globalization::NumberStyles) 方法


使用指定的樣式，將十進位數字的字串表示轉換為等效的 [Decimal](../) 類別 實例。

```cpp
static Decimal System::Decimal::Parse(const String &s, Globalization::NumberStyles styles)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | 要轉換的十進位值的字串表示 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | 列舉值的位元組合，提供有關 **s** 的其他資訊、**s** 中可能出現的樣式元素，或 **s** 轉換為 [Decimal](../) 物件的相關資訊 |

### 返回值

[Decimal](../) 類別 的新實例，表示與指定字串所表示的值等價的值。

## Decimal::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) 方法


使用指定的格式提供程式，將十進位數字的字串表示轉換為等效的 [Decimal](../) 類別 實例。

```cpp
static Decimal System::Decimal::Parse(const String &s, const SharedPtr<IFormatProvider> &provider)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | 要轉換的十進位值的字串表示 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 格式提供程式 |

### 返回值

[Decimal](../) 類別 的新實例，表示與指定字串所表示的值等價的值。

## Decimal::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) 方法


使用指定的樣式與格式提供程式，將十進位數字的字串表示轉換為等效的 [Decimal](../) 類別 實例。

```cpp
static Decimal System::Decimal::Parse(const String &s, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | 要轉換的十進位值的字串表示 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | 列舉值的位元組合，提供有關 **s** 的其他資訊、**s** 中可能出現的樣式元素，或 **s** 轉換為 [Decimal](../) 物件的相關資訊 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 格式提供程式 |

### 返回值

[Decimal](../) 類別 的新實例，表示與指定字串所表示的值等價的值。

## 另請參閱

* 列舉 [NumberStyles](../../../system.globalization/numberstyles/)
* 型別別名 [SharedPtr](../../sharedptr/)
* 類別 [Decimal](../)
* 類別 [String](../../string/)
* 類別 [IFormatProvider](../../iformatprovider/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)