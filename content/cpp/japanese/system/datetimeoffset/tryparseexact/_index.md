---
title: TryParseExact()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたフォーマット、フォーマットプロバイダー、書式設定スタイルを使用して、指定された文字列を DateTimeOffset オブジェクトに変換しようとします。
type: docs
weight: 742
url: /ja/system/datetimeoffset/tryparseexact/
---
## DateTimeOffset::TryParseExact(const String&, const ArrayPtr<String>&, const SharedPtr<IFormatProvider>&, Globalization::DateTimeStyles, DateTimeOffset&) メソッド

指定された文字列を、指定されたフォーマット、フォーマットプロバイダー、および書式設定スタイルを使用して [DateTimeOffset](../) オブジェクトに変換しようとします。

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | const [String](../../string/)& | [String](../../string/) を変換します。 |
| formats | const [ArrayPtr](../../arrayptr/)<[String](../../string/)>& | フォーマット文字列の配列です。 |
| provider | const [SharedPtr](../../sharedptr/)<[IFormatProvider](../../iformatprovider/)>& | フォーマットプロバイダーです。 |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | 日付と時刻の書式設定スタイルです。 |
| result | [DateTimeOffset](../)& | **input** に相当する [DateTimeOffset](../) です。 |

### 戻り値

**input** が正常に変換された場合は true、そうでない場合は false。

## DateTimeOffset::TryParseExact(const String&, const String&, const SharedPtr<IFormatProvider>&, Globalization::DateTimeStyles, DateTimeOffset&) メソッド

指定された文字列を、指定されたフォーマット、フォーマットプロバイダー、および書式設定スタイルを使用して [DateTimeOffset](../) オブジェクトに変換しようとします。

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | const [String](../../string/)& | [String](../../string/) を変換します。 |
| format | const [String](../../string/)& | フォーマット文字列です。 |
| provider | const [SharedPtr](../../sharedptr/)<[IFormatProvider](../../iformatprovider/)>& | フォーマットプロバイダーです。 |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | 日付と時刻の書式設定スタイルです。 |
| result | [DateTimeOffset](../)& | **input** に相当する [DateTimeOffset](../) です。 |

### 戻り値

**input** が正常に変換された場合は true、そうでない場合は false。

## 参照

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)