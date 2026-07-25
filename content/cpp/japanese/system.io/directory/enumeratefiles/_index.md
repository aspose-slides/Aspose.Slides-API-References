---
title: EnumerateFiles()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された検索条件を満たすファイルを、指定ディレクトリ内または指定ディレクトリを根とするディレクトリツリー全体から検索します。
type: docs
weight: 40
url: /ja/system.io/directory/enumeratefiles/
---
## Directory::EnumerateFiles(const String&, const String&, SearchOption) メソッド


指定された検索条件を満たすファイルを、指定ディレクトリ内または指定ディレクトリを根とするディレクトリツリー全体から検索します。

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateFiles(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 検索対象ディレクトリへのフルパスまたは相対パス |
| searchPattern | const [String](../../../system/string/)\& | 検索対象ファイルの名前パターン |
| searchOption | [SearchOption](../../searchoption/) | 検索を指定ディレクトリのみで実行するか、指定ディレクトリを根とするディレクトリツリー全体で実行するかを指定します |

### 戻り値

検索結果のファイルで、名前が **searchPattern** と一致するファイルのフルパスの列挙可能なコレクション

## 関連項目

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)