---
title: Path
second_title: C++ 用 Aspose.Slides API リファレンス
description: パスを操作するためのメソッドを提供します。これはインスタンスサービスを持たない静的型です。いかなる手段でもインスタンスを作成すべきではありません。
type: docs
weight: 339
url: /ja/system.io/path/
---
## Path クラス

パスを操作するためのメソッドを提供します。これはインスタンスサービスを持たない静的型です。いかなる手段でもインスタンスを作成すべきではありません。

```cpp
class Path
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| static [String](../../system/string/) [ChangeExtension](./changeextension/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 指定されたファイルパスの拡張子を変更します。 |
| static void [CheckPath](./checkpath/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | 指定されたパスが無効な文字を含んでいないか確認することで、パスが有効かどうかを判断します。パスに無効な文字が含まれている場合は例外がスローされます。 |
| static [String](../../system/string/) [Combine](./combine/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | 必要に応じてディレクトリ区切り文字をセグメント間に挿入し、指定されたパスセグメントを単一のパスに結合します。 |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 必要に応じてディレクトリ区切り文字をセグメント間に挿入し、指定された2つのパスセグメントを単一のパスに結合します。 |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 必要に応じてディレクトリ区切り文字をセグメント間に挿入し、指定された3つのパスセグメントを単一のパスに結合します。 |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 必要に応じてディレクトリ区切り文字をセグメント間に挿入し、指定された4つのパスセグメントを単一のパスに結合します。 |
| static [String](../../system/string/) [GetDirectoryName](./getdirectoryname/)(const [String](../../system/string/)\&) | 指定されたパスが参照するディレクトリ名を返します。 |
| static [String](../../system/string/) [GetExtension](./getextension/)(const [String](../../system/string/)\&) | 指定されたパスが参照するファイルの拡張子を返します。 |
| static [String](../../system/string/) [GetFileName](./getfilename/)(const [String](../../system/string/)\&) | 指定されたパスが参照するファイル名を返します。 |
| static [String](../../system/string/) [GetFileNameWithoutExtension](./getfilenamewithoutextension/)(const [String](../../system/string/)\&) | 指定されたパスが参照するファイルの拡張子なしの名前を返します。 |
| static [String](../../system/string/) [GetFullPath](./getfullpath/)(const [String](../../system/string/)\&) | 指定されたパスを絶対パスに変換します。 |
| static [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetInvalidFileNameChars](./getinvalidfilenamechars/)() | ファイル名に使用できない文字を含む配列を返します。 |
| static [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetInvalidPathChars](./getinvalidpathchars/)() | パス名に使用できない文字を含む配列を返します。 |
| static [String](../../system/string/) [GetPathRoot](./getpathroot/)(const [String](../../system/string/)\&) | 指定されたパスのルートディレクトリを返します。 |
| static [String](../../system/string/) [GetRandomFileName](./getrandomfilename/)() | ランダムに生成されたファイル名を返します。 |
| static [String](../../system/string/) [GetTempFileName_](./gettempfilename_/)() | 一意の名前で新しいファイルを作成し、その完全パスを返します。 |
| static [String](../../system/string/) [GetTempFileNameSafe](./gettempfilenamesafe/)() | 一意の名前で新しいファイルを作成し、その完全パスを返します。[GetTempFileName_()](./gettempfilename_/) メソッドの同義語です。 |
| static [String](../../system/string/) [GetTempPath](./gettemppath/)() | 現在のユーザーの一時ディレクトリのパスを返します。 |
| static **bool** [HasExtension](./hasextension/)(const [String](../../system/string/)\&) | 指定されたパスが拡張子付きのファイルを参照しているかどうかを判断します。 |
| static **bool** [IsPathRooted](./ispathrooted/)(const [String](../../system/string/)\&) | 指定されたパスにルートが含まれているかどうかを判断します。 |
| static [String](../../system/string/) [NormalizePath](./normalizepath/)(const [String](../../system/string/)\&) | 指定されたパスを正規化します。 |
| static boost::filesystem::path [ToBoost](./toboost/)(const [String](../../system/string/)\&) | 指定されたパスを表す boost::filesystem::path クラスのインスタンスを返します。 |
| static [String](../../system/string/) [ToString](./tostring/)(const boost::filesystem::path\&) | 指定された Boost のパスオブジェクトの文字列表現を返します。 |

## フィールド

| フィールド | 説明 |
| --- | --- |
| static [AltDirectorySeparatorChar](./altdirectoryseparatorchar/) | パス内のディレクトリ階層を区切るために使用される代替文字です。 |
| static [DirectorySeparatorChar](./directoryseparatorchar/) | パス内のディレクトリ階層を区切るために使用される文字です。 |
| static [PathSeparator](./pathseparator/) | 環境変数内でパス文字列を区切るために使用される区切り文字です。 |
| static [VolumeSeparatorChar](./volumeseparatorchar/) | ボリューム区切り文字です。 |

## 備考



```cpp
#include "system/io/path.h"
#include <iostream>

int main()
{
  using namespace System::IO;

  // ランダムなファイル名を生成します。
  auto filename = Path::GetRandomFileName();

  // ファイル名に関する情報を出力します。
  std::cout <<
    "Filename: " << Path::GetFileName(filename) << std::endl <<
    "Filename w/o an extension: " << Path::GetFileNameWithoutExtension(filename) << std::endl <<
    "Extension: " << Path::GetExtension(filename) << std::endl;

  return 0;
}
/*
このコード例は以下の出力を生成します：
ファイル名: qhuzkyqv.y6p
拡張子なしのファイル名: qhuzkyqv
拡張子: .y6p
*/
```

## 参照

* 名前空間 [System::IO](../)
* ライブラリ [Aspose.Slides](../../)