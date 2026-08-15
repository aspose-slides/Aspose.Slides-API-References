---
title: GetDateTimeFormats()
second_title: Aspose.Slides for C++ API 參考文件
description: 傳回字串陣列，其中每個元素都是以標準日期和時間格式說明符之一格式化的目前物件之字串表示形式。
type: docs
weight: 547
url: /zh-hant/system/datetime/getdatetimeformats/
---
## DateTime::GetDateTimeFormats() const 方法

傳回字串陣列，其中每個元素都是以標準日期和時間格式說明符之一格式化的目前物件之字串表示形式。

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats() const
```
## DateTime::GetDateTimeFormats(char_t) const 方法

傳回字串陣列，其中每個元素都是以指定的標準日期和時間格式說明符格式化的目前物件之字串表示形式。

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(char_t format) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| format | char_t | 標準日期和時間格式說明符。 |

## DateTime::GetDateTimeFormats(const SharedPtr\<IFormatProvider\>\&) const 方法

傳回字串陣列，其中每個元素都是以標準日期和時間格式說明符之一以及指定的格式提供程式格式化的目前物件之字串表示形式。

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(const SharedPtr<IFormatProvider> &provider) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 格式提供程式。 |

## DateTime::GetDateTimeFormats(char_t, const SharedPtr\<IFormatProvider\>\&) const 方法

傳回字串陣列，其中每個元素都是以指定的標準日期和時間格式說明符以及格式提供程式格式化的目前物件之字串表示形式。

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(char_t format, const SharedPtr<IFormatProvider> &provider) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| format | char_t | 標準日期和時間格式說明符。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 格式提供程式。 |

## 參見

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* 類別 [String](../../string/)
* 類別 [DateTime](../)
* 類別 [IFormatProvider](../../iformatprovider/)
* 命名空間 [System](../../)
* Library [Aspose.Slides](../../../)