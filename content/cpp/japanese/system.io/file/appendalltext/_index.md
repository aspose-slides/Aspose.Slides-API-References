---
title: AppendAllText()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたエンコーディングを使用して、指定された文字列を指定されたファイルに追加します。
type: docs
weight: 14
url: /ja/system.io/file/appendalltext/
---
## File::AppendAllText(const String\&, const String\&, const EncodingPtr\&) メソッド


指定されたエンコーディングを使用して、指定された文字列を指定されたファイルに追加します。

```cpp
static void System::IO::File::AppendAllText(const String &path, const String &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 文字列を追加するファイルのパス |
| contents | const [String](../../../system/string/)\& | ファイルに書き込む文字列 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 使用する文字エンコーディング |

## 参照

* Typedef [EncodingPtr](../../../system/encodingptr/)
* クラス [String](../../../system/string/)
* クラス [File](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)