---
title: WriteAllLines()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しいテキストファイルを作成するか、既存のファイルを上書きし、指定された列挙可能な文字列コレクションからすべての文字列を書き込みます。各文字列は新しい行に配置され、指定されたエンコーディングが使用されます。
type: docs
weight: 456
url: /ja/system.io/file/writealllines/
---
## File::WriteAllLines(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) メソッド

新しいテキストファイルを作成するか、既存のファイルを上書きし、指定された列挙可能な文字列コレクションからすべての文字列を書き込みます。各文字列は新しい行に配置され、指定されたエンコーディングが使用されます。

```cpp
static void System::IO::File::WriteAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 作成または上書きするファイル |
| contents | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | 列挙可能な文字列コレクション |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 使用する文字エンコーディング |

## File::WriteAllLines(const String\&, const ArrayPtr\<String\>\&, const EncodingPtr\&) メソッド

新しいテキストファイルを作成するか、既存のファイルを上書きし、指定された文字列配列からすべての文字列を書き込みます。各文字列は新しい行に配置され、指定されたエンコーディングが使用されます。

```cpp
static void System::IO::File::WriteAllLines(const String &path, const ArrayPtr<String> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 作成または上書きするファイル |
| contents | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | 文字列配列 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 使用する文字エンコーディング |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [EncodingPtr](../../../system/encodingptr/)
* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [String](../../../system/string/)
* クラス [IEnumerable](../../../system.collections.generic/ienumerable/)
* クラス [File](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)