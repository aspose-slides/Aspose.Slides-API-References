---
title: ReadAllText()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された文字エンコーディングを使用して、指定されたテキストファイルの内容を単一の String オブジェクトに読み込みます。
type: docs
weight: 313
url: /ja/system.io/file/readalltext/
---
## File::ReadAllText(const String&, const EncodingPtr&) メソッド


指定されたテキストファイルの内容を、指定された文字エンコーディングを使用して単一の [String](../../../system/string/) オブジェクトに読み込みます。

```cpp
static String System::IO::File::ReadAllText(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| path | const [String](../../../system/string/)& | 読み込むファイルのパス |
| encoding | const [EncodingPtr](../../../system/encodingptr/)& | 使用する文字エンコーディング |

### 戻り値

指定されたファイルの内容を含む文字列

## 関連項目

* 型定義 [EncodingPtr](../../../system/encodingptr/)
* クラス [String](../../../system/string/)
* クラス [File](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)