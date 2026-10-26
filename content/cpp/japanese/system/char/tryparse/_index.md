---
title: TryParse()
second_title: Aspose.Slides for C++ API リファレンス
description: 単一文字からなる文字列を UTF-16 文字に変換しようとします。入力文字列が null でなく、長さがちょうど 1 文字である場合にのみ関数は成功します。
type: docs
weight: 300
url: /ja/system/char/tryparse/
---
## Char::TryParse(const System::String\&, char_t\&) メソッド

単一文字からなる文字列を UTF-16 文字に変換しようとします。入力文字列が null でなく、長さがちょうど 1 文字である場合にのみ関数は成功します。

```cpp
static bool System::Char::TryParse(const System::String &s, char_t &result)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| s | const [System::String](../../string/)\& | [String](../../string/) を変換する |
| result | char_t\& | 変換が成功した場合に結果を格納する出力変数 |

### 戻り値

変換が成功した場合は true、そうでない場合は false

## 参照

* クラス [String](../../string/)
* クラス [Char](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)