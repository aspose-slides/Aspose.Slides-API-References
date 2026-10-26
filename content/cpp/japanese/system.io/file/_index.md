---
title: File
second_title: Aspose.Slides for C++ API リファレンス
description: ファイルを操作するためのメソッドを提供します。これはインスタンスサービスを持たない static 型です。いかなる方法でもインスタンスを作成すべきではありません。
type: docs
weight: 261
url: /ja/system.io/file/
---
## File クラス

ファイルを操作するためのメソッドを提供します。これはインスタンスサービスを持たない static 型です。いかなる方法でもインスタンスを作成すべきではありません。

```cpp
class File
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| static void [AppendAllLines](./appendalllines/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | 指定された文字列コレクションから文字列を指定されたファイルへ、指定されたエンコーディングを使用して各文字列を新しい行に書き込むことで追加します。指定されたファイルが存在しない場合は作成されます。すべての文字列の書き込みが完了した後、ファイルは閉じられます。 |
| static void [AppendAllText](./appendalltext/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | 指定された文字列を指定されたファイルへ、指定されたエンコーディングを使用して追加します。 |
| static [StreamWriterPtr](../../system/streamwriterptr/) [AppendText](./appendtext/)(const [String](../../system/string/)\&) | UTF-8 エンコーディングを使用して、指定されたファイルにテキストを追加する [StreamWriter](../streamwriter/) オブジェクトを作成します。指定されたファイルが存在しない場合は作成されます。 |
| static void [Copy](./copy/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | 指定されたファイルを指定された場所へコピーします。宛先のファイルが既に存在する場合、パラメータで上書きするかどうかを指定します。 |
| static [FileStreamPtr](../../system/filestreamptr/) [Create](./create/)(const [String](../../system/string/)\&, **int32_t**, [FileOptions](../fileoptions/)) | 指定されたバッファサイズとオプションを使用して、新しいファイル（または既存のファイルを上書き）を作成し、読み書きアクセス用に開きます。 |
| static [StreamWriterPtr](../../system/streamwriterptr/) [CreateText](./createtext/)(const [String](../../system/string/)\&) | UTF-8 エンコードされたテキストを書き込むために、新しいファイルまたは既存のファイルを作成または開きます。 |
| static void [Decrypt](./decrypt/)(const [String](../../system/string/)\&) | NOT IMPLEMENTED. |
| static void [Delete](./delete/)(const [String](../../system/string/)\&) | 指定されたファイルまたはディレクトリを削除します。 |
| static void [Encrypt](./encrypt/)(const [String](../../system/string/)\&) | NOT IMPLEMENTED. |
| static **bool** [Exists](./exists/)(const [String](../../system/string/)\&) | 指定されたパスが既存のファイルを参照しているかどうかを判断します。 |
| static [FileAttributes](../fileattributes/) [GetAttributes](./getattributes/)(const [String](../../system/string/)\&) | 指定されたエンティティの属性を返します。 |
| static [DateTime](../../system/datetime/) [GetCreationTime](./getcreationtime/)(const [String](../../system/string/)\&) | 指定されたエンティティの作成時刻をローカル時間で返します。 |
| static [DateTime](../../system/datetime/) [GetCreationTimeUtc](./getcreationtimeutc/)(const [String](../../system/string/)\&) | 指定されたエンティティの作成時刻を UTC 時間で返します。 |
| static [DateTime](../../system/datetime/) [GetLastAccessTime](./getlastaccesstime/)(const [String](../../system/string/)\&) | 指定されたエンティティの最終アクセス時刻をローカル時間で返します。 |
| static [DateTime](../../system/datetime/) [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const [String](../../system/string/)\&) | 指定されたエンティティの最終アクセス時刻を UTC 時間で返します。 |
| static [DateTime](../../system/datetime/) [GetLastWriteTime](./getlastwritetime/)(const [String](../../system/string/)\&) | 指定されたエンティティの最終書き込み時刻をローカル時間で返します。 |
| static [DateTime](../../system/datetime/) [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const [String](../../system/string/)\&) | 指定されたエンティティの最終書き込み時刻を UTC 時間で返します。 |
| static void [Move](./move/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 指定されたファイルを新しい場所へ移動します。 |
| static [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)(const [String](../../system/string/)\&, [FileMode](../filemode/)) | 指定されたモードで指定されたファイルを読み書き用に開き、共有なしで操作します。 |
| static [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)(const [String](../../system/string/)\&, [FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/)) | 指定されたモードで、指定されたアクセス種別と共有オプションを使用して指定されたファイルを開きます。 |
| static [FileStreamPtr](../../system/filestreamptr/) [OpenRead](./openread/)(const [String](../../system/string/)\&) | 読み取り専用で、'Open' モードかつ読み取り用の共有アクセスで指定されたファイルを開きます。 |
| static [StreamReaderPtr](../../system/streamreaderptr/) [OpenText](./opentext/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | UTF-8 エンコーディングを使用してテキストを読み取り、共有なしで既存の指定ファイルを開きます。 |
| static [FileStreamPtr](../../system/filestreamptr/) [OpenWrite](./openwrite/)(const [String](../../system/string/)\&) | 書き込み専用で、'OpenOrCreate' モードかつ共有なしで指定されたファイルを開きます。 |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ReadAllBytes](./readallbytes/)(const [String](../../system/string/)\&) | 指定されたバイナリファイルの内容をバイト配列に読み取ります。 |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [ReadAllLines](./readalllines/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | 指定された文字エンコーディングを使用して、指定されたテキストファイルの内容を行ごとに文字列配列へ読み取ります。 |
| static [String](../../system/string/) [ReadAllText](./readalltext/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | 指定された文字エンコーディングを使用して、指定されたテキストファイルの内容を単一の [String](../../system/string/) オブジェクトに読み取ります。 |
| static [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\> [ReadLines](./readlines/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | 指定された文字エンコーディングを使用して、指定されたテキストファイルの内容を行ごとに読み取り、各行を表す文字列の列挙可能なコレクションを返します。 |
| static void [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | あるファイルの内容を別のファイルで置き換え、置き換えられたファイルのバックアップを作成します。 |
| static void [SetAttributes](./setattributes/)(const [String](../../system/string/)\&, [FileAttributes](../fileattributes/)) | 指定されたファイルに指定された属性を設定します。 |
| static void [SetCreationTime](./setcreationtime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NOT IMPLEMENTED. |
| static void [SetCreationTimeUtc](./setcreationtimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NOT IMPLEMENTED. |
| static void [SetLastAccessTime](./setlastaccesstime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NOT IMPLEMENTED. |
| static void [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NOT IMPLEMENTED. |
| static void [SetLastWriteTime](./setlastwritetime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | 指定されたエンティティの最終書き込み時刻をローカル時間として設定します。 |
| static void [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | 指定されたエンティティの最終書き込み時刻を UTC 時間として設定します。 |
| static void [WriteAllBytes](./writeallbytes/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | 指定されたバイナリファイルを上書きし、指定されたバイトを書き込みます。 |
| static void [WriteAllLines](./writealllines/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | 指定されたエンコーディングを使用して、新しいテキストファイルを作成または既存のものを上書きし、指定された列挙可能な文字列コレクションからすべての文字列を各行に新しい行として書き込みます。 |
| static void [WriteAllLines](./writealllines/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | 指定されたエンコーディングを使用して、新しいテキストファイルを作成または既存のものを上書きし、指定された文字列配列からすべての文字列を各行に新しい行として書き込みます。 |
| static void [WriteAllText](./writealltext/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | 指定されたエンコーディングを使用して、新しいテキストファイルを作成または既存のものを上書きし、指定された文字列の内容を書き込みます。 |

## フィールド

| フィールド | 説明 |
| --- | --- |
| static [DefaultBufferSize](./defaultbuffersize/) | ファイルの読み取りおよび書き込み時にバッファリングされるバイト数のデフォルト値です。 |

## 参照

* 名前空間 [System::IO](../)
* ライブラリ [Aspose.Slides](../../)