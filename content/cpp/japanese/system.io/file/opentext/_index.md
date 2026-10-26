---
title: OpenText()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された既存のファイルを、UTF-8 エンコーディングでテキスト読み取り用に、共有なしで開きます。
type: docs
weight: 261
url: /ja/system.io/file/opentext/
---
## File::OpenText(const String\&, const EncodingPtr\&) メソッド

指定された既存のファイルを、UTF-8 エンコーディングでテキスト読み取り用に、共有なしで開きます。

```cpp
static StreamReaderPtr System::IO::File::OpenText(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 開くファイルのパス |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 使用する文字エンコーディング |

### 戻り値

開かれたファイルに関連付けられた [StreamWriter](../../streamwriter/) オブジェクトへの共有ポインタ

## 参照

* typedef [StreamReaderPtr](../../../system/streamreaderptr/)
* typedef [EncodingPtr](../../../system/encodingptr/)
* クラス [String](../../../system/string/)
* クラス [File](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)