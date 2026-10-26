---
title: GetDateTimeFormats()
second_title: Aspose.Slides for C++ API リファレンス
description: 標準の日付および時刻書式指定子のいずれかでフォーマットされた、現在のオブジェクトの文字列表現を要素とする文字列配列を返します。
type: docs
weight: 547
url: /ja/system/datetime/getdatetimeformats/
---
## DateTime::GetDateTimeFormats() const メソッド

標準の日付および時刻書式指定子のいずれかでフォーマットされた、現在のオブジェクトの文字列表現を要素とする文字列配列を返します。

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats() const
```
## DateTime::GetDateTimeFormats(char_t) const メソッド

指定された標準の日付および時刻書式指定子でフォーマットされた、現在のオブジェクトの文字列表現を要素とする文字列配列を返します。

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(char_t format) const
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| format | char_t | Standard date and time format specifier. |

## DateTime::GetDateTimeFormats(const SharedPtr\<IFormatProvider\>\&) const メソッド

標準の日付および時刻書式指定子のいずれかと、指定されたフォーマットプロバイダーを使用してフォーマットされた、現在のオブジェクトの文字列表現を要素とする文字列配列を返します。

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(const SharedPtr<IFormatProvider> &provider) const
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format provider. |

## DateTime::GetDateTimeFormats(char_t, const SharedPtr\<IFormatProvider\>\&) const メソッド

指定された標準の日付および時刻書式指定子とフォーマットプロバイダーを使用してフォーマットされた、現在のオブジェクトの文字列表現を要素とする文字列配列を返します。

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(char_t format, const SharedPtr<IFormatProvider> &provider) const
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| format | char_t | Standard date and time format specifier. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format provider. |

## 参照

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* クラス [String](../../string/)
* クラス [DateTime](../)
* クラス [IFormatProvider](../../iformatprovider/)
* 名前空間 [System](../../)
* Library [Aspose.Slides](../../../)