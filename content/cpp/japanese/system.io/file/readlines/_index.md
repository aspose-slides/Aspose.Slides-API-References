---
title: ReadLines()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたテキストファイルの内容を、指定された文字エンコーディングを使用して行単位で読み取り、各行を表す文字列の列挙可能なコレクションを返します。
type: docs
weight: 326
url: /ja/system.io/file/readlines/
---
## File::ReadLines(const String&, const EncodingPtr&) メソッド

指定されたテキストファイルの内容を、指定された文字エンコーディングを使用して行単位で読み取り、各行を表す文字列の列挙可能なコレクションを返します。

```cpp
static SharedPtr<Collections::Generic::IEnumerable<String>> System::IO::File::ReadLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 読み取るファイルのパス |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 使用する文字エンコーディング |

### 戻り値

指定されたファイルの内容を表す文字列の列挙可能なコレクション

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* クラス [IEnumerable](../../../system.collections.generic/ienumerable/)
* クラス [String](../../../system/string/)
* クラス [File](../)
* 名前空間 [System::IO](../../)
* Library [Aspose.Slides](../../../)