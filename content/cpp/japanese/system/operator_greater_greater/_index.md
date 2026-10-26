---
title: operator>>()
second_title: Aspose.Slides for C++ API リファレンス
description: 入力ストリームから UTF-8 エンコーディングを使用して文字列を取得します。
type: docs
weight: 3004
url: /ja/system/operator_greater_greater/
---
## System::operator>>(std::istream\&, String\&) 関数

入力ストリームから UTF-8 エンコーディングを使用して文字列を取得します。

```cpp
std::istream & System::operator>>(std::istream &in, String &str)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| in | std::istream\& | 入力ストリームオブジェクト（**char** を使用した **basic_ostream** のインスタンス）。 |
| str | [String](../string/)\& | 入力ストリームから読み取る文字列。 |

### 戻り値

文字列が抽出された入力ストリーム。

## System::operator>>(std::wistream\&, String\&) 関数

入力ストリームから文字列を取得します。

```cpp
std::wistream & System::operator>>(std::wistream &in, String &str)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| in | std::wistream\& | 入力ストリームオブジェクト（****wchar_t**** を使用した **basic_ostream** のインスタンス）。 |
| str | [String](../string/)\& | 入力ストリームから読み取る文字列。 |

### 戻り値

文字列が抽出された入力ストリーム。

## 参照

* クラス [String](../string/)
* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)