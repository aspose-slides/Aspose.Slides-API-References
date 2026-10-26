---
title: WriteAllText()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたエンコーディングを使用して、指定された文字列の内容を新しいテキストファイルに作成するか、既存のファイルを上書きして書き込みます。
type: docs
weight: 469
url: /ja/system.io/file/writealltext/
---
## File::WriteAllText(const String&, const String&, const EncodingPtr&) メソッド

指定された文字列の内容を、指定されたエンコーディングを使用して新しいテキストファイルに作成するか、既存のファイルを上書きして書き込みます。

```cpp
static void System::IO::File::WriteAllText(const String &path, const String &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 作成または上書きするファイル |
| contents | const [String](../../../system/string/)\& | 文字列配列 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 使用する文字エンコーディング |

## 参照

* Typedef [EncodingPtr](../../../system/encodingptr/)
* クラス [String](../../../system/string/)
* クラス [File](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)