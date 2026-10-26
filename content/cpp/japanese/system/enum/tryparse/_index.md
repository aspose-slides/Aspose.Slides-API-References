---
title: TryParse()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された文字列を等価の列挙定数に変換しようとします。
type: docs
weight: 79
url: /ja/system/enum/tryparse/
---
## Enum::TryParse(const String\&, E\&) メソッド

指定された文字列を等価の列挙定数に変換しようとします。

```cpp
static bool System::Enum<E, Guard>::TryParse(const String &str, E &result)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | const [String](../../string/)\& | [String](../../string/) は列挙定数の名前が含まれていると解釈されます |
| result | E\& | 変換が成功した場合、関数の変換結果を含む出力パラメータです |

### 戻り値

変換が成功した場合は true、そうでない場合は false

## Enum::TryParse(const String\&, bool, E\&) メソッド

指定された文字列を等価の列挙定数に変換しようとします。

```cpp
static bool System::Enum<E, Guard>::TryParse(const String &str, bool ignoreCase, E &result)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | const [String](../../string/)\& | [String](../../string/) は列挙定数の名前が含まれていると解釈されます |
| ignoreCase | **bool** | 文字列を解釈する際に大文字小文字を無視するかどうかを指定します |
| result | E\& | 変換が成功した場合、関数の戻り値の変換結果を含む出力パラメータです |

### 戻り値

変換が成功した場合は true、そうでない場合は false

## 関連項目

* クラス [String](../../string/)
* 構造体 [Enum](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)