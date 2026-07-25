---
title: EnumerateFileSystemEntries()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたディレクトリ内、またはそのディレクトリをルートとするディレクトリツリー全体で、指定された検索条件を満たすファイルおよびディレクトリを検索します。
type: docs
weight: 53
url: /ja/system.io/directory/enumeratefilesystementries/
---
## Directory::EnumerateFileSystemEntries(const String&, const String&, SearchOption) メソッド

指定された検索条件を満たすファイルとディレクトリを、指定されたディレクトリ内またはそのディレクトリをルートとするディレクトリツリー全体から検索します。

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateFileSystemEntries(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 検索対象ディレクトリへのフルパスまたは相対パス |
| searchPattern | const [String](../../../system/string/)\& | 検索対象のファイルおよびディレクトリの名前パターン |
| searchOption | [SearchOption](../../searchoption/) | 検索を指定ディレクトリのみで行うか、指定ディレクトリをルートとするディレクトリツリー全体で行うかを指定します |

### 戻り値

検索されたファイルおよびディレクトリの、名前が **searchPattern** と一致するフルパスの列挙可能なコレクション

## 参照

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)