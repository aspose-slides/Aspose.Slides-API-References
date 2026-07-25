---
title: ParseExact()
second_title: Aspose.Slides for C++ APIリファレンス
description: 指定された形式、フォーマット プロバイダー、および書式設定スタイルを使用して、指定された文字列を DateTimeOffset オブジェクトに変換します。
type: docs
weight: 716
url: /ja/system/datetimeoffset/parseexact/
---
## DateTimeOffset::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) メソッド


指定された文字列を、指定された形式、フォーマット プロバイダー、および書式設定スタイルを使用して [DateTimeOffset](../) オブジェクトに変換します。

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) を変換します。 |
| format | const [String](../../string/)\& | フォーマット文字列。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | フォーマット プロバイダー。 |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | 日付と時刻の書式設定スタイル。 |

### 戻り値

[DateTimeOffset](../) は **input** と同等です。

## DateTimeOffset::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) メソッド


指定された文字列を、指定された形式群、フォーマット プロバイダー、および書式設定スタイルを使用して [DateTimeOffset](../) オブジェクトに変換します。

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) を変換します。 |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | [Array](../../array/) のフォーマット文字列。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | フォーマット プロバイダー。 |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | 日付と時刻の書式設定スタイル。 |

### 戻り値

[DateTimeOffset](../) は **input** と同等です。

## 参照

* 列挙 [DateTimeStyles](../../../system.globalization/datetimestyles/)
* 型定義 [SharedPtr](../../sharedptr/)
* 型定義 [ArrayPtr](../../arrayptr/)
* クラス [DateTimeOffset](../)
* クラス [String](../../string/)
* クラス [IFormatProvider](../../iformatprovider/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)