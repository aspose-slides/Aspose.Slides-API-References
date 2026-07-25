---
title: Parse()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された文字列を DateTimeOffset に相当するものに変換します。
type: docs
weight: 703
url: /ja/system/datetimeoffset/parse/
---
## DateTimeOffset::Parse(const String\&) メソッド

指定された文字列を [DateTimeOffset](../) に相当するものに変換します。

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) を変換します。 |

### 戻り値

[DateTimeOffset](../) は **input** に相当します。

## DateTimeOffset::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) メソッド

指定された文字列を、指定されたフォーマットプロバイダーと書式スタイルを使用して [DateTimeOffset](../) オブジェクトに変換します。

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) を変換します。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | フォーマットプロバイダー。 |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | 日付と時刻の書式スタイル。 |

### 戻り値

[DateTimeOffset](../) は **input** に相当します。

## 参照

* 列挙体 [DateTimeStyles](../../../system.globalization/datetimestyles/)
* 型定義 [SharedPtr](../../sharedptr/)
* クラス [DateTimeOffset](../)
* クラス [String](../../string/)
* クラス [IFormatProvider](../../iformatprovider/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)