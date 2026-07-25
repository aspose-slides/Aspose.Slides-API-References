---
title: EnumerateDirectories()
second_title: Aspose.Slides の C++ API リファレンス
description: 指定されたディレクトリ内、または指定されたディレクトリをルートとするディレクトリツリー全体から、指定された検索条件を満たすディレクトリを検索します。
type: docs
weight: 27
url: /ja/system.io/directory/enumeratedirectories/
---
## Directory::EnumerateDirectories(const String&, const String&, SearchOption) メソッド

指定した検索条件を満たすディレクトリを、指定されたディレクトリ内または指定されたディレクトリをルートとするディレクトリツリー全体から検索します。

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateDirectories(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 検索対象ディレクトリへの完全パスまたは相対パス |
| searchPattern | const [String](../../../system/string/)\& | 検索対象ディレクトリの名前パターン |
| searchOption | [SearchOption](../../searchoption/) | 検索を指定ディレクトリのみで実行するか、指定ディレクトリをルートとするディレクトリツリー全体で実行するかを指定します |

### 戻り値

検索されたディレクトリのうち、名前が **searchPattern** と一致するディレクトリの完全パスの列挙可能なコレクション

## 参照

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)