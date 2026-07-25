---
title: ReadAllLines()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された文字エンコーディングを使用して、指定されたテキストファイルの内容を行単位で文字列の配列に読み取ります。
type: docs
weight: 300
url: /ja/system.io/file/readalllines/
---
## File::ReadAllLines(const String\&, const EncodingPtr\&) メソッド

指定されたテキストファイルの内容を、指定された文字エンコーディングを使用して、行単位で文字列の配列に読み込みます。

```cpp
static ArrayPtr<String> System::IO::File::ReadAllLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 読み込むファイルのパス |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 使用する文字エンコーディング |

### 戻り値

各要素が指定されたファイルの 1 行を表す文字列配列です。

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* 型定義 [EncodingPtr](../../../system/encodingptr/)
* クラス [String](../../../system/string/)
* クラス [File](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)