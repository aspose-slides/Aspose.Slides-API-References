---
title: GetCultureInfo()
second_title: Aspose.Slides for C++ API リファレンス
description: 名前でカルチャーを取得します。CreateSpecificCulture と同じです。
type: docs
weight: 586
url: /ja/system.globalization/cultureinfo/getcultureinfo/
---
## CultureInfo::GetCultureInfo(const String\&) メソッド

名前でカルチャーを取得します。CreateSpecificCulture と同じです。

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(const String &name)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | 事前定義されたカルチャー名または既存のカルチャーオブジェクトの名前。 |

### 戻り値

新しく作成されたカルチャーオブジェクト。

## CultureInfo::GetCultureInfo(const String\&, const String\&) メソッド

名前でカルチャーを取得します。

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(const String &name, const String &text_and_compare_culture_name)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | カルチャー名。 |
| text_and_compare_culture_name | const [String](../../../system/string/)\& | [TextInfo](../../textinfo/) と [CompareInfo](../../compareinfo/) オブジェクトに使用されるカルチャー名。 |

### 戻り値

カルチャーオブジェクト。

## CultureInfo::GetCultureInfo(int32_t) メソッド

IDでカルチャーを取得します。

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(int32_t culture)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| culture | **int32_t** | カルチャー識別子。 |

### 戻り値

新しく作成されたカルチャーオブジェクト。

## 参照

* 型定義 [CultureInfoPtr](../../cultureinfoptr/)
* クラス [String](../../../system/string/)
* クラス [CultureInfo](../)
* 名前空間 [System::Globalization](../../)
* ライブラリ [Aspose.Slides](../../../)