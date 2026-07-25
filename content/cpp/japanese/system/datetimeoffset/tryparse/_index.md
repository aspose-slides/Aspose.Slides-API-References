---
title: TryParse()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された文字列を DateTimeOffset オブジェクトに変換しようとします。
type: docs
weight: 729
url: /ja/system/datetimeoffset/tryparse/
---
## DateTimeOffset::TryParse(const String\&, DateTimeOffset\&) method

指定された文字列を [DateTimeOffset](../) オブジェクトに変換しようとします。

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, DateTimeOffset &result)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) を変換します。 |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) は **input** と等価です。 |

### 戻り値

**input** が正常に変換された場合は true、そうでない場合は false を返します。

## DateTimeOffset::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) method

指定された文字列を、指定されたフォーマット プロバイダーと書式設定スタイルを使用して [DateTimeOffset](../) オブジェクトに変換しようとします。

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) を変換します。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | フォーマット プロバイダー。 |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | 日付と時刻の書式設定スタイル。 |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) は **input** と等価です。 |

### 戻り値

**input** が正常に変換された場合は true、そうでない場合は false を返します。

## 参照

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* クラス [String](../../string/)
* クラス [DateTimeOffset](../)
* クラス [IFormatProvider](../../iformatprovider/)
* 名前空間 [System](../../)
* Library [Aspose.Slides](../../../)