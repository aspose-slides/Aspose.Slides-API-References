---
title: AppendAllLines()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたエンコーディングを使用し、指定された文字列コレクションから文字列を新しい行に書き込むことで、指定されたファイルに文字列を追加します。指定されたファイルが存在しない場合は作成されます。すべての文字列を書き込んだ後、ファイルは閉じられます。
type: docs
weight: 1
url: /ja/system.io/file/appendalllines/
---
## File::AppendAllLines(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) メソッド

指定された文字エンコーディングを使用して、指定された文字列コレクションから文字列を新しい行に書き込むことで、指定されたファイルに追加します。指定されたファイルが存在しない場合は作成されます。すべての文字列を書き込んだ後、ファイルは閉じられます。

```cpp
static void System::IO::File::AppendAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 文字列を追加するファイルのパス |
| contents | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | ファイルに書き込む文字列 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 使用する文字エンコーディング |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* クラス [String](../../../system/string/)
* クラス [IEnumerable](../../../system.collections.generic/ienumerable/)
* クラス [File](../)
* 名前空間 [System::IO](../../)
* Library [Aspose.Slides](../../../)