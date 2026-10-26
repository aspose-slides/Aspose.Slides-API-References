---
title: Directory
second_title: Aspose.Slides for C++ API リファレンス
description: ディレクトリを操作するメソッドを含みます。これはインスタンスサービスを持たない静的型です。いかなる手段でもインスタンスを作成してはいけません。
type: docs
weight: 235
url: /ja/system.io/directory/
---
## Directory クラス

ディレクトリを操作するメソッドを含みます。これはインスタンスサービスを持たない静的型です。いかなる手段でもインスタンスを作成してはいけません。

```cpp
class Directory
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| static void [CreateDirectory_](./createdirectory_/)(const [String](../../system/string/)\&) | 指定されたパスにディレクトリが存在しない場合、すべてのディレクトリを作成します。 |
| static void [Delete](./delete/)(const [String](../../system/string/)\&, **bool**) | 指定されたファイルまたはディレクトリを削除します。例外はスローしません。 |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | 指定されたディレクトリ、または指定ディレクトリを根とするディレクトリツリー全体で、指定された検索条件を満たすディレクトリを検索します。 |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | 指定されたディレクトリ、または指定ディレクトリを根とするディレクトリツリー全体で、指定された検索条件を満たすファイルを検索します。 |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateFileSystemEntries](./enumeratefilesystementries/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | 指定されたディレクトリ、または指定ディレクトリを根とするディレクトリツリー全体で、指定された検索条件を満たすファイルとディレクトリを検索します。 |
| static **bool** [Exists](./exists/)(const [String](../../system/string/)\&) | 指定されたパスが既存のディレクトリを指すかどうかを判定します。 |
| static [DateTime](../../system/datetime/) [GetCreationTime](./getcreationtime/)(const [String](../../system/string/)\&) | 指定されたエンティティの作成時刻をローカル時間で返します。 |
| static [DateTime](../../system/datetime/) [GetCreationTimeUtc](./getcreationtimeutc/)(const [String](../../system/string/)\&) | 指定されたエンティティの作成時刻を UTC 時間で返します。 |
| static [String](../../system/string/) [GetCurrentDirectory](./getcurrentdirectory/)() | 現在のディレクトリのフルパス名（パスを含む）を返します。 |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | 指定されたディレクトリ、または指定ディレクトリを根とするディレクトリツリー全体で、指定された検索条件を満たすディレクトリを検索します。 |
| static [String](../../system/string/) [GetDirectoryRoot](./getdirectoryroot/)(const [String](../../system/string/)\&) | 指定されたパスのルートディレクトリを返します。 |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | 指定されたディレクトリ、または指定ディレクトリを根とするディレクトリツリー全体で、指定された検索条件を満たすファイルを検索します。 |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetFileSystemEntries](./getfilesystementries/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | 指定されたディレクトリ、または指定ディレクトリを根とするディレクトリツリー全体で、指定された検索条件を満たすファイルとディレクトリを検索します。 |
| static [DateTime](../../system/datetime/) [GetLastAccessTime](./getlastaccesstime/)(const [String](../../system/string/)\&) | 指定されたエンティティの最終アクセス時刻をローカル時間で返します。 |
| static [DateTime](../../system/datetime/) [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const [String](../../system/string/)\&) | 指定されたエンティティの最終アクセス時刻を UTC 時間で返します。 |
| static [DateTime](../../system/datetime/) [GetLastWriteTime](./getlastwritetime/)(const [String](../../system/string/)\&) | 指定されたエンティティの最終書き込み時刻をローカル時間で返します。 |
| static [DateTime](../../system/datetime/) [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const [String](../../system/string/)\&) | 指定されたエンティティの最終書き込み時刻を UTC 時間で返します。 |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetLogicalDrives](./getlogicaldrives/)() | NOT IMPLEMENTED. |
| static [DirectoryInfoPtr](../../system/directoryinfoptr/) [GetParent](./getparent/)(const [String](../../system/string/)\&) | 指定されたエンティティの親ディレクトリを表す [DirectoryInfo](../directoryinfo/) オブジェクトへの共有ポインタを返します。 |
| static void [Move](./move/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 指定されたエンティティを新しい場所へ移動します。ディレクトリを移動する場合、その内容すべてが移動されます。 |
| static void [SetCreationTime](./setcreationtime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | 指定されたエンティティの作成時刻をローカル時間で設定します。 |
| static void [SetCreationTimeUtc](./setcreationtimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | 指定されたエンティティの作成時刻を UTC 時間で設定します。 |
| static void [SetCurrentDirectory](./setcurrentdirectory/)(const [String](../../system/string/)\&) | 現在のディレクトリを設定します。 |
| static void [SetLastAccessTime](./setlastaccesstime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | 指定されたエンティティの最終アクセス時刻をローカル時間で設定します。 |
| static void [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | 指定されたエンティティの最終アクセス時刻を UTC 時間で設定します。 |
| static void [SetLastWriteTime](./setlastwritetime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | 指定されたエンティティの最終書き込み時刻をローカル時間で設定します。 |
| static void [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | 指定されたエンティティの最終書き込み時刻を UTC 時間で設定します。 |

## 型エイリアス

| 型エイリアス | 説明 |
| --- | --- |
| [StringEnumerablePtr](./stringenumerableptr/) | [String](../../system/string/) オブジェクトの集合を列挙する IEnumerable オブジェクトへの共有ポインタのエイリアスです。 |

## 備考



```cpp
#include "system/io/directory.h"
#include "system/io/path.h"
#include "system/string.h"
#include <iostream>

void PrintMessage(const System::String &path)
{
  std::cout << "Directory '" << path << (System::IO::Directory::Exists(path) ? "' exists." : "' doesn't exist.") << std::endl;
}

int main()
{
  // ディレクトリへのパスを含む文字列を作成します。
  System::String discPath(u"C:\\");
  System::String directoryPath(u"C:\\Some directory");
  auto tempPath = System::IO::Path::GetTempPath();

  // ディレクトリが存在するか確認します。
  PrintMessage(discPath);
  PrintMessage(directoryPath);
  PrintMessage(tempPath);

  // 一時ディレクトリの情報を出力します。
  std::cout <<
    "Creation Time: " << System::IO::Directory::GetCreationTime(tempPath) << std::endl <<
    "Last Access Time: " << System::IO::Directory::GetLastAccessTime(tempPath) << std::endl <<
    "Last Write Time: " << System::IO::Directory::GetLastWriteTime(tempPath) << std::endl;

  return 0;
}
/*
このコード例は以下の出力を生成します：
Directory 'C:\' が存在します。
Directory 'C:\Some directory' が存在しません。
Directory 'C:\Users\lanor\AppData\Local\Temp\' が存在します。
作成時刻: 27.08.2021 14:21:42
最終アクセス時刻: 07.10.2021 12:16:41
最終書き込み時刻: 07.10.2021 12:16:41
*/
```

## 参照

* Namespace [System::IO](../)
* ライブラリ [Aspose.Slides](../../)